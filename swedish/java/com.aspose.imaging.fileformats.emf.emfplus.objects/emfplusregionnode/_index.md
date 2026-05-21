---
title: "EmfPlusRegionNode"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusRegionNode-objektet specificerar noder i en grafikregion."
type: docs
weight: 69
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusRegionNode extends EmfPlusStructureObjectType
```

EmfPlusRegionNode-objektet specificerar noder i en grafikregion.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRegionNodeData()](#getRegionNodeData--) | Hämtar eller anger en valfri, variabel‑längd data som definierar regionnodens dataobjekt som anges i fältet Type. |
| [setRegionNodeData(EmfPlusStructureObjectType value)](#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-) | Hämtar eller anger en valfri, variabel‑längd data som definierar regionnodens dataobjekt som anges i fältet Type. |
| [getType()](#getType--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar datatypen i fältet RegionNodeData. |
| [setType(int value)](#setType-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar datatypen i fältet RegionNodeData. |
### EmfPlusRegionNode() {#EmfPlusRegionNode--}
```
public EmfPlusRegionNode()
```


### getRegionNodeData() {#getRegionNodeData--}
```
public EmfPlusStructureObjectType getRegionNodeData()
```


Hämtar eller anger en valfri, variabel‑längd data som definierar regionnodens dataobjekt som anges i fältet Type. Innehållet och formatet på datan kan variera för varje regionnodtyp. Detta fält FÅR INTE vara närvarande om nodtypen är RegionNodeDataTypeEmpty eller RegionNodeDataTypeInfinite. Detta objekt är generiskt och används för att specificera olika typer av regionnoddata, inklusive: ett EmfPlusRegionNodePath‑objekt (avsnitt 2.2.2.42) för en terminalnod; ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) för en terminalnod; och ett EmfPlusRegionNodeChildNodes‑objekt (avsnitt 2.2.2.41) för en icke‑terminalnod.

**Returns:**
[EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
### setRegionNodeData(EmfPlusStructureObjectType value) {#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-}
```
public void setRegionNodeData(EmfPlusStructureObjectType value)
```


Hämtar eller anger en valfri, variabel‑längd data som definierar regionnodens dataobjekt som anges i fältet Type. Innehållet och formatet på datan kan variera för varje regionnodtyp. Detta fält FÅR INTE vara närvarande om nodtypen är RegionNodeDataTypeEmpty eller RegionNodeDataTypeInfinite. Detta objekt är generiskt och används för att specificera olika typer av regionnoddata, inklusive: ett EmfPlusRegionNodePath‑objekt (avsnitt 2.2.2.42) för en terminalnod; ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) för en terminalnod; och ett EmfPlusRegionNodeChildNodes‑objekt (avsnitt 2.2.2.41) för en icke‑terminalnod.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype) |  |

### getType() {#getType--}
```
public int getType()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar datatypen i fältet RegionNodeData. Detta värde MÅSTE vara definierat i uppräkningen RegionNodeDataType (avsnitt 2.1.1.27).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar datatypen i fältet RegionNodeData. Detta värde MÅSTE vara definierat i uppräkningen RegionNodeDataType (avsnitt 2.1.1.27).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

