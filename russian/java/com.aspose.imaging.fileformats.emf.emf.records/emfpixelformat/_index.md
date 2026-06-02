---
title: "EmfPixelFormat"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_PIXELFORMAT указывает формат пикселей, используемый для графических операций."
type: docs
weight: 83
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfpixelformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfPixelFormat extends EmfStateRecordType
```

Запись EMR_PIXELFORMAT задаёт формат пикселей, используемый для графических операций.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPixelFormat(EmfRecord source)](#EmfPixelFormat-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfPixelFormat`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPfd()](#getPfd--) | Получает или задает объект PixelFormatDescriptor (раздел 2.2.22), который указывает данные формата пикселей. |
| [setPfd(EmfPixelFormatDescriptor value)](#setPfd-com.aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor-) | Получает или задает объект PixelFormatDescriptor (раздел 2.2.22), который указывает данные формата пикселей. |
### EmfPixelFormat(EmfRecord source) {#EmfPixelFormat-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPixelFormat(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfPixelFormat`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getPfd() {#getPfd--}
```
public EmfPixelFormatDescriptor getPfd()
```


Получает или задает объект PixelFormatDescriptor (раздел 2.2.22), который указывает данные формата пикселей.

**Returns:**
[EmfPixelFormatDescriptor](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor)
### setPfd(EmfPixelFormatDescriptor value) {#setPfd-com.aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor-}
```
public void setPfd(EmfPixelFormatDescriptor value)
```


Получает или задает объект PixelFormatDescriptor (раздел 2.2.22), который указывает данные формата пикселей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPixelFormatDescriptor](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor) |  |

