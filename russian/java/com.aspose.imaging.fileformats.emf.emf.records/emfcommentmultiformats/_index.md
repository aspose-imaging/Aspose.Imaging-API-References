---
title: "EmfCommentMultiFormats"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_COMMENT_MULTIFORMATS указывает изображение в нескольких графических форматах."
type: docs
weight: 30
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentMultiFormats extends EmfCommentPublicRecordType
```

Запись EMR\_COMMENT\_MULTIFORMATS указывает изображение в нескольких графических форматах.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfCommentMultiFormats(EmfRecord source)](#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfCommentMultiFormats`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getOutputRect()](#getOutputRect--) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет выходной прямоугольник в логических координатах. |
| [setOutputRect(Rectangle value)](#setOutputRect-com.aspose.imaging.Rectangle-) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет выходной прямоугольник в логических координатах. |
| [getAFormats()](#getAFormats--) | Получает или задает массив длиной CountFormats графических форматов, указанных объектами EmrFormat (раздел 2.2.4), в порядке предпочтения. |
| [setAFormats(EmfFormat[] value)](#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---) | Получает или задает массив длиной CountFormats графических форматов, указанных объектами EmrFormat (раздел 2.2.4), в порядке предпочтения. |
| [getFormatData()](#getFormatData--) | Получает или задает переменного размера массив байтов данных изображения для всех графических форматов, содержащихся в этой записи. |
| [setFormatData(byte[][] value)](#setFormatData-byte-----) | Получает или задает переменного размера массив байтов данных изображения для всех графических форматов, содержащихся в этой записи. |
### EmfCommentMultiFormats(EmfRecord source) {#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentMultiFormats(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfCommentMultiFormats`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getOutputRect() {#getOutputRect--}
```
public Rectangle getOutputRect()
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет выходной прямоугольник в логических координатах.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setOutputRect(Rectangle value) {#setOutputRect-com.aspose.imaging.Rectangle-}
```
public void setOutputRect(Rectangle value)
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет выходной прямоугольник в логических координатах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAFormats() {#getAFormats--}
```
public EmfFormat[] getAFormats()
```


Получает или задает массив длиной CountFormats графических форматов, указанных объектами EmrFormat (раздел 2.2.4), в порядке предпочтения.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat[]
### setAFormats(EmfFormat[] value) {#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---}
```
public void setAFormats(EmfFormat[] value)
```


Получает или задает массив длиной CountFormats графических форматов, указанных объектами EmrFormat (раздел 2.2.4), в порядке предпочтения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfFormat\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfformat) |  |

### getFormatData() {#getFormatData--}
```
public byte[][] getFormatData()
```


Получает или задает переменного размера массив байтов данных изображения для всех графических форматов, содержащихся в этой записи. Размер данных для каждого изображения задаётся полем DataSize в соответствующем объекте EmrFormat. Таким образом, общий размер этого поля является суммой значений DataSize во всех объектах EmrFormat. Графический формат данных для каждого изображения указывается полем Signature в соответствующем объекте EmrFormat.

**Returns:**
byte[][]
### setFormatData(byte[][] value) {#setFormatData-byte-----}
```
public void setFormatData(byte[][] value)
```


Получает или задает переменного размера массив байтов данных изображения для всех графических форматов, содержащихся в этой записи. Размер данных для каждого изображения задаётся полем DataSize в соответствующем объекте EmrFormat. Таким образом, общий размер этого поля является суммой значений DataSize во всех объектах EmrFormat. Графический формат данных для каждого изображения указывается полем Signature в соответствующем объекте EmrFormat.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[][] |  |

