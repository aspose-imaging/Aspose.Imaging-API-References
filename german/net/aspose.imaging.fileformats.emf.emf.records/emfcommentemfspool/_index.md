---
title: EmfCommentEmfSpool
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der Datensatz EMR_COMMENT_EMFSPOOL enthält eingebettete EMFSPOOL-Datensätze. Hinweis Felder die in diesem Abschnitt nicht beschrieben sind werden in Abschnitt 2.3.3. spezifiziert.
type: docs
weight: 3370
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
## EmfCommentEmfSpool class

Der Datensatz EMR_COMMENT_EMFSPOOL enthält eingebettete EMFSPOOL-Datensätze. Hinweis Felder, die in diesem Abschnitt nicht beschrieben sind, werden in Abschnitt 2.3.3. spezifiziert.

```csharp
public sealed class EmfCommentEmfSpool : EmfCommentRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfCommentEmfSpool](emfcommentemfspool#constructor)() | Initialisiert eine neue Instanz von[`EmfCommentEmfSpool`](../emfcommentemfspool) Klasse. |
| [EmfCommentEmfSpool](emfcommentemfspool#constructor_1)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfCommentEmfSpool`](../emfcommentemfspool) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/commentidentifier) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die diesen Kommentardatensatz als EMFSPOOL-Datensätze enthaltend identifiziert. Der Wert 0x00000000 identifiziert dies als einen EMR_COMMENT_EMFSPOOL-Datensatz. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Größe der Felder CommentIdentifier und CommentRecordParm in Byte im Feld RecordBuffer angibt, auf das folgt. Es DARF NICHT die Größe von sich selbst oder die Größe des AlignmentPadding-Felds enthalten, wenn vorhanden |
| [EmfSpoolRecordIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/emfspoolrecordidentifier) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die den Typ des EMR_COMMENT_EMFSPOOL-Datensatzes identifiziert. |
| [EmfSpoolRecords](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/emfspoolrecords) { get; set; } | Ruft ein Byte-Array variabler Länge ab oder legt es fest, das einen oder mehrere EMFSPOOL-Schriftdefinitionsdatensätze enthält ([MS-EMFSPOOL] Abschnitt 2.2.3.3). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |

### Siehe auch

* class [EmfCommentRecordType](../emfcommentrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->