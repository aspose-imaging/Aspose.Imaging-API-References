---
title: EmfPlusHeader
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusHeader указывает начало данных EMF в метафайле. Запись EmfPlusHeader ДОЛЖНА быть встроена в запись EMF EMR_COMMENT_EMFPLUS  которая ДОЛЖНА быть записью следующей за заголовком EMF в метафайле. Запись EMR_COMMENT_EMFPLUS указана в разделе MS-EMF 2.3.3.2.
type: docs
weight: 6140
url: /ru/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
## EmfPlusHeader class

Запись EmfPlusHeader указывает начало данных EMF+ в метафайле. Запись EmfPlusHeader ДОЛЖНА быть встроена в запись EMF EMR_COMMENT_EMFPLUS, , которая ДОЛЖНА быть записью, следующей за заголовком EMF в метафайле. Запись EMR_COMMENT_EMFPLUS указана в разделе [MS-EMF] 2.3.3.2.

```csharp
public sealed class EmfPlusHeader : EmfPlusControlRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusHeader](emfplusheader)(EmfPlusRecord) | Инициализирует новый экземпляр[`EmfPlusHeader`](../emfplusheader) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное количество байтов данных в следующем поле RecordData. Это число не включает 12-байтовый заголовок записи. |
| [DualMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode) { get; set; } | Получает или задает значение, указывающее, является ли [двойной режим]. Если установлен, этот флаг указывает, что этот метафайл является "двойным режимом", что означает, , что он содержит два набора записей, каждый из которых полностью определяет графическое содержимое. Если этот флажок установлен, графическое содержимое определяется записями EMF+ и, возможно, записями EMF, которым предшествует запись EmfPlusGetDC. Если этот флаг установлен, одних записей EMF ДОЛЖНО быть достаточно для определения графического содержимого . Обратите внимание, что независимо от того, установлен флаг «двойной режим» или нет, некоторые записи EMF всегда присутствуют, а именно контрольные записи EMF и записи EMF , которые содержат записи EMF+. Записи управления EMF указаны в [MS-EMF] , раздел 2.3.4. . |
| [EmfPlusFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/emfplusflags) { get; set; } | Получает или устанавливает флаги EMF plus. 32-битное целое число без знака, содержащее информацию о том, как этот метафайл был записан. контекст устройства для отображения видео. Если флажок снят, метафайл был записан с контекстом эталонного устройства для принтера. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция, и о структуре записи. |
| [IsValid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/isvalid) { get; } | Получает значение, указывающее, является ли этот экземпляр допустимым. |
| [LogicalDpiX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpix) { get; set; } | Получает или задает логическое значение dpi x. 32-разрядное целое число без знака, указывающее горизонтальное разрешение, для которого был записан метафайл , в единицах пикселей на дюйм. |
| [LogicalDpiY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpiy) { get; set; } | Получает или задает логическое значение dpi. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее 32-разрядное выровненное количество байтов во всей записи, включая 12-разрядный заголовок записи и данные, относящиеся к записи. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/version) { get; set; } | Получает или задает версию. Объект EmfPlusGraphicsVersion (раздел 2.2.2.19), указывающий версию операционной системной графики, которая использовалась для создания этого метафайла. |
| [VideoDisplay](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/videodisplay) { get; set; } | Получает или задает значение, указывающее, отображается ли видео. Если установлено, этот флаг указывает, что метафайл был записан с эталонным контекстом device для отображения видео. Если этот параметр не установлен, метафайл был записан с эталонным контекстом device для принтера. |

### Смотрите также

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
