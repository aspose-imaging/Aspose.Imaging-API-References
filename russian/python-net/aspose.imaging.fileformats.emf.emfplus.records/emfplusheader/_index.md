---
title: "Класс EmfPlusHeader"
type: docs
weight: 310
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---

**Summary:** The EmfPlusHeader record specifies the start of EMF+ data in the metafile.<br/>            The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record,<br/>             which MUST be the record immediately following the EMF header in the metafile. <br/>            The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusHeader

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusHeader(source)](#EmfPlusHeader_source_1) | Инициализирует новый экземпляр класса [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| dual_mode | bool | r/w | Получает или задает значение, указывающее, включён ли [dual mode].<br/>            Если установлено, этот флаг указывает, что данный метафайл является "dual-mode", что означает<br/>            что он содержит два набора записей, каждый из которых полностью определяет <br/>            графическое содержимое. Если флаг сброшен, графическое содержимое задаётся записями EMF+ <br/>            и, возможно, записями EMF, предшествующими записи EmfPlusGetDC. <br/>            Если этот флаг установлен, записи EMF сами по себе SHOULD быть достаточными для определения <br/>            графического содержимого. Обратите внимание, что независимо от того, установлен ли флаг "dual-mode", некоторые <br/>            записи EMF всегда присутствуют, а именно управляющие записи EMF и записи EMF, <br/>            содержащие записи EMF+. Управляющие записи EMF указаны в [MS-EMF] <br/>            раздел 2.3.4. |
| emf_plus_flags | int | r/w | Получает или задает флаги EMF plus.<br/>            32-битное беззнаковое целое, содержащее информацию о том, как был записан этот метафайл.<br/>            если 31‑й бит поля установлен, этот флаг указывает, что метафайл был записан с <br/>            контекстом устройства ссылки для видеодисплея. Если флаг сброшен, метафайл был записан с<br/>            контекстом устройства ссылки для принтера. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| is_valid | bool | r | Получает значение, указывающее, является ли этот экземпляр действительным. |
| logical_dpi_x | int | r/w | Получает или задает логическое dpi x.<br/>            32-битное беззнаковое целое, указывающее горизонтальное разрешение, для которого был записан метафайл <br/>            в единицах пикселей на дюйм. |
| logical_dpi_y | int | r/w | Получает или задает логическое dpi y.<br/>            32-битное беззнаковое целое, указывающее вертикальное разрешение, для которого был записан метафайл <br/>            в единицах строк на дюйм. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Получает или задает версию.<br/>            Объект EmfPlusGraphicsVersion (раздел 2.2.2.19), который указывает версию графики операционной<br/>            системы, использованной для создания этого метафайла. |
| video_display | bool | r/w | Получает или задает значение, указывающее, относится ли к видеодисплею.<br/>            если установлен, этот флаг указывает, что метафайл был записан с контекстом устройства ссылки для видеодисплея. Если сброшен, метафайл был записан с контекстом устройства ссылки для принтера. |


### Constructor: EmfPlusHeader(source) {#EmfPlusHeader_source_1}


```
 EmfPlusHeader(source) 
```

Инициализирует новый экземпляр класса [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

