---
title: Os22XBitmapHeader
second_title: Aspose.Imaging for Java API Reference
description: An OS/2 2.x OS22XBITMAPHEADER aka BITMAPCOREHEADER2.
type: docs
weight: 16
url: /com.aspose.imaging.fileformats.bmp/os22xbitmapheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class Os22XBitmapHeader extends BitmapInfoHeader
```

An OS/2 2.x OS22XBITMAPHEADER aka BITMAPCOREHEADER2.
## Methods

| Method | Description |
| --- | --- |
| [getUnits()](#getUnits--) | Gets the units. |
| [getReserved()](#getReserved--) | Gets the reserved. |
| [getRecording()](#getRecording--) | Gets the recording. |
| [getRendering()](#getRendering--) | Gets the rendering. |
| [getSize1()](#getSize1--) | Gets the size1. |
| [getSize2()](#getSize2--) | Gets the size2. |
| [getColorEncoding()](#getColorEncoding--) | Gets the color encoding. |
| [getIdentifier()](#getIdentifier--) | Gets the identifier. |
### getUnits() {#getUnits--}
```
public int getUnits()
```


Gets the units.

**Returns:**
int - Type of units used to measure resolution
### getReserved() {#getReserved--}
```
public int getReserved()
```


Gets the reserved.

**Returns:**
int - Pad structure to 4-byte boundary
### getRecording() {#getRecording--}
```
public int getRecording()
```


Gets the recording.

**Returns:**
int - Recording algorithm
### getRendering() {#getRendering--}
```
public int getRendering()
```


Gets the rendering.

**Returns:**
int - Halftoning algorithm used
### getSize1() {#getSize1--}
```
public int getSize1()
```


Gets the size1.

**Returns:**
int - Reserved for halftoning algorithm use
### getSize2() {#getSize2--}
```
public int getSize2()
```


Gets the size2.

**Returns:**
int - Reserved for halftoning algorithm use
### getColorEncoding() {#getColorEncoding--}
```
public int getColorEncoding()
```


Gets the color encoding.

**Returns:**
int - Color model used in bitmap
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Gets the identifier.

**Returns:**
int - Reserved for application use
