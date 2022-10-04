---
title: EmfCommentMultiFormats
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der Datensatz EMR_COMMENT_MULTIFORMATS gibt ein Bild in mehreren Grafikformaten an.
type: docs
weight: 3400
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
## EmfCommentMultiFormats class

Der Datensatz EMR_COMMENT_MULTIFORMATS gibt ein Bild in mehreren Grafikformaten an.

```csharp
public sealed class EmfCommentMultiFormats : EmfCommentPublicRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfCommentMultiFormats](emfcommentmultiformats)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfCommentMultiFormats`](../emfcommentmultiformats) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AFormats](../../aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/aformats) { get; set; } | Ruft ein CountFormats-Längen-Array von Grafikformaten ab oder legt sie fest, die von EmrFormat-Objekten (Abschnitt 2.2.4) in der Reihenfolge ihrer Präferenz angegeben werden |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die diesen Kommentardatensatz als Angabe öffentlicher Daten identifiziert. Der Wert 0x43494447, bei dem es sich um die ASCII-Zeichenfolge „CIDG“ handelt, identifiziert dies als einen EMR_COMMENT_PUBLIC-Datensatz. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Größe der Felder CommentIdentifier und CommentRecordParm in Byte im Feld RecordBuffer angibt, auf das folgt. Es DARF NICHT die Größe von sich selbst oder die Größe des AlignmentPadding-Felds enthalten, wenn vorhanden |
| [FormatData](../../aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/formatdata) { get; set; } | Holt oder setzt ein Array variabler Länge von Bilddaten in Bytes für alle Grafikformate , die in diesem Datensatz enthalten sind. Die Größe der Daten für jedes Bild wird vom DataSize-Feld im entsprechenden -EmrFormat-Objekt bereitgestellt. Daher ist die Gesamtgröße dieses Felds die Summe der DataSize-Werte in allen -EmrFormat-Objekten. Das Grafikformat der Daten für jedes Bild wird durch das Signaturfeld im entsprechenden EmrFormat-Objekt angegeben. |
| [OutputRect](../../aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/outputrect) { get; set; } | Ruft ein WMF-RectL-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.19), das das -Ausgaberechteck in logischen Koordinaten angibt. |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die den Typ des öffentlichen Kommentardatensatzes identifiziert. Dies SOLLTE einer der in der vorhergehenden Tabelle aufgeführten Werte sein, die in der EmrComment-Enumeration (Abschnitt 2.1.10) angegeben sind, es sei denn, auf dem Druckserver wurden zusätzliche öffentliche -Kommentardatensatztypen implementiert. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |

### Siehe auch

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->