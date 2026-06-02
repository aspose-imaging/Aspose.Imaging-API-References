---
title: "EmfResizePalette"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_RESIZEPALETTE-posten ökar eller minskar storleken på ett befintligt LogPalette-objekt avsnitt 2.2.17."
type: docs
weight: 108
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfresizepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfResizePalette extends EmfObjectManipulationRecordType
```

EMR\_RESIZEPALETTE-posten ökar eller minskar storleken på ett befintligt LogPalette-objekt (avsnitt 2.2.17).

Den nya storleken på LogPalette-objektet MÅSTE återspeglas i fältet NumberOfEntries i den strukturen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfResizePalette(EmfRecord source)](#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfResizePalette`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhPal()](#getIhPal--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för palettobjektet i EMF Object Table (avsnitt 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för palettobjektet i EMF Object Table (avsnitt 3.1.1.1). |
### EmfResizePalette(EmfRecord source) {#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfResizePalette(EmfRecord source)
```


Initierar en ny instans av klassen `EmfResizePalette`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för palettobjektet i EMF Object Table (avsnitt 3.1.1.1).

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för palettobjektet i EMF Object Table (avsnitt 3.1.1.1).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

