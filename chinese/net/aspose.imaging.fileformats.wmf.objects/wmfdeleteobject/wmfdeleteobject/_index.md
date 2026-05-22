---
title: "WmfDeleteObject.WmfDeleteObject"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WmfDeleteObject 构造函数。初始化 WmfDeleteObject 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.wmf.objects/wmfdeleteobject/wmfdeleteobject/
---
## WmfDeleteObject(WmfGraphicObject) {#constructor_1}

初始化 [`WmfDeleteObject`](../) 类的新实例。

```csharp
public WmfDeleteObject(WmfGraphicObject deletedObject)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deletedObject | WmfGraphicObject | 已删除的对象。 |

### 另请参见

* class [WmfGraphicObject](../../wmfgraphicobject/)
* class [WmfDeleteObject](../)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../wmfdeleteobject/)
* assembly [Aspose.Imaging](../../../)

---

## WmfDeleteObject() {#constructor}

初始化 [`WmfDeleteObject`](../) 类的新实例。

```csharp
public WmfDeleteObject()
```

## 示例

以下示例展示了如何为 WMF 设置背景颜色。实际上，它在绘制所有其他对象之前先绘制一个背景颜色的矩形。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string inputFilePath = dir + "image2.wmf";
string outputFilePath = dir + "ChangeBackground_" + "image2.wmf";

using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    AddBackgroundRectangleWmf((Aspose.Imaging.FileFormats.Wmf.WmfImage)image, Aspose.Imaging.Color.Blue);
    image.Save(outputFilePath);
}

/// <summary>
/// 更改 WMF 背景的辅助方法。
/// </summary>
public static void AddBackgroundRectangleWmf(Aspose.Imaging.FileFormats.Wmf.WmfImage image, Aspose.Imaging.Color color)
{
    image.CacheData();
    if (image.Records.Count < 1)
    {
        return;
    }

    //设置矩形
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfRectangle rectangle = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfRectangle();
    rectangle.Rectangle = image.FrameBounds;

    //设置画刷
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfCreateBrushInDirect brush = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfCreateBrushInDirect();
    brush.LogBrush = new Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogBrushEx();
    brush.LogBrush.Argb32ColorRef = color.ToArgb();

    //选择画笔
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfSelectObject selectObject = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfSelectObject(brush);

    //移除画笔
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeleteObject deleteObject = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeleteObject(brush);

    //添加记录
    image.Records.Insert(0, brush);
    image.Records.Insert(1, selectObject);
    image.Records.Insert(2, rectangle);
    image.Records.Insert(3, deleteObject);
}
```

### 另请参见

* class [WmfDeleteObject](../)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../wmfdeleteobject/)
* assembly [Aspose.Imaging](../../../)


