---
title: "EmfModifyWorldTransform"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_MODIFYWORLDTRANSFORM-posten modifierar den aktuella värld-till-sida-omvandlingen i uppspelningsenhetens kontext."
type: docs
weight: 73
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfTransformRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype)
```
public final class EmfModifyWorldTransform extends EmfTransformRecordType
```

Den EMR_MODIFYWORLDTRANSFORM-posten modifierar den aktuella värld‑till‑sidtransformen i uppspelningsenhetens kontext.

För mer information om transformationer och koordinatrum, se [MSDN-WRLDPGSPC]. Se avsnitt 2.3.12 för specifikationen av andra transformposttyper.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfModifyWorldTransform(EmfRecord source)](#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfModifyWorldTransform`. |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform--) | Initierar en ny instans av klassen `EmfModifyWorldTransform`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getModifyWorldTransformMode()](#getModifyWorldTransformMode--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur den i Xform angivna transformationen används. |
| [setModifyWorldTransformMode(int value)](#setModifyWorldTransformMode-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur den i Xform angivna transformationen används. |
### EmfModifyWorldTransform(EmfRecord source) {#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfModifyWorldTransform(EmfRecord source)
```


Initierar en ny instans av klassen `EmfModifyWorldTransform`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfModifyWorldTransform() {#EmfModifyWorldTransform--}
```
public EmfModifyWorldTransform()
```


Initierar en ny instans av klassen `EmfModifyWorldTransform`.

### getModifyWorldTransformMode() {#getModifyWorldTransformMode--}
```
public int getModifyWorldTransformMode()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur den i Xform angivna transformationen används. Detta värde MÅSTE finnas i enumerationen ModifyWorldTransformMode (avsnitt 2.1.24).

**Returns:**
int
### setModifyWorldTransformMode(int value) {#setModifyWorldTransformMode-int-}
```
public void setModifyWorldTransformMode(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur den i Xform angivna transformationen används. Detta värde MÅSTE finnas i enumerationen ModifyWorldTransformMode (avsnitt 2.1.24).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

