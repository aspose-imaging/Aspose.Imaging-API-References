---
title: "EmfPlusRegionNode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusRegionNode-Objekt gibt Knoten einer Grafikregion an."
type: docs
weight: 69
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusRegionNode extends EmfPlusStructureObjectType
```

Das EmfPlusRegionNode-Objekt gibt Knoten einer Grafikregion an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRegionNodeData()](#getRegionNodeData--) | Liest oder setzt optionale, variable Daten, die das im Typfeld angegebene Region‑Node‑Datenobjekt definieren. |
| [setRegionNodeData(EmfPlusStructureObjectType value)](#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-) | Liest oder setzt optionale, variable Daten, die das im Typfeld angegebene Region‑Node‑Datenobjekt definieren. |
| [getType()](#getType--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ der Daten im Feld RegionNodeData angibt. |
| [setType(int value)](#setType-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ der Daten im Feld RegionNodeData angibt. |
### EmfPlusRegionNode() {#EmfPlusRegionNode--}
```
public EmfPlusRegionNode()
```


### getRegionNodeData() {#getRegionNodeData--}
```
public EmfPlusStructureObjectType getRegionNodeData()
```


Liest oder setzt optionale, variable Daten, die das im Typfeld angegebene Region‑Node‑Datenobjekt definieren. Der Inhalt und das Format der Daten können für jeden Region‑Node‑Typ unterschiedlich sein. Dieses Feld MUST NOT vorhanden sein, wenn der Knotentyp RegionNodeDataTypeEmpty oder RegionNodeDataTypeInfinite ist. Dieses Objekt ist generisch und wird verwendet, um verschiedene Typen von Region‑Node‑Daten anzugeben, einschließlich: Ein EmfPlusRegionNodePath‑Objekt (Abschnitt 2.2.2.42) für einen Terminalknoten; ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39) für einen Terminalknoten; und ein EmfPlusRegionNodeChildNodes‑Objekt (Abschnitt 2.2.2.41) für einen Nicht‑Terminalknoten.

**Returns:**
[EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
### setRegionNodeData(EmfPlusStructureObjectType value) {#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-}
```
public void setRegionNodeData(EmfPlusStructureObjectType value)
```


Liest oder setzt optionale, variable Daten, die das im Typfeld angegebene Region‑Node‑Datenobjekt definieren. Der Inhalt und das Format der Daten können für jeden Region‑Node‑Typ unterschiedlich sein. Dieses Feld MUST NOT vorhanden sein, wenn der Knotentyp RegionNodeDataTypeEmpty oder RegionNodeDataTypeInfinite ist. Dieses Objekt ist generisch und wird verwendet, um verschiedene Typen von Region‑Node‑Daten anzugeben, einschließlich: Ein EmfPlusRegionNodePath‑Objekt (Abschnitt 2.2.2.42) für einen Terminalknoten; ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39) für einen Terminalknoten; und ein EmfPlusRegionNodeChildNodes‑Objekt (Abschnitt 2.2.2.41) für einen Nicht‑Terminalknoten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype) |  |

### getType() {#getType--}
```
public int getType()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ der Daten im Feld RegionNodeData angibt. Dieser Wert MUST in der Aufzählung RegionNodeDataType definiert sein (Abschnitt 2.1.1.27).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ der Daten im Feld RegionNodeData angibt. Dieser Wert MUST in der Aufzählung RegionNodeDataType definiert sein (Abschnitt 2.1.1.27).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

