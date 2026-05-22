---
title: "MetaImage.ResizeCanvas"
second_title: "Aspose.Imaging for .NET API 参考"
description: "MetaImage 方法。调整画布大小"
type: docs
weight: 50
url: /zh/net/aspose.imaging.fileformats.emf/metaimage/resizecanvas/
---
## MetaImage.ResizeCanvas method

调整画布大小。

```csharp
public abstract void ResizeCanvas(Rectangle newRectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newRectangle | Rectangle | 新的矩形。 |

## 示例

以下示例展示了如何在元文件（WMF 和 EMF）周围添加具有指定边距的边框。

```csharp
[C#]

int borderLeft = 50;
int borderTop = 50;
int borderRight = 50;
int borderBottom = 50;

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string[] fileNames = new[] { "image1.emf", "image2.wmf" };
foreach (string fileName in fileNames)
{
    string inputFilePath = dir + fileName;
    string outputFilePath = dir + "AddBorder_" + fileName;
    using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
    {
        image.ResizeCanvas(new Aspose.Imaging.Rectangle(-borderLeft, -borderTop, image.Width + borderLeft + borderRight, image.Height + borderTop + borderBottom));
        image.Save(outputFilePath);
    }
}
```

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [MetaImage](../)
* namespace [Aspose.Imaging.FileFormats.Emf](../../metaimage/)
* assembly [Aspose.Imaging](../../../)


