---
title: "EmfOffsetClipRgn"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_OFFSETCLIPRGN перемещает текущий регион отсечения в контексте воспроизведения устройства на указанные смещения."
type: docs
weight: 78
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfOffsetClipRgn extends EmfClippingRecordType
```

Запись EMR_OFFSETCLIPRGN перемещает текущую область отсечения в контексте устройства воспроизведения на указанные смещения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfOffsetClipRgn(EmfRecord source)](#EmfOffsetClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfOffsetClipRgn`. |
| [EmfOffsetClipRgn()](#EmfOffsetClipRgn--) | Инициализирует новый экземпляр класса `EmfOffsetClipRgn`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getOffset()](#getOffset--) | Получает объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который задает горизонтальные и вертикальные смещения в логических единицах. |
| [setOffset(Point value)](#setOffset-com.aspose.imaging.Point-) | Устанавливает объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который задает горизонтальные и вертикальные смещения в логических единицах. |
### EmfOffsetClipRgn(EmfRecord source) {#EmfOffsetClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfOffsetClipRgn(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfOffsetClipRgn`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfOffsetClipRgn() {#EmfOffsetClipRgn--}
```
public EmfOffsetClipRgn()
```


Инициализирует новый экземпляр класса `EmfOffsetClipRgn`.

### getOffset() {#getOffset--}
```
public Point getOffset()
```


Получает объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который задает горизонтальные и вертикальные смещения в логических единицах.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setOffset(Point value) {#setOffset-com.aspose.imaging.Point-}
```
public void setOffset(Point value)
```


Устанавливает объект WMF PointL ([MS-WMF] раздел 2.2.2.15), который задает горизонтальные и вертикальные смещения в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

