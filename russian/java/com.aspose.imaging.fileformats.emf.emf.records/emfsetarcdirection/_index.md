---
title: "EmfSetArcDirection"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETARCDIRECTION указывает направление рисования, которое будет использоваться для вывода дуг и прямоугольников."
type: docs
weight: 118
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetArcDirection extends EmfStateRecordType
```

Запись EMR\_SETARCDIRECTION определяет направление рисования, которое будет использоваться для вывода дуг и прямоугольников.

Запись EMR\_SETARCDIRECTION влияет на направление, в котором рисуются следующие записи: - EMR\_ARC (раздел 2.3.5.2) - EMR\_ARCTO (раздел 2.3.5.3) - EMR\_CHORD (раздел 2.3.5.4) - EMR\_ELLIPSE (раздел 2.3.5.5) - EMR\_PIE (раздел 2.3.5.15) - EMR\_RECTANGLE (раздел 2.3.5.34) - EMR\_ROUNDRECT (раздел 2.3.5.35)
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetArcDirection(EmfRecord source)](#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetArcDirection`. |
| [EmfSetArcDirection()](#EmfSetArcDirection--) | Инициализирует новый экземпляр класса `EmfSetArcDirection`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getArcDirection()](#getArcDirection--) | Получает или задает 32‑битное беззнаковое целое, определяющее направление дуги. |
| [setArcDirection(int value)](#setArcDirection-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее направление дуги. |
### EmfSetArcDirection(EmfRecord source) {#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetArcDirection(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetArcDirection`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfSetArcDirection() {#EmfSetArcDirection--}
```
public EmfSetArcDirection()
```


Инициализирует новый экземпляр класса `EmfSetArcDirection`.

### getArcDirection() {#getArcDirection--}
```
public int getArcDirection()
```


Получает или задает 32‑битное беззнаковое целое, определяющее направление дуги. Значение ДОЛЖНО быть из перечисления ArcDirection (раздел 2.1.2). Направление по умолчанию — против часовой стрелки.

**Returns:**
int
### setArcDirection(int value) {#setArcDirection-int-}
```
public void setArcDirection(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее направление дуги. Значение ДОЛЖНО быть из перечисления ArcDirection (раздел 2.1.2). Направление по умолчанию — против часовой стрелки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

