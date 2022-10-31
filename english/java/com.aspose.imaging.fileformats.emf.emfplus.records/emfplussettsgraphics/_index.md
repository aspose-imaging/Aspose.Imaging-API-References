---
title: EmfPlusSetTsGraphics
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.
type: docs
weight: 67
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsGraphics extends EmfPlusTerminalServerRecordType
```

The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSetTsGraphics(EmfPlusRecord source)](#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusSetTsGraphics` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBasicVgaColors()](#getBasicVgaColors--) | Gets a value indicating whether [basic vga colors]. |
| [getHavePalette()](#getHavePalette--) | Gets a value indicating whether [have palette]. |
| [getAntiAliasMode()](#getAntiAliasMode--) | Gets or sets an 8-bit unsigned integer that specifies the quality of line rendering, including the type of line anti-aliasing. |
| [setAntiAliasMode(byte value)](#setAntiAliasMode-byte-) | Gets or sets an 8-bit unsigned integer that specifies the quality of line rendering, including the type of line anti-aliasing. |
| [getTextRenderHint()](#getTextRenderHint--) | Gets or sets an 8-bit unsigned integer that specifies the quality of text rendering, including the type of text anti-aliasing. |
| [setTextRenderHint(byte value)](#setTextRenderHint-byte-) | Gets or sets an 8-bit unsigned integer that specifies the quality of text rendering, including the type of text anti-aliasing. |
| [getCompositingMode()](#getCompositingMode--) | Gets or sets an 8-bit unsigned integer that specifies how source colors are combined with background colors. |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Gets or sets an 8-bit unsigned integer that specifies how source colors are combined with background colors. |
| [getCompositingQuality()](#getCompositingQuality--) | Gets or sets an 8-bit unsigned integer that specifies the degree of smoothing to apply to lines, curves and the edges of filled areas to make them appear more continuous or sharply defined. |
| [setCompositingQuality(byte value)](#setCompositingQuality-byte-) | Gets or sets an 8-bit unsigned integer that specifies the degree of smoothing to apply to lines, curves and the edges of filled areas to make them appear more continuous or sharply defined. |
| [getRenderOriginX()](#getRenderOriginX--) | Gets or sets a 16-bit signed integer, which is the horizontal coordinate of the origin for rendering halftoning and dithering matrixes. |
| [setRenderOriginX(short value)](#setRenderOriginX-short-) | Gets or sets a 16-bit signed integer, which is the horizontal coordinate of the origin for rendering halftoning and dithering matrixes. |
| [getRenderOriginY()](#getRenderOriginY--) | Gets or sets a 16-bit signed integer, which is the vertical coordinate of the origin for rendering halftoning and dithering matrixes. |
| [setRenderOriginY(short value)](#setRenderOriginY-short-) | Gets or sets a 16-bit signed integer, which is the vertical coordinate of the origin for rendering halftoning and dithering matrixes. |
| [getTextContrast()](#getTextContrast--) | Gets or sets a 16-bit unsigned integer that specifies the gamma correction value used for rendering anti-aliased and ClearType text. |
| [setTextContrast(short value)](#setTextContrast-short-) | Gets or sets a 16-bit unsigned integer that specifies the gamma correction value used for rendering anti-aliased and ClearType text. |
| [getFilterType()](#getFilterType--) | Gets or sets an 8-bit unsigned integer that specifies how scaling, including stretching and shrinking, is performed. |
| [setFilterType(byte value)](#setFilterType-byte-) | Gets or sets an 8-bit unsigned integer that specifies how scaling, including stretching and shrinking, is performed. |
| [getPixelOffset()](#getPixelOffset--) | Gets or sets an 8-bit unsigned integer that specifies the overall quality of the image and text-rendering process. |
| [setPixelOffset(byte value)](#setPixelOffset-byte-) | Gets or sets an 8-bit unsigned integer that specifies the overall quality of the image and text-rendering process. |
| [getWorldToDevice()](#getWorldToDevice--) | Gets or sets an 192-bit EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the world space to device space transforms. |
| [setWorldToDevice(Matrix value)](#setWorldToDevice-com.aspose.imaging.Matrix-) | Gets or sets an 192-bit EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the world space to device space transforms. |
| [getPalette()](#getPalette--) | Gets or sets an optional EmfPlusPalette object. |
| [setPalette(EmfPlusPalette value)](#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Gets or sets an optional EmfPlusPalette object. |
### EmfPlusSetTsGraphics(EmfPlusRecord source) {#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsGraphics(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusSetTsGraphics` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getBasicVgaColors() {#getBasicVgaColors--}
```
public boolean getBasicVgaColors()
```


Gets a value indicating whether [basic vga colors]. If set, the palette contains only the basic VGA colors.

Value: `true` if [basic vga colors]; otherwise, `false`.

**Returns:**
boolean
### getHavePalette() {#getHavePalette--}
```
public boolean getHavePalette()
```


Gets a value indicating whether [have palette]. If set, this record contains an EmfPlusPalette object (section 2.2.2.28) in the Palette field following the graphics state data.

Value: `true` if [have palette]; otherwise, `false`.

**Returns:**
boolean
### getAntiAliasMode() {#getAntiAliasMode--}
```
public byte getAntiAliasMode()
```


Gets or sets an 8-bit unsigned integer that specifies the quality of line rendering, including the type of line anti-aliasing. It MUST be defined in the SmoothingMode enumeration (section 2.1.1.28).

Value: The anti alias mode.

**Returns:**
byte
### setAntiAliasMode(byte value) {#setAntiAliasMode-byte-}
```
public void setAntiAliasMode(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies the quality of line rendering, including the type of line anti-aliasing. It MUST be defined in the SmoothingMode enumeration (section 2.1.1.28).

Value: The anti alias mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextRenderHint() {#getTextRenderHint--}
```
public byte getTextRenderHint()
```


Gets or sets an 8-bit unsigned integer that specifies the quality of text rendering, including the type of text anti-aliasing. It MUST be defined in the TextRenderingHint enumeration (section 2.1.1.32).

Value: The text render hint.

**Returns:**
byte
### setTextRenderHint(byte value) {#setTextRenderHint-byte-}
```
public void setTextRenderHint(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies the quality of text rendering, including the type of text anti-aliasing. It MUST be defined in the TextRenderingHint enumeration (section 2.1.1.32).

Value: The text render hint.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Gets or sets an 8-bit unsigned integer that specifies how source colors are combined with background colors. It MUST be a value in the CompositingMode enumeration (section 2.1.1.5).

Value: The compositing mode.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies how source colors are combined with background colors. It MUST be a value in the CompositingMode enumeration (section 2.1.1.5).

Value: The compositing mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompositingQuality() {#getCompositingQuality--}
```
public byte getCompositingQuality()
```


Gets or sets an 8-bit unsigned integer that specifies the degree of smoothing to apply to lines, curves and the edges of filled areas to make them appear more continuous or sharply defined. It MUST be a value in the CompositingQuality enumeration (section 2.1.1.6).

Value: The compositing quality.

**Returns:**
byte
### setCompositingQuality(byte value) {#setCompositingQuality-byte-}
```
public void setCompositingQuality(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies the degree of smoothing to apply to lines, curves and the edges of filled areas to make them appear more continuous or sharply defined. It MUST be a value in the CompositingQuality enumeration (section 2.1.1.6).

Value: The compositing quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRenderOriginX() {#getRenderOriginX--}
```
public short getRenderOriginX()
```


Gets or sets a 16-bit signed integer, which is the horizontal coordinate of the origin for rendering halftoning and dithering matrixes.

Value: The render origin x.

**Returns:**
short
### setRenderOriginX(short value) {#setRenderOriginX-short-}
```
public void setRenderOriginX(short value)
```


Gets or sets a 16-bit signed integer, which is the horizontal coordinate of the origin for rendering halftoning and dithering matrixes.

Value: The render origin x.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getRenderOriginY() {#getRenderOriginY--}
```
public short getRenderOriginY()
```


Gets or sets a 16-bit signed integer, which is the vertical coordinate of the origin for rendering halftoning and dithering matrixes.

Value: The render origin y.

**Returns:**
short
### setRenderOriginY(short value) {#setRenderOriginY-short-}
```
public void setRenderOriginY(short value)
```


Gets or sets a 16-bit signed integer, which is the vertical coordinate of the origin for rendering halftoning and dithering matrixes.

Value: The render origin y.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


Gets or sets a 16-bit unsigned integer that specifies the gamma correction value used for rendering anti-aliased and ClearType text. This value MUST be in the range 0 to 12, inclusive.

Value: The text contrast.

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


Gets or sets a 16-bit unsigned integer that specifies the gamma correction value used for rendering anti-aliased and ClearType text. This value MUST be in the range 0 to 12, inclusive.

Value: The text contrast.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getFilterType() {#getFilterType--}
```
public byte getFilterType()
```


Gets or sets an 8-bit unsigned integer that specifies how scaling, including stretching and shrinking, is performed. It MUST be a value in the FilterType enumeration (section 2.1.1.11).

Value: The type of the filter.

**Returns:**
byte
### setFilterType(byte value) {#setFilterType-byte-}
```
public void setFilterType(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies how scaling, including stretching and shrinking, is performed. It MUST be a value in the FilterType enumeration (section 2.1.1.11).

Value: The type of the filter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPixelOffset() {#getPixelOffset--}
```
public byte getPixelOffset()
```


Gets or sets an 8-bit unsigned integer that specifies the overall quality of the image and text-rendering process. It MUST be a value in the PixelOffsetMode enumeration (section 2.1.1.26).

Value: The pixel offset.

**Returns:**
byte
### setPixelOffset(byte value) {#setPixelOffset-byte-}
```
public void setPixelOffset(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies the overall quality of the image and text-rendering process. It MUST be a value in the PixelOffsetMode enumeration (section 2.1.1.26).

Value: The pixel offset.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getWorldToDevice() {#getWorldToDevice--}
```
public Matrix getWorldToDevice()
```


Gets or sets an 192-bit EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the world space to device space transforms.

Value: The world to device.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setWorldToDevice(Matrix value) {#setWorldToDevice-com.aspose.imaging.Matrix-}
```
public void setWorldToDevice(Matrix value)
```


Gets or sets an 192-bit EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the world space to device space transforms.

Value: The world to device.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getPalette() {#getPalette--}
```
public EmfPlusPalette getPalette()
```


Gets or sets an optional EmfPlusPalette object.

Value: The palette.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setPalette(EmfPlusPalette value) {#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setPalette(EmfPlusPalette value)
```


Gets or sets an optional EmfPlusPalette object.

Value: The palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

