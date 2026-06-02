---
title: "EmfPlusRegion"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusRegion especifica segmentos de líneas y curvas que definen una forma no rectilínea"
type: docs
weight: 68
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusRegion extends EmfPlusGraphicsObjectType
```

El objeto EmfPlusRegion especifica segmentos de líneas y curvas que definen una forma no rectilínea
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusRegion()](#EmfPlusRegion--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRegionNode()](#getRegionNode--) | Obtiene o establece una matriz de objetos RegionNodeCount+1 EmfPlusRegionNode (sección 2.2.2.40). |
| [setRegionNode(EmfPlusRegionNode[] value)](#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---) | Obtiene o establece una matriz de objetos RegionNodeCount+1 EmfPlusRegionNode (sección 2.2.2.40). |
### EmfPlusRegion() {#EmfPlusRegion--}
```
public EmfPlusRegion()
```


### getRegionNode() {#getRegionNode--}
```
public EmfPlusRegionNode[] getRegionNode()
```


Obtiene o establece una matriz de objetos RegionNodeCount+1 EmfPlusRegionNode (sección 2.2.40). Las regiones se especifican como un árbol binario de nodos de región, y cada nodo DEBE ser un nodo terminal o especificar uno o dos nodos hijos. RegionNode DEBE contener al menos un elemento.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode[]
### setRegionNode(EmfPlusRegionNode[] value) {#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---}
```
public void setRegionNode(EmfPlusRegionNode[] value)
```


Obtiene o establece una matriz de objetos RegionNodeCount+1 EmfPlusRegionNode (sección 2.2.40). Las regiones se especifican como un árbol binario de nodos de región, y cada nodo DEBE ser un nodo terminal o especificar uno o dos nodos hijos. RegionNode DEBE contener al menos un elemento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusRegionNode\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) |  |

