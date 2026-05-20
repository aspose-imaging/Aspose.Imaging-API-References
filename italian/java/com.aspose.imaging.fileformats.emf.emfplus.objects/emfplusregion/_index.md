---
title: "EmfPlusRegion"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusRegion specifica segmenti di linee e curve che definiscono una forma non rettilinea"
type: docs
weight: 68
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusRegion extends EmfPlusGraphicsObjectType
```

L'oggetto EmfPlusRegion specifica segmenti di linee e curve che definiscono una forma non rettilinea
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusRegion()](#EmfPlusRegion--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRegionNode()](#getRegionNode--) | Ottiene o imposta un array di oggetti EmfPlusRegionNode di dimensione RegionNodeCount+1 (sezione 2.2.2.40). |
| [setRegionNode(EmfPlusRegionNode[] value)](#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---) | Ottiene o imposta un array di oggetti EmfPlusRegionNode di dimensione RegionNodeCount+1 (sezione 2.2.2.40). |
### EmfPlusRegion() {#EmfPlusRegion--}
```
public EmfPlusRegion()
```


### getRegionNode() {#getRegionNode--}
```
public EmfPlusRegionNode[] getRegionNode()
```


Ottiene o imposta un array di oggetti EmfPlusRegionNode di dimensione RegionNodeCount+1 (sezione 2.2.2.40). Le regioni sono specificate come un albero binario di nodi di regione, e ogni nodo DEVE essere un nodo terminale o specificare uno o due nodi figli. RegionNode DEVE contenere almeno un elemento.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode[]
### setRegionNode(EmfPlusRegionNode[] value) {#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---}
```
public void setRegionNode(EmfPlusRegionNode[] value)
```


Ottiene o imposta un array di oggetti EmfPlusRegionNode di dimensione RegionNodeCount+1 (sezione 2.2.2.40). Le regioni sono specificate come un albero binario di nodi di regione, e ogni nodo DEVE essere un nodo terminale o specificare uno o due nodi figli. RegionNode DEVE contenere almeno un elemento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusRegionNode\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) |  |

