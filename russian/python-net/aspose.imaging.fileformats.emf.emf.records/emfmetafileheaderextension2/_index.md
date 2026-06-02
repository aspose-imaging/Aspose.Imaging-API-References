---
title: "Класс EmfMetafileHeaderExtension2"
type: docs
weight: 630
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/
---

**Summary:** The EmfMetafileHeaderExtension2 record is the header record used in the second extension to EMF<br/>            metafiles. Following the EmfHeaderExtension2 field, the remaining fields are optional and<br/>            can be present in any order.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension2

**Inheritance:** EmfMetafileHeaderExtension1

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfMetafileHeaderExtension2(header)](#EmfMetafileHeaderExtension2_header_1) | Инициализирует новый экземпляр класса [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/). |
| [EmfMetafileHeaderExtension2(header)](#EmfMetafileHeaderExtension2_header_2) | Инициализирует новый экземпляр класса [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| emf_description | string | r/w | Получает или задает описание EMF<br/>            Необязательная, нуль-терминированная строка Unicode UTF16-LE произвольной длины и содержания. <br/>            Ее расположение в записи и количество символов указываются полями offDescription <br/>            и nDescription соответственно в EmfHeader. Если значение любого из этих полей <br/>            равно нулю, строка описания отсутствует. |
| emf_description_buffer | System.Byte | r/w | Получает или задает буфер описания EMF<br/>            Необязательный массив байтов, содержащий строку описания EMF, которая <br/>            не обязана быть смежной с фиксированной частью записи EmfMetafileHeader <br/>            record. Соответственно, поле в этом буфере с меткой "UndefinedSpace" <br/>            является необязательным и MUST быть игнорировано. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Получает или задает объект Header (раздел 2.2.9), который содержит информацию о содержимом<br/>            и структуре метафайла |
| emf_header_extension1 | [EmfHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/) | r/w | Получает или задает объект HeaderExtension1, который определяет дополнительную информацию об изображении в метафайле. |
| emf_header_extension2 | [EmfHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/) | r/w | Получает или задает объект HeaderExtension2, который определяет дополнительную информацию об изображении в метафайле. |
| emf_header_record_buffer | System.Byte | r/w | Получает или задает необязательный массив байтов, содержащий оставшуюся часть записи заголовка EMF. <br/>            Размер этого поля MUST быть кратным 4 байтам |
| emf_pixel_format_buffer | System.Byte | r/w | Получает или задает необязательный массив байтов, содержащий дескриптор формата пикселей EMF, который не обязана быть смежным с фиксированной частью записи EmfMetafileHeaderExtension1 или со строкой описания EMF. Соответственно, поле в этом буфере с меткой "UndefinedSpace" является <br/>            необязательным и MUST быть игнорировано |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | Инициализирует новый экземпляр класса [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/). |
| [create_from_header_extension1(header)](#create_from_header_extension1_header_2) | Инициализирует новый экземпляр класса [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/). |
| [create_from_header_extension2(header)](#create_from_header_extension2_header_3) | Инициализирует новый экземпляр класса [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/). |
| [create_from_record(record)](#create_from_record_record_4) | Инициализирует новый экземпляр класса [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_type(type)](#create_from_type_type_5) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMetafileHeaderExtension2(header) {#EmfMetafileHeaderExtension2_header_1}


```
 EmfMetafileHeaderExtension2(header) 
```

Инициализирует новый экземпляр класса [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | Заголовок. |

### Constructor: EmfMetafileHeaderExtension2(header) {#EmfMetafileHeaderExtension2_header_2}


```
 EmfMetafileHeaderExtension2(header) 
```

Инициализирует новый экземпляр класса [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) | Заголовок. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

Инициализирует новый экземпляр класса [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | Заголовок. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_header_extension1(header)  [static] {#create_from_header_extension1_header_2}


```
 create_from_header_extension1(header) 
```

Инициализирует новый экземпляр класса [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | Заголовок. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) |  |


### Method: create_from_header_extension2(header)  [static] {#create_from_header_extension2_header_3}


```
 create_from_header_extension2(header) 
```

Инициализирует новый экземпляр класса [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) | Заголовок. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_4}


```
 create_from_record(record) 
```

Инициализирует новый экземпляр класса [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Запись. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_5}


```
 create_from_type(type) 
```

Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Тип записи. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


