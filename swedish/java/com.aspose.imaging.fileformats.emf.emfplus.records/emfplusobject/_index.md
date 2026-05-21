---
title: "EmfPlusObject"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusObject-posten specificerar ett objekt för användning i grafikoperationer."
type: docs
weight: 42
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusObject extends EmfPlusObjectRecordType
```

EmfPlusObject‑posten specificerar ett objekt för användning i grafikoperationer. Objektdefinitionen kan sträcka sig över flera poster, vilket indikeras av värdet i fältet Flags.

EmfPlusObject‑posten är generisk; den används för alla typer av objekt. Värden som är specifika för vissa objekttyper finns i fältet ObjectData. En konceptuell modell för hantering av grafikobjekt beskrivs i Managing Graphics Objects (avsnitt 3.1.2).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusObject(EmfPlusRecord source)](#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusObject`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isContinuable()](#isContinuable--) | Hämtar eller anger ett värde som indikerar om den här instansen kan fortsättas. |
| [setContinuable(boolean value)](#setContinuable-boolean-) | Hämtar eller anger ett värde som indikerar om den här instansen kan fortsättas. |
| [getObjectType()](#getObjectType--) | Hämtar eller anger objektets typ. |
| [setObjectType(byte value)](#setObjectType-byte-) | Hämtar eller anger objektets typ. |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getTotalObjectSize()](#getTotalObjectSize--) | Hämtar eller anger objektets totala storlek. |
| [setTotalObjectSize(int value)](#setTotalObjectSize-int-) | Hämtar eller anger objektets totala storlek. |
| [getObjectData()](#getObjectData--) | Hämtar eller anger en byte‑array som innehåller data för den typ av objekt som anges i fältet Flags. |
| [setObjectData(EmfPlusGraphicsObjectType value)](#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-) | Hämtar eller anger en byte‑array som innehåller data för den typ av objekt som anges i fältet Flags. |
### EmfPlusObject(EmfPlusRecord source) {#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusObject(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusObject`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### isContinuable() {#isContinuable--}
```
public boolean isContinuable()
```


Hämtar eller anger ett värde som indikerar om den här instansen kan fortsättas. Anger att objektdefinitionen fortsätter i nästa EmfPlusObject‑post. Detta flagga sätts aldrig i den sista posten som definierar objektet.

Värde: `true` om denna instans är komprimerad; annars `false`.

**Returns:**
boolean
### setContinuable(boolean value) {#setContinuable-boolean-}
```
public void setContinuable(boolean value)
```


Hämtar eller anger ett värde som indikerar om den här instansen kan fortsättas. Anger att objektdefinitionen fortsätter i nästa EmfPlusObject‑post. Detta flagga sätts aldrig i den sista posten som definierar objektet.

Värde: `true` om denna instans är komprimerad; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getObjectType() {#getObjectType--}
```
public byte getObjectType()
```


Hämtar eller anger objektets typ.

Värde: Objektets typ.

**Returns:**
byte
### setObjectType(byte value) {#setObjectType-byte-}
```
public void setObjectType(byte value)
```


Hämtar eller anger objektets typ.

Värde: Objektets typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger objektidentifieraren. Indexet i EMF+ Object Table som ska associeras med objektet som skapats av denna post. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Indexet i EMF+ Object Table som ska associeras med objektet som skapats av denna post. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getTotalObjectSize() {#getTotalObjectSize--}
```
public int getTotalObjectSize()
```


Hämtar eller anger objektets totala storlek. Om posten är fortsättningsbar, när fortsättningsbiten är satt, kommer detta fält att finnas. Fortsättande objekt har flera EMF+-poster som börjar med EmfPlusContineudObjectRecord. Varje EmfPlusContinuedObjectRecord kommer att innehålla en TotalObjectSize. När antalet byte enligt TotalObjectSize har lästs, kommer nästa EMF+-post inte att behandlas som en del av det fortsättande objektet.

Värde: Objektets totala storlek.

**Returns:**
int
### setTotalObjectSize(int value) {#setTotalObjectSize-int-}
```
public void setTotalObjectSize(int value)
```


Hämtar eller anger objektets totala storlek. Om posten är fortsättningsbar, när fortsättningsbiten är satt, kommer detta fält att finnas. Fortsättande objekt har flera EMF+-poster som börjar med EmfPlusContineudObjectRecord. Varje EmfPlusContinuedObjectRecord kommer att innehålla en TotalObjectSize. När antalet byte enligt TotalObjectSize har lästs, kommer nästa EMF+-post inte att behandlas som en del av det fortsättande objektet.

Värde: Objektets totala storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getObjectData() {#getObjectData--}
```
public EmfPlusGraphicsObjectType getObjectData()
```


Hämtar eller anger en byte‑array som innehåller data för den typ av objekt som anges i fältet Flags. Innehållet och formatet på data kan variera för varje objekttyp. Se de enskilda objekdefinitionerna i avsnitt 2.2.1 för ytterligare information.

Värde: Objektdata.

**Returns:**
[EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
### setObjectData(EmfPlusGraphicsObjectType value) {#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-}
```
public void setObjectData(EmfPlusGraphicsObjectType value)
```


Hämtar eller anger en byte‑array som innehåller data för den typ av objekt som anges i fältet Flags. Innehållet och formatet på data kan variera för varje objekttyp. Se de enskilda objekdefinitionerna i avsnitt 2.2.1 för ytterligare information.

Värde: Objektdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype) |  |

