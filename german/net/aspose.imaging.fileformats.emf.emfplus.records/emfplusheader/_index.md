---
title: EmfPlusHeader
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EmfPlusHeader-Datensatz gibt den Beginn der EMF-Daten in der Metadatei an. Der EmfPlusHeader-Datensatz MUSS in einen EMF EMR_COMMENT_EMFPLUS-Datensatz eingebettet werden  der der Datensatz sein MUSS der unmittelbar auf den EMF-Header in der Metadatei folgt. Der EMR_COMMENT_EMFPLUS-Datensatz ist in MS-EMF Abschnitt 2.3.3.2 angegeben.
type: docs
weight: 6140
url: /de/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
## EmfPlusHeader class

Der EmfPlusHeader-Datensatz gibt den Beginn der EMF+-Daten in der Metadatei an. Der EmfPlusHeader-Datensatz MUSS in einen EMF EMR_COMMENT_EMFPLUS-Datensatz eingebettet werden, , der der Datensatz sein MUSS, der unmittelbar auf den EMF-Header in der Metadatei folgt. Der EMR_COMMENT_EMFPLUS-Datensatz ist in [MS-EMF] Abschnitt 2.3.3.2 angegeben.

```csharp
public sealed class EmfPlusHeader : EmfPlusControlRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusHeader](emfplusheader)(EmfPlusRecord) | Initialisiert eine neue Instanz von[`EmfPlusHeader`](../emfplusheader) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes von Daten im folgenden RecordData-Feld definieren MUSS. Diese Nummer enthält nicht den 12-Byte-Datensatzheader. |
| [DualMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob [Dual-Modus]. Wenn gesetzt, zeigt dieses Flag an, dass diese Metadatei "Dual-Modus" ist, was bedeutet, dass sie zwei Sätze von Datensätzen enthält, von denen jeder vollständig den Grafikinhalt spezifiziert. Wenn klar, wird der Grafikinhalt durch EMF+ -Datensätze und möglicherweise EMF-Datensätze, denen ein EmfPlusGetDC-Datensatz vorangeht, angegeben. Wenn dieses Flag gesetzt ist, MÜSSEN EMF-Datensätze allein ausreichen, um den -Grafikinhalt zu definieren. Beachten Sie, dass unabhängig davon, ob das "Dual-Mode"-Flag gesetzt ist oder nicht, einige EMF-Datensätze immer vorhanden sind, nämlich EMF-Steuerdatensätze und die EMF-Datensätze , die EMF+-Datensätze enthalten. EMF-Kontrolldatensätze sind in [MS-EMF] Abschnitt 2.3.4. angegeben. |
| [EmfPlusFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/emfplusflags) { get; set; } | Ruft die EMF-Plus-Flags ab oder setzt sie. Eine 32-Bit-Ganzzahl ohne Vorzeichen, die Informationen darüber enthält, wie diese Metadatei aufgezeichnet wurde. Wenn das 31. Bit des Felds gesetzt ist, zeigt diese Flagge an, dass die Metadatei mit einer Referenz aufgezeichnet wurde Gerätekontext für eine Videoanzeige. Wenn klar, wurde die Metadatei mit einem Referenzgerätekontext für einen Drucker aufgezeichnet. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die für einige Datensätze Informationen darüber enthält, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. |
| [IsValid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/isvalid) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz gültig ist. |
| [LogicalDpiX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpix) { get; set; } | Ruft die logische Auflösung x ab oder legt sie fest. Eine 32-Bit-Ganzzahl ohne Vorzeichen, die die horizontale Auflösung angibt, für die die Metadatei aufgezeichnet wurde, in Einheiten von Pixel pro Zoll. |
| [LogicalDpiY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpiy) { get; set; } | Ruft den logischen Wert für dpi y ab oder legt ihn fest. Eine 32-Bit-Ganzzahl ohne Vorzeichen, die die vertikale Auflösung angibt, für die die Metadatei aufgezeichnet wurde, in Einheiten von Zeilen pro Zoll |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12-Byte-Datensatzheaders und datensatzspezifischer Daten. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab, die den Datensatztyp identifiziert. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/version) { get; set; } | Ruft die Version ab oder legt sie fest. Ein EmfPlusGraphicsVersion-Objekt (Abschnitt 2.2.2.19), das die Version der Operating -Systemgrafik angibt, die zum Erstellen dieser Metadatei verwendet wurde. |
| [VideoDisplay](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/videodisplay) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob ein Video angezeigt wird. Wenn es gesetzt ist, zeigt dieses Flag an, dass die Metadatei mit einem Referenzgerät -Kontext für eine Videoanzeige aufgezeichnet wurde. Wenn klar, wurde die Metadatei mit einem Referenzgerät -Kontext für einen Drucker aufgezeichnet. |

### Siehe auch

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
