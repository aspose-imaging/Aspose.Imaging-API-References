---
title: "EmfPixelFormatDescriptor"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das PixelFormatDescriptor-Objekt kann in EMR_HEADER‑Datensätzen Abschnitt 2.3.4.2 verwendet werden, um das Pixel‑Format der Ausgabefläche für den Wiedergabegeräte‑Kontext anzugeben."
type: docs
weight: 31
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPixelFormatDescriptor extends EmfObject
```

Das PixelFormatDescriptor‑Objekt kann in EMR\_HEADER‑Datensätzen (Abschnitt 2.3.4.2) verwendet werden, um das Pixelformat der Ausgabefläche für den Wiedergabe‑Gerätekontext anzugeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNSize()](#getNSize--) | Liest oder setzt einen 16‑Bit‑Integer, der die Größe dieser Datenstruktur in Byte angibt. |
| [setNSize(short value)](#setNSize-short-) | Liest oder setzt einen 16‑Bit‑Integer, der die Größe dieser Datenstruktur in Byte angibt. |
| [getNVersion()](#getNVersion--) | Liest oder setzt einen 16‑Bit‑Integer, der AUF 0x0001 gesetzt werden MUSS. |
| [setNVersion(short value)](#setNVersion-short-) | Liest oder setzt einen 16‑Bit‑Integer, der AUF 0x0001 gesetzt werden MUSS. |
| [getDwFlags()](#getDwFlags--) | Liest oder setzt Bit‑Flags, die Eigenschaften des Pixelpuffers angeben, der für die Ausgabe auf die Zeichenfläche verwendet wird. |
| [setDwFlags(int value)](#setDwFlags-int-) | Liest oder setzt Bit‑Flags, die Eigenschaften des Pixelpuffers angeben, der für die Ausgabe auf die Zeichenfläche verwendet wird. |
| [getIPixelType()](#getIPixelType--) | Liest oder setzt den Typ der Pixeldaten PFD\\_TYPE\\_RGBA 0x00. Das Pixel‑Format ist RGBA. |
| [setIPixelType(byte value)](#setIPixelType-byte-) | Liest oder setzt den Typ der Pixeldaten PFD\\_TYPE\\_RGBA 0x00. Das Pixel‑Format ist RGBA. |
| [getCColorBits()](#getCColorBits--) | Liest oder setzt die Anzahl der Bits pro Pixel für RGBA‑Pixelformate, ohne die Alpha‑Bitebenen. |
| [setCColorBits(byte value)](#setCColorBits-byte-) | Liest oder setzt die Anzahl der Bits pro Pixel für RGBA‑Pixelformate, ohne die Alpha‑Bitebenen. |
| [getCRedBits()](#getCRedBits--) | Liest oder setzt Gibt die Anzahl der roten Bitebenen in jedem RGBA‑Farbpuffer an. |
| [setCRedBits(byte value)](#setCRedBits-byte-) | Liest oder setzt Gibt die Anzahl der roten Bitebenen in jedem RGBA‑Farbpuffer an. |
| [getCRedShift()](#getCRedShift--) | Liest oder setzt Gibt die Verschiebungsanzahl in Bits für rote Bitebenen in jedem RGBA‑Farbpuffer an. |
| [setCRedShift(byte value)](#setCRedShift-byte-) | Liest oder setzt Gibt die Verschiebungsanzahl in Bits für rote Bitebenen in jedem RGBA‑Farbpuffer an. |
| [getCGreenBits()](#getCGreenBits--) | Liest oder setzt Gibt die Anzahl der grünen Bitebenen in jedem RGBA‑Farbpuffer an. |
| [setCGreenBits(byte value)](#setCGreenBits-byte-) | Liest oder setzt Gibt die Anzahl der grünen Bitebenen in jedem RGBA‑Farbpuffer an. |
| [getCGreenShift()](#getCGreenShift--) | Liest oder setzt Gibt die Verschiebungsanzahl für grüne Bitebenen in jedem RGBA‑Farbpuffer an. |
| [setCGreenShift(byte value)](#setCGreenShift-byte-) | Liest oder setzt Gibt die Verschiebungsanzahl für grüne Bitebenen in jedem RGBA‑Farbpuffer an. |
| [getCBlueBits()](#getCBlueBits--) | Liest oder setzt Gibt die Anzahl der blauen Bitebenen in jedem RGBA‑Farbpuffer an. |
| [setCBlueBits(byte value)](#setCBlueBits-byte-) | Liest oder setzt Gibt die Anzahl der blauen Bitebenen in jedem RGBA‑Farbpuffer an. |
| [getCBlueShift()](#getCBlueShift--) | Liest oder setzt Gibt die Verschiebungsanzahl für blaue Bitebenen in jedem RGBA‑Farbpuffer an. |
| [setCBlueShift(byte value)](#setCBlueShift-byte-) | Liest oder setzt Gibt die Verschiebungsanzahl für blaue Bitebenen in jedem RGBA‑Farbpuffer an. |
| [getCAlphaBits()](#getCAlphaBits--) | Liest oder setzt Gibt die Anzahl der Alpha‑Bitebenen in jedem RGBA‑Farbpuffer an. |
| [setCAlphaBits(byte value)](#setCAlphaBits-byte-) | Liest oder setzt Gibt die Anzahl der Alpha‑Bitebenen in jedem RGBA‑Farbpuffer an. |
| [getCAlphaShift()](#getCAlphaShift--) | Liest oder setzt Gibt die Verschiebungsanzahl für Alpha‑Bitebenen in jedem RGBA‑Farbpuffer an. |
| [setCAlphaShift(byte value)](#setCAlphaShift-byte-) | Liest oder setzt Gibt die Verschiebungsanzahl für Alpha‑Bitebenen in jedem RGBA‑Farbpuffer an. |
| [getCAccumBits()](#getCAccumBits--) | Liest oder setzt Gibt die Gesamtzahl der Bitebenen im Akkumulationspuffer an. |
| [setCAccumBits(byte value)](#setCAccumBits-byte-) | Liest oder setzt Gibt die Gesamtzahl der Bitebenen im Akkumulationspuffer an. |
| [getCAccumRedBits()](#getCAccumRedBits--) | Liest oder setzt Gibt die Anzahl der roten Bitebenen im Akkumulationspuffer an. |
| [setCAccumRedBits(byte value)](#setCAccumRedBits-byte-) | Liest oder setzt Gibt die Anzahl der roten Bitebenen im Akkumulationspuffer an. |
| [getCAccumGreenBits()](#getCAccumGreenBits--) | Liest oder setzt Gibt die Anzahl der grünen Bitebenen in der Akkumulation an. |
| [setCAccumGreenBits(byte value)](#setCAccumGreenBits-byte-) | Liest oder setzt Gibt die Anzahl der grünen Bitebenen in der Akkumulation an. |
| [getCAccumBlueBits()](#getCAccumBlueBits--) | Liest oder setzt Gibt die Anzahl der blauen Bitebenen im Akkumulationspuffer an. |
| [setCAccumBlueBits(byte value)](#setCAccumBlueBits-byte-) | Liest oder setzt Gibt die Anzahl der blauen Bitebenen im Akkumulationspuffer an. |
| [getCAccumAlphaBits()](#getCAccumAlphaBits--) | Liest oder setzt Gibt die Anzahl der Alpha‑Bitebenen im Akkumulationspuffer an. |
| [setCAccumAlphaBits(byte value)](#setCAccumAlphaBits-byte-) | Liest oder setzt Gibt die Anzahl der Alpha‑Bitebenen im Akkumulationspuffer an. |
| [getCDepthBits()](#getCDepthBits--) | Liest oder setzt Gibt die Tiefe des Tiefen‑ (z‑Achsen‑) Puffers an. |
| [setCDepthBits(byte value)](#setCDepthBits-byte-) | Liest oder setzt Gibt die Tiefe des Tiefen‑ (z‑Achsen‑) Puffers an. |
| [getCStencilBits()](#getCStencilBits--) | Liest oder setzt Gibt die Tiefe des Stencil‑Puffers an. |
| [setCStencilBits(byte value)](#setCStencilBits-byte-) | Liest oder setzt Gibt die Tiefe des Stencil‑Puffers an. |
| [getCAuxBuffers()](#getCAuxBuffers--) | Liest oder setzt Gibt die Anzahl der Hilfspuffer an. |
| [setCAuxBuffers(byte value)](#setCAuxBuffers-byte-) | Liest oder setzt Gibt die Anzahl der Hilfspuffer an. |
| [getILayerType()](#getILayerType--) | Liest oder setzt dieses Feld KANN ignoriert werden. |
| [setILayerType(byte value)](#setILayerType-byte-) | Liest oder setzt dieses Feld KANN ignoriert werden. |
| [getBReserved()](#getBReserved--) | Liest oder setzt gibt die Anzahl der Overlay- und Underlay-Ebenen an. |
| [setBReserved(byte value)](#setBReserved-byte-) | Liest oder setzt gibt die Anzahl der Overlay- und Underlay-Ebenen an. |
| [getDwLayerMask()](#getDwLayerMask--) | Liest oder setzt dieses Feld KANN ignoriert werden. |
| [setDwLayerMask(int value)](#setDwLayerMask-int-) | Liest oder setzt dieses Feld KANN ignoriert werden. |
| [getDwVisibleMask()](#getDwVisibleMask--) | Liest oder setzt gibt die transparente Farbe oder den Index einer Underlay-Ebene an. |
| [setDwVisibleMask(int value)](#setDwVisibleMask-int-) | Liest oder setzt gibt die transparente Farbe oder den Index einer Underlay-Ebene an. |
| [getDwDamageMask()](#getDwDamageMask--) | Liest oder setzt dieses Feld KANN ignoriert werden. |
| [setDwDamageMask(int value)](#setDwDamageMask-int-) | Liest oder setzt dieses Feld KANN ignoriert werden. |
### EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor--}
```
public EmfPixelFormatDescriptor()
```


### getNSize() {#getNSize--}
```
public short getNSize()
```


Liest oder setzt einen 16‑Bit‑Integer, der die Größe dieser Datenstruktur in Byte angibt.

**Returns:**
short
### setNSize(short value) {#setNSize-short-}
```
public void setNSize(short value)
```


Liest oder setzt einen 16‑Bit‑Integer, der die Größe dieser Datenstruktur in Byte angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getNVersion() {#getNVersion--}
```
public short getNVersion()
```


Liest oder setzt einen 16‑Bit‑Integer, der AUF 0x0001 gesetzt werden MUSS.

**Returns:**
short
### setNVersion(short value) {#setNVersion-short-}
```
public void setNVersion(short value)
```


Liest oder setzt einen 16‑Bit‑Integer, der AUF 0x0001 gesetzt werden MUSS.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Liest oder setzt Bit‑Flags, die Eigenschaften des Pixelpuffers angeben, der für die Ausgabe auf die Zeichenfläche verwendet wird. Diese Eigenschaften sind nicht alle gegenseitig ausschließend; Kombinationen von Flags sind zulässig, außer wo anders angegeben.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Liest oder setzt Bit‑Flags, die Eigenschaften des Pixelpuffers angeben, der für die Ausgabe auf die Zeichenfläche verwendet wird. Diese Eigenschaften sind nicht alle gegenseitig ausschließend; Kombinationen von Flags sind zulässig, außer wo anders angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getIPixelType() {#getIPixelType--}
```
public byte getIPixelType()
```


Liest oder setzt den Typ der Pixeldaten PFD\_TYPE\_RGBA 0x00 Das Pixelformat ist RGBA. PFD\_TYPE\_COLORINDEX 0x01 Jeder Pixel ist ein Index in einer Farbpalette.

**Returns:**
byte
### setIPixelType(byte value) {#setIPixelType-byte-}
```
public void setIPixelType(byte value)
```


Liest oder setzt den Typ der Pixeldaten PFD\_TYPE\_RGBA 0x00 Das Pixelformat ist RGBA. PFD\_TYPE\_COLORINDEX 0x01 Jeder Pixel ist ein Index in einer Farbpalette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCColorBits() {#getCColorBits--}
```
public byte getCColorBits()
```


Liest oder setzt die Anzahl der Bits pro Pixel für RGBA‑Pixelt­ypen, ohne die Alpha‑Bitebenen. Für Farbpaletten‑Pixel ist es die Größe jedes Farbpaletten‑Index.

**Returns:**
byte
### setCColorBits(byte value) {#setCColorBits-byte-}
```
public void setCColorBits(byte value)
```


Liest oder setzt die Anzahl der Bits pro Pixel für RGBA‑Pixelt­ypen, ohne die Alpha‑Bitebenen. Für Farbpaletten‑Pixel ist es die Größe jedes Farbpaletten‑Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCRedBits() {#getCRedBits--}
```
public byte getCRedBits()
```


Liest oder setzt Gibt die Anzahl der roten Bitebenen in jedem RGBA‑Farbpuffer an.

**Returns:**
byte
### setCRedBits(byte value) {#setCRedBits-byte-}
```
public void setCRedBits(byte value)
```


Liest oder setzt Gibt die Anzahl der roten Bitebenen in jedem RGBA‑Farbpuffer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCRedShift() {#getCRedShift--}
```
public byte getCRedShift()
```


Liest oder setzt Gibt die Verschiebungsanzahl in Bits für rote Bitebenen in jedem RGBA‑Farbpuffer an.

**Returns:**
byte
### setCRedShift(byte value) {#setCRedShift-byte-}
```
public void setCRedShift(byte value)
```


Liest oder setzt Gibt die Verschiebungsanzahl in Bits für rote Bitebenen in jedem RGBA‑Farbpuffer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCGreenBits() {#getCGreenBits--}
```
public byte getCGreenBits()
```


Liest oder setzt Gibt die Anzahl der grünen Bitebenen in jedem RGBA‑Farbpuffer an.

**Returns:**
byte
### setCGreenBits(byte value) {#setCGreenBits-byte-}
```
public void setCGreenBits(byte value)
```


Liest oder setzt Gibt die Anzahl der grünen Bitebenen in jedem RGBA‑Farbpuffer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCGreenShift() {#getCGreenShift--}
```
public byte getCGreenShift()
```


Liest oder setzt Gibt die Verschiebungsanzahl für grüne Bitebenen in jedem RGBA‑Farbpuffer an.

**Returns:**
byte
### setCGreenShift(byte value) {#setCGreenShift-byte-}
```
public void setCGreenShift(byte value)
```


Liest oder setzt Gibt die Verschiebungsanzahl für grüne Bitebenen in jedem RGBA‑Farbpuffer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCBlueBits() {#getCBlueBits--}
```
public byte getCBlueBits()
```


Liest oder setzt Gibt die Anzahl der blauen Bitebenen in jedem RGBA‑Farbpuffer an.

**Returns:**
byte
### setCBlueBits(byte value) {#setCBlueBits-byte-}
```
public void setCBlueBits(byte value)
```


Liest oder setzt Gibt die Anzahl der blauen Bitebenen in jedem RGBA‑Farbpuffer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCBlueShift() {#getCBlueShift--}
```
public byte getCBlueShift()
```


Liest oder setzt Gibt die Verschiebungsanzahl für blaue Bitebenen in jedem RGBA‑Farbpuffer an.

**Returns:**
byte
### setCBlueShift(byte value) {#setCBlueShift-byte-}
```
public void setCBlueShift(byte value)
```


Liest oder setzt Gibt die Verschiebungsanzahl für blaue Bitebenen in jedem RGBA‑Farbpuffer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCAlphaBits() {#getCAlphaBits--}
```
public byte getCAlphaBits()
```


Liest oder setzt Gibt die Anzahl der Alpha‑Bitebenen in jedem RGBA‑Farbpuffer an.

**Returns:**
byte
### setCAlphaBits(byte value) {#setCAlphaBits-byte-}
```
public void setCAlphaBits(byte value)
```


Liest oder setzt Gibt die Anzahl der Alpha‑Bitebenen in jedem RGBA‑Farbpuffer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCAlphaShift() {#getCAlphaShift--}
```
public byte getCAlphaShift()
```


Liest oder setzt Gibt die Verschiebungsanzahl für Alpha‑Bitebenen in jedem RGBA‑Farbpuffer an.

**Returns:**
byte
### setCAlphaShift(byte value) {#setCAlphaShift-byte-}
```
public void setCAlphaShift(byte value)
```


Liest oder setzt Gibt die Verschiebungsanzahl für Alpha‑Bitebenen in jedem RGBA‑Farbpuffer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCAccumBits() {#getCAccumBits--}
```
public byte getCAccumBits()
```


Liest oder setzt Gibt die Gesamtzahl der Bitebenen im Akkumulationspuffer an.

**Returns:**
byte
### setCAccumBits(byte value) {#setCAccumBits-byte-}
```
public void setCAccumBits(byte value)
```


Liest oder setzt Gibt die Gesamtzahl der Bitebenen im Akkumulationspuffer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCAccumRedBits() {#getCAccumRedBits--}
```
public byte getCAccumRedBits()
```


Liest oder setzt Gibt die Anzahl der roten Bitebenen im Akkumulationspuffer an.

**Returns:**
byte
### setCAccumRedBits(byte value) {#setCAccumRedBits-byte-}
```
public void setCAccumRedBits(byte value)
```


Liest oder setzt Gibt die Anzahl der roten Bitebenen im Akkumulationspuffer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCAccumGreenBits() {#getCAccumGreenBits--}
```
public byte getCAccumGreenBits()
```


Liest oder setzt Gibt die Anzahl der grünen Bitebenen in der Akkumulation an.

**Returns:**
byte
### setCAccumGreenBits(byte value) {#setCAccumGreenBits-byte-}
```
public void setCAccumGreenBits(byte value)
```


Liest oder setzt Gibt die Anzahl der grünen Bitebenen in der Akkumulation an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCAccumBlueBits() {#getCAccumBlueBits--}
```
public byte getCAccumBlueBits()
```


Liest oder setzt Gibt die Anzahl der blauen Bitebenen im Akkumulationspuffer an.

**Returns:**
byte
### setCAccumBlueBits(byte value) {#setCAccumBlueBits-byte-}
```
public void setCAccumBlueBits(byte value)
```


Liest oder setzt Gibt die Anzahl der blauen Bitebenen im Akkumulationspuffer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCAccumAlphaBits() {#getCAccumAlphaBits--}
```
public byte getCAccumAlphaBits()
```


Liest oder setzt Gibt die Anzahl der Alpha‑Bitebenen im Akkumulationspuffer an.

**Returns:**
byte
### setCAccumAlphaBits(byte value) {#setCAccumAlphaBits-byte-}
```
public void setCAccumAlphaBits(byte value)
```


Liest oder setzt Gibt die Anzahl der Alpha‑Bitebenen im Akkumulationspuffer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCDepthBits() {#getCDepthBits--}
```
public byte getCDepthBits()
```


Liest oder setzt Gibt die Tiefe des Tiefen‑ (z‑Achsen‑) Puffers an.

**Returns:**
byte
### setCDepthBits(byte value) {#setCDepthBits-byte-}
```
public void setCDepthBits(byte value)
```


Liest oder setzt Gibt die Tiefe des Tiefen‑ (z‑Achsen‑) Puffers an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCStencilBits() {#getCStencilBits--}
```
public byte getCStencilBits()
```


Liest oder setzt Gibt die Tiefe des Stencil‑Puffers an.

**Returns:**
byte
### setCStencilBits(byte value) {#setCStencilBits-byte-}
```
public void setCStencilBits(byte value)
```


Liest oder setzt Gibt die Tiefe des Stencil‑Puffers an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCAuxBuffers() {#getCAuxBuffers--}
```
public byte getCAuxBuffers()
```


Liest oder setzt gibt die Anzahl der Hilfspuffer an. Hilfspuffer werden nicht unterstützt.

**Returns:**
byte
### setCAuxBuffers(byte value) {#setCAuxBuffers-byte-}
```
public void setCAuxBuffers(byte value)
```


Liest oder setzt gibt die Anzahl der Hilfspuffer an. Hilfspuffer werden nicht unterstützt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getILayerType() {#getILayerType--}
```
public byte getILayerType()
```


Liest oder setzt dieses Feld KANN ignoriert werden.

**Returns:**
byte
### setILayerType(byte value) {#setILayerType-byte-}
```
public void setILayerType(byte value)
```


Liest oder setzt dieses Feld KANN ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getBReserved() {#getBReserved--}
```
public byte getBReserved()
```


Liest oder setzt gibt die Anzahl der Overlay‑ und Underlay‑Ebenen an. Bits 0 bis 3 geben bis zu 15 Overlay‑Ebenen an und Bits 4 bis 7 geben bis zu 15 Underlay‑Ebenen an.

**Returns:**
byte
### setBReserved(byte value) {#setBReserved-byte-}
```
public void setBReserved(byte value)
```


Liest oder setzt gibt die Anzahl der Overlay‑ und Underlay‑Ebenen an. Bits 0 bis 3 geben bis zu 15 Overlay‑Ebenen an und Bits 4 bis 7 geben bis zu 15 Underlay‑Ebenen an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getDwLayerMask() {#getDwLayerMask--}
```
public int getDwLayerMask()
```


Liest oder setzt dieses Feld KANN ignoriert werden.

**Returns:**
int
### setDwLayerMask(int value) {#setDwLayerMask-int-}
```
public void setDwLayerMask(int value)
```


Liest oder setzt dieses Feld KANN ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDwVisibleMask() {#getDwVisibleMask--}
```
public int getDwVisibleMask()
```


Liest oder setzt gibt die transparente Farbe oder den Index einer Underlay‑Ebene an. Wenn der Pixelt­yp RGBA ist, ist dwVisibleMask ein transparenter RGB‑Farbwert. Wenn der Pixelt­yp ein Farbindex ist, ist es ein transparenter Indexwert.

**Returns:**
int
### setDwVisibleMask(int value) {#setDwVisibleMask-int-}
```
public void setDwVisibleMask(int value)
```


Liest oder setzt gibt die transparente Farbe oder den Index einer Underlay‑Ebene an. Wenn der Pixelt­yp RGBA ist, ist dwVisibleMask ein transparenter RGB‑Farbwert. Wenn der Pixelt­yp ein Farbindex ist, ist es ein transparenter Indexwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDwDamageMask() {#getDwDamageMask--}
```
public int getDwDamageMask()
```


Liest oder setzt dieses Feld KANN ignoriert werden.

**Returns:**
int
### setDwDamageMask(int value) {#setDwDamageMask-int-}
```
public void setDwDamageMask(int value)
```


Liest oder setzt dieses Feld KANN ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

