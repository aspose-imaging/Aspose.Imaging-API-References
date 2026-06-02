---
title: "类 EmfSetDiBitsToDevice"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetDiBitsToDevice 类。EMR_SETDIBITSTODEVICE 记录指定将源位图的指定扫描线像素块传输到目标矩形。"
type: docs
weight: 4450
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
## EmfSetDiBitsToDevice class

该 EMR_SETDIBITSTODEVICE 记录指定将像素从源位图的指定扫描线块传输到目标矩形。

```csharp
public sealed class EmfSetDiBitsToDevice : EmfBitmapRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetDiBitsToDevice](emfsetdibitstodevice/)(EmfRecord) | 初始化 `EmfSetDiBitsToDevice` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/bounds/) { get; set; } | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义目标边界矩形。 |
| [CScans](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/cscans/) { get; set; } | 获取或设置一个 32 位无符号整数，用于指定扫描线的数量。 |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/cxsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的像素宽度。 |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/cysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的高度（像素） |
| [IStartScan](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/istartscan/) { get; set; } | 获取或设置一个 32 位无符号整数，指定数组中的第一扫描线。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/sourcebitmap/) { get; set; } | 获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR_SETDIBITSTODEVICE 记录的固定部分连续。因此，缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/usagesrc/) { get; set; } | 获取或设置一个 32 位无符号整数，指定如何解释源位图头部颜色表中的值。该值必须属于 DIBColors 枚举（第 2.1.9 节）。 |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/xdest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 x 坐标。 |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/xsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形左下角的 x 坐标（像素）。 |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/ydest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 y 坐标。 |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/ysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形左下角的 y 坐标（像素）。 |

## 备注

此记录支持 JPEG 和 PNG 格式的源图像。源位图头中的 Compression 字段指定图像格式。

### 另请参见

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


