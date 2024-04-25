---
title: EmfPixelFormatDescriptor
second_title: Aspose.Imaging for Java API Reference
description: The PixelFormatDescriptor object can be used in EMR_HEADER records section 2.3.4.2 to specify the pixel format of the output surface for the playback device context.
type: docs
weight: 31
url: /com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPixelFormatDescriptor extends EmfObject
```

The PixelFormatDescriptor object can be used in EMR\_HEADER records (section 2.3.4.2) to specify the pixel format of the output surface for the playback device context.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getNSize()](#getNSize--) | Gets or sets a 16-bit integer that specifies the size, in bytes, of this data structure. |
| [setNSize(short value)](#setNSize-short-) | Gets or sets a 16-bit integer that specifies the size, in bytes, of this data structure. |
| [getNVersion()](#getNVersion--) | Gets or sets a 16-bit integer that MUST be set to 0x0001. |
| [setNVersion(short value)](#setNVersion-short-) | Gets or sets a 16-bit integer that MUST be set to 0x0001. |
| [getDwFlags()](#getDwFlags--) | Gets or sets bit flags that specify properties of the pixel buffer that is used for output to the drawing surface. |
| [setDwFlags(int value)](#setDwFlags-int-) | Gets or sets bit flags that specify properties of the pixel buffer that is used for output to the drawing surface. |
| [getIPixelType()](#getIPixelType--) | Gets or sets the type of pixel data PFD\_TYPE\_RGBA 0x00 The pixel format is RGBA. |
| [setIPixelType(byte value)](#setIPixelType-byte-) | Gets or sets the type of pixel data PFD\_TYPE\_RGBA 0x00 The pixel format is RGBA. |
| [getCColorBits()](#getCColorBits--) | Gets or sets the number of bits per pixel for RGBA pixel types, excluding the alpha bitplanes. |
| [setCColorBits(byte value)](#setCColorBits-byte-) | Gets or sets the number of bits per pixel for RGBA pixel types, excluding the alpha bitplanes. |
| [getCRedBits()](#getCRedBits--) | Gets or sets Specifies the number of red bitplanes in each RGBA color buffer |
| [setCRedBits(byte value)](#setCRedBits-byte-) | Gets or sets Specifies the number of red bitplanes in each RGBA color buffer |
| [getCRedShift()](#getCRedShift--) | Gets or sets Specifies the shift count in bits for red bitplanes in each RGBA color buffer. |
| [setCRedShift(byte value)](#setCRedShift-byte-) | Gets or sets Specifies the shift count in bits for red bitplanes in each RGBA color buffer. |
| [getCGreenBits()](#getCGreenBits--) | Gets or sets Specifies the number of green bitplanes in each RGBA color buffer |
| [setCGreenBits(byte value)](#setCGreenBits-byte-) | Gets or sets Specifies the number of green bitplanes in each RGBA color buffer |
| [getCGreenShift()](#getCGreenShift--) | Gets or sets Specifies the shift count for green bitplanes in each RGBA color buffer. |
| [setCGreenShift(byte value)](#setCGreenShift-byte-) | Gets or sets Specifies the shift count for green bitplanes in each RGBA color buffer. |
| [getCBlueBits()](#getCBlueBits--) | Gets or sets Specifies the number of blue bitplanes in each RGBA color buffer. |
| [setCBlueBits(byte value)](#setCBlueBits-byte-) | Gets or sets Specifies the number of blue bitplanes in each RGBA color buffer. |
| [getCBlueShift()](#getCBlueShift--) | Gets or sets Specifies the shift count for blue bitplanes in each RGBA color buffer. |
| [setCBlueShift(byte value)](#setCBlueShift-byte-) | Gets or sets Specifies the shift count for blue bitplanes in each RGBA color buffer. |
| [getCAlphaBits()](#getCAlphaBits--) | Gets or sets Specifies the number of alpha bitplanes in each RGBA color buffer |
| [setCAlphaBits(byte value)](#setCAlphaBits-byte-) | Gets or sets Specifies the number of alpha bitplanes in each RGBA color buffer |
| [getCAlphaShift()](#getCAlphaShift--) | Gets or sets Specifies the shift count for alpha bitplanes in each RGBA color buffer |
| [setCAlphaShift(byte value)](#setCAlphaShift-byte-) | Gets or sets Specifies the shift count for alpha bitplanes in each RGBA color buffer |
| [getCAccumBits()](#getCAccumBits--) | Gets or sets specifies the total number of bitplanes in the accumulation buffer. |
| [setCAccumBits(byte value)](#setCAccumBits-byte-) | Gets or sets specifies the total number of bitplanes in the accumulation buffer. |
| [getCAccumRedBits()](#getCAccumRedBits--) | Gets or sets specifies the number of red bitplanes in the accumulation buffer |
| [setCAccumRedBits(byte value)](#setCAccumRedBits-byte-) | Gets or sets specifies the number of red bitplanes in the accumulation buffer |
| [getCAccumGreenBits()](#getCAccumGreenBits--) | Gets or sets specifies the number of green bitplanes in the accumulation |
| [setCAccumGreenBits(byte value)](#setCAccumGreenBits-byte-) | Gets or sets specifies the number of green bitplanes in the accumulation |
| [getCAccumBlueBits()](#getCAccumBlueBits--) | Gets or sets specifies the number of blue bitplanes in the accumulation buffer. |
| [setCAccumBlueBits(byte value)](#setCAccumBlueBits-byte-) | Gets or sets specifies the number of blue bitplanes in the accumulation buffer. |
| [getCAccumAlphaBits()](#getCAccumAlphaBits--) | Gets or sets specifies the number of alpha bitplanes in the accumulation buffer |
| [setCAccumAlphaBits(byte value)](#setCAccumAlphaBits-byte-) | Gets or sets specifies the number of alpha bitplanes in the accumulation buffer |
| [getCDepthBits()](#getCDepthBits--) | Gets or sets specifies the depth of the depth (z-axis) buffer. |
| [setCDepthBits(byte value)](#setCDepthBits-byte-) | Gets or sets specifies the depth of the depth (z-axis) buffer. |
| [getCStencilBits()](#getCStencilBits--) | Gets or sets specifies the depth of the stencil buffer. |
| [setCStencilBits(byte value)](#setCStencilBits-byte-) | Gets or sets specifies the depth of the stencil buffer. |
| [getCAuxBuffers()](#getCAuxBuffers--) | Gets or sets specifies the number of auxiliary buffers. |
| [setCAuxBuffers(byte value)](#setCAuxBuffers-byte-) | Gets or sets specifies the number of auxiliary buffers. |
| [getILayerType()](#getILayerType--) | Gets or sets This field MAY be ignored |
| [setILayerType(byte value)](#setILayerType-byte-) | Gets or sets This field MAY be ignored |
| [getBReserved()](#getBReserved--) | Gets or sets specifies the number of overlay and underlay planes. |
| [setBReserved(byte value)](#setBReserved-byte-) | Gets or sets specifies the number of overlay and underlay planes. |
| [getDwLayerMask()](#getDwLayerMask--) | Gets or sets This field MAY be ignored. |
| [setDwLayerMask(int value)](#setDwLayerMask-int-) | Gets or sets This field MAY be ignored. |
| [getDwVisibleMask()](#getDwVisibleMask--) | Gets or sets specifies the transparent color or index of an underlay plane. |
| [setDwVisibleMask(int value)](#setDwVisibleMask-int-) | Gets or sets specifies the transparent color or index of an underlay plane. |
| [getDwDamageMask()](#getDwDamageMask--) | Gets or sets This field MAY be ignored |
| [setDwDamageMask(int value)](#setDwDamageMask-int-) | Gets or sets This field MAY be ignored |
### EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor--}
```
public EmfPixelFormatDescriptor()
```


### getNSize() {#getNSize--}
```
public short getNSize()
```


Gets or sets a 16-bit integer that specifies the size, in bytes, of this data structure.

**Returns:**
short
### setNSize(short value) {#setNSize-short-}
```
public void setNSize(short value)
```


Gets or sets a 16-bit integer that specifies the size, in bytes, of this data structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getNVersion() {#getNVersion--}
```
public short getNVersion()
```


Gets or sets a 16-bit integer that MUST be set to 0x0001.

**Returns:**
short
### setNVersion(short value) {#setNVersion-short-}
```
public void setNVersion(short value)
```


Gets or sets a 16-bit integer that MUST be set to 0x0001.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Gets or sets bit flags that specify properties of the pixel buffer that is used for output to the drawing surface. These properties are not all mutually exclusive; combinations of flags are allowed, except where noted otherwise.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Gets or sets bit flags that specify properties of the pixel buffer that is used for output to the drawing surface. These properties are not all mutually exclusive; combinations of flags are allowed, except where noted otherwise.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getIPixelType() {#getIPixelType--}
```
public byte getIPixelType()
```


Gets or sets the type of pixel data PFD\_TYPE\_RGBA 0x00 The pixel format is RGBA. PFD\_TYPE\_COLORINDEX 0x01 Each pixel is an index in a color table.

**Returns:**
byte
### setIPixelType(byte value) {#setIPixelType-byte-}
```
public void setIPixelType(byte value)
```


Gets or sets the type of pixel data PFD\_TYPE\_RGBA 0x00 The pixel format is RGBA. PFD\_TYPE\_COLORINDEX 0x01 Each pixel is an index in a color table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCColorBits() {#getCColorBits--}
```
public byte getCColorBits()
```


Gets or sets the number of bits per pixel for RGBA pixel types, excluding the alpha bitplanes. For color table pixels, it is the size of each color table index

**Returns:**
byte
### setCColorBits(byte value) {#setCColorBits-byte-}
```
public void setCColorBits(byte value)
```


Gets or sets the number of bits per pixel for RGBA pixel types, excluding the alpha bitplanes. For color table pixels, it is the size of each color table index

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCRedBits() {#getCRedBits--}
```
public byte getCRedBits()
```


Gets or sets Specifies the number of red bitplanes in each RGBA color buffer

**Returns:**
byte
### setCRedBits(byte value) {#setCRedBits-byte-}
```
public void setCRedBits(byte value)
```


Gets or sets Specifies the number of red bitplanes in each RGBA color buffer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCRedShift() {#getCRedShift--}
```
public byte getCRedShift()
```


Gets or sets Specifies the shift count in bits for red bitplanes in each RGBA color buffer.

**Returns:**
byte
### setCRedShift(byte value) {#setCRedShift-byte-}
```
public void setCRedShift(byte value)
```


Gets or sets Specifies the shift count in bits for red bitplanes in each RGBA color buffer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCGreenBits() {#getCGreenBits--}
```
public byte getCGreenBits()
```


Gets or sets Specifies the number of green bitplanes in each RGBA color buffer

**Returns:**
byte
### setCGreenBits(byte value) {#setCGreenBits-byte-}
```
public void setCGreenBits(byte value)
```


Gets or sets Specifies the number of green bitplanes in each RGBA color buffer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCGreenShift() {#getCGreenShift--}
```
public byte getCGreenShift()
```


Gets or sets Specifies the shift count for green bitplanes in each RGBA color buffer.

**Returns:**
byte
### setCGreenShift(byte value) {#setCGreenShift-byte-}
```
public void setCGreenShift(byte value)
```


Gets or sets Specifies the shift count for green bitplanes in each RGBA color buffer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCBlueBits() {#getCBlueBits--}
```
public byte getCBlueBits()
```


Gets or sets Specifies the number of blue bitplanes in each RGBA color buffer.

**Returns:**
byte
### setCBlueBits(byte value) {#setCBlueBits-byte-}
```
public void setCBlueBits(byte value)
```


Gets or sets Specifies the number of blue bitplanes in each RGBA color buffer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCBlueShift() {#getCBlueShift--}
```
public byte getCBlueShift()
```


Gets or sets Specifies the shift count for blue bitplanes in each RGBA color buffer.

**Returns:**
byte
### setCBlueShift(byte value) {#setCBlueShift-byte-}
```
public void setCBlueShift(byte value)
```


Gets or sets Specifies the shift count for blue bitplanes in each RGBA color buffer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCAlphaBits() {#getCAlphaBits--}
```
public byte getCAlphaBits()
```


Gets or sets Specifies the number of alpha bitplanes in each RGBA color buffer

**Returns:**
byte
### setCAlphaBits(byte value) {#setCAlphaBits-byte-}
```
public void setCAlphaBits(byte value)
```


Gets or sets Specifies the number of alpha bitplanes in each RGBA color buffer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCAlphaShift() {#getCAlphaShift--}
```
public byte getCAlphaShift()
```


Gets or sets Specifies the shift count for alpha bitplanes in each RGBA color buffer

**Returns:**
byte
### setCAlphaShift(byte value) {#setCAlphaShift-byte-}
```
public void setCAlphaShift(byte value)
```


Gets or sets Specifies the shift count for alpha bitplanes in each RGBA color buffer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCAccumBits() {#getCAccumBits--}
```
public byte getCAccumBits()
```


Gets or sets specifies the total number of bitplanes in the accumulation buffer.

**Returns:**
byte
### setCAccumBits(byte value) {#setCAccumBits-byte-}
```
public void setCAccumBits(byte value)
```


Gets or sets specifies the total number of bitplanes in the accumulation buffer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCAccumRedBits() {#getCAccumRedBits--}
```
public byte getCAccumRedBits()
```


Gets or sets specifies the number of red bitplanes in the accumulation buffer

**Returns:**
byte
### setCAccumRedBits(byte value) {#setCAccumRedBits-byte-}
```
public void setCAccumRedBits(byte value)
```


Gets or sets specifies the number of red bitplanes in the accumulation buffer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCAccumGreenBits() {#getCAccumGreenBits--}
```
public byte getCAccumGreenBits()
```


Gets or sets specifies the number of green bitplanes in the accumulation

**Returns:**
byte
### setCAccumGreenBits(byte value) {#setCAccumGreenBits-byte-}
```
public void setCAccumGreenBits(byte value)
```


Gets or sets specifies the number of green bitplanes in the accumulation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCAccumBlueBits() {#getCAccumBlueBits--}
```
public byte getCAccumBlueBits()
```


Gets or sets specifies the number of blue bitplanes in the accumulation buffer.

**Returns:**
byte
### setCAccumBlueBits(byte value) {#setCAccumBlueBits-byte-}
```
public void setCAccumBlueBits(byte value)
```


Gets or sets specifies the number of blue bitplanes in the accumulation buffer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCAccumAlphaBits() {#getCAccumAlphaBits--}
```
public byte getCAccumAlphaBits()
```


Gets or sets specifies the number of alpha bitplanes in the accumulation buffer

**Returns:**
byte
### setCAccumAlphaBits(byte value) {#setCAccumAlphaBits-byte-}
```
public void setCAccumAlphaBits(byte value)
```


Gets or sets specifies the number of alpha bitplanes in the accumulation buffer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCDepthBits() {#getCDepthBits--}
```
public byte getCDepthBits()
```


Gets or sets specifies the depth of the depth (z-axis) buffer.

**Returns:**
byte
### setCDepthBits(byte value) {#setCDepthBits-byte-}
```
public void setCDepthBits(byte value)
```


Gets or sets specifies the depth of the depth (z-axis) buffer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCStencilBits() {#getCStencilBits--}
```
public byte getCStencilBits()
```


Gets or sets specifies the depth of the stencil buffer.

**Returns:**
byte
### setCStencilBits(byte value) {#setCStencilBits-byte-}
```
public void setCStencilBits(byte value)
```


Gets or sets specifies the depth of the stencil buffer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCAuxBuffers() {#getCAuxBuffers--}
```
public byte getCAuxBuffers()
```


Gets or sets specifies the number of auxiliary buffers. Auxiliary buffers are not supported

**Returns:**
byte
### setCAuxBuffers(byte value) {#setCAuxBuffers-byte-}
```
public void setCAuxBuffers(byte value)
```


Gets or sets specifies the number of auxiliary buffers. Auxiliary buffers are not supported

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getILayerType() {#getILayerType--}
```
public byte getILayerType()
```


Gets or sets This field MAY be ignored

**Returns:**
byte
### setILayerType(byte value) {#setILayerType-byte-}
```
public void setILayerType(byte value)
```


Gets or sets This field MAY be ignored

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBReserved() {#getBReserved--}
```
public byte getBReserved()
```


Gets or sets specifies the number of overlay and underlay planes. Bits 0 through 3 specify up to 15 overlay planes and bits 4 through 7 specify up to 15 underlay planes

**Returns:**
byte
### setBReserved(byte value) {#setBReserved-byte-}
```
public void setBReserved(byte value)
```


Gets or sets specifies the number of overlay and underlay planes. Bits 0 through 3 specify up to 15 overlay planes and bits 4 through 7 specify up to 15 underlay planes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getDwLayerMask() {#getDwLayerMask--}
```
public int getDwLayerMask()
```


Gets or sets This field MAY be ignored.

**Returns:**
int
### setDwLayerMask(int value) {#setDwLayerMask-int-}
```
public void setDwLayerMask(int value)
```


Gets or sets This field MAY be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDwVisibleMask() {#getDwVisibleMask--}
```
public int getDwVisibleMask()
```


Gets or sets specifies the transparent color or index of an underlay plane. When the pixel type is RGBA, dwVisibleMask is a transparent RGB color value. When the pixel type is color index, it is a transparent index value.

**Returns:**
int
### setDwVisibleMask(int value) {#setDwVisibleMask-int-}
```
public void setDwVisibleMask(int value)
```


Gets or sets specifies the transparent color or index of an underlay plane. When the pixel type is RGBA, dwVisibleMask is a transparent RGB color value. When the pixel type is color index, it is a transparent index value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDwDamageMask() {#getDwDamageMask--}
```
public int getDwDamageMask()
```


Gets or sets This field MAY be ignored

**Returns:**
int
### setDwDamageMask(int value) {#setDwDamageMask-int-}
```
public void setDwDamageMask(int value)
```


Gets or sets This field MAY be ignored

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

