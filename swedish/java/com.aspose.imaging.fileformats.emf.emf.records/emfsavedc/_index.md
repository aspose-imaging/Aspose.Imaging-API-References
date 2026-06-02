---
title: "EmfSaveDc"
second_title: "Aspose.Imaging för Java API-referens"
description: "Sparar det aktuella tillståndet för uppspelningsenhetens kontext på en stack av tillstånd som sparats av föregående EMR_SAVEDC‑poster, om sådana finns."
type: docs
weight: 112
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSaveDc extends EmfStateRecordType
```

Sparar det aktuella tillståndet för uppspelningsenhetens kontext på en stack av tillstånd som sparats av föregående EMR\\_SAVEDC‑poster, om sådana finns. Tillståndet består av grafikegenskaper och objekt, inklusive den för närvarande valda bitmapen, penseln, paletten, teckensnittet, pennan och regionen. En EMR\\_RESTOREDC‑post används för att återställa tillståndet. Denna EMF‑post specificerar inga parametrar.

Stacken kan innehålla tillståndsinformation för flera instanser av uppspelningsenhetens kontext. När ett tillstånd återställs måste alla tillståndsinstanser som sparades senare MÅSTE kasseras.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSaveDc(EmfRecord source)](#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSaveDc`. |
| [EmfSaveDc()](#EmfSaveDc--) | Initierar en ny instans av klassen `EmfSaveDc`. |
### EmfSaveDc(EmfRecord source) {#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSaveDc(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSaveDc`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfSaveDc() {#EmfSaveDc--}
```
public EmfSaveDc()
```


Initierar en ny instans av klassen `EmfSaveDc`.

