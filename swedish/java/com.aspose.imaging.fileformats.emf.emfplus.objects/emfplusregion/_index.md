---
title: "EmfPlusRegion"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusRegion-objektet specificerar linje- och kurvsegment som definierar en icke-rektlinjär form."
type: docs
weight: 68
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusRegion extends EmfPlusGraphicsObjectType
```

EmfPlusRegion-objektet specificerar linje- och kurvsegment som definierar en icke-rektlinjär form.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusRegion()](#EmfPlusRegion--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRegionNode()](#getRegionNode--) | Hämtar eller anger en array med RegionNodeCount+1 EmfPlusRegionNode‑objekt (avsnitt 2.2.2.40). |
| [setRegionNode(EmfPlusRegionNode[] value)](#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---) | Hämtar eller anger en array med RegionNodeCount+1 EmfPlusRegionNode‑objekt (avsnitt 2.2.2.40). |
### EmfPlusRegion() {#EmfPlusRegion--}
```
public EmfPlusRegion()
```


### getRegionNode() {#getRegionNode--}
```
public EmfPlusRegionNode[] getRegionNode()
```


Hämtar eller anger en array med RegionNodeCount+1 EmfPlusRegionNode‑objekt (avsnitt 2.2.2.40). Regioner specificeras som ett binärt träd av regionnoder, och varje nod MÅSTE antingen vara en terminalnod eller specificera en eller två barnnoder. RegionNode MÅSTE innehålla minst ett element.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode[]
### setRegionNode(EmfPlusRegionNode[] value) {#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---}
```
public void setRegionNode(EmfPlusRegionNode[] value)
```


Hämtar eller anger en array med RegionNodeCount+1 EmfPlusRegionNode‑objekt (avsnitt 2.2.2.40). Regioner specificeras som ett binärt träd av regionnoder, och varje nod MÅSTE antingen vara en terminalnod eller specificera en eller två barnnoder. RegionNode MÅSTE innehålla minst ett element.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusRegionNode\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) |  |

