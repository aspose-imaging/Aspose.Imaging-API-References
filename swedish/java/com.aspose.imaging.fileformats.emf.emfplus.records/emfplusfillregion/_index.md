---
title: "EmfPlusFillRegion"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusFillRegion-posten specificerar fyllning av insidan av en grafikregion."
type: docs
weight: 38
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRegion extends EmfPlusDrawingRecordType
```

EmfPlusFillRegion-posten specificerar fyllning av insidan av en grafikregion.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusFillRegion(EmfPlusRecord source)](#EmfPlusFillRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusFillRegion`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [isColor()](#isColor--) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [setColor(boolean value)](#setColor-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [getBrushId()](#getBrushId--) | Hämtar eller anger borstidentifieraren Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll bestäms av S‑biten i Flag‑fältet. |
| [setBrushId(int value)](#setBrushId-int-) | Hämtar eller anger borstidentifieraren Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll bestäms av S‑biten i Flag‑fältet. |
### EmfPlusFillRegion(EmfPlusRecord source) {#EmfPlusFillRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRegion(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusFillRegion`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger objektidentifieraren. Index för EmfPlusRegion-objektet (avsnitt 2.2.1.8) som ska fyllas i EMF+-objektabellen. Värdet MÅSTE vara 0 till 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Index för EmfPlusRegion-objektet (avsnitt 2.2.1.8) som ska fyllas i EMF+-objektabellen. Värdet MÅSTE vara 0 till 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

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

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Hämtar eller anger borstidentifieraren Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll bestäms av S‑biten i Flag‑fältet.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Hämtar eller anger borstidentifieraren Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll bestäms av S‑biten i Flag‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

