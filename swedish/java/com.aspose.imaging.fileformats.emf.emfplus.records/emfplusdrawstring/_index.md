---
title: "EmfPlusDrawString"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawString-posten specificerar textutmatning med strängformatering"
type: docs
weight: 28
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawString extends EmfPlusDrawingRecordType
```

EmfPlusDrawString-posten specificerar textutmatning med strängformatering
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawString(EmfPlusRecord source)](#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawString`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isColor()](#isColor--) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [setColor(boolean value)](#setColor-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getBrushId()](#getBrushId--) | Hämtar eller anger penselidentifieraren Ett 32-bitars osignerat heltal som specificerar penseln, vars innehåll bestäms av S‑biten i Flags‑fältet. |
| [setBrushId(int value)](#setBrushId-int-) | Hämtar eller anger penselidentifieraren Ett 32-bitars osignerat heltal som specificerar penseln, vars innehåll bestäms av S‑biten i Flags‑fältet. |
| [getFormatId()](#getFormatId--) | Hämtar eller anger formatidentifieraren Ett 32-bitars osignerat heltal som specificerar indexet för ett valfritt EmfPlusStringFormat‑objekt (avsnitt 2.2.1.9) i EMF+‑objektabellen. |
| [setFormatId(int value)](#setFormatId-int-) | Hämtar eller anger formatidentifieraren Ett 32-bitars osignerat heltal som specificerar indexet för ett valfritt EmfPlusStringFormat‑objekt (avsnitt 2.2.1.9) i EMF+‑objektabellen. |
| [getLength()](#getLength--) | Hämtar eller anger längden Ett 32-bitars osignerat heltal som specificerar antalet tecken i strängen. |
| [setLength(int value)](#setLength-int-) | Hämtar eller anger längden Ett 32-bitars osignerat heltal som specificerar antalet tecken i strängen. |
| [getLayoutRect()](#getLayoutRect--) | Hämtar eller anger layout‑rektangeln Ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) som definierar det omgivande området för destinationen som ska ta emot strängen |
| [setLayoutRect(RectangleF value)](#setLayoutRect-com.aspose.imaging.RectangleF-) | Hämtar eller anger layout‑rektangeln Ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) som definierar det omgivande området för destinationen som ska ta emot strängen |
| [getStringData()](#getStringData--) | Hämtar eller anger strängdata En array av 16-bitars Unicode‑tecken som specificerar strängen som ska ritas |
| [setStringData(String value)](#setStringData-java.lang.String-) | Hämtar eller anger strängdata En array av 16-bitars Unicode‑tecken som specificerar strängen som ska ritas |
### EmfPlusDrawString(EmfPlusRecord source) {#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawString(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawString`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Hämtar eller anger ett värde som indikerar om denna instans är färg. Om satt specificerar BrushId en färg som ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om rensad innehåller BrushId indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1) i EMF+‑objektabellen.

Värde: `true` om denna instans är färg; annars `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna instans är färg. Om satt specificerar BrushId en färg som ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om rensad innehåller BrushId indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1) i EMF+‑objektabellen.

Värde: `true` om denna instans är färg; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusFont‑objekt (avsnitt 2.2.1.3) i EMF+‑objektabellen för att rendera texten. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusFont‑objekt (avsnitt 2.2.1.3) i EMF+‑objektabellen för att rendera texten. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Hämtar eller anger penselidentifieraren Ett 32-bitars osignerat heltal som specificerar penseln, vars innehåll bestäms av S‑biten i Flags‑fältet. Denna definition används för att måla förgrundens textfärg; det vill säga endast själva glyferna.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Hämtar eller anger penselidentifieraren Ett 32-bitars osignerat heltal som specificerar penseln, vars innehåll bestäms av S‑biten i Flags‑fältet. Denna definition används för att måla förgrundens textfärg; det vill säga endast själva glyferna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFormatId() {#getFormatId--}
```
public int getFormatId()
```


Hämtar eller anger formatidentifieraren Ett 32-bitars osignerat heltal som specificerar indexet för ett valfritt EmfPlusStringFormat‑objekt (avsnitt 2.2.1.9) i EMF+‑objektabellen. Detta objekt specificerar information om textlayout och visningsmanipulationer som ska tillämpas på en sträng

**Returns:**
int
### setFormatId(int value) {#setFormatId-int-}
```
public void setFormatId(int value)
```


Hämtar eller anger formatidentifieraren Ett 32-bitars osignerat heltal som specificerar indexet för ett valfritt EmfPlusStringFormat‑objekt (avsnitt 2.2.1.9) i EMF+‑objektabellen. Detta objekt specificerar information om textlayout och visningsmanipulationer som ska tillämpas på en sträng

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLength() {#getLength--}
```
public int getLength()
```


Hämtar eller anger längden Ett 32-bitars osignerat heltal som specificerar antalet tecken i strängen.

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Hämtar eller anger längden Ett 32-bitars osignerat heltal som specificerar antalet tecken i strängen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLayoutRect() {#getLayoutRect--}
```
public RectangleF getLayoutRect()
```


Hämtar eller anger layout‑rektangeln Ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) som definierar det omgivande området för destinationen som ska ta emot strängen

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setLayoutRect(RectangleF value) {#setLayoutRect-com.aspose.imaging.RectangleF-}
```
public void setLayoutRect(RectangleF value)
```


Hämtar eller anger layout‑rektangeln Ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) som definierar det omgivande området för destinationen som ska ta emot strängen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStringData() {#getStringData--}
```
public String getStringData()
```


Hämtar eller anger strängdata En array av 16-bitars Unicode‑tecken som specificerar strängen som ska ritas

**Returns:**
java.lang.String
### setStringData(String value) {#setStringData-java.lang.String-}
```
public void setStringData(String value)
```


Hämtar eller anger strängdata En array av 16-bitars Unicode‑tecken som specificerar strängen som ska ritas

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

