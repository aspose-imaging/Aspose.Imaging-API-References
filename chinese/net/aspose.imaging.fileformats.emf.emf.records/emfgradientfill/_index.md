---
title: "类 EmfGradientFill"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfGradientFill 类。EMR_GRADIENTFILL 记录指定使用颜色渐变填充矩形或三角形。"
type: docs
weight: 3860
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
## EmfGradientFill class

EMR_GRADIENTFILL 记录指定使用颜色渐变填充矩形或三角形。

```csharp
public sealed class EmfGradientFill : EmfDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfGradientFill](emfgradientfill/)(EmfRecord) | 初始化 `EmfGradientFill` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/bounds/) { get; set; } | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以包含-包含的设备单位指定边界矩形。 |
| [NTri](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/ntri/) { get; set; } | 获取或设置一个 32 位无符号整数，指定要填充的矩形或三角形数量。 |
| [NVer](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/nver/) { get; set; } | 获取或设置一个 32 位无符号整数，指定顶点数量。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [UlMode](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/ulmode/) { get; set; } | 获取或设置一个 32 位无符号整数，指定渐变填充模式。该值必须属于 GradientFill 枚举（第 2.1.15 节）。 |
| [VertexData](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/vertexdata/) { get; set; } | 获取或设置对象，这些对象指定矩形或三角形的顶点以及对应的颜色。 |

## 备注

EMR_GRADIENTFILL 记录指定三角形的三个顶点应使用平滑的颜色渐变填充图形。[85] EMR_GRADIENTFILL 记录指定矩形的左上角和右下角顶点应使用平滑的颜色渐变填充图形。GradientFill 枚举中有两种可用于绘制矩形的渐变填充模式。在 GRADIENT_FILL_RECT_H 模式下，矩形从左到右填充；在 GRADIENT_FILL_RECT_V 模式下，矩形从上到下填充。注意，EMR_GRADIENTFILL 记录必须忽略 TriVertex 对象中的 Alpha 字段。紧随 EMR_GRADIENTFILL 记录之后的 EMR_ALPHABLEND 记录（第 2.3.1.1 节）可用于对填充区域应用 alpha 透明度渐变。

### 另请参见

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


