---
title: EmfCommentEmfPlus
second_title: Aspose.Imaging för .NET API-referens
description: EMR_COMMENT_EMFPLUS-posten innehåller inbäddade EMF-poster. Obs Fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.3.
type: docs
weight: 3360
url: /sv/net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
## EmfCommentEmfPlus class

EMR_COMMENT_EMFPLUS-posten innehåller inbäddade EMF+-poster. Obs Fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.3.

```csharp
public sealed class EmfCommentEmfPlus : EmfCommentRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfCommentEmfPlus](emfcommentemfplus)(EmfRecord) | Initierar en ny instans av[`EmfCommentEmfPlus`](../emfcommentemfplus) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/commentidentifier) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som identifierar denna kommentarpost som innehållande EMF+-poster. Värdet 0x2B464D45, som är ASCII-strängen "+FME", identifierar detta som en EMR_COMMENT_EMFPLUS-post. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger storleken, i byte, på fälten CommentIdentifier och CommentRecordParm i fältet RecordBuffer som följer. Den FÅR INTE inkludera storleken på sig själv eller storleken på AlignmentPadding-fältet, om present |
| [EmfPlusRecords](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/emfplusrecords) { get; set; } | Hämtar eller ställer in en array av byte som innehåller en eller flera EMF+-poster ([MS-EMFPLUS] avsnitt 2.3.1). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |

### Se även

* class [EmfCommentRecordType](../emfcommentrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->