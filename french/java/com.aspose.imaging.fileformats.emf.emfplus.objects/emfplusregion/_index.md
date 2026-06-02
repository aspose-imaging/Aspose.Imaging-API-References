---
title: "EmfPlusRegion"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusRegion spécifie les segments de lignes et de courbes qui définissent une forme non rectiligne."
type: docs
weight: 68
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusRegion extends EmfPlusGraphicsObjectType
```

L'objet EmfPlusRegion spécifie les segments de lignes et de courbes qui définissent une forme non rectiligne.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusRegion()](#EmfPlusRegion--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRegionNode()](#getRegionNode--) | Obtient ou définit un tableau de RegionNodeCount+1 objets EmfPlusRegionNode (section 2.2.2.40). |
| [setRegionNode(EmfPlusRegionNode[] value)](#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---) | Obtient ou définit un tableau de RegionNodeCount+1 objets EmfPlusRegionNode (section 2.2.2.40). |
### EmfPlusRegion() {#EmfPlusRegion--}
```
public EmfPlusRegion()
```


### getRegionNode() {#getRegionNode--}
```
public EmfPlusRegionNode[] getRegionNode()
```


Obtient ou définit un tableau de RegionNodeCount+1 objets EmfPlusRegionNode (section 2.2.2.40). Les régions sont spécifiées comme un arbre binaire de nœuds de région, et chaque nœud DOIT être soit un nœud terminal, soit spécifier un ou deux nœuds enfants. RegionNode DOIT contenir au moins un élément.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode[]
### setRegionNode(EmfPlusRegionNode[] value) {#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---}
```
public void setRegionNode(EmfPlusRegionNode[] value)
```


Obtient ou définit un tableau de RegionNodeCount+1 objets EmfPlusRegionNode (section 2.2.2.40). Les régions sont spécifiées comme un arbre binaire de nœuds de région, et chaque nœud DOIT être soit un nœud terminal, soit spécifier un ou deux nœuds enfants. RegionNode DOIT contenir au moins un élément.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusRegionNode\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) |  |

