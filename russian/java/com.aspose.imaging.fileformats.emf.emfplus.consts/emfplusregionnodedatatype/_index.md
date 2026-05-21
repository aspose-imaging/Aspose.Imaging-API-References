---
title: "EmfPlusRegionNodeDataType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление RegionNodeDataType определяет типы данных узлов региона."
type: docs
weight: 46
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRegionNodeDataType extends System.Enum
```

Перечисление RegionNodeDataType определяет типы данных узлов региона.

--------------------

Данные узла региона задаются объектами [EmfPlusRegionNode](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) (раздел 2.2.2.40).
## Поля

| Поле | Описание |
| --- | --- |
| [RegionNodeDataTypeAnd](#RegionNodeDataTypeAnd) | Определяет узел региона с дочерними узлами. |
| [RegionNodeDataTypeOr](#RegionNodeDataTypeOr) | Определяет узел региона с дочерними узлами. |
| [RegionNodeDataTypeXor](#RegionNodeDataTypeXor) | Определяет узел региона с дочерними узлами. |
| [RegionNodeDataTypeExclude](#RegionNodeDataTypeExclude) | Определяет узел региона с дочерними узлами. |
| [RegionNodeDataTypeComplement](#RegionNodeDataTypeComplement) | Определяет узел региона с дочерними узлами. |
| [RegionNodeDataTypeRect](#RegionNodeDataTypeRect) | Определяет узел региона без дочерних узлов. |
| [RegionNodeDataTypePath](#RegionNodeDataTypePath) | Определяет узел региона без дочерних узлов. |
| [RegionNodeDataTypeEmpty](#RegionNodeDataTypeEmpty) | Определяет узел региона без дочерних узлов. |
| [RegionNodeDataTypeInfinite](#RegionNodeDataTypeInfinite) | Определяет узел региона без дочерних узлов, и его границы не определены. |
### RegionNodeDataTypeAnd {#RegionNodeDataTypeAnd}
```
public static final int RegionNodeDataTypeAnd
```


Определяет узел региона с дочерними узлами. Булева операция И ДОЛЖНА быть применена к левому и правому дочерним узлам, указанным объектом [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) (раздел 2.2.2.41).

### RegionNodeDataTypeOr {#RegionNodeDataTypeOr}
```
public static final int RegionNodeDataTypeOr
```


Определяет узел региона с дочерними узлами. Булева операция ИЛИ ДОЛЖНА быть применена к левому и правому дочерним узлам, указанным объектом [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeXor {#RegionNodeDataTypeXor}
```
public static final int RegionNodeDataTypeXor
```


Определяет узел региона с дочерними узлами. Булева операция XOR ДОЛЖНА быть применена к левому и правому дочерним узлам, указанным объектом [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeExclude {#RegionNodeDataTypeExclude}
```
public static final int RegionNodeDataTypeExclude
```


Определяет узел региона с дочерними узлами. Булева операция, определённая как «часть региона 1, исключённая из региона 2», ДОЛЖНА быть применена к левому и правому дочерним узлам, указанным объектом [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeComplement {#RegionNodeDataTypeComplement}
```
public static final int RegionNodeDataTypeComplement
```


Определяет узел региона с дочерними узлами. Булева операция, определённая как «часть региона 2, исключённая из региона 1», ДОЛЖНА быть применена к левому и правому дочерним узлам, указанным объектом [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeRect {#RegionNodeDataTypeRect}
```
public static final int RegionNodeDataTypeRect
```


Определяет узел региона без дочерних узлов. Поле RegionNodeData ДОЛЖНО задавать границу с объектом [EmfPlusRectF](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf) (раздел 2.2.2.39).

### RegionNodeDataTypePath {#RegionNodeDataTypePath}
```
public static final int RegionNodeDataTypePath
```


Определяет узел региона без дочерних узлов. Поле RegionNodeData ДОЛЖНО задавать границу с объектом [EmfPlusRegionNodePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath) (раздел 2.2.2.42).

### RegionNodeDataTypeEmpty {#RegionNodeDataTypeEmpty}
```
public static final int RegionNodeDataTypeEmpty
```


Определяет узел региона без дочерних узлов. Поле RegionNodeData НЕ ДОЛЖНО присутствовать

### RegionNodeDataTypeInfinite {#RegionNodeDataTypeInfinite}
```
public static final int RegionNodeDataTypeInfinite
```


Определяет узел региона без дочерних узлов, и его границы не определены.

