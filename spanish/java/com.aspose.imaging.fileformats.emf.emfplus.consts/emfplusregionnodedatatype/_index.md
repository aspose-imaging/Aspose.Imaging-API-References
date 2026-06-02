---
title: "EmfPlusRegionNodeDataType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración RegionNodeDataType define los tipos de datos de nodo de región."
type: docs
weight: 46
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRegionNodeDataType extends System.Enum
```

La enumeración RegionNodeDataType define los tipos de datos de nodo de región.

--------------------

Los datos del nodo de región se especifican mediante objetos [EmfPlusRegionNode](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) (sección 2.2.2.40).
## Campos

| Campo | Descripción |
| --- | --- |
| [RegionNodeDataTypeAnd](#RegionNodeDataTypeAnd) | Especifica un nodo de región con nodos hijos. |
| [RegionNodeDataTypeOr](#RegionNodeDataTypeOr) | Especifica un nodo de región con nodos hijos. |
| [RegionNodeDataTypeXor](#RegionNodeDataTypeXor) | Especifica un nodo de región con nodos hijos. |
| [RegionNodeDataTypeExclude](#RegionNodeDataTypeExclude) | Especifica un nodo de región con nodos hijos. |
| [RegionNodeDataTypeComplement](#RegionNodeDataTypeComplement) | Especifica un nodo de región con nodos hijos. |
| [RegionNodeDataTypeRect](#RegionNodeDataTypeRect) | Especifica un nodo de región sin nodos hijos. |
| [RegionNodeDataTypePath](#RegionNodeDataTypePath) | Especifica un nodo de región sin nodos hijos. |
| [RegionNodeDataTypeEmpty](#RegionNodeDataTypeEmpty) | Especifica un nodo de región sin nodos hijos. |
| [RegionNodeDataTypeInfinite](#RegionNodeDataTypeInfinite) | Especifica un nodo de región sin nodos hijos, y sus límites no están definidos. |
### RegionNodeDataTypeAnd {#RegionNodeDataTypeAnd}
```
public static final int RegionNodeDataTypeAnd
```


Especifica un nodo de región con nodos hijos. Se DEBE aplicar una operación Boolean AND a los nodos hijos izquierdo y derecho especificados por un objeto [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) (sección 2.2.2.41).

### RegionNodeDataTypeOr {#RegionNodeDataTypeOr}
```
public static final int RegionNodeDataTypeOr
```


Especifica un nodo de región con nodos hijos. Se DEBE aplicar una operación Boolean OR a los nodos hijos izquierdo y derecho especificados por un objeto [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeXor {#RegionNodeDataTypeXor}
```
public static final int RegionNodeDataTypeXor
```


Especifica un nodo de región con nodos hijos. Se DEBE aplicar una operación Boolean XOR a los nodos hijos izquierdo y derecho especificados por un objeto [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeExclude {#RegionNodeDataTypeExclude}
```
public static final int RegionNodeDataTypeExclude
```


Especifica un nodo de región con nodos hijos. Se DEBE aplicar una operación Boolean, definida como "la parte de la región 1 que se excluye de la región 2", a los nodos hijos izquierdo y derecho especificados por un objeto [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeComplement {#RegionNodeDataTypeComplement}
```
public static final int RegionNodeDataTypeComplement
```


Especifica un nodo de región con nodos hijos. Se DEBE aplicar una operación Boolean, definida como "la parte de la región 2 que se excluye de la región 1", a los nodos hijos izquierdo y derecho especificados por un objeto [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeRect {#RegionNodeDataTypeRect}
```
public static final int RegionNodeDataTypeRect
```


Especifica un nodo de región sin nodos hijos. El campo RegionNodeData DEBE especificar un límite con un objeto [EmfPlusRectF](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf) (sección 2.2.2.39).

### RegionNodeDataTypePath {#RegionNodeDataTypePath}
```
public static final int RegionNodeDataTypePath
```


Especifica un nodo de región sin nodos hijos. El campo RegionNodeData DEBE especificar un límite con un objeto [EmfPlusRegionNodePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath) (sección 2.2.2.42).

### RegionNodeDataTypeEmpty {#RegionNodeDataTypeEmpty}
```
public static final int RegionNodeDataTypeEmpty
```


Especifica un nodo de región sin nodos hijos. El campo RegionNodeData NO DEBE estar presente

### RegionNodeDataTypeInfinite {#RegionNodeDataTypeInfinite}
```
public static final int RegionNodeDataTypeInfinite
```


Especifica un nodo de región sin nodos hijos, y sus límites no están definidos.

