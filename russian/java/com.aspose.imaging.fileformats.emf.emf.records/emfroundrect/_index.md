---
title: "EmfRoundRect"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_ROUNDRECT определяет прямоугольник со скруглёнными углами."
type: docs
weight: 111
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRoundRect extends EmfDrawingRecordType
```

Запись EMR\_ROUNDRECT определяет прямоугольник со скруглёнными углами. Прямоугольник обводится текущей ручкой и заполняется текущей кистью.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfRoundRect(EmfRecord source)](#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfRoundRect`. |
| [EmfRoundRect()](#EmfRoundRect--) | Инициализирует новый экземпляр класса [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect). |
## Методы

| Метод | Описание |
| --- | --- |
| [getBox()](#getBox--) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] раздел 2.2.2.19, который определяет включительно‑включительный прямоугольник для рисования. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] раздел 2.2.2.19, который определяет включительно‑включительный прямоугольник для рисования. |
| [getCorner()](#getCorner--) | Получает или задает 64‑битный объект WMF SizeL, указанный в [MS-WMF] раздел 2.2.2.22, который определяет ширину и высоту в логических координатах эллипса, используемого для рисования скруглённых углов. |
| [setCorner(Size value)](#setCorner-com.aspose.imaging.Size-) | Получает или задает 64‑битный объект WMF SizeL, указанный в [MS-WMF] раздел 2.2.2.22, который определяет ширину и высоту в логических координатах эллипса, используемого для рисования скруглённых углов. |
### EmfRoundRect(EmfRecord source) {#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRoundRect(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfRoundRect`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfRoundRect() {#EmfRoundRect--}
```
public EmfRoundRect()
```


Инициализирует новый экземпляр класса [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect).

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

### getCorner() {#getCorner--}
```
public Size getCorner()
```


Получает или задает 64‑битный объект WMF SizeL, указанный в [MS-WMF] раздел 2.2.2.22, который определяет ширину и высоту в логических координатах эллипса, используемого для рисования скруглённых углов.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setCorner(Size value) {#setCorner-com.aspose.imaging.Size-}
```
public void setCorner(Size value)
```


Получает или задает 64‑битный объект WMF SizeL, указанный в [MS-WMF] раздел 2.2.2.22, который определяет ширину и высоту в логических координатах эллипса, используемого для рисования скруглённых углов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

