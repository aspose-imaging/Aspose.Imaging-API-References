---
title: "类 EmfHeaderExtension2"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfHeaderExtension2 类。HeaderExtension2 对象定义了 EMF 元文件头的第二个扩展。它增加了以微米测量设备表面的能力，从而提升了 EMF 元文件的分辨率和可伸缩性。"
type: docs
weight: 3090
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/
---
## EmfHeaderExtension2 class

HeaderExtension2 对象定义了 EMF 元文件头的第二个扩展。它增加了以微米为单位测量设备表面的能力，从而提升了 EMF 元文件的分辨率和可伸缩性。

```csharp
public sealed class EmfHeaderExtension2 : EmfHeaderObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfHeaderExtension2](emfheaderextension2/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds/) { get; set; } | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定以设备单位计的包含在内的最小矩形边界，该矩形可围绕存储在元文件中的图像绘制。 |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes/) { get; set; } | 获取或设置一个 32 位无符号整数，指定元文件的大小（以字节计）。 |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device/) { get; set; } | 获取或设置一个 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），指定参考设备的大小（以像素计）。 |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame/) { get; set; } | 获取或设置一个 WMF RectL 对象，指定以 0.01 毫米单位计的包含在内的矩形尺寸，该矩形围绕存储在元文件中的图像。 |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles/) { get; set; } | 获取或设置一个 16 位无符号整数，指定在处理元文件期间将使用的图形对象数量。 |
| [MicrometersX](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersx/) { get; set; } | 获取或设置生成元文件图像的显示设备的 32 位水平尺寸（以微米计）。 |
| [MicrometersY](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersy/) { get; set; } | 获取或设置生成元文件图像的显示设备的 32 位垂直尺寸（以微米计）。 |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters/) { get; set; } | 获取或设置一个 WMF SizeL 对象，指定参考设备的大小（以毫米计）。 |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription/) { get; set; } | 获取或设置一个 32 位无符号整数，指定包含元文件内容描述的数组中的字符数。如果没有描述字符串，则为零。 |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries/) { get; set; } | 获取或设置一个 32 位无符号整数，指定元文件调色板中的条目数。调色板位于 EMR_EOF 记录中。 |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription/) { get; set; } | 获取或设置一个 32 位无符号整数，指定从此记录开始到包含元文件内容描述的数组的偏移量。 |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records/) { get; set; } | 获取或设置一个 32 位无符号整数，指定元文件中的记录数。 |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature/) { get; set; } | 获取或设置一个 32 位无符号整数，用于指定记录签名。该值必须是 ENHMETA_SIGNATURE，来自 FormatSignature 枚举（第 2.1.14 节）。 |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved/) { get; set; } | 获取或设置一个 16 位无符号整数，该值必须为 0x0000 且必须被忽略。 |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid/) { get; } | 获取一个值，指示此 [`EmfHeaderObject`](../emfheaderobject/) 是否有效。 |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version/) { get; set; } | 获取或设置版本（4 字节）：一个 32 位无符号整数，用于指定 EMF 元文件的互操作性。该值应为 0x00010000。 |

### 另请参见

* class [EmfHeaderObject](../emfheaderobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


