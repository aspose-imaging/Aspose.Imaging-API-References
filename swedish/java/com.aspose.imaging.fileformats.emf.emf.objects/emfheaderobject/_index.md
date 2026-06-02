---
title: "EmfHeaderObject"
second_title: "Aspose.Imaging för Java API-referens"
description: "Header-objektet definierar EMF‑metafilsrubriken."
type: docs
weight: 20
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfHeaderObject extends EmfObject
```

Header-objektet definierar EMF-metafilsheadern. Det specificerar egenskaperna för enheten där bilden i metafilen skapades.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfHeaderObject()](#EmfHeaderObject--) | Initierar en ny instans av klassen `EmfHeaderObject`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar de rektangulära inklusiva gränserna i enhetsenheter för den minsta rektangel som kan ritas runt bilden som lagras i metafilen. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar de rektangulära inklusiva gränserna i enhetsenheter för den minsta rektangel som kan ritas runt bilden som lagras i metafilen. |
| [getFrame()](#getFrame--) | Hämtar eller anger ett WMF RectL-objekt som specificerar de rektangulära inklusiva dimensionerna, i .01 millimeterenheter, för en rektangel som omger bilden som lagras i metafilen. |
| [setFrame(Rectangle value)](#setFrame-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL-objekt som specificerar de rektangulära inklusiva dimensionerna, i .01 millimeterenheter, för en rektangel som omger bilden som lagras i metafilen. |
| [getRecordSignature()](#getRecordSignature--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar postens signatur. |
| [setRecordSignature(int value)](#setRecordSignature-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar postens signatur. |
| [getVersion()](#getVersion--) | Hämtar eller anger Version (4 byte): Ett 32-bitars osignerat heltal som specificerar EMF-metafils interoperabilitet. |
| [setVersion(int value)](#setVersion-int-) | Hämtar eller anger Version (4 byte): Ett 32-bitars osignerat heltal som specificerar EMF-metafils interoperabilitet. |
| [getBytes()](#getBytes--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på metafilen, i byte. |
| [setBytes(int value)](#setBytes-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på metafilen, i byte. |
| [getRecords()](#getRecords--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet poster i metafilen. |
| [setRecords(int value)](#setRecords-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet poster i metafilen. |
| [getHandles()](#getHandles--) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar antalet grafikobjekt som kommer att användas under bearbetning av metafilen. |
| [setHandles(short value)](#setHandles-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar antalet grafikobjekt som kommer att användas under bearbetning av metafilen. |
| [getReserved()](#getReserved--) | Hämtar eller anger ett 16-bitars osignerat heltal som MÅSTE vara 0x0000 och som MÅSTE ignoreras. |
| [setReserved(short value)](#setReserved-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som MÅSTE vara 0x0000 och som MÅSTE ignoreras. |
| [getNDesription()](#getNDesription--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet tecken i arrayen som innehåller beskrivningen av metafilens innehåll. |
| [setNDesription(int value)](#setNDesription-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet tecken i arrayen som innehåller beskrivningen av metafilens innehåll. |
| [getOffDescription()](#getOffDescription--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar förskjutningen från början av denna post till arrayen som innehåller beskrivningen av metafilens innehåll. |
| [setOffDescription(int value)](#setOffDescription-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar förskjutningen från början av denna post till arrayen som innehåller beskrivningen av metafilens innehåll. |
| [getNPalEntries()](#getNPalEntries--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet poster i metafilens palett. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet poster i metafilens palett. |
| [getDevice()](#getDevice--) | Hämtar eller anger ett WMF SizeL-objekt ([MS-WMF] avsnitt 2.2.2.22) som specificerar storleken på referensenheten, i pixlar. |
| [setDevice(Size value)](#setDevice-com.aspose.imaging.Size-) | Hämtar eller anger ett WMF SizeL-objekt ([MS-WMF] avsnitt 2.2.2.22) som specificerar storleken på referensenheten, i pixlar. |
| [getMillimeters()](#getMillimeters--) | Hämtar eller anger ett WMF SizeL-objekt som specificerar storleken på referensenheten, i millimeter. |
| [setMillimeters(Size value)](#setMillimeters-com.aspose.imaging.Size-) | Hämtar eller anger ett WMF SizeL-objekt som specificerar storleken på referensenheten, i millimeter. |
| [getValid()](#getValid--) | Hämtar ett värde som indikerar om detta `EmfHeaderObject` är giltigt. |
### EmfHeaderObject() {#EmfHeaderObject--}
```
public EmfHeaderObject()
```


Initierar en ny instans av klassen `EmfHeaderObject`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar de rektangulära inklusiva gränserna i enhetsenheter för den minsta rektangel som kan ritas runt bilden som lagras i metafilen.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar de rektangulära inklusiva gränserna i enhetsenheter för den minsta rektangel som kan ritas runt bilden som lagras i metafilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getFrame() {#getFrame--}
```
public Rectangle getFrame()
```


Hämtar eller anger ett WMF RectL-objekt som specificerar de rektangulära inklusiva dimensionerna, i .01 millimeterenheter, för en rektangel som omger bilden som lagras i metafilen.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setFrame(Rectangle value) {#setFrame-com.aspose.imaging.Rectangle-}
```
public void setFrame(Rectangle value)
```


Hämtar eller anger ett WMF RectL-objekt som specificerar de rektangulära inklusiva dimensionerna, i .01 millimeterenheter, för en rektangel som omger bilden som lagras i metafilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRecordSignature() {#getRecordSignature--}
```
public int getRecordSignature()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar postens signatur. Detta MÅSTE vara ENHMETA\_SIGNATURE, från FormatSignature‑enumerationen (avsnitt 2.1.14).

