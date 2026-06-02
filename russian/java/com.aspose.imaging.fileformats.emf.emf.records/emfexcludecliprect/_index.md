---
title: "EmfExcludeClipRect"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_EXCLUDECLIPRECT определяет новую область отсечения, состоящую из существующей области отсечения за вычетом указанного прямоугольника."
type: docs
weight: 50
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExcludeClipRect extends EmfClippingRecordType
```

Запись EMR\_EXCLUDECLIPRECT определяет новую область отсечения, состоящую из существующей области отсечения за вычетом указанного прямоугольника. Примечание: поля, не описанные в этом разделе, указаны в разделе 2.3.2.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfExcludeClipRect(EmfRecord source)](#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfExcludeClipRect`. |
| [EmfExcludeClipRect()](#EmfExcludeClipRect--) | Инициализирует новый экземпляр класса `EmfExcludeClipRect`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getClip()](#getClip--) | Получает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольник отсечения в логических единицах. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольник отсечения в логических единицах. |
### EmfExcludeClipRect(EmfRecord source) {#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExcludeClipRect(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfExcludeClipRect`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfExcludeClipRect() {#EmfExcludeClipRect--}
```
public EmfExcludeClipRect()
```


Инициализирует новый экземпляр класса `EmfExcludeClipRect`.

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Получает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольник отсечения в логических единицах.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольник отсечения в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

