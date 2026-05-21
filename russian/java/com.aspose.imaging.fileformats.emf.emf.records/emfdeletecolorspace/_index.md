---
title: "EmfDeleteColorSpace"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_DELETECOLORSPACE удаляет логический объект цветового пространства."
type: docs
weight: 42
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfDeleteColorSpace extends EmfObjectManipulationRecordType
```

Запись EMR\_DELETECOLORSPACE удаляет объект логического цветового пространства.

Запись EMR\_DELETEOBJECT ДОЛЖНА использоваться вместо EMR\_DELETECOLORSPACE для удаления логического объекта цветового пространства.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfDeleteColorSpace(EmfRecord source)](#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfDeleteColorSpace`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhCS()](#getIhCS--) | Получает или задает 32‑битное беззнаковое целое, определяющее индекс логического объекта цветового пространства в таблице EMF Object Table (раздел 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее индекс логического объекта цветового пространства в таблице EMF Object Table (раздел 3.1.1.1). |
### EmfDeleteColorSpace(EmfRecord source) {#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteColorSpace(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfDeleteColorSpace`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Получает или задает 32‑битное беззнаковое целое, определяющее индекс логического объекта цветового пространства в таблице EMF Object Table (раздел 3.1.1.1).

Этот объект является либо объектом WMF LogColorSpace, либо LogColorSpaceW ([MS-WMF] разделы 2.2.2.11 и 2.2.2.12 соответственно).

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее индекс логического объекта цветового пространства в таблице EMF Object Table (раздел 3.1.1.1).

Этот объект является либо объектом WMF LogColorSpace, либо LogColorSpaceW ([MS-WMF] разделы 2.2.2.11 и 2.2.2.12 соответственно).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

