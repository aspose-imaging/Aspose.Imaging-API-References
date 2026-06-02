---
title: "类 EmfPlusSetTsClip"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetTsClip 类。EmfPlusSetTSClip 记录为终端服务器指定图形设备上下文中的裁剪区域。"
type: docs
weight: 6520
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
## EmfPlusSetTsClip class

EmfPlusSetTSClip 记录指定终端服务器的图形设备上下文中的裁剪区域。

```csharp
public sealed class EmfPlusSetTsClip : EmfPlusTerminalServerRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusSetTsClip](emfplussettsclip/)(EmfPlusRecord) | 初始化 `EmfPlusSetTsClip` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/compressed/) { get; } | 获取一个值，指示此 `EmfPlusSetTsClip` 是否已压缩。此位指定 rects 字段中矩形数据的格式。如果设置，则每个矩形占用 4 字节；如果未设置，则每个矩形占用 8 字节。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [NumRects](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/numrects/) { get; } | 获取矩形数量。此字段指定在 rect 字段中定义的矩形数量。 |
| [Rects](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/rects/) { get; set; } | 获取或设置一个 NumRects 矩形数组，用于定义裁剪区域。此数据的格式由 Flags 字段中的 C 位决定。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

## 备注

此记录中数据的压缩方案使用以下算法。每个矩形的每个点要么以单字节编码，要么以 2 字节编码。如果点以单字节编码，则该字节的最高位 (0x80) 必须被设置，值为由低 7 位表示的有符号数。如果最高位未设置，则该值以 2 字节编码，首字节的高 7 位编码高序字节，第二字节编码低序字节。每个点被编码为当前矩形中的点与前一个矩形中的点之间的差值。矩形的底部点被编码为当前矩形中底部坐标与顶部坐标之间的差值。

### 另请参见

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


