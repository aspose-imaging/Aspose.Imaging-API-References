---
title: EmfCommentEndGroup
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_COMMENT_ENDGROUP указывает конец группы записей чертежей.
type: docs
weight: 3390
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfcommentendgroup/
---
## EmfCommentEndGroup class

Запись EMR_COMMENT_ENDGROUP указывает конец группы записей чертежей.

```csharp
public sealed class EmfCommentEndGroup : EmfCommentPublicRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfCommentEndGroup](emfcommentendgroup)(EmfRecord) | Инициализирует новый экземпляр класса[`EmfCommentEndGroup`](../emfcommentendgroup). |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое идентифицирует эту запись комментария как определяющую общедоступные данные. Значение 0x43494447, представляющее собой строку ASCII "CIDG", идентифицирует это как запись EMR_COMMENT_PUBLIC. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее размер (в байтах) полей CommentIdentifier и CommentRecordParm в поле RecordBuffer, следует. Он НЕ ДОЛЖЕН включать размер самого себя или размер поля AlignmentPadding, если присутствует |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier) { get; set; } | Получает или задает 32-разрядное целое число без знака, определяющее тип записи открытого комментария . Это ДОЛЖНО быть одним из значений, перечисленных в предыдущей таблице, которые указаны в перечислении EmrComment (раздел 2.1.10), если не были реализованы дополнительные общедоступные типы записей комментариев. на сервере печати. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или устанавливает размер записи |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |

### Смотрите также

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
