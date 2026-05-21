---
title: "EmfCreatePalette"
second_title: "Aspose.Imaging för Java API-referens"
description: "Posten EMR_CREATEPALETTE definierar en logisk palett för grafikoperationer."
type: docs
weight: 40
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePalette extends EmfObjectCreationRecordType
```

Den EMR\_CREATEPALETTE-posten definierar en logisk palett för grafikoperationer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCreatePalette(EmfRecord source)](#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfCreatePalette`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhPal()](#getIhPal--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska palettobjektet i EMF Object Table (avsnitt 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska palettobjektet i EMF Object Table (avsnitt 3.1.1.1). |
| [getLogPalette()](#getLogPalette--) | Hämtar eller anger ett LogPalette-objekt (avsnitt 2.2.17). |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | Hämtar eller anger ett LogPalette-objekt (avsnitt 2.2.17). |
### EmfCreatePalette(EmfRecord source) {#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePalette(EmfRecord source)
```


Initierar en ny instans av klassen `EmfCreatePalette`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska palettobjektet i EMF Object Table (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska palettobjektet i EMF Object Table (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


Hämtar eller anger ett LogPalette-objekt (avsnitt 2.2.17). Version‑fältet i detta objekt MÅSTE sättas till 0x0300. Om NumberOfEntries‑värdet i detta objekt är noll, måste bearbetningen av denna post misslyckas.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette)
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


Hämtar eller anger ett LogPalette-objekt (avsnitt 2.2.17). Version‑fältet i detta objekt MÅSTE sättas till 0x0300. Om NumberOfEntries‑värdet i detta objekt är noll, måste bearbetningen av denna post misslyckas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) |  |

