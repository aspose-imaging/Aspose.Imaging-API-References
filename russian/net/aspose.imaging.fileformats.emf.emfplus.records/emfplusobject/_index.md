---
title: EmfPlusObject
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusObject определяет объект для использования в графических операциях. Определение объекта может охватывать несколько записей на что указывает значение поля Flags.
type: docs
weight: 6160
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
## EmfPlusObject class

Запись EmfPlusObject определяет объект для использования в графических операциях. Определение объекта может охватывать несколько записей, на что указывает значение поля Flags.

```csharp
public sealed class EmfPlusObject : EmfPlusObjectRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusObject](emfplusobject)(EmfPlusRecord) | Инициализирует новый экземпляр класса[`EmfPlusObject`](../emfplusobject). |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное число байтов данных в поле RecordData, которое следует. Это число не включает 12-байтовый заголовок записи. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция , и о структуре запись. |
| [IsContinuable](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/iscontinuable) { get; set; } | Получает или задает значение, указывающее, можно ли продолжить этот экземпляр. Указывает, что определение объекта продолжается в следующей записи EmfPlusObject . Этот флаг никогда не устанавливается в окончательной записи, определяющей объект. |
| [ObjectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objectdata) { get; set; } | Получает или задает массив байтов, содержащий данные для типа объекта, указанного в поле Флаги. Содержание и формат данных могут различаться для каждого типа объекта. См. определения отдельных объектов в разделе 2.2.1 для получения дополнительной информации. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objectid) { get; set; } | Получает или задает идентификатор объекта. Индекс в таблице объектов EMF+ для связи с объектом , созданным этой записью. Значение ДОЛЖНО быть от нуля до 63 включительно. |
| [ObjectType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objecttype) { get; set; } | Получает или задает тип объекта. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее число байтов, выровненных по 32-разрядному выравниванию во всей записи, включая 12 -байтовый заголовок записи и данные, относящиеся к записи. |
| [TotalObjectSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/totalobjectsize) { get; set; } | Получает или задает общий размер объекта. Если запись может быть продолжена, когда бит продолжения установлен, это поле будет присутствовать. Продолжающиеся объекты имеют несколько записей EMF+, начинающихся с EmfPlusContineudObjectRecord. Каждый EmfPlusContinuedObjectRecord будет содержать TotalObjectSize. Как только TotalObjectSize считывает количество байтов, следующая запись EMF+ не будет рассматриваться как часть продолжающегося объекта. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |

### Примечания

Запись EmfPlusObject является общей; используется для всех типов объектов. Значения, характерные для конкретных типов объектов, содержатся в поле ObjectData. Концептуальная модель для управления графическими объектами описана в разделе Управление графическими объектами (раздел 3.1.2).

### Смотрите также

* class [EmfPlusObjectRecordType](../emfplusobjectrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
