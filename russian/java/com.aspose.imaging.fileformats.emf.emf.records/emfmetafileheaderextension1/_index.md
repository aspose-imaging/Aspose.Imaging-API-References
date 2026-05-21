---
title: "EmfMetafileHeaderExtension1"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfMetafileHeaderExtension1 является заголовочной записью, используемой в первом расширении метафайлов EMF."
type: docs
weight: 71
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
```
public class EmfMetafileHeaderExtension1 extends EmfMetafileHeader
```

Запись EmfMetafileHeaderExtension1 является заголовочной записью, используемой в первом расширении метафайлов EMF. После поля EmfHeaderExtension1 остальные поля являются необязательными и могут присутствовать в любом порядке.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfMetafileHeaderExtension1(EmfMetafileHeader header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Инициализирует новый экземпляр класса `EmfMetafileHeaderExtension1`. |
| [EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-) | Инициализирует новый экземпляр класса `EmfMetafileHeaderExtension1`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getEmfHeaderExtension1()](#getEmfHeaderExtension1--) | Получает или задает объект HeaderExtension1, который определяет дополнительную информацию об изображении в метафайле. |
| [setEmfHeaderExtension1(EmfHeaderExtension1 value)](#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-) | Получает или задает объект HeaderExtension1, который определяет дополнительную информацию об изображении в метафайле. |
| [getEmfPixelFormatBuffer()](#getEmfPixelFormatBuffer--) | Получает или задает необязательный массив байтов, содержащий дескриптор формата пикселей EMF, который не обязан быть смежным с фиксированной частью записи EmfMetafileHeaderExtension1 или со строкой описания EMF. |
| [setEmfPixelFormatBuffer(byte[] value)](#setEmfPixelFormatBuffer-byte---) | Получает или задает необязательный массив байтов, содержащий дескриптор формата пикселей EMF, который не обязан быть смежным с фиксированной частью записи EmfMetafileHeaderExtension1 или со строкой описания EMF. |
### EmfMetafileHeaderExtension1(EmfMetafileHeader header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeader header)
```


Инициализирует новый экземпляр класса `EmfMetafileHeaderExtension1`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | Заголовок. |

### EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)
```


Инициализирует новый экземпляр класса `EmfMetafileHeaderExtension1`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| header | [EmfMetafileHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | Заголовок. |

### getEmfHeaderExtension1() {#getEmfHeaderExtension1--}
```
public EmfHeaderExtension1 getEmfHeaderExtension1()
```


Получает или задает объект HeaderExtension1, который определяет дополнительную информацию об изображении в метафайле.

**Returns:**
[EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1)
### setEmfHeaderExtension1(EmfHeaderExtension1 value) {#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-}
```
public void setEmfHeaderExtension1(EmfHeaderExtension1 value)
```


Получает или задает объект HeaderExtension1, который определяет дополнительную информацию об изображении в метафайле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1) |  |

### getEmfPixelFormatBuffer() {#getEmfPixelFormatBuffer--}
```
public byte[] getEmfPixelFormatBuffer()
```


Получает или задает необязательный массив байтов, содержащий дескриптор формата пикселей EMF, который не обязан быть смежным с фиксированной частью записи EmfMetafileHeaderExtension1 или со строкой описания EMF. Соответственно, поле в этом буфере, помеченное как "UndefinedSpace", является необязательным и ДОЛЖНО быть проигнорировано.

**Returns:**
byte[]
### setEmfPixelFormatBuffer(byte[] value) {#setEmfPixelFormatBuffer-byte---}
```
public void setEmfPixelFormatBuffer(byte[] value)
```


Получает или задает необязательный массив байтов, содержащий дескриптор формата пикселей EMF, который не обязан быть смежным с фиксированной частью записи EmfMetafileHeaderExtension1 или со строкой описания EMF. Соответственно, поле в этом буфере, помеченное как "UndefinedSpace", является необязательным и ДОЛЖНО быть проигнорировано.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