**Returns:**
int
### setRecordSignature(int value) {#setRecordSignature-int-}
```
public void setRecordSignature(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar postens signatur. Detta MÅSTE vara ENHMETA\_SIGNATURE, från FormatSignature‑enumerationen (avsnitt 2.1.14).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Hämtar eller anger Version (4 byte): Ett 32-bitars osignerat heltal som specificerar EMF-metafils interoperabilitet. Detta BÖR vara 0x00010000.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Hämtar eller anger Version (4 byte): Ett 32-bitars osignerat heltal som specificerar EMF-metafils interoperabilitet. Detta BÖR vara 0x00010000.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBytes() {#getBytes--}
```
public int getBytes()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på metafilen, i byte.

**Returns:**
int
### setBytes(int value) {#setBytes-int-}
```
public void setBytes(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på metafilen, i byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRecords() {#getRecords--}
```
public int getRecords()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet poster i metafilen.

**Returns:**
int
### setRecords(int value) {#setRecords-int-}
```
public void setRecords(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet poster i metafilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHandles() {#getHandles--}
```
public short getHandles()
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar antalet grafikobjekt som kommer att användas under bearbetning av metafilen.

**Returns:**
short
### setHandles(short value) {#setHandles-short-}
```
public void setHandles(short value)
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar antalet grafikobjekt som kommer att användas under bearbetning av metafilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Hämtar eller anger ett 16-bitars osignerat heltal som MÅSTE vara 0x0000 och som MÅSTE ignoreras.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Hämtar eller anger ett 16-bitars osignerat heltal som MÅSTE vara 0x0000 och som MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getNDesription() {#getNDesription--}
```
public int getNDesription()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet tecken i arrayen som innehåller beskrivningen av metafilens innehåll. Detta är noll om det inte finns någon beskrivningssträng.

**Returns:**
int
### setNDesription(int value) {#setNDesription-int-}
```
public void setNDesription(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet tecken i arrayen som innehåller beskrivningen av metafilens innehåll. Detta är noll om det inte finns någon beskrivningssträng.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getOffDescription() {#getOffDescription--}
```
public int getOffDescription()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar förskjutningen från början av denna post till arrayen som innehåller beskrivningen av metafilens innehåll.

**Returns:**
int
### setOffDescription(int value) {#setOffDescription-int-}
```
public void setOffDescription(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar förskjutningen från början av denna post till arrayen som innehåller beskrivningen av metafilens innehåll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet poster i metafilens palett. Paletten finns i EMR\_EOF-posten.

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet poster i metafilens palett. Paletten finns i EMR\_EOF-posten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDevice() {#getDevice--}
```
public Size getDevice()
```


Hämtar eller anger ett WMF SizeL-objekt ([MS-WMF] avsnitt 2.2.2.22) som specificerar storleken på referensenheten, i pixlar.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setDevice(Size value) {#setDevice-com.aspose.imaging.Size-}
```
public void setDevice(Size value)
```


Hämtar eller anger ett WMF SizeL-objekt ([MS-WMF] avsnitt 2.2.2.22) som specificerar storleken på referensenheten, i pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getMillimeters() {#getMillimeters--}
```
public Size getMillimeters()
```


Hämtar eller anger ett WMF SizeL-objekt som specificerar storleken på referensenheten, i millimeter.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setMillimeters(Size value) {#setMillimeters-com.aspose.imaging.Size-}
```
public void setMillimeters(Size value)
```


Hämtar eller anger ett WMF SizeL-objekt som specificerar storleken på referensenheten, i millimeter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getValid() {#getValid--}
```
public boolean getValid()
```


Hämtar ett värde som indikerar om detta `EmfHeaderObject` är giltigt.

Värde: `true` om giltig; annars `false`.

**Returns:**
boolean
