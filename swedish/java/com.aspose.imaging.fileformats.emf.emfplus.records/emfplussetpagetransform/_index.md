---
title: "EmfPlusSetPageTransform"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den EmfPlusSetPageTransform-posten specificerar skalningsfaktorer och enheter för att konvertera koordinater i sidrymd till enhetsrymd."
type: docs
weight: 61
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetPageTransform extends EmfPlusTerminalServerRecordType
```

Den EmfPlusSetPageTransform-posten specificerar skalningsfaktorer och enheter för att konvertera koordinater i sidrymd till enhetsrymd.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusSetPageTransform(EmfPlusRecord source)](#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusSetPageTransform`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Hämtar måttenheten för sidrymdskoordinater, från UnitType-uppslagningen (avsnitt 2.1.1.33). |
| [getPageScale()](#getPageScale--) | Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn för att konvertera sidrymdskoordinater till enhetsrymdskoordinater. |
| [setPageScale(float value)](#setPageScale-float-) | Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn för att konvertera sidrymdskoordinater till enhetsrymdskoordinater. |
### EmfPlusSetPageTransform(EmfPlusRecord source) {#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetPageTransform(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusSetPageTransform`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Hämtar måttenheten för sidrymdskoordinater, från UnitType-uppslagningen (avsnitt 2.1.1.33). Detta värde BÖR INTE vara UnitTypeDisplay eller UnitTypeWorld.

Värde: Sidans enhet.

**Returns:**
int
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn för att konvertera sidrymdskoordinater till enhetsrymdskoordinater.

Värde: Sidans skala.

**Returns:**
float
### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn för att konvertera sidrymdskoordinater till enhetsrymdskoordinater.

Värde: Sidans skala.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

