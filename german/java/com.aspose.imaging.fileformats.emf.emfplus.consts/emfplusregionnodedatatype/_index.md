---
title: "EmfPlusRegionNodeDataType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die RegionNodeDataType-Aufzählung definiert Typen von Regionsknoten-Daten."
type: docs
weight: 46
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRegionNodeDataType extends System.Enum
```

Die RegionNodeDataType-Aufzählung definiert Typen von Regionsknoten-Daten.

--------------------

Regionknotendaten werden durch [EmfPlusRegionNode](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode)-Objekte (Abschnitt 2.2.2.40) angegeben.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [RegionNodeDataTypeAnd](#RegionNodeDataTypeAnd) | Gibt einen Regionsknoten mit Kindknoten an. |
| [RegionNodeDataTypeOr](#RegionNodeDataTypeOr) | Gibt einen Regionsknoten mit Kindknoten an. |
| [RegionNodeDataTypeXor](#RegionNodeDataTypeXor) | Gibt einen Regionsknoten mit Kindknoten an. |
| [RegionNodeDataTypeExclude](#RegionNodeDataTypeExclude) | Gibt einen Regionsknoten mit Kindknoten an. |
| [RegionNodeDataTypeComplement](#RegionNodeDataTypeComplement) | Gibt einen Regionsknoten mit Kindknoten an. |
| [RegionNodeDataTypeRect](#RegionNodeDataTypeRect) | Gibt einen Regionsknoten ohne Kindknoten an. |
| [RegionNodeDataTypePath](#RegionNodeDataTypePath) | Gibt einen Regionsknoten ohne Kindknoten an. |
| [RegionNodeDataTypeEmpty](#RegionNodeDataTypeEmpty) | Gibt einen Regionsknoten ohne Kindknoten an. |
| [RegionNodeDataTypeInfinite](#RegionNodeDataTypeInfinite) | Gibt einen Regionsknoten ohne Kindknoten an, und seine Grenzen sind nicht definiert. |
### RegionNodeDataTypeAnd {#RegionNodeDataTypeAnd}
```
public static final int RegionNodeDataTypeAnd
```


Gibt einen Regionsknoten mit Kindknoten an. Eine boolesche UND‑Operation SOLLTE auf die linken und rechten Kindknoten angewendet werden, die durch ein [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes)-Objekt (Abschnitt 2.2.2.41) angegeben sind.

### RegionNodeDataTypeOr {#RegionNodeDataTypeOr}
```
public static final int RegionNodeDataTypeOr
```


Gibt einen Regionsknoten mit Kindknoten an. Eine boolesche ODER‑Operation SOLLTE auf die linken und rechten Kindknoten angewendet werden, die durch ein [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes)-Objekt angegeben sind.

### RegionNodeDataTypeXor {#RegionNodeDataTypeXor}
```
public static final int RegionNodeDataTypeXor
```


Gibt einen Regionsknoten mit Kindknoten an. Eine boolesche XOR‑Operation SOLLTE auf die linken und rechten Kindknoten angewendet werden, die durch ein [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes)-Objekt angegeben sind.

### RegionNodeDataTypeExclude {#RegionNodeDataTypeExclude}
```
public static final int RegionNodeDataTypeExclude
```


Gibt einen Regionsknoten mit Kindknoten an. Eine boolesche Operation, definiert als "der Teil von Region 1, der von Region 2 ausgeschlossen ist", SOLLTE auf die linken und rechten Kindknoten angewendet werden, die durch ein [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes)-Objekt angegeben sind.

### RegionNodeDataTypeComplement {#RegionNodeDataTypeComplement}
```
public static final int RegionNodeDataTypeComplement
```


Gibt einen Regionsknoten mit Kindknoten an. Eine boolesche Operation, definiert als "der Teil von Region 2, der von Region 1 ausgeschlossen ist", SOLLTE auf die linken und rechten Kindknoten angewendet werden, die durch ein [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes)-Objekt angegeben sind.

### RegionNodeDataTypeRect {#RegionNodeDataTypeRect}
```
public static final int RegionNodeDataTypeRect
```


Gibt einen Regionsknoten ohne Kindknoten an. Das Feld RegionNodeData SOLLTE eine Grenze mit einem [EmfPlusRectF](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf)-Objekt (Abschnitt 2.2.2.39) angeben.

### RegionNodeDataTypePath {#RegionNodeDataTypePath}
```
public static final int RegionNodeDataTypePath
```


Gibt einen Regionsknoten ohne Kindknoten an. Das Feld RegionNodeData SOLLTE eine Grenze mit einem [EmfPlusRegionNodePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath)-Objekt (Abschnitt 2.2.2.42) angeben.

### RegionNodeDataTypeEmpty {#RegionNodeDataTypeEmpty}
```
public static final int RegionNodeDataTypeEmpty
```


Gibt einen Regionsknoten ohne Kindknoten an. Das Feld RegionNodeData SOLLTE NICHT vorhanden sein.

### RegionNodeDataTypeInfinite {#RegionNodeDataTypeInfinite}
```
public static final int RegionNodeDataTypeInfinite
```


Gibt einen Regionsknoten ohne Kindknoten an, und seine Grenzen sind nicht definiert.

