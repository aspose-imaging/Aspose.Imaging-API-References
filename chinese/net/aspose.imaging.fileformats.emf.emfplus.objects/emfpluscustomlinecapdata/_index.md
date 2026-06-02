---
title: "类 EmfPlusCustomLineCapData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusCustomLineCapData 类。EmfPlusCustomLineCapData 对象指定自定义线帽的默认数据。"
type: docs
weight: 5510
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
## EmfPlusCustomLineCapData class

EmfPlusCustomLineCapData 对象指定自定义线帽的默认数据。

```csharp
public sealed class EmfPlusCustomLineCapData : EmfPlusCustomBaseLineCap
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusCustomLineCapData](emfpluscustomlinecapdata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BaseCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/basecap/) { get; set; } | 获取或设置 32 位无符号整数，指定基于 LineCap 枚举（第 2.1.1.18 节）的自定义线帽的值。 |
| [BaseInset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/baseinset/) { get; set; } | 获取或设置 32 位浮点值，指定线帽起始端与线结束端之间的距离。 |
| [CustomLineCapDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/customlinecapdataflags/) { get; set; } | 获取或设置 32 位无符号整数，指定 OptionalData 字段中的数据。 |
| [FillHotSpot](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/fillhotspot/) { get; set; } | 获取或设置 EmfPlusPointF 对象，该对象当前未使用。它必须设置为 {0.0, 0.0}。 |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/optionaldata/) { get; set; } | 获取或设置 可选的 EmfPlusCustomLineCapOptionalData 对象（第 2.2.2.14 节），该对象指定自定义图形线帽的附加数据。此字段的具体内容由 CustomLineCapDataFlags 字段的值决定。 |
| [StrokeEndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokeendcap/) { get; set; } | 获取或设置 32 位无符号整数，指定 LineCap 枚举中的值，指示在绘制的线段末端使用的线帽。 |
| [StrokeHotSpot](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokehotspot/) { get; set; } | 获取或设置 EmfPlusPointF 对象，该对象当前未使用。它必须设置为 {0.0, 0.0}。 |
| [StrokeJoin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokejoin/) { get; set; } | 获取或设置 32 位无符号整数，指定 LineJoin 枚举（第 2.1.1.19 节）中的值，该值指定如何连接同一笔绘制且端点相接的两条线。在两条线端点的交叉处，线段连接使连接看起来更连续。 |
| [StrokeMiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokemiterlimit/) { get; set; } | 获取或设置 32 位浮点值，包含通过设置斜接长度与线宽的最大允许比例来限制斜接角处连接的厚度。 |
| [StrokeStartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokestartcap/) { get; set; } | 获取或设置 32 位无符号整数，指定 LineCap 枚举中的值，指示在绘制的线段起始端使用的线帽。 |
| [WidthScale](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/widthscale/) { get; set; } | 获取或设置 32 位浮点值，指定相对于用于绘制线条的 EmfPlusPen 对象（第 2.2.1.7 节）宽度，对自定义线帽的缩放量。 |

### 另请参见

* class [EmfPlusCustomBaseLineCap](../emfpluscustombaselinecap/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


