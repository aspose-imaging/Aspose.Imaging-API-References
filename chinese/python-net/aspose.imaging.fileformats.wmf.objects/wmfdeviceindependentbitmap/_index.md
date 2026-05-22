---
title: "WmfDeviceIndependentBitmap 类"
type: docs
weight: 180
url: /zh/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---

**Summary:** The DeviceIndependentBitmap Object defines an image in<br/>                device-independent bitmap (DIB) format

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap__1) | 初始化 WmfDeviceIndependentBitmap 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| a_data | System.Byte | r/w | 获取或设置定义图像的字节数组。此数据的大小和<br/>                格式由 DIBHeaderInfo 字段中的信息决定。 |
| cached_image | System.Byte | r/w | 获取或设置缓存的光栅图像。 |
| colors_data | System.Byte | r/w | 获取或设置一个可选数组，该数组可以是 RGBQuad 对象（第<br/>                2.2.2.20 节）或定义颜色表的 16 位无符号整数。此<br/>                字段的大小和内容应从<br/>                包含此 DeviceIndependentBitmap 的元文件记录或对象<br/>                以及 DIBHeaderInfo 字段中的信息确定。请参阅 ColorUsage<br/>                枚举（第 2.1.1.6 节）和 BitCount 枚举（第<br/>                2.1.1.3 节）以获取更多细节 |
| header | [WmfBitmapBaseHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) | r/w | 获取或设置 BitmapCoreHeader 对象（第 2.2.2.2 节）或<br/>                BitmapInfoHeader 对象（第 2.2.2.3 节），该对象指定图像信息 |


### Constructor: WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap__1}


```
 WmfDeviceIndependentBitmap() 
```

初始化 WmfDeviceIndependentBitmap 类的新实例

