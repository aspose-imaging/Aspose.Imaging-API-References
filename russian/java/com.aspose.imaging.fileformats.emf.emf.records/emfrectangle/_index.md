---
title: "EmfRectangle"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_RECTANGLE рисует прямоугольник."
type: docs
weight: 107
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRectangle extends EmfDrawingRecordType
```

Запись EMR\_RECTANGLE рисует прямоугольник. Прямоугольник обводится с помощью текущей ручки и заполняется с помощью текущей кисти.

Текущее положение не используется и не обновляется функцией Rectangle. Если используется ручка PS\_NULL, размеры прямоугольника на 1 пиксель меньше по высоте и на 1 пиксель меньше по ширине.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfRectangle(EmfRecord source)](#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfRectangle`. |
| [EmfRectangle()](#EmfRectangle--) | Инициализирует новый экземпляр класса `EmfRectangle`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBox()](#getBox--) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] раздел 2.2.2.19, который определяет включительно‑включительный прямоугольник для рисования. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] раздел 2.2.2.19, который определяет включительно‑включительный прямоугольник для рисования. |
### EmfRectangle(EmfRecord source) {#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRectangle(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfRectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfRectangle() {#EmfRectangle--}
```
public EmfRectangle()
```


Инициализирует новый экземпляр класса `EmfRectangle`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] раздел 2.2.2.19, который определяет включительно‑включительный прямоугольник для рисования.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] раздел 2.2.2.19, который определяет включительно‑включительный прямоугольник для рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

