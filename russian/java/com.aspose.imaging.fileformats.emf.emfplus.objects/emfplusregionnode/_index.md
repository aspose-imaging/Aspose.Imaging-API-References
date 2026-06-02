---
title: "EmfPlusRegionNode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusRegionNode указывает узлы графической области."
type: docs
weight: 69
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusRegionNode extends EmfPlusStructureObjectType
```

Объект EmfPlusRegionNode указывает узлы графической области.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getRegionNodeData()](#getRegionNodeData--) | Получает или задает необязательные данные переменной длины, определяющие объект данных узла региона, указанный в поле Type. |
| [setRegionNodeData(EmfPlusStructureObjectType value)](#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-) | Получает или задает необязательные данные переменной длины, определяющие объект данных узла региона, указанный в поле Type. |
| [getType()](#getType--) | Получает или задает 32‑битное беззнаковое целое, которое указывает тип данных в поле RegionNodeData. |
| [setType(int value)](#setType-int-) | Получает или задает 32‑битное беззнаковое целое, которое указывает тип данных в поле RegionNodeData. |
### EmfPlusRegionNode() {#EmfPlusRegionNode--}
```
public EmfPlusRegionNode()
```


### getRegionNodeData() {#getRegionNodeData--}
```
public EmfPlusStructureObjectType getRegionNodeData()
```


Получает или задает необязательные данные переменной длины, определяющие объект данных узла региона, указанный в поле Type. Содержание и формат данных могут различаться для каждого типа узла региона. Это поле НЕ ДОЛЖНО присутствовать, если тип узла равен RegionNodeDataTypeEmpty или RegionNodeDataTypeInfinite. Этот объект является универсальным и используется для указания различных типов данных узла региона, включая: объект EmfPlusRegionNodePath (раздел 2.2.2.42) для терминального узла; объект EmfPlusRectF (раздел 2.2.2.39) для терминального узла; и объект EmfPlusRegionNodeChildNodes (раздел 2.2.2.41) для нетерминального узла.

**Returns:**
[EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
### setRegionNodeData(EmfPlusStructureObjectType value) {#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-}
```
public void setRegionNodeData(EmfPlusStructureObjectType value)
```


Получает или задает необязательные данные переменной длины, определяющие объект данных узла региона, указанный в поле Type. Содержание и формат данных могут различаться для каждого типа узла региона. Это поле НЕ ДОЛЖНО присутствовать, если тип узла равен RegionNodeDataTypeEmpty или RegionNodeDataTypeInfinite. Этот объект является универсальным и используется для указания различных типов данных узла региона, включая: объект EmfPlusRegionNodePath (раздел 2.2.2.42) для терминального узла; объект EmfPlusRectF (раздел 2.2.2.39) для терминального узла; и объект EmfPlusRegionNodeChildNodes (раздел 2.2.2.41) для нетерминального узла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype) |  |

### getType() {#getType--}
```
public int getType()
```


Получает или задает 32‑битное беззнаковое целое, которое указывает тип данных в поле RegionNodeData. Это значение ДОЛЖНО быть определено в перечислении RegionNodeDataType (раздел 2.1.1.27).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое указывает тип данных в поле RegionNodeData. Это значение ДОЛЖНО быть определено в перечислении RegionNodeDataType (раздел 2.1.1.27).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

