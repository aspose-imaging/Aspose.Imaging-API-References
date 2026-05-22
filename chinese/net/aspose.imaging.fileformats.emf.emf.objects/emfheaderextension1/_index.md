---
title: "类 EmfHeaderExtension1"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfHeaderExtension1 类。HeaderExtension1 对象定义 EMF 元文件头的第一个扩展。它增加了对 PixelFormatDescriptor 对象（第 2.2.22 节）和 OpenGL 记录（第 2.3.9 节）的支持。"
type: docs
weight: 3080
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
## EmfHeaderExtension1 class

HeaderExtension1 对象定义了 EMF 元文件头的第一个扩展。它添加了对 PixelFormatDescriptor 对象（第 2.2.22 节）和 OpenGL [OPENGL] 记录（第 2.3.9 节）的支持。

```csharp
public sealed class EmfHeaderExtension1 : EmfHeaderObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfHeaderExtension1](emfheaderextension1/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BOpenGl](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/bopengl/) { get; set; } | 获取或设置一个 32 位无符号整数，指示元文件中是否存在 OpenGL 命令。0x00000000 表示元文件中不存在 OpenGL 记录。0x00000001 表示元文件中存在 OpenGL 记录。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds/) { get; set; } | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定以设备单位计的包含在内的最小矩形边界，该矩形可围绕存储在元文件中的图像绘制。 |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes/) { get; set; } | 获取或设置一个 32 位无符号整数，指定元文件的大小（以字节计）。 |
| [CbPixelFormat](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/cbpixelformat/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 PixelFormatDescriptor 对象的大小。如果未设置像素格式，则此值必须为 0x00000000。 |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device/) { get; set; } | 获取或设置一个 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），指定参考设备的大小（以像素计）。 |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame/) { get; set; } | 获取或设置一个 WMF RectL 对象，指定以 0.01 毫米单位计的包含在内的矩形尺寸，该矩形围绕存储在元文件中的图像。 |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles/) { get; set; } | 获取或设置一个 16 位无符号整数，指定在处理元文件期间将使用的图形对象数量。 |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters/) { get; set; } | 获取或设置一个 WMF SizeL 对象，指定参考设备的大小（以毫米计）。 |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription/) { get; set; } | 获取或设置一个 32 位无符号整数，指定包含元文件内容描述的数组中的字符数。如果没有描述字符串，则为零。 |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries/) { get; set; } | 获取或设置一个 32 位无符号整数，指定元文件调色板中的条目数。调色板位于 EMR_EOF 记录中。 |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription/) { get; set; } | 获取或设置一个 32 位无符号整数，指定从此记录开始到包含元文件内容描述的数组的偏移量。 |
| [OffPixelFormat](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/offpixelformat/) { get; set; } | 获取或设置一个 32 位无符号整数，指定指向 PixelFormatDescriptor 对象的偏移量。如果未设置像素格式，则此值必须为 0x00000000。 |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records/) { get; set; } | 获取或设置一个 32 位无符号整数，指定元文件中的记录数。 |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature/) { get; set; } | 获取或设置一个 32 位无符号整数，用于指定记录签名。该值必须是 ENHMETA_SIGNATURE，来自 FormatSignature 枚举（第 2.1.14 节）。 |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved/) { get; set; } | 获取或设置一个 16 位无符号整数，该值必须为 0x0000 且必须被忽略。 |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid/) { get; } | 获取一个值，指示此 [`EmfHeaderObject`](../emfheaderobject/) 是否有效。 |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version/) { get; set; } | 获取或设置版本（4 字节）：一个 32 位无符号整数，用于指定 EMF 元文件的互操作性。该值应为 0x00010000。 |

### 另请参见

* class [EmfHeaderObject](../emfheaderobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


