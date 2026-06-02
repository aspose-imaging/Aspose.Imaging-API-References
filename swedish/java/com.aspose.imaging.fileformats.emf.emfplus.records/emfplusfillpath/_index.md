---
title: "EmfPlusFillPath"
second_title: "Aspose.Imaging för Java API-referens"
description: "Fyllningsvägspost FLAGS 16-bitars osignerat heltal som ger information om hur operationen ska utföras och om postens struktur."
type: docs
weight: 34
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPath extends EmfPlusDrawingRecordType
```

Fyllningsvägspost FLAGS: 16-bitars osignerat heltal som ger information om hur operationen ska utföras och om postens struktur. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X | ObjectId | S (1 bit): Denna bit indikerar datatypen i BrushId‑fältet. Om satt anger BrushId en färg som ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om avmarkerad innehåller BrushId indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1) i EMF+‑objektabellen. X (1 bit): Reserverad och MÅSTE ignoreras. ObjectId (1 byte): Indexet för ett EmfPlusPath‑objekt (avsnitt 2.2.1.6) som ska fyllas i EMF+‑objektabellen. Värdet MÅSTE vara mellan 0 och 63, inklusive.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusFillPath(EmfPlusRecord source)](#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusFillPath`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isColor()](#isColor--) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [setColor(boolean value)](#setColor-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getBrushId()](#getBrushId--) | Hämtar eller anger Brush‑ID:t Ett 32-bitars osignerat heltal som definierar penseln, vars innehåll bestäms av S‑biten i Flags‑fältet. |
| [setBrushId(int value)](#setBrushId-int-) | Hämtar eller anger Brush‑ID:t Ett 32-bitars osignerat heltal som definierar penseln, vars innehåll bestäms av S‑biten i Flags‑fältet. |
### EmfPlusFillPath(EmfPlusRecord source) {#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPath(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusFillPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Hämtar eller anger ett värde som indikerar om den här instansen är färg. Om satt anger BrushId en färg som ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om avmarkerad innehåller BrushId indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1) i EMF+‑objektabellen.

Värde: `true` om denna instans är färg; annars `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Hämtar eller anger ett värde som indikerar om den här instansen är färg. Om satt anger BrushId en färg som ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om avmarkerad innehåller BrushId indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1) i EMF+‑objektabellen.

Värde: `true` om denna instans är färg; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger objektidentifieraren. Indexet för EmfPlusPath‑objektet (avsnitt 2.2.1.6) som ska fyllas i EMF+‑objektabellen. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Indexet för EmfPlusPath‑objektet (avsnitt 2.2.1.6) som ska fyllas i EMF+‑objektabellen. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Hämtar eller anger Brush‑ID:t Ett 32-bitars osignerat heltal som definierar penseln, vars innehåll bestäms av S‑biten i Flags‑fältet.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Hämtar eller anger Brush‑ID:t Ett 32-bitars osignerat heltal som definierar penseln, vars innehåll bestäms av S‑biten i Flags‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

