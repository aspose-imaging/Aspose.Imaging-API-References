---
title: BitmapInfoHeader
second_title: Aspose.Imaging for Java API Reference
description: Specifies BITMAPINFOHEADER.
type: docs
weight: 12
url: /java/com.aspose.imaging.fileformats.bmp/bitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader)
```
public class BitmapInfoHeader extends BitmapCoreHeader
```

Specifies BITMAPINFOHEADER. OS Support: Windows NT, 3.1x or later. Features: Adds 16 bpp and 32 bpp formats. Adds RLE compression.
## Methods

| Method | Description |
| --- | --- |
| [getBitmapCompression()](#getBitmapCompression--) | Gets bitmap compression. |
| [setBitmapCompression(long value)](#setBitmapCompression-long-) | Sets bitmap compression. |
| [getBitmapImageSize()](#getBitmapImageSize--) | Gets specifies bitmap raw data size in bytes. |
| [setBitmapImageSize(long value)](#setBitmapImageSize-long-) | Sets specifies bitmap raw data size in bytes. |
| [getBitmapXPelsPerMeter()](#getBitmapXPelsPerMeter--) | Gets horizontal pixels resolution. |
| [setBitmapXPelsPerMeter(int value)](#setBitmapXPelsPerMeter-int-) | Gets or sets horizontal pixels resolution. |
| [getBitmapYPelsPerMeter()](#getBitmapYPelsPerMeter--) | Gets or sets vertical pixels resolution. |
| [setBitmapYPelsPerMeter(int value)](#setBitmapYPelsPerMeter-int-) | Gets or sets vertical pixels resolution. |
| [getBitmapColorsUsed()](#getBitmapColorsUsed--) | Gets number of palette colors used. |
| [setBitmapColorsUsed(long value)](#setBitmapColorsUsed-long-) | Gets or sets number of palette colors used. |
| [getBitmapColorsImportant()](#getBitmapColorsImportant--) | Gets or sets number of important palette colors. |
| [setBitmapColorsImportant(long value)](#setBitmapColorsImportant-long-) | Gets or sets number of important palette colors. |
| [getExtraBitMasks()](#getExtraBitMasks--) | Gets or sets the extra bit masks. |
| [setExtraBitMasks(int[] value)](#setExtraBitMasks-int---) | Gets or sets the extra bit masks. |
### getBitmapCompression() {#getBitmapCompression--}
```
public long getBitmapCompression()
```


Gets bitmap compression.

**Returns:**
long - bitmap compression.
### setBitmapCompression(long value) {#setBitmapCompression-long-}
```
public void setBitmapCompression(long value)
```


Sets bitmap compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | bitmap compression. |

### getBitmapImageSize() {#getBitmapImageSize--}
```
public long getBitmapImageSize()
```


Gets specifies bitmap raw data size in bytes.

**Returns:**
long - bitmap raw data size in bytes.
### setBitmapImageSize(long value) {#setBitmapImageSize-long-}
```
public void setBitmapImageSize(long value)
```


Sets specifies bitmap raw data size in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | bitmap raw data size in bytes. |

### getBitmapXPelsPerMeter() {#getBitmapXPelsPerMeter--}
```
public int getBitmapXPelsPerMeter()
```


Gets horizontal pixels resolution.

**Returns:**
int - horizontal pixels resolution.
### setBitmapXPelsPerMeter(int value) {#setBitmapXPelsPerMeter-int-}
```
public void setBitmapXPelsPerMeter(int value)
```


Gets or sets horizontal pixels resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | horizontal pixels resolution. |

### getBitmapYPelsPerMeter() {#getBitmapYPelsPerMeter--}
```
public int getBitmapYPelsPerMeter()
```


Gets or sets vertical pixels resolution.

**Returns:**
int - vertical pixels resolution.
### setBitmapYPelsPerMeter(int value) {#setBitmapYPelsPerMeter-int-}
```
public void setBitmapYPelsPerMeter(int value)
```


Gets or sets vertical pixels resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | vertical pixels resolution. |

### getBitmapColorsUsed() {#getBitmapColorsUsed--}
```
public long getBitmapColorsUsed()
```


Gets number of palette colors used.

**Returns:**
long - number of palette colors used.
### setBitmapColorsUsed(long value) {#setBitmapColorsUsed-long-}
```
public void setBitmapColorsUsed(long value)
```


Gets or sets number of palette colors used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | number of palette colors used. |

### getBitmapColorsImportant() {#getBitmapColorsImportant--}
```
public long getBitmapColorsImportant()
```


Gets or sets number of important palette colors.

**Returns:**
long - number of important palette colors.
### setBitmapColorsImportant(long value) {#setBitmapColorsImportant-long-}
```
public void setBitmapColorsImportant(long value)
```


Gets or sets number of important palette colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | number of important palette colors. |

### getExtraBitMasks() {#getExtraBitMasks--}
```
public int[] getExtraBitMasks()
```


Gets or sets the extra bit masks. Present only in case the DIB header is the BITMAPINFOHEADER and the `BitmapCompression` is set to either `BitmapCompression.Bitfields` (RGB) or `BitmapCompression.AlphaBitfields` (RGBA).

**Returns:**
int[] - the extra bit masks.
### setExtraBitMasks(int[] value) {#setExtraBitMasks-int---}
```
public void setExtraBitMasks(int[] value)
```


Gets or sets the extra bit masks. Present only in case the DIB header is the BITMAPINFOHEADER and the `BitmapCompression` is set to either `BitmapCompression.Bitfields` (RGB) or `BitmapCompression.AlphaBitfields` (RGBA).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | the extra bit masks. |

