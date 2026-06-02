---
title: "EmfSetColorSpace"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETCOLORSPACE определяет текущий логический объект цветового пространства для графических операций."
type: docs
weight: 123
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetColorSpace extends EmfObjectManipulationRecordType
```

Запись EMR\_SETCOLORSPACE определяет текущий объект логического цветового пространства для графических операций.

Логический объект цветового пространства, определенный этой записью, ДОЛЖЕН использоваться в операциях рисования, указанных последующими записями EMF, пока не будет указан другой логический объект цветового пространства другой записью EMR\_SETCOLORSPACE, или объект не будет удалён записью EMR\_DELETECOLORSPACE.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetColorSpace(EmfRecord source)](#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetColorSpace`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhCS()](#getIhCS--) | Получает или задает 32‑битное беззнаковое целое, определяющее индекс логического объекта цветового пространства в таблице EMF Object Table (раздел 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее индекс логического объекта цветового пространства в таблице EMF Object Table (раздел 3.1.1.1). |
### EmfSetColorSpace(EmfRecord source) {#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorSpace(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetColorSpace`.

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

