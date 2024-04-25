---
title: WmfDeviceIndependentBitmap
second_title: Aspose.Imaging for Java API Reference
description: The DeviceIndependentBitmap Object defines an image in device-independent bitmap DIB format
type: docs
weight: 27
url: /com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfDeviceIndependentBitmap extends MetaObject
```

The DeviceIndependentBitmap Object defines an image in device-independent bitmap (DIB) format
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getHeader()](#getHeader--) | Gets or sets either a BitmapCoreHeader Object (section 2.2.2.2) or a BitmapInfoHeader Object (section 2.2.2.3) that specifies information about the image |
| [setHeader(WmfBitmapBaseHeader value)](#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-) | Gets or sets either a BitmapCoreHeader Object (section 2.2.2.2) or a BitmapInfoHeader Object (section 2.2.2.3) that specifies information about the image |
| [getColorsData()](#getColorsData--) | Gets or sets an optional array of either RGBQuad Objects (section 2.2.2.20) or 16-bit unsigned integers that define a color table. |
| [setColorsData(byte[] value)](#setColorsData-byte---) | Gets or sets an optional array of either RGBQuad Objects (section 2.2.2.20) or 16-bit unsigned integers that define a color table. |
| [getAData()](#getAData--) | Gets or sets an array of bytes that define the image. |
| [setAData(byte[] value)](#setAData-byte---) | Gets or sets an array of bytes that define the image. |
| [getCachedImage()](#getCachedImage--) | Gets the cached raster image. |
| [setCachedImage(byte[] value)](#setCachedImage-byte---) | Sets the cached raster image. |
### WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap--}
```
public WmfDeviceIndependentBitmap()
```


### getHeader() {#getHeader--}
```
public WmfBitmapBaseHeader getHeader()
```


Gets or sets either a BitmapCoreHeader Object (section 2.2.2.2) or a BitmapInfoHeader Object (section 2.2.2.3) that specifies information about the image

**Returns:**
[WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
### setHeader(WmfBitmapBaseHeader value) {#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-}
```
public void setHeader(WmfBitmapBaseHeader value)
```


Gets or sets either a BitmapCoreHeader Object (section 2.2.2.2) or a BitmapInfoHeader Object (section 2.2.2.3) that specifies information about the image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader) |  |

### getColorsData() {#getColorsData--}
```
public byte[] getColorsData()
```


Gets or sets an optional array of either RGBQuad Objects (section 2.2.2.20) or 16-bit unsigned integers that define a color table. The size and contents of this field SHOULD be determined from the metafile record or object that contains this DeviceIndependentBitmap and from information in the DIBHeaderInfo field. See ColorUsage Enumeration (section 2.1.1.6) and BitCount Enumeration (section 2.1.1.3) for additional details

**Returns:**
byte[]
### setColorsData(byte[] value) {#setColorsData-byte---}
```
public void setColorsData(byte[] value)
```


Gets or sets an optional array of either RGBQuad Objects (section 2.2.2.20) or 16-bit unsigned integers that define a color table. The size and contents of this field SHOULD be determined from the metafile record or object that contains this DeviceIndependentBitmap and from information in the DIBHeaderInfo field. See ColorUsage Enumeration (section 2.1.1.6) and BitCount Enumeration (section 2.1.1.3) for additional details

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getAData() {#getAData--}
```
public byte[] getAData()
```


Gets or sets an array of bytes that define the image. The size and format of this data is determined by information in the DIBHeaderInfo field.

**Returns:**
byte[]
### setAData(byte[] value) {#setAData-byte---}
```
public void setAData(byte[] value)
```


Gets or sets an array of bytes that define the image. The size and format of this data is determined by information in the DIBHeaderInfo field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getCachedImage() {#getCachedImage--}
```
public final byte[] getCachedImage()
```


Gets the cached raster image.

Value: The cached image.

**Returns:**
byte[]
### setCachedImage(byte[] value) {#setCachedImage-byte---}
```
public void setCachedImage(byte[] value)
```


Sets the cached raster image.

Value: The cached image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

