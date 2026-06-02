---
title: "EmfBoundedRecord"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Базовый класс полигональной формы EMF."
type: docs
weight: 19
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public abstract class EmfBoundedRecord extends EmfDrawingRecordType
```

Базовый класс полигональной формы EMF.
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает 128-битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в единицах устройства. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Задает 128-битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в единицах устройства. |
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Получает 128-битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в единицах устройства.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - an 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units.
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Задает 128-битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в единицах устройства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | 128-битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в единицах устройства. |

