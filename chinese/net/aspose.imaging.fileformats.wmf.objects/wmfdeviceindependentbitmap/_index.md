---
title: "类 WmfDeviceIndependentBitmap"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeviceIndependentBitmap 类。DeviceIndependentBitmap 对象以设备无关位图（DIB）格式定义图像"
type: docs
weight: 8760
url: /zh/net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
## WmfDeviceIndependentBitmap class

该 DeviceIndependentBitmap 对象定义了以设备无关位图（DIB）格式表示的图像。

```csharp
public class WmfDeviceIndependentBitmap : MetaObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WmfDeviceIndependentBitmap](wmfdeviceindependentbitmap/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AData](../../aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/adata/) { get; set; } | 获取或设置定义图像的字节数组。此数据的大小和格式由 DIBHeaderInfo 字段中的信息决定。 |
| [CachedImage](../../aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/cachedimage/) { get; set; } | 获取或设置缓存的光栅图像。 |
| [ColorsData](../../aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/colorsdata/) { get; set; } | 获取或设置一个可选数组，该数组可以是 RGBQuad 对象（第 2.2.2.20 节）或 16 位无符号整数，用于定义颜色表。此字段的大小和内容应根据包含此 DeviceIndependentBitmap 的元文件记录或对象以及 DIBHeaderInfo 字段中的信息来确定。有关更多细节，请参阅 ColorUsage 枚举（第 2.1.1.6 节）和 BitCount 枚举（第 2.1.1.3 节）。 |
| [Header](../../aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/header/) { get; set; } | 获取或设置 BitmapCoreHeader 对象（第 2.2.2.2 节）或 BitmapInfoHeader 对象（第 2.2.2.3 节），以指定图像信息。 |

### 另请参见

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


