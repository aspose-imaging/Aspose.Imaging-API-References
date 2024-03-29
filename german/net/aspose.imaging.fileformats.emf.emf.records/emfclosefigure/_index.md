---
title: EmfCloseFigure
second_title: Aspose.Imaging für .NET-API-Referenz
description: Dieser Datensatz schließt eine offene Figur in einem Pfad. Die Verarbeitung des EMR_CLOSEFIGURE-Datensatzes MUSS die Figur schließen indem eine Linie von der aktuellen Position zum ersten Punkt der Figur gezogen wird und dann MUSS er die Linien mit verbinden indem er den Linienverbindungsstil verwendet. Wenn eine Figur geschlossen wird indem der EMR_LINETO-Datensatz anstelle des EMR_CLOSEFIGURE-Datensatzes verarbeitet wird werden Endkappen verwendet um die Ecke anstelle einer Verbindung zu erstellen. EMR_LINETO ist in Abschnitt 2.3.5.13. angegeben open path Klammer im Kontext des Wiedergabegeräts. Eine Figur in einem Pfad ist offen es sei denn sie wird durch die Verarbeitung dieses Datensatzes explizit geschlossen.
type: docs
weight: 3310
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
## EmfCloseFigure class

Dieser Datensatz schließt eine offene Figur in einem Pfad. Die Verarbeitung des EMR_CLOSEFIGURE-Datensatzes MUSS die Figur schließen, indem eine Linie von der aktuellen Position zum ersten Punkt der Figur gezogen wird, und dann MUSS er die Linien mit verbinden, indem er den Linienverbindungsstil verwendet. Wenn eine Figur geschlossen wird, indem der EMR_LINETO-Datensatz anstelle des EMR_CLOSEFIGURE-Datensatzes verarbeitet wird, werden Endkappen verwendet, um die Ecke anstelle einer Verbindung zu erstellen. EMR_LINETO ist in Abschnitt 2.3.5.13. angegeben open path Klammer im Kontext des Wiedergabegeräts. Eine Figur in einem Pfad ist offen, es sei denn, sie wird durch die Verarbeitung dieses Datensatzes explizit geschlossen.

```csharp
public sealed class EmfCloseFigure : EmfPathBracketRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfCloseFigure](emfclosefigure)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |

### Bemerkungen

Hinweis: Eine Figur kann auch dann offen sein, wenn der aktuelle Punkt und der Startpunkt der Figur identisch sind. Nach der Verarbeitung des EMR_CLOSEFIGURE-Datensatzes MUSS das Hinzufügen einer Linie oder Kurve zum Pfad eine neue Figur beginnen.

### Siehe auch

* class [EmfPathBracketRecordType](../emfpathbracketrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
