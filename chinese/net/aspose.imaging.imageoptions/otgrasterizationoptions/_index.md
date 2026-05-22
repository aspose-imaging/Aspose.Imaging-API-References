---
title: "类 OtgRasterizationOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.OtgRasterizationOptions 类。Otg 栅格化选项"
type: docs
weight: 10470
url: /zh/net/aspose.imaging.imageoptions/otgrasterizationoptions/
---
## OtgRasterizationOptions class

Otg 栅格化选项

```csharp
public class OtgRasterizationOptions : OdRasterizationOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OtgRasterizationOptions](otgrasterizationoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | 获取或设置背景颜色。 |
| [BorderX](../../aspose.imaging.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | 获取或设置边框 X。 |
| [BorderY](../../aspose.imaging.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | 获取或设置边框 Y。 |
| [CenterDrawing](../../aspose.imaging.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | 获取或设置一个值，指示是否居中绘制。 |
| [DrawColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | 获取或设置前景颜色。 |
| [PageHeight](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | 获取或设置页面高度。如果该值为 0，则会保留源图像的宽高比。 |
| [PageSize](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | 获取或设置页面大小。如果 [`SizeF`](../../aspose.imaging/sizef/) 的任一维度为 0，则会保留源图像的宽高比。 |
| [PageWidth](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | 获取或设置页面宽度。如果该值为 0，则会保留源图像的宽高比。 |
| [Positioning](../../aspose.imaging.imageoptions/vectorrasterizationoptions/positioning/) { get; set; } | 获取或设置定位。 |
| [ReplaceTextMapping](../../aspose.imaging.imageoptions/vectorrasterizationoptions/replacetextmapping/) { get; set; } | 获取或设置文本替换映射。 |
| [SmoothingMode](../../aspose.imaging.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | 获取或设置平滑模式。 |
| [TextRenderingHint](../../aspose.imaging.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | 获取或设置文本渲染提示。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../aspose.imaging.imageoptions/vectorrasterizationoptions/clone/)() | 创建一个当前实例的浅拷贝新对象。 |
| virtual [CopyTo](../../aspose.imaging.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | 复制到。 |

## 示例

以下代码片段演示如何将 OTG 图像转换为 PDF 及其他图像格式。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3567\\";
string inputFilePath = dir + "VariousObjectsMultiPage.otg";
Aspose.Imaging.ImageOptionsBase[] options = { new Aspose.Imaging.ImageOptions.PngOptions(), new Aspose.Imaging.ImageOptions.PdfOptions() };
foreach (Aspose.Imaging.ImageOptionsBase saveOptions in options)
{
    string extension = saveOptions is Aspose.Imaging.ImageOptions.PngOptions ? ".png" : ".pdf";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
    {
        Aspose.Imaging.ImageOptions.OtgRasterizationOptions otgRasterizationOptions = new Aspose.Imaging.ImageOptions.OtgRasterizationOptions();
        otgRasterizationOptions.PageSize = image.Size;
        saveOptions.VectorRasterizationOptions = otgRasterizationOptions;

        image.Save(inputFilePath + extension, saveOptions);
    }
}
```

### 另请参见

* class [OdRasterizationOptions](../odrasterizationoptions/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


