---
title: "EmfMetafileHeader Класс"
type: docs
weight: 610
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---

**Summary:** The EMR_HEADER record types define the starting points of EMF metafiles<br/>            and specify properties of the device on which the image in the metafile<br/>            was created. The information in the header record makes it possible for<br/>            EMF metafiles to be independent of any specific output device.<br/>            The value of the Size field can be used to distinguish between the different<br/>            EMR_HEADER record types listed earlier in this section.<br/>            There are three possible headers:<br/>            The base header, which is the EmfMetafileHeader record.<br/>            The fixed-size part of this header is 88 bytes, and it contains a Header object.<br/>            The first extension header, which is the EmfMetafileHeaderExtension1 record.<br/>            The fixed-size part of this header is 100 bytes, and it contains a Header object<br/>            and a HeaderExtension1 object (section 2.2.10).<br/>            The second extension header, which is the EmfMetafileHeaderExtension2 record.<br/>            The fixed-size part of this header is 108 bytes, and it contains a Header object,<br/>            a HeaderExtension1 object, and a HeaderExtension2 object (section 2.2.11).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfMetafileHeader()](#EmfMetafileHeader__1) | Инициализирует новый экземпляр класса [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [EmfMetafileHeader(header)](#EmfMetafileHeader_header_2) | Инициализирует новый экземпляр класса [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [EmfMetafileHeader(record)](#EmfMetafileHeader_record_3) | Инициализирует новый экземпляр класса [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| emf_description | string | r/w | Получает или задает описание EMF<br/>            Необязательная, нуль-терминированная строка Unicode UTF16-LE произвольной длины и содержания. <br/>            Ее расположение в записи и количество символов указываются полями offDescription <br/>            и nDescription соответственно в EmfHeader. Если значение любого из этих полей <br/>            равно нулю, строка описания отсутствует. |
| emf_description_buffer | System.Byte | r/w | Получает или задает буфер описания EMF<br/>            Необязательный массив байтов, содержащий строку описания EMF, которая <br/>            не обязана быть смежной с фиксированной частью записи EmfMetafileHeader <br/>            record. Соответственно, поле в этом буфере с меткой "UndefinedSpace" <br/>            является необязательным и MUST быть игнорировано. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Получает или задает объект Header (раздел 2.2.9), который содержит информацию о содержимом<br/>            и структуре метафайла |
| emf_header_record_buffer | System.Byte | r/w | Получает или задает необязательный массив байтов, содержащий оставшуюся часть записи заголовка EMF. <br/>            Размер этого поля MUST быть кратным 4 байтам |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | Инициализирует новый экземпляр класса [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_record(record)](#create_from_record_record_2) | Инициализирует новый экземпляр класса [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_type(type)](#create_from_type_type_3) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMetafileHeader() {#EmfMetafileHeader__1}


```
 EmfMetafileHeader() 
```

Инициализирует новый экземпляр класса [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

### Constructor: EmfMetafileHeader(header) {#EmfMetafileHeader_header_2}


```
 EmfMetafileHeader(header) 
```

Инициализирует новый экземпляр класса [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | Заголовок. |

### Constructor: EmfMetafileHeader(record) {#EmfMetafileHeader_record_3}


```
 EmfMetafileHeader(record) 
```

Инициализирует новый экземпляр класса [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Запись. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

Инициализирует новый экземпляр класса [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | Заголовок. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_2}


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


### Method: create_from_type(type)  [static] {#create_from_type_type_3}


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


