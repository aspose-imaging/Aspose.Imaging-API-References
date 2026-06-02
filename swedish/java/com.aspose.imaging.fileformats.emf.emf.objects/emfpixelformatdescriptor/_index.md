---
title: "EmfPixelFormatDescriptor"
second_title: "Aspose.Imaging för Java API-referens"
description: "PixelFormatDescriptor-objektet kan användas i EMR_HEADER-poster avsnitt 2.3.4.2 för att ange pixelformatet för utskriftsytan för uppspelningsenhetens kontext."
type: docs
weight: 31
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPixelFormatDescriptor extends EmfObject
```

PixelFormatDescriptor-objektet kan användas i EMR\_HEADER‑poster (avsnitt 2.3.4.2) för att specificera pixelformatet för utsurfaces för uppspelnings‑enhetskontexten.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNSize()](#getNSize--) | Hämtar eller anger ett 16-bitars heltal som specificerar storleken, i byte, för denna datastruktur. |
| [setNSize(short value)](#setNSize-short-) | Hämtar eller anger ett 16-bitars heltal som specificerar storleken, i byte, för denna datastruktur. |
| [getNVersion()](#getNVersion--) | Hämtar eller anger ett 16-bitars heltal som MÅSTE sättas till 0x0001. |
| [setNVersion(short value)](#setNVersion-short-) | Hämtar eller anger ett 16-bitars heltal som MÅSTE sättas till 0x0001. |
| [getDwFlags()](#getDwFlags--) | Hämtar eller anger bitflaggor som specificerar egenskaperna för pixelbufferten som används för utskrift till ritytan. |
| [setDwFlags(int value)](#setDwFlags-int-) | Hämtar eller anger bitflaggor som specificerar egenskaperna för pixelbufferten som används för utskrift till ritytan. |
| [getIPixelType()](#getIPixelType--) | Hämtar eller anger typen av pixeldata PFD\_TYPE\_RGBA 0x00 Pixelformatet är RGBA. |
| [setIPixelType(byte value)](#setIPixelType-byte-) | Hämtar eller anger typen av pixeldata PFD\_TYPE\_RGBA 0x00 Pixelformatet är RGBA. |
| [getCColorBits()](#getCColorBits--) | Hämtar eller anger antalet bitar per pixel för RGBA-pixeltyper, exklusive alfa-bitplan. |
| [setCColorBits(byte value)](#setCColorBits-byte-) | Hämtar eller anger antalet bitar per pixel för RGBA-pixeltyper, exklusive alfa-bitplan. |
| [getCRedBits()](#getCRedBits--) | Hämtar eller anger antalet röda bitplan i varje RGBA-färgbuffert. |
| [setCRedBits(byte value)](#setCRedBits-byte-) | Hämtar eller anger antalet röda bitplan i varje RGBA-färgbuffert. |
| [getCRedShift()](#getCRedShift--) | Hämtar eller anger skiftantalet i bitar för röda bitplan i varje RGBA-färgbuffert. |
| [setCRedShift(byte value)](#setCRedShift-byte-) | Hämtar eller anger skiftantalet i bitar för röda bitplan i varje RGBA-färgbuffert. |
| [getCGreenBits()](#getCGreenBits--) | Hämtar eller anger antalet gröna bitplan i varje RGBA-färgbuffert. |
| [setCGreenBits(byte value)](#setCGreenBits-byte-) | Hämtar eller anger antalet gröna bitplan i varje RGBA-färgbuffert. |
| [getCGreenShift()](#getCGreenShift--) | Hämtar eller anger skiftantalet för gröna bitplan i varje RGBA-färgbuffert. |
| [setCGreenShift(byte value)](#setCGreenShift-byte-) | Hämtar eller anger skiftantalet för gröna bitplan i varje RGBA-färgbuffert. |
| [getCBlueBits()](#getCBlueBits--) | Hämtar eller anger antalet blåa bitplan i varje RGBA-färgbuffert. |
| [setCBlueBits(byte value)](#setCBlueBits-byte-) | Hämtar eller anger antalet blåa bitplan i varje RGBA-färgbuffert. |
| [getCBlueShift()](#getCBlueShift--) | Hämtar eller anger skiftantalet för blåa bitplan i varje RGBA-färgbuffert. |
| [setCBlueShift(byte value)](#setCBlueShift-byte-) | Hämtar eller anger skiftantalet för blåa bitplan i varje RGBA-färgbuffert. |
| [getCAlphaBits()](#getCAlphaBits--) | Hämtar eller anger antalet alfa-bitplan i varje RGBA-färgbuffert. |
| [setCAlphaBits(byte value)](#setCAlphaBits-byte-) | Hämtar eller anger antalet alfa-bitplan i varje RGBA-färgbuffert. |
| [getCAlphaShift()](#getCAlphaShift--) | Hämtar eller anger skiftantalet för alfa-bitplan i varje RGBA-färgbuffert. |
| [setCAlphaShift(byte value)](#setCAlphaShift-byte-) | Hämtar eller anger skiftantalet för alfa-bitplan i varje RGBA-färgbuffert. |
| [getCAccumBits()](#getCAccumBits--) | Hämtar eller anger det totala antalet bitplan i ackumuleringsbufferten. |
| [setCAccumBits(byte value)](#setCAccumBits-byte-) | Hämtar eller anger det totala antalet bitplan i ackumuleringsbufferten. |
| [getCAccumRedBits()](#getCAccumRedBits--) | Hämtar eller anger antalet röda bitplan i ackumuleringsbufferten. |
| [setCAccumRedBits(byte value)](#setCAccumRedBits-byte-) | Hämtar eller anger antalet röda bitplan i ackumuleringsbufferten. |
| [getCAccumGreenBits()](#getCAccumGreenBits--) | Hämtar eller anger antalet gröna bitplan i ackumuleringsbufferten. |
| [setCAccumGreenBits(byte value)](#setCAccumGreenBits-byte-) | Hämtar eller anger antalet gröna bitplan i ackumuleringsbufferten. |
| [getCAccumBlueBits()](#getCAccumBlueBits--) | Hämtar eller anger antalet blåa bitplan i ackumuleringsbufferten. |
| [setCAccumBlueBits(byte value)](#setCAccumBlueBits-byte-) | Hämtar eller anger antalet blåa bitplan i ackumuleringsbufferten. |
| [getCAccumAlphaBits()](#getCAccumAlphaBits--) | Hämtar eller anger antalet alfa-bitplan i ackumuleringsbufferten. |
| [setCAccumAlphaBits(byte value)](#setCAccumAlphaBits-byte-) | Hämtar eller anger antalet alfa-bitplan i ackumuleringsbufferten. |
| [getCDepthBits()](#getCDepthBits--) | Hämtar eller anger djupet på djupbufferten (z-axeln). |
| [setCDepthBits(byte value)](#setCDepthBits-byte-) | Hämtar eller anger djupet på djupbufferten (z-axeln). |
| [getCStencilBits()](#getCStencilBits--) | Hämtar eller anger djupet på stencil-bufferten. |
| [setCStencilBits(byte value)](#setCStencilBits-byte-) | Hämtar eller anger djupet på stencil-bufferten. |
| [getCAuxBuffers()](#getCAuxBuffers--) | Hämtar eller anger antalet hjälpbuffertar. |
| [setCAuxBuffers(byte value)](#setCAuxBuffers-byte-) | Hämtar eller anger antalet hjälpbuffertar. |
| [getILayerType()](#getILayerType--) | Hämtar eller anger Detta fält KAN ignoreras |
| [setILayerType(byte value)](#setILayerType-byte-) | Hämtar eller anger Detta fält KAN ignoreras |
| [getBReserved()](#getBReserved--) | Hämtar eller anger specificerar antalet överlagrings- och underlagringsplan. |
| [setBReserved(byte value)](#setBReserved-byte-) | Hämtar eller anger specificerar antalet överlagrings- och underlagringsplan. |
| [getDwLayerMask()](#getDwLayerMask--) | Hämtar eller anger Detta fält KAN ignoreras. |
| [setDwLayerMask(int value)](#setDwLayerMask-int-) | Hämtar eller anger Detta fält KAN ignoreras. |
| [getDwVisibleMask()](#getDwVisibleMask--) | Hämtar eller anger specificerar den transparenta färgen eller indexet för ett underlagringsplan. |
| [setDwVisibleMask(int value)](#setDwVisibleMask-int-) | Hämtar eller anger specificerar den transparenta färgen eller indexet för ett underlagringsplan. |
| [getDwDamageMask()](#getDwDamageMask--) | Hämtar eller anger Detta fält KAN ignoreras |
| [setDwDamageMask(int value)](#setDwDamageMask-int-) | Hämtar eller anger Detta fält KAN ignoreras |
### EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor--}
```
public EmfPixelFormatDescriptor()
```


### getNSize() {#getNSize--}
```
public short getNSize()
```


Hämtar eller anger ett 16-bitars heltal som specificerar storleken, i byte, för denna datastruktur.

**Returns:**
short
### setNSize(short value) {#setNSize-short-}
```
public void setNSize(short value)
```


Hämtar eller anger ett 16-bitars heltal som specificerar storleken, i byte, för denna datastruktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getNVersion() {#getNVersion--}
```
public short getNVersion()
```


Hämtar eller anger ett 16-bitars heltal som MÅSTE sättas till 0x0001.

**Returns:**
short
### setNVersion(short value) {#setNVersion-short-}
```
public void setNVersion(short value)
```


Hämtar eller anger ett 16-bitars heltal som MÅSTE sättas till 0x0001.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Hämtar eller anger bitflaggor som specificerar egenskaperna hos pixelbufferten som används för utmatning till ritytan. Dessa egenskaper är inte alla ömsesidigt uteslutande; kombinationer av flaggor är tillåtna, förutom där annat anges.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Hämtar eller anger bitflaggor som specificerar egenskaperna hos pixelbufferten som används för utmatning till ritytan. Dessa egenskaper är inte alla ömsesidigt uteslutande; kombinationer av flaggor är tillåtna, förutom där annat anges.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getIPixelType() {#getIPixelType--}
```
public byte getIPixelType()
```


Hämtar eller anger typen av pixeldata PFD\_TYPE\_RGBA 0x00 Pixelformatet är RGBA. PFD\_TYPE\_COLORINDEX 0x01 Varje pixel är ett index i en färgtabell.

**Returns:**
byte
### setIPixelType(byte value) {#setIPixelType-byte-}
```
public void setIPixelType(byte value)
```


Hämtar eller anger typen av pixeldata PFD\_TYPE\_RGBA 0x00 Pixelformatet är RGBA. PFD\_TYPE\_COLORINDEX 0x01 Varje pixel är ett index i en färgtabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCColorBits() {#getCColorBits--}
```
public byte getCColorBits()
```


Hämtar eller anger antalet bitar per pixel för RGBA-pixeltyper, exklusive alfabitplanen. För färgtabellspixlar är det storleken på varje färgtabellindex.

**Returns:**
byte
### setCColorBits(byte value) {#setCColorBits-byte-}
```
public void setCColorBits(byte value)
```


Hämtar eller anger antalet bitar per pixel för RGBA-pixeltyper, exklusive alfabitplanen. För färgtabellspixlar är det storleken på varje färgtabellindex.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCRedBits() {#getCRedBits--}
```
public byte getCRedBits()
```


Hämtar eller anger antalet röda bitplan i varje RGBA-färgbuffert.

**Returns:**
byte
### setCRedBits(byte value) {#setCRedBits-byte-}
```
public void setCRedBits(byte value)
```


Hämtar eller anger antalet röda bitplan i varje RGBA-färgbuffert.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCRedShift() {#getCRedShift--}
```
public byte getCRedShift()
```


Hämtar eller anger skiftantalet i bitar för röda bitplan i varje RGBA-färgbuffert.

**Returns:**
byte
### setCRedShift(byte value) {#setCRedShift-byte-}
```
public void setCRedShift(byte value)
```


Hämtar eller anger skiftantalet i bitar för röda bitplan i varje RGBA-färgbuffert.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCGreenBits() {#getCGreenBits--}
```
public byte getCGreenBits()
```


Hämtar eller anger antalet gröna bitplan i varje RGBA-färgbuffert.

**Returns:**
byte
### setCGreenBits(byte value) {#setCGreenBits-byte-}
```
public void setCGreenBits(byte value)
```


Hämtar eller anger antalet gröna bitplan i varje RGBA-färgbuffert.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCGreenShift() {#getCGreenShift--}
```
public byte getCGreenShift()
```


Hämtar eller anger skiftantalet för gröna bitplan i varje RGBA-färgbuffert.

**Returns:**
byte
### setCGreenShift(byte value) {#setCGreenShift-byte-}
```
public void setCGreenShift(byte value)
```


Hämtar eller anger skiftantalet för gröna bitplan i varje RGBA-färgbuffert.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCBlueBits() {#getCBlueBits--}
```
public byte getCBlueBits()
```


Hämtar eller anger antalet blåa bitplan i varje RGBA-färgbuffert.

**Returns:**
byte
### setCBlueBits(byte value) {#setCBlueBits-byte-}
```
public void setCBlueBits(byte value)
```


Hämtar eller anger antalet blåa bitplan i varje RGBA-färgbuffert.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCBlueShift() {#getCBlueShift--}
```
public byte getCBlueShift()
```


Hämtar eller anger skiftantalet för blåa bitplan i varje RGBA-färgbuffert.

**Returns:**
byte
### setCBlueShift(byte value) {#setCBlueShift-byte-}
```
public void setCBlueShift(byte value)
```


Hämtar eller anger skiftantalet för blåa bitplan i varje RGBA-färgbuffert.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCAlphaBits() {#getCAlphaBits--}
```
public byte getCAlphaBits()
```


Hämtar eller anger antalet alfa-bitplan i varje RGBA-färgbuffert.

**Returns:**
byte
### setCAlphaBits(byte value) {#setCAlphaBits-byte-}
```
public void setCAlphaBits(byte value)
```


Hämtar eller anger antalet alfa-bitplan i varje RGBA-färgbuffert.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCAlphaShift() {#getCAlphaShift--}
```
public byte getCAlphaShift()
```


Hämtar eller anger skiftantalet för alfa-bitplan i varje RGBA-färgbuffert.

**Returns:**
byte
### setCAlphaShift(byte value) {#setCAlphaShift-byte-}
```
public void setCAlphaShift(byte value)
```


Hämtar eller anger skiftantalet för alfa-bitplan i varje RGBA-färgbuffert.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCAccumBits() {#getCAccumBits--}
```
public byte getCAccumBits()
```


Hämtar eller anger det totala antalet bitplan i ackumuleringsbufferten.

**Returns:**
byte
### setCAccumBits(byte value) {#setCAccumBits-byte-}
```
public void setCAccumBits(byte value)
```


Hämtar eller anger det totala antalet bitplan i ackumuleringsbufferten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCAccumRedBits() {#getCAccumRedBits--}
```
public byte getCAccumRedBits()
```


Hämtar eller anger antalet röda bitplan i ackumuleringsbufferten.

**Returns:**
byte
### setCAccumRedBits(byte value) {#setCAccumRedBits-byte-}
```
public void setCAccumRedBits(byte value)
```


Hämtar eller anger antalet röda bitplan i ackumuleringsbufferten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCAccumGreenBits() {#getCAccumGreenBits--}
```
public byte getCAccumGreenBits()
```


Hämtar eller anger antalet gröna bitplan i ackumuleringsbufferten.

**Returns:**
byte
### setCAccumGreenBits(byte value) {#setCAccumGreenBits-byte-}
```
public void setCAccumGreenBits(byte value)
```


Hämtar eller anger antalet gröna bitplan i ackumuleringsbufferten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCAccumBlueBits() {#getCAccumBlueBits--}
```
public byte getCAccumBlueBits()
```


Hämtar eller anger antalet blåa bitplan i ackumuleringsbufferten.

**Returns:**
byte
### setCAccumBlueBits(byte value) {#setCAccumBlueBits-byte-}
```
public void setCAccumBlueBits(byte value)
```


Hämtar eller anger antalet blåa bitplan i ackumuleringsbufferten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCAccumAlphaBits() {#getCAccumAlphaBits--}
```
public byte getCAccumAlphaBits()
```


Hämtar eller anger antalet alfa-bitplan i ackumuleringsbufferten.

**Returns:**
byte
### setCAccumAlphaBits(byte value) {#setCAccumAlphaBits-byte-}
```
public void setCAccumAlphaBits(byte value)
```


Hämtar eller anger antalet alfa-bitplan i ackumuleringsbufferten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCDepthBits() {#getCDepthBits--}
```
public byte getCDepthBits()
```


Hämtar eller anger djupet på djupbufferten (z-axeln).

**Returns:**
byte
### setCDepthBits(byte value) {#setCDepthBits-byte-}
```
public void setCDepthBits(byte value)
```


Hämtar eller anger djupet på djupbufferten (z-axeln).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCStencilBits() {#getCStencilBits--}
```
public byte getCStencilBits()
```


Hämtar eller anger djupet på stencil-bufferten.

**Returns:**
byte
### setCStencilBits(byte value) {#setCStencilBits-byte-}
```
public void setCStencilBits(byte value)
```


Hämtar eller anger djupet på stencil-bufferten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCAuxBuffers() {#getCAuxBuffers--}
```
public byte getCAuxBuffers()
```


Hämtar eller anger specificerar antalet hjälpbuffertar. Hjälpbuffertar stöds inte.

**Returns:**
byte
### setCAuxBuffers(byte value) {#setCAuxBuffers-byte-}
```
public void setCAuxBuffers(byte value)
```


Hämtar eller anger specificerar antalet hjälpbuffertar. Hjälpbuffertar stöds inte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getILayerType() {#getILayerType--}
```
public byte getILayerType()
```


Hämtar eller anger Detta fält KAN ignoreras

**Returns:**
byte
### setILayerType(byte value) {#setILayerType-byte-}
```
public void setILayerType(byte value)
```


Hämtar eller anger Detta fält KAN ignoreras

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getBReserved() {#getBReserved--}
```
public byte getBReserved()
```


Hämtar eller anger specificerar antalet överlagrings- och underlagringsplan. Bitarna 0 till 3 specificerar upp till 15 överlagringsplan och bitarna 4 till 7 specificerar upp till 15 underlagringsplan.

**Returns:**
byte
### setBReserved(byte value) {#setBReserved-byte-}
```
public void setBReserved(byte value)
```


Hämtar eller anger specificerar antalet överlagrings- och underlagringsplan. Bitarna 0 till 3 specificerar upp till 15 överlagringsplan och bitarna 4 till 7 specificerar upp till 15 underlagringsplan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getDwLayerMask() {#getDwLayerMask--}
```
public int getDwLayerMask()
```


Hämtar eller anger Detta fält KAN ignoreras.

**Returns:**
int
### setDwLayerMask(int value) {#setDwLayerMask-int-}
```
public void setDwLayerMask(int value)
```


Hämtar eller anger Detta fält KAN ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDwVisibleMask() {#getDwVisibleMask--}
```
public int getDwVisibleMask()
```


Hämtar eller anger specificerar den transparenta färgen eller indexet för ett underlagringsplan. När pixeltypen är RGBA är dwVisibleMask ett transparent RGB-färgvärde. När pixeltypen är färgindex är det ett transparent indexvärde.

**Returns:**
int
### setDwVisibleMask(int value) {#setDwVisibleMask-int-}
```
public void setDwVisibleMask(int value)
```


Hämtar eller anger specificerar den transparenta färgen eller indexet för ett underlagringsplan. När pixeltypen är RGBA är dwVisibleMask ett transparent RGB-färgvärde. När pixeltypen är färgindex är det ett transparent indexvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDwDamageMask() {#getDwDamageMask--}
```
public int getDwDamageMask()
```


Hämtar eller anger Detta fält KAN ignoreras

**Returns:**
int
### setDwDamageMask(int value) {#setDwDamageMask-int-}
```
public void setDwDamageMask(int value)
```


Hämtar eller anger Detta fält KAN ignoreras

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

