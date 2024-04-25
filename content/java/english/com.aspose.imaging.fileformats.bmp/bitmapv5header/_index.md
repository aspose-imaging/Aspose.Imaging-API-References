---
title: BitmapV5Header
second_title: Aspose.Imaging for Java API Reference
description: The BitmapV5Header structure is the bitmap information header file.
type: docs
weight: 14
url: /com.aspose.imaging.fileformats.bmp/bitmapv5header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader), [com.aspose.imaging.fileformats.bmp.BitmapV4Header](../../com.aspose.imaging.fileformats.bmp/bitmapv4header)
```
public class BitmapV5Header extends BitmapV4Header
```

The BitmapV5Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.

If bV5Height is negative, indicating a top-down DIB, bV5Compression must be either BI\_RGB or BI\_BITFIELDS. Top-down DIBs cannot be compressed. The Independent Color Management interface (ICM) 2.0 allows International Color Consortium (ICC) color profiles to be linked or embedded in DIBs (DIBs). See Using Structures for more information. When a DIB is loaded into memory, the profile data (if present) should follow the color table, and the bV5ProfileData should provide the offset of the profile data from the beginning of the BITMAPV5HEADER structure. The value stored in bV5ProfileData will be different from the value returned by the sizeof operator given the BITMAPV5HEADER argument, because bV5ProfileData is the offset in bytes from the beginning of the BITMAPV5HEADER structure to the start of the profile data. (Bitmap bits do not follow the color table in memory). Applications should modify the bV5ProfileData member after loading the DIB into memory. For packed DIBs, the profile data should follow the bitmap bits similar to the file format. The bV5ProfileData member should still give the offset of the profile data from the beginning of the BITMAPV5HEADER. Applications should access the profile data only when bV5Size equals the size of the BITMAPV5HEADER and bV5CSType equals PROFILE\_EMBEDDED or PROFILE\_LINKED.
## Constructors

| Constructor | Description |
| --- | --- |
| [BitmapV5Header()](#BitmapV5Header--) | Initializes a new instance of the `BitmapV5Header` class. |
| [BitmapV5Header(byte[] bytes)](#BitmapV5Header-byte---) | Initializes a new instance of the `BitmapV5Header` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIntent()](#getIntent--) | Gets the rendering intent for bitmap. |
| [setIntent(long value)](#setIntent-long-) | Sets the rendering intent for bitmap. |
| [getProfileData()](#getProfileData--) | Gets the profile data. |
| [setProfileData(long value)](#setProfileData-long-) | Sets the profile data. |
| [getProfileSize()](#getProfileSize--) | Gets the size of the profile. |
| [setProfileSize(long value)](#setProfileSize-long-) | Sets the size of the profile. |
| [getReserved()](#getReserved--) | Gets the reserved member. |
| [setReserved(long value)](#setReserved-long-) | Sets the reserved member. |
### BitmapV5Header() {#BitmapV5Header--}
```
public BitmapV5Header()
```


Initializes a new instance of the `BitmapV5Header` class.

### BitmapV5Header(byte[] bytes) {#BitmapV5Header-byte---}
```
public BitmapV5Header(byte[] bytes)
```


Initializes a new instance of the `BitmapV5Header` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | byte[] | The bytes. |

### getIntent() {#getIntent--}
```
public long getIntent()
```


Gets the rendering intent for bitmap.

**Returns:**
long - The intent.
### setIntent(long value) {#setIntent-long-}
```
public void setIntent(long value)
```


Sets the rendering intent for bitmap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The intent. |

### getProfileData() {#getProfileData--}
```
public long getProfileData()
```


Gets the profile data.

**Returns:**
long - The profile data.
### setProfileData(long value) {#setProfileData-long-}
```
public void setProfileData(long value)
```


Sets the profile data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The profile data. |

### getProfileSize() {#getProfileSize--}
```
public long getProfileSize()
```


Gets the size of the profile.

**Returns:**
long - The size of the profile.
### setProfileSize(long value) {#setProfileSize-long-}
```
public void setProfileSize(long value)
```


Sets the size of the profile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The size of the profile. |

### getReserved() {#getReserved--}
```
public long getReserved()
```


Gets the reserved member.

**Returns:**
long - The reserved value.
### setReserved(long value) {#setReserved-long-}
```
public void setReserved(long value)
```


Sets the reserved member.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The reserved value. |

