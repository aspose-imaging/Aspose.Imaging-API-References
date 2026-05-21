---
title: "EmfModifyWorldTransform"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_MODIFYWORLDTRANSFORM‑Datensatz ändert die aktuelle Welt‑zu‑Seiten‑Transformation im Wiedergabegeräte‑Kontext."
type: docs
weight: 73
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfTransformRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype)
```
public final class EmfModifyWorldTransform extends EmfTransformRecordType
```

Der EMR\_MODIFYWORLDTRANSFORM-Datensatz verändert die aktuelle Welt-zu-Seiten-Transformation im Wiedergabegerätekontext.

Weitere Informationen zu Transformationen und Koordinatenräumen finden Sie unter [MSDN-WRLDPGSPC]. Siehe Abschnitt 2.3.12 für die Spezifikation anderer Transformationsdatensatztypen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfModifyWorldTransform(EmfRecord source)](#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfModifyWorldTransform`‑Klasse. |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform--) | Initialisiert eine neue Instanz der `EmfModifyWorldTransform`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getModifyWorldTransformMode()](#getModifyWorldTransformMode--) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie die in Xform angegebene Transformation verwendet wird. |
| [setModifyWorldTransformMode(int value)](#setModifyWorldTransformMode-int-) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie die in Xform angegebene Transformation verwendet wird. |
### EmfModifyWorldTransform(EmfRecord source) {#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfModifyWorldTransform(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfModifyWorldTransform`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfModifyWorldTransform() {#EmfModifyWorldTransform--}
```
public EmfModifyWorldTransform()
```


Initialisiert eine neue Instanz der `EmfModifyWorldTransform`‑Klasse.

### getModifyWorldTransformMode() {#getModifyWorldTransformMode--}
```
public int getModifyWorldTransformMode()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie die in Xform angegebene Transformation verwendet wird. Dieser Wert MUSS in der ModifyWorldTransformMode‑Aufzählung (Abschnitt 2.1.24) enthalten sein.

**Returns:**
int
### setModifyWorldTransformMode(int value) {#setModifyWorldTransformMode-int-}
```
public void setModifyWorldTransformMode(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie die in Xform angegebene Transformation verwendet wird. Dieser Wert MUSS in der ModifyWorldTransformMode‑Aufzählung (Abschnitt 2.1.24) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

