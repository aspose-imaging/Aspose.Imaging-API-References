---
title: "EmfPlusRegion"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusRegion-Objekt gibt Linien- und Kurvensegmente an, die eine nicht rechtwinklige Form definieren."
type: docs
weight: 68
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusRegion extends EmfPlusGraphicsObjectType
```

Das EmfPlusRegion-Objekt gibt Linien- und Kurvensegmente an, die eine nicht rechtwinklige Form definieren.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusRegion()](#EmfPlusRegion--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRegionNode()](#getRegionNode--) | Liest oder setzt ein Array von RegionNodeCount+1 EmfPlusRegionNode‑Objekten (Abschnitt 2.2.2.40). |
| [setRegionNode(EmfPlusRegionNode[] value)](#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---) | Liest oder setzt ein Array von RegionNodeCount+1 EmfPlusRegionNode‑Objekten (Abschnitt 2.2.2.40). |
### EmfPlusRegion() {#EmfPlusRegion--}
```
public EmfPlusRegion()
```


### getRegionNode() {#getRegionNode--}
```
public EmfPlusRegionNode[] getRegionNode()
```


Liest oder setzt ein Array von RegionNodeCount+1 EmfPlusRegionNode‑Objekten (Abschnitt 2.2.2.40). Regionen werden als binärer Baum von Regionsknoten angegeben, und jeder Knoten MUSS entweder ein Endknoten sein oder ein oder zwei Kindknoten spezifizieren. RegionNode MUSS mindestens ein Element enthalten.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode[]
### setRegionNode(EmfPlusRegionNode[] value) {#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---}
```
public void setRegionNode(EmfPlusRegionNode[] value)
```


Liest oder setzt ein Array von RegionNodeCount+1 EmfPlusRegionNode‑Objekten (Abschnitt 2.2.2.40). Regionen werden als binärer Baum von Regionsknoten angegeben, und jeder Knoten MUSS entweder ein Endknoten sein oder ein oder zwei Kindknoten spezifizieren. RegionNode MUSS mindestens ein Element enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusRegionNode\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) |  |

