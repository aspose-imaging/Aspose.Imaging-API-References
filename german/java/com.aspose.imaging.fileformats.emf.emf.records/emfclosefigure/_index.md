---
title: "EmfCloseFigure"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Dieser Datensatz schließt eine offene Figur in einem Pfad."
type: docs
weight: 22
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfCloseFigure extends EmfPathBracketRecordType
```

Dieser Datensatz schließt eine offene Figur in einem Pfad. Die Verarbeitung des EMR\_CLOSEFIGURE‑Datensatzes MUSS die Figur schließen, indem eine Linie von der aktuellen Position zum ersten Punkt der Figur gezeichnet wird, und anschließend MUSS die Linie mit dem Linienverbindungsstil verbunden werden. Wenn eine Figur durch Verarbeitung des EMR\_LINETO‑Datensatzes anstelle des EMR\_CLOSEFIGURE‑Datensatzes geschlossen wird, werden Endkappen verwendet, um die Ecke zu erzeugen, anstatt einer Verbindung. EMR\_LINETO ist in Abschnitt 2.3.5.13 angegeben. Der EMR\_CLOSEFIGURE‑Datensatz SOLLTE nur verwendet werden, wenn im Wiedergabegeräte‑Kontext eine offene Pfadklammer vorhanden ist. Eine Figur in einem Pfad ist offen, sofern sie nicht ausdrücklich durch Verarbeitung dieses Datensatzes geschlossen wird.

Hinweis: Eine Figur kann offen sein, selbst wenn der aktuelle Punkt und der Startpunkt der Figur identisch sind. Nach der Verarbeitung des EMR\_CLOSEFIGURE‑Datensatzes MUSS das Hinzufügen einer Linie oder Kurve zum Pfad eine neue Figur beginnen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCloseFigure()](#EmfCloseFigure--) | Initialisiert eine neue Instanz der `EmfCloseFigure`‑Klasse. |
### EmfCloseFigure() {#EmfCloseFigure--}
```
public EmfCloseFigure()
```


Initialisiert eine neue Instanz der `EmfCloseFigure`‑Klasse.

