---
title: "EmfInvertRgn"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_INVERTRGN инвертирует цвета в указанном регионе."
type: docs
weight: 67
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfInvertRgn extends EmfStateRecordType
```

Запись EMR\_INVERTRGN инвертирует цвета в указанной области.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfInvertRgn(EmfRecord source)](#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfInvertRgn`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник. |
| [getRgnDataSize()](#getRgnDataSize--) | Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных региона в байтах. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных региона в байтах. |
| [getRgnData()](#getRgnData--) | Получает или задает массив байтов длиной RgnDataSize, который определяет объект RegionData в логических единицах. |
| [setRgnData(byte[] value)](#setRgnData-byte---) | Получает или задает массив байтов длиной RgnDataSize, который определяет объект RegionData в логических единицах. |
### EmfInvertRgn(EmfRecord source) {#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfInvertRgn(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfInvertRgn`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который определяет ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных региона в байтах.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных региона в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public byte[] getRgnData()
```


Получает или задает массив байтов длиной RgnDataSize, который определяет объект RegionData в логических единицах.

**Returns:**
byte[]
### setRgnData(byte[] value) {#setRgnData-byte---}
```
public void setRgnData(byte[] value)
```


Получает или задает массив байтов длиной RgnDataSize, который определяет объект RegionData в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

