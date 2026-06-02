---
title: "EmfBeginPath"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Dieser Datensatz öffnet eine Pfadklammer im aktuellen Wiedergabegeräte-Kontext."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfBeginPath extends EmfPathBracketRecordType
```

Dieser Datensatz öffnet eine Pfadklammer im aktuellen Wiedergabegeräte‑Kontext. Nachdem eine Pfadklammer geöffnet ist, kann eine Anwendung mit der Verarbeitung von Datensätzen beginnen, um die Punkte zu definieren, die im Pfad liegen. Eine Anwendung MUSS eine offene Pfadklammer schließen, indem sie den EMR\_ENDPATH‑Datensatz verarbeitet. Wenn eine Anwendung den EMR\_BEGINPATH‑Datensatz verarbeitet, MUSS jeder vorherige Pfad aus dem Wiedergabegeräte‑Kontext verworfen werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfBeginPath()](#EmfBeginPath--) | Initialisiert eine neue Instanz der `EmfBeginPath`‑Klasse. |
### EmfBeginPath() {#EmfBeginPath--}
```
public EmfBeginPath()
```


Initialisiert eine neue Instanz der `EmfBeginPath`‑Klasse.

