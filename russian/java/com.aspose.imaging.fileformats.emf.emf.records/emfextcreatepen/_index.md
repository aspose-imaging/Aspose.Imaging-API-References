---
title: "EmfExtCreatePen"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_EXTCREATEPEN определяет расширенную логическую ручку для графических операций."
type: docs
weight: 52
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreatePen extends EmfObjectCreationRecordType
```

Запись EMR\\_EXTCREATEPEN определяет расширенную логическую ручку для графических операций. Можно указать необязательный DIB, который будет использоваться в качестве стиля линии.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfExtCreatePen(EmfRecord record)](#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfExtCreatePen`. |
| [EmfExtCreatePen()](#EmfExtCreatePen--) | Инициализирует новый экземпляр класса `EmfExtCreatePen`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhPen()](#getIhPen--) | Получает или задает 32‑битное беззнаковое целое, которое указывает индекс расширенного логического объекта пера в таблице объектов EMF (раздел 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | Получает или задает 32‑битное беззнаковое целое, которое указывает индекс расширенного логического объекта пера в таблице объектов EMF (раздел 3.1.1.1). |
| [getElp()](#getElp--) | Получает или задает объект LogPenEx (раздел 2.2.20), который определяет расширенное логическое перо с атрибутами, включая необязательный массив стилей линий. |
| [setElp(EmfLogPenEx value)](#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-) | Получает или задает объект LogPenEx (раздел 2.2.20), который определяет расширенное логическое перо с атрибутами, включая необязательный массив стилей линий. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Получает или задает необязательный буфер, содержащий упакованный DIB в виде объекта WMF DeviceIndependentBitmap ([MS-WMF] раздел 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает необязательный буфер, содержащий упакованный DIB в виде объекта WMF DeviceIndependentBitmap ([MS-WMF] раздел 2.2.2.9). |
### EmfExtCreatePen(EmfRecord record) {#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreatePen(EmfRecord record)
```


Инициализирует новый экземпляр класса `EmfExtCreatePen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Запись. |

### EmfExtCreatePen() {#EmfExtCreatePen--}
```
public EmfExtCreatePen()
```


Инициализирует новый экземпляр класса `EmfExtCreatePen`.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Получает или задает 32‑битное беззнаковое целое, которое указывает индекс расширенного логического объекта пера в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект можно было повторно использовать или изменить.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое указывает индекс расширенного логического объекта пера в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект можно было повторно использовать или изменить.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getElp() {#getElp--}
```
public EmfLogPenEx getElp()
```


Получает или задает объект LogPenEx (раздел 2.2.20), который определяет расширенное логическое перо с атрибутами, включая необязательный массив стилей линий.

**Returns:**
[EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex)
### setElp(EmfLogPenEx value) {#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-}
```
public void setElp(EmfLogPenEx value)
```


Получает или задает объект LogPenEx (раздел 2.2.20), который определяет расширенное логическое перо с атрибутами, включая необязательный массив стилей линий.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex) |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Получает или задает необязательный буфер, содержащий упакованный DIB в виде объекта WMF DeviceIndependentBitmap ([MS-WMF] раздел 2.2.2.9). Он не обязан быть смежным с фиксированной частью записи EMR\\_EXTCREATEPEN.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Получает или задает необязательный буфер, содержащий упакованный DIB в виде объекта WMF DeviceIndependentBitmap ([MS-WMF] раздел 2.2.2.9). Он не обязан быть смежным с фиксированной частью записи EMR\\_EXTCREATEPEN.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

