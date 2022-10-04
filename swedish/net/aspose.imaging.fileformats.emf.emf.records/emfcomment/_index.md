---
title: EmfComment
second_title: Aspose.Imaging för .NET API-referens
description: EMR_COMMENT-posten innehåller godtyckliga privata data. Obs Fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.3.
type: docs
weight: 3340
url: /sv/net/aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
## EmfComment class

EMR_COMMENT-posten innehåller godtyckliga privata data. Obs Fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.3.

```csharp
public sealed class EmfComment : EmfCommentRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfComment](emfcomment)(EmfRecord) | Initierar en ny instans av[`EmfComment`](../emfcomment) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcomment/commentidentifier) { get; set; } | Hämtar eller ställer in kommentarsidentifieraren. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger storleken, i byte, på fälten CommentIdentifier och CommentRecordParm i fältet RecordBuffer som följer. Den FÅR INTE inkludera storleken på sig själv eller storleken på AlignmentPadding-fältet, om present |
| [PrivateData](../../aspose.imaging.fileformats.emf.emf.records/emfcomment/privatedata) { get; set; } | Hämtar eller ställer in en valfri array av byte som specificerar privata data. Den första DWORD av denna data FÅR INTE vara ett av de fördefinierade kommentarsidentifieringsvärdena som anges i avsnitt 2.3.3. Privata data är okända för EMF; det är endast meningsfullt för applikationer som känner till formatet för -data och hur de ska användas. EMR_COMMENT privata dataposter KAN ignoreras. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |

### Se även

* class [EmfCommentRecordType](../emfcommentrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->