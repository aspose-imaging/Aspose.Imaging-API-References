---
title: "EmfExtSelectClipRgn"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_EXTSELECTCLIPRGN объединяет указанную область с текущей областью отсечения, используя указанный режим."
type: docs
weight: 55
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExtSelectClipRgn extends EmfClippingRecordType
```

Запись EMR\_EXTSELECTCLIPRGN объединяет указанную область с текущей областью отсечения, используя указанный режим. Примечание: поля, не описанные в этом разделе, указаны в разделе 2.3.2.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfExtSelectClipRgn(EmfRecord source)](#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfExtSelectClipRgn`. |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn--) | Инициализирует новый экземпляр класса `EmfExtSelectClipRgn`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRgnDataSize()](#getRgnDataSize--) | Получает или задает 32-битное беззнаковое целое, определяющее размер данных области в байтах. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Получает или задает 32-битное беззнаковое целое, определяющее размер данных области в байтах. |
| [getRegionMode()](#getRegionMode--) | Получает или задает 32-битное беззнаковое целое, определяющее способ использования области. |
| [setRegionMode(int value)](#setRegionMode-int-) | Получает или задает 32-битное беззнаковое целое, определяющее способ использования области. |
| [getRgnData()](#getRgnData--) | Получает или задает массив байтов длиной RgnDataSize, определяющий объект RegionData в логических единицах. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Получает или задает массив байтов длиной RgnDataSize, определяющий объект RegionData в логических единицах. |
### EmfExtSelectClipRgn(EmfRecord source) {#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtSelectClipRgn(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfExtSelectClipRgn`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfExtSelectClipRgn() {#EmfExtSelectClipRgn--}
```
public EmfExtSelectClipRgn()
```


Инициализирует новый экземпляр класса `EmfExtSelectClipRgn`.

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Получает или задает 32-битное беззнаковое целое, определяющее размер данных области в байтах.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Получает или задает 32-битное беззнаковое целое, определяющее размер данных области в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Получает или задает 32-битное беззнаковое целое, определяющее способ использования области. Значение ДОЛЖНО быть в перечислении RegionMode (раздел 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Получает или задает 32-битное беззнаковое целое, определяющее способ использования области. Значение ДОЛЖНО быть в перечислении RegionMode (раздел 2.1.29).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Получает или задает массив байтов длиной RgnDataSize, определяющий объект RegionData в логических единицах. Если RegionMode равен RGN\_COPY, эти данные могут быть опущены, и область отсечения ДОЛЖНА быть установлена в значение по умолчанию (NULL).

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Получает или задает массив байтов длиной RgnDataSize, определяющий объект RegionData в логических единицах. Если RegionMode равен RGN\_COPY, эти данные могут быть опущены, и область отсечения ДОЛЖНА быть установлена в значение по умолчанию (NULL).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

