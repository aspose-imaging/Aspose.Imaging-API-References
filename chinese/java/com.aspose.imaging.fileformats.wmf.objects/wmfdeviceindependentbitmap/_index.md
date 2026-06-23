---
title: "WmfDeviceIndependentBitmap"
second_title: "Aspose.Imaging for Java API 参考"
description: "DeviceIndependentBitmap 对象定义了设备无关位图（DIB）格式的图像。"
type: docs
weight: 27
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfDeviceIndependentBitmap extends MetaObject
```

DeviceIndependentBitmap 对象定义了设备无关位图 (DIB) 格式的图像。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeader()](#getHeader--) | 获取或设置 BitmapCoreHeader 对象（第 2.2.2.2 节）或 BitmapInfoHeader 对象（第 2.2.2.3 节），用于指定图像信息。 |
| [setHeader(WmfBitmapBaseHeader value)](#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-) | 获取或设置 BitmapCoreHeader 对象（第 2.2.2.2 节）或 BitmapInfoHeader 对象（第 2.2.2.3 节），用于指定图像信息。 |
| [getColorsData()](#getColorsData--) | 获取或设置一个可选数组，该数组可以是 RGBQuad 对象（第 2.2.2.20 节）或定义颜色表的 16 位无符号整数。 |
| [setColorsData(byte[] value)](#setColorsData-byte---) | 获取或设置一个可选数组，该数组可以是 RGBQuad 对象（第 2.2.2.20 节）或定义颜色表的 16 位无符号整数。 |
| [getAData()](#getAData--) | 获取或设置定义图像的字节数组。 |
| [setAData(byte[] value)](#setAData-byte---) | 获取或设置定义图像的字节数组。 |
| [getCachedImage()](#getCachedImage--) | 获取缓存的光栅图像。 |
| [setCachedImage(byte[] value)](#setCachedImage-byte---) | 设置缓存的光栅图像。 |
### WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap--}
```
public WmfDeviceIndependentBitmap()
```


### getHeader() {#getHeader--}
```
public WmfBitmapBaseHeader getHeader()
```


获取或设置 BitmapCoreHeader 对象（第 2.2.2.2 节）或 BitmapInfoHeader 对象（第 2.2.2.3 节），用于指定图像信息。

**Returns:**
[WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
### setHeader(WmfBitmapBaseHeader value) {#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-}
```
public void setHeader(WmfBitmapBaseHeader value)
```


获取或设置 BitmapCoreHeader 对象（第 2.2.2.2 节）或 BitmapInfoHeader 对象（第 2.2.2.3 节），用于指定图像信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader) |  |

### getColorsData() {#getColorsData--}
```
public byte[] getColorsData()
```


获取或设置一个可选数组，该数组可以是 RGBQuad 对象（第 2.2.2.20 节）或定义颜色表的 16 位无符号整数。此字段的大小和内容应从包含此 DeviceIndependentBitmap 的元文件记录或对象以及 DIBHeaderInfo 字段的信息中确定。有关更多细节，请参阅 ColorUsage 枚举（第 2.1.1.6 节）和 BitCount 枚举（第 2.1.1.3 节）。

**Returns:**
byte[]
### setColorsData(byte[] value) {#setColorsData-byte---}
```
public void setColorsData(byte[] value)
```


获取或设置一个可选数组，该数组可以是 RGBQuad 对象（第 2.2.2.20 节）或定义颜色表的 16 位无符号整数。此字段的大小和内容应从包含此 DeviceIndependentBitmap 的元文件记录或对象以及 DIBHeaderInfo 字段的信息中确定。有关更多细节，请参阅 ColorUsage 枚举（第 2.1.1.6 节）和 BitCount 枚举（第 2.1.1.3 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### getAData() {#getAData--}
```
public byte[] getAData()
```


获取或设置定义图像的字节数组。此数据的大小和格式由 DIBHeaderInfo 字段中的信息决定。

**Returns:**
byte[]
### setAData(byte[] value) {#setAData-byte---}
```
public void setAData(byte[] value)
```


获取或设置定义图像的字节数组。此数据的大小和格式由 DIBHeaderInfo 字段中的信息决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### getCachedImage() {#getCachedImage--}
```
public final byte[] getCachedImage()
```


获取缓存的光栅图像。

值：缓存的图像。

**Returns:**
byte[]
### setCachedImage(byte[] value) {#setCachedImage-byte---}
```
public void setCachedImage(byte[] value)
```


设置缓存的光栅图像。

值：缓存的图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

