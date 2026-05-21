---
title: "EmfSetTextAlign"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SETTEXTALIGN-posten specificerar textjustering."
type: docs
weight: 139
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextAlign extends EmfStateRecordType
```

EMR\\_SETTEXTALIGN-posten specificerar textjustering.

EMR\_SMALLTEXTOUT-, EMR\_EXTTEXTOUTA- och EMR\_EXTTEXTOUTW-poster använder värden för textjustering för att placera en textsträng på utskriftsmediet. Värdena specificerar förhållandet mellan en referenspunkt och en rektangel som omger texten. Referenspunkten är antingen den aktuella positionen eller en punkt som skickas till en textutmatningspost. Rektangeln som omger texten bildas av teckencellerna i textsträngen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetTextAlign(EmfRecord source)](#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetTextAlign`. |
| [EmfSetTextAlign()](#EmfSetTextAlign--) | Initierar en ny instans av klassen `EmfSetTextAlign`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTextAlignmentMode()](#getTextAlignmentMode--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar textjustering genom att använda en mask av flaggor för textjustering. |
| [setTextAlignmentMode(int value)](#setTextAlignmentMode-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar textjustering genom att använda en mask av flaggor för textjustering. |
### EmfSetTextAlign(EmfRecord source) {#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextAlign(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetTextAlign`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfSetTextAlign() {#EmfSetTextAlign--}
```
public EmfSetTextAlign()
```


Initierar en ny instans av klassen `EmfSetTextAlign`.

### getTextAlignmentMode() {#getTextAlignmentMode--}
```
public int getTextAlignmentMode()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar textjustering genom att använda en mask av flaggor för textjustering. Dessa är antingen `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] avsnitt 2.1.2.3) för text med horisontell baslinje, eller `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] avsnitt 2.1.2.4) för text med vertikal baslinje. Endast ett värde kan väljas bland de som påverkar horisontell och vertikal justering.

**Returns:**
int
### setTextAlignmentMode(int value) {#setTextAlignmentMode-int-}
```
public void setTextAlignmentMode(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar textjustering genom att använda en mask av flaggor för textjustering. Dessa är antingen `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] avsnitt 2.1.2.3) för text med horisontell baslinje, eller `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] avsnitt 2.1.2.4) för text med vertikal baslinje. Endast ett värde kan väljas bland de som påverkar horisontell och vertikal justering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

