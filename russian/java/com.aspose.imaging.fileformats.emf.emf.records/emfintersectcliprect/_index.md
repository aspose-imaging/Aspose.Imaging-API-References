---
title: "EmfIntersectClipRect"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_INTERSECTCLIPRECT определяет новую область отсечения как пересечение текущей области отсечения и указанного прямоугольника."
type: docs
weight: 66
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfintersectcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfIntersectClipRect extends EmfClippingRecordType
```

Запись EMR\\_INTERSECTCLIPRECT определяет новую область отсечения как пересечение текущей области отсечения и указанного прямоугольника. Обратите внимание, что поля, не описанные в этом разделе, указаны в разделе 2.3.2.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfIntersectClipRect(EmfRecord source)](#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfIntersectClipRect`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getClip()](#getClip--) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольник в логических единицах. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольник в логических единицах. |
### EmfIntersectClipRect(EmfRecord source) {#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfIntersectClipRect(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfIntersectClipRect`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольник в логических единицах.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольник в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

