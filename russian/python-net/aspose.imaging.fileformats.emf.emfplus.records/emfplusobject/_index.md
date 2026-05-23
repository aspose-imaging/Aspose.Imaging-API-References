---
title: "Класс EmfPlusObject"
type: docs
weight: 330
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---

**Summary:** The EmfPlusObject record specifies an object for use in graphics operations. The object definition<br/>            can span multiple records, which is indicated by the value of the Flags field.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusObject(source)](#EmfPlusObject_source_1) | Инициализирует новый экземпляр класса [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| is_continuable | bool | r/w | Получает или задает значение, указывающее, является ли данный экземпляр продолжаемым.<br/>            Указывает, что определение объекта продолжается в следующей записи EmfPlusObject<br/>            . Этот флаг никогда не устанавливается в последней записи, определяющей объект. |
| object_data | [EmfPlusGraphicsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/) | r/w | Получает или задает массив байтов, содержащий данные для типа объекта, указанного в<br/>            поле Flags. Содержание и формат данных могут различаться для каждого типа объекта. См.<br/>            отдельные определения объектов в разделе 2.2.1 для дополнительной информации. |
| object_id | System.Byte | r/w | Получает или задает идентификатор объекта.<br/>            Индекс в таблице объектов EMF+, ассоциированный с объектом,<br/>            созданным этой записью. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| object_type | [EmfPlusObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjecttype/) | r/w | Получает или задает тип объекта. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| total_object_size | int | r/w | Получает или задает общий размер объекта.<br/>            Если запись является продолжаемой, при установленном бите continue это поле<br/>            будет присутствовать. Продолжающие объекты имеют несколько записей EMF+, начинающихся с<br/>            EmfPlusContineudObjectRecord. Каждая запись EmfPlusContinuedObjectRecord будет содержать<br/>            TotalObjectSize. После чтения количества байтов, указанного в TotalObjectSize, следующая запись EMF+<br/>            не будет рассматриваться как часть продолжающегося объекта. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusObject(source) {#EmfPlusObject_source_1}


```
 EmfPlusObject(source) 
```

Инициализирует новый экземпляр класса [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

