---
title: "EmfPlusRegion"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusRegion указывает линейные и криволинейные сегменты, определяющие нелинейную форму"
type: docs
weight: 68
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusRegion extends EmfPlusGraphicsObjectType
```

Объект EmfPlusRegion указывает линейные и криволинейные сегменты, определяющие нелинейную форму
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusRegion()](#EmfPlusRegion--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getRegionNode()](#getRegionNode--) | Получает или задает массив из RegionNodeCount+1 объектов EmfPlusRegionNode (раздел 2.2.2.40). |
| [setRegionNode(EmfPlusRegionNode[] value)](#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---) | Получает или задает массив из RegionNodeCount+1 объектов EmfPlusRegionNode (раздел 2.2.2.40). |
### EmfPlusRegion() {#EmfPlusRegion--}
```
public EmfPlusRegion()
```


### getRegionNode() {#getRegionNode--}
```
public EmfPlusRegionNode[] getRegionNode()
```


Получает или задает массив из RegionNodeCount+1 объектов EmfPlusRegionNode (раздел 2.2.2.40). Области задаются как бинарное дерево узлов области, и каждый узел ДОЛЖЕН быть либо терминальным узлом, либо указывать один или два дочерних узла. RegionNode ДОЛЖЕН содержать как минимум один элемент.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode[]
### setRegionNode(EmfPlusRegionNode[] value) {#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---}
```
public void setRegionNode(EmfPlusRegionNode[] value)
```


Получает или задает массив из RegionNodeCount+1 объектов EmfPlusRegionNode (раздел 2.2.2.40). Области задаются как бинарное дерево узлов области, и каждый узел ДОЛЖЕН быть либо терминальным узлом, либо указывать один или два дочерних узла. RegionNode ДОЛЖЕН содержать как минимум один элемент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusRegionNode\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) |  |

