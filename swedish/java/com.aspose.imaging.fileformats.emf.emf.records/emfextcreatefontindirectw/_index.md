---
title: "EmfExtCreateFontIndirectW"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_EXTCREATEFONTINDIRECTW‑posten definierar ett logiskt teckensnitt för grafikoperationer."
type: docs
weight: 51
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreateFontIndirectW extends EmfObjectCreationRecordType
```

Den EMR_EXTCREATEFONTINDIRECTW-posten definierar ett logiskt teckensnitt för grafikoperationer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfExtCreateFontIndirectW(EmfRecord source)](#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfExtCreateFontIndirectW`. |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW--) | Initierar en ny instans av klassen `EmfExtCreateFontIndirectW`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhFonts()](#getIhFonts--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska teckensnittobjektet i EMF Object Table (avsnitt 3.1.1.1). |
| [setIhFonts(int value)](#setIhFonts-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska teckensnittobjektet i EMF Object Table (avsnitt 3.1.1.1). |
| [getElw()](#getElw--) | Hämtar eller anger ett LogFontExDv-objekt (avsnitt 2.2.15), som specificerar det logiska teckensnittet. |
| [setElw(EmfLogFont value)](#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Hämtar eller anger ett LogFontExDv-objekt (avsnitt 2.2.15), som specificerar det logiska teckensnittet. |
### EmfExtCreateFontIndirectW(EmfRecord source) {#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreateFontIndirectW(EmfRecord source)
```


Initierar en ny instans av klassen `EmfExtCreateFontIndirectW`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW--}
```
public EmfExtCreateFontIndirectW()
```


Initierar en ny instans av klassen `EmfExtCreateFontIndirectW`.

### getIhFonts() {#getIhFonts--}
```
public int getIhFonts()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska teckensnittobjektet i EMF Object Table (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras.

**Returns:**
int
### setIhFonts(int value) {#setIhFonts-int-}
```
public void setIhFonts(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska teckensnittobjektet i EMF Object Table (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getElw() {#getElw--}
```
public EmfLogFont getElw()
```


Hämtar eller anger ett LogFontExDv-objekt (avsnitt 2.2.15), som specificerar det logiska teckensnittet. Ett LogFont-objekt 2.2.13 KAN vara närvarande istället.[90]Processen för att bestämma typen av objekt i detta fält beskrivs nedan.

**Returns:**
[EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
### setElw(EmfLogFont value) {#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public void setElw(EmfLogFont value)
```


Hämtar eller anger ett LogFontExDv-objekt (avsnitt 2.2.15), som specificerar det logiska teckensnittet. Ett LogFont-objekt 2.2.13 KAN vara närvarande istället.[90]Processen för att bestämma typen av objekt i detta fält beskrivs nedan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) |  |

