---
title: EmfCommentEmfPlus
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der Datensatz EMR_COMMENT_EMFPLUS enthält eingebettete EMF-Datensätze. Hinweis Felder die in diesem Abschnitt nicht beschrieben sind werden in Abschnitt 2.3.3. spezifiziert.
type: docs
weight: 3360
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
## EmfCommentEmfPlus class

Der Datensatz EMR_COMMENT_EMFPLUS enthält eingebettete EMF+-Datensätze. Hinweis Felder, die in diesem Abschnitt nicht beschrieben sind, werden in Abschnitt 2.3.3. spezifiziert.

```csharp
public sealed class EmfCommentEmfPlus : EmfCommentRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfCommentEmfPlus](emfcommentemfplus)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfCommentEmfPlus`](../emfcommentemfplus) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/commentidentifier) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die diesen Kommentardatensatz als EMF+-Datensätze enthaltend identifiziert. Der Wert 0x2B464D45, bei dem es sich um die ASCII-Zeichenfolge „+FME“, handelt, identifiziert dies als EMR_COMMENT_EMFPLUS-Datensatz. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Größe der Felder CommentIdentifier und CommentRecordParm in Byte im Feld RecordBuffer angibt, auf das folgt. Es DARF NICHT die Größe von sich selbst oder die Größe des AlignmentPadding-Felds enthalten, wenn vorhanden |
| [EmfPlusRecords](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/emfplusrecords) { get; set; } | Ruft ein Byte-Array ab oder legt es fest, das einen oder mehrere EMF+-Datensätze enthält ([MS-EMFPLUS] Abschnitt 2.3.1). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |

### Siehe auch

* class [EmfCommentRecordType](../emfcommentrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
