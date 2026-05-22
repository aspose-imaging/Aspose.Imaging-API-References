---
title: "EmfDeleteObject.EmfDeleteObject"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfDeleteObject 构造函数。初始化 EmfDeleteObject 类的新实例。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/emfdeleteobject/
---
## EmfDeleteObject(EmfRecord) {#constructor_1}

初始化 [`EmfDeleteObject`](../) 类的新实例。

```csharp
public EmfDeleteObject(EmfRecord record)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 记录 | EmfRecord | 该记录。 |

### 另请参见

* class [EmfRecord](../../emfrecord/)
* class [EmfDeleteObject](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../emfdeleteobject/)
* assembly [Aspose.Imaging](../../../)

---

## EmfDeleteObject() {#constructor}

初始化 [`EmfDeleteObject`](../) 类的新实例。

```csharp
public EmfDeleteObject()
```

## 示例

以下示例展示了如何为 EMF 设置背景颜色。它实际上在绘制所有其他对象之前绘制一个背景颜色的矩形。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string inputFilePath = dir + "image1.emf";
string outputFilePath = dir + "ChangeBackground_" + "image1.emf";

using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    AddBackgroundRectangleEmf((Aspose.Imaging.FileFormats.Emf.EmfImage)image, Aspose.Imaging.Color.Blue);

    image.Save(outputFilePath);
}
    
/// <summary>
/// 用于更改 EMF 背景的辅助方法。
/// </summary>
public static void AddBackgroundRectangleEmf(Aspose.Imaging.FileFormats.Emf.EmfImage image, Aspose.Imaging.Color color)
{
    image.CacheData();
    if (image.Records.Count < 1)
    {
        return;
    }

    //设置矩形
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRectangle rectangle = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRectangle();
    rectangle.Box = image.Header.EmfHeader.Bounds;

    //设置画刷
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateBrushIndirect brush = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateBrushIndirect();
    brush.LogBrush = new Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogBrushEx();
    brush.LogBrush.Argb32ColorRef = color.ToArgb();

    // 对象索引从 1 开始；0 保留用于对元文件本身的引用，参见
    // https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-emf/e4fa4e63-9096-4cdc-b776-85e2a1e4e1f4
    brush.IhBrush = 1;

    //选择画笔
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSelectObject selectObject = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSelectObject();
    selectObject.ObjectHandle = 1;

    //移除画笔
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfDeleteObject deleteObject = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfDeleteObject();
    deleteObject.ObjectHandle = 1;

    //添加记录
    image.Records.Insert(1, brush);
    image.Records.Insert(2, selectObject);
    image.Records.Insert(3, rectangle);
    image.Records.Insert(4, deleteObject);
}
```

### 另请参见

* class [EmfDeleteObject](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../emfdeleteobject/)
* assembly [Aspose.Imaging](../../../)


