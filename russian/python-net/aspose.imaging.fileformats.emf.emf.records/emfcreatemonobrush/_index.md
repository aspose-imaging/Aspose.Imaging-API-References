---
title: "Класс EmfCreateMonoBrush"
type: docs
weight: 300
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---

**Summary:** The EMR_CREATEMONOBRUSH record defines a monochrome pattern brush for graphics operations.<br/>            The pattern is specified by a monochrome DIB.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateMonoBrush

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCreateMonoBrush(source)](#EmfCreateMonoBrush_source_1) | Инициализирует новый экземпляр класса [EmfCreateMonoBrush](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Получает или задает буфер, содержащий упакованный DIB в виде объекта WMF<br/>            DeviceIndependentBitmap ([MS-WMF] раздел 2.2.2.9). Не требуется, чтобы он был<br/>            смежным с фиксированной частью записи EMR_CREATEDIBPATTERNBRUSHPT. |
| ih_brush | int | r/w | Получает или задает 32-битное беззнаковое целое, указывающее индекс монохромного<br/>            объекта кисти узора в таблице объектов EMF (section 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы<br/>            объект можно было повторно использовать или изменить. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
| usage | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет, как интерпретировать значения в таблице цветов<br/>            в заголовке DIB. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreateMonoBrush(source) {#EmfCreateMonoBrush_source_1}


```
 EmfCreateMonoBrush(source) 
```

Инициализирует новый экземпляр класса [EmfCreateMonoBrush](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Источник. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Источник. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


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


