---
title: "EmfCreateDibPatternBrushPt"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_CREATEDIBPATTERNBRUSHPT определяет шаблонную кисть для графических операций."
type: docs
weight: 38
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateDibPatternBrushPt extends EmfObjectCreationRecordType
```

Запись EMR\_CREATEDIBPATTERNBRUSHPT определяет шаблонную кисть для графических операций. Шаблон задаётся DIB.

Объект шаблонной кисти, определённый этой записью, может быть выбран в контекст устройства воспроизведения записью EMR\_SELECTOBJECT (раздел 2.3.8.5), которая указывает шаблонную кисть для последующих графических операций.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfCreateDibPatternBrushPt(EmfRecord source)](#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfCreateDibPatternBrushPt`. |
| [EmfCreateDibPatternBrushPt()](#EmfCreateDibPatternBrushPt--) | Инициализирует новый экземпляр класса `EmfCreateDibPatternBrushPt`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Получает или задает 32‑битное беззнаковое целое, определяющее индекс объекта шаблонной кисти в таблице EMF Object Table (раздел 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее индекс объекта шаблонной кисти в таблице EMF Object Table (раздел 3.1.1.1). |
| [getUsage()](#getUsage--) | Получает или задает 32‑битное беззнаковое целое, определяющее способ интерпретации значений в таблице цветов заголовка DIB. |
| [setUsage(int value)](#setUsage-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее способ интерпретации значений в таблице цветов заголовка DIB. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Получает или задает буфер, содержащий упакованный DIB в виде объекта WMF DeviceIndependentBitmap ([MS-WMF] раздел 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает буфер, содержащий упакованный DIB в виде объекта WMF DeviceIndependentBitmap ([MS-WMF] раздел 2.2.2.9). |
### EmfCreateDibPatternBrushPt(EmfRecord source) {#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateDibPatternBrushPt(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfCreateDibPatternBrushPt`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfCreateDibPatternBrushPt() {#EmfCreateDibPatternBrushPt--}
```
public EmfCreateDibPatternBrushPt()
```


Инициализирует новый экземпляр класса `EmfCreateDibPatternBrushPt`.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Получает или задает 32‑битное беззнаковое целое, определяющее индекс объекта шаблонной кисти в таблице EMF Object Table (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект мог быть повторно использован или изменён.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее индекс объекта шаблонной кисти в таблице EMF Object Table (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект мог быть повторно использован или изменён.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getUsage() {#getUsage--}
```
public int getUsage()
```


Получает или задает 32-битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов в заголовке DIB. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9).

**Returns:**
int
### setUsage(int value) {#setUsage-int-}
```
public void setUsage(int value)
```


Получает или задает 32-битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов в заголовке DIB. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Получает или задает буфер, содержащий упакованный DIB в виде объекта WMF DeviceIndependentBitmap ([MS-WMF] раздел 2.2.2.9). Он не обязан быть смежным с фиксированной частью записи EMR\_CREATEDIBPATTERNBRUSHPT.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Получает или задает буфер, содержащий упакованный DIB в виде объекта WMF DeviceIndependentBitmap ([MS-WMF] раздел 2.2.2.9). Он не обязан быть смежным с фиксированной частью записи EMR\_CREATEDIBPATTERNBRUSHPT.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

