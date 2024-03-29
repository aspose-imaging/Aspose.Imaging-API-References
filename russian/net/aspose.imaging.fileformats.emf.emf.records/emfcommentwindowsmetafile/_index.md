---
title: EmfCommentWindowsMetaFile
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_COMMENT_WINDOWS_METAFILE указывает изображение во встроенном метафайле WMF.
type: docs
weight: 3440
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
## EmfCommentWindowsMetaFile class

Запись EMR_COMMENT_WINDOWS_METAFILE указывает изображение во встроенном метафайле WMF.

```csharp
public sealed class EmfCommentWindowsMetaFile : EmfCommentPublicRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfCommentWindowsMetaFile](emfcommentwindowsmetafile)(EmfRecord) | Инициализирует новый экземпляр[`EmfCommentWindowsMetaFile`](../emfcommentwindowsmetafile) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Checksum](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/checksum) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее контрольную сумму для этой записи. |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое идентифицирует эту запись комментария как определяющую общедоступные данные. Значение 0x43494447, которое является строкой ASCII "CIDG", идентифицирует это как запись EMR_COMMENT_PUBLIC. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее размер в байтах полей CommentIdentifier и CommentRecordParm в поле RecordBuffer, за которым следует . Он НЕ ДОЛЖЕН включать размер самого себя или размер поля AlignmentPadding, если present |
| [Flags](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/flags) { get; set; } | Получает или устанавливает 32-битное значение, которое ДОЛЖНО быть 0x00000000 и ДОЛЖНО игнорироваться. |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier) { get; set; } | Получает или задает 32-разрядное целое число без знака, определяющее тип записи общественного комментария . Это ДОЛЖНО быть одним из значений, перечисленных в предыдущей таблице, которые указаны в перечислении EmrComment (раздел 2.1.10), если на сервере печати не реализованы дополнительные общедоступные типы записей комментариев . |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или задает размер записи |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |
| [Version](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/version) { get; set; } | Получает или задает 16-разрядное целое число без знака, указывающее версию метафайла WMF в терминах поддержки аппаратно-независимых растровых изображений (DIB) из перечисления WMF MetafileVersion ([MS-WMF], раздел 2.1.1.19). |
| [WinMetafile](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/winmetafile) { get; set; } | Получает или задает буфер, содержащий метафайл WMF. |
| [WinMetafileSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/winmetafilesize) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее размер в байтах метафайла WMF в поле WinMetafile. |

### Смотрите также

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
