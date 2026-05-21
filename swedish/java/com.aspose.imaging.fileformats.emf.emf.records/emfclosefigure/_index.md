---
title: "EmfCloseFigure"
second_title: "Aspose.Imaging för Java API-referens"
description: "Denna post stänger en öppen figur i en sökväg."
type: docs
weight: 22
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfCloseFigure extends EmfPathBracketRecordType
```

Denna post stänger en öppen figur i en bana. Bearbetning av EMR\_CLOSEFIGURE‑posten MÅSTE stänga figuren genom att rita en linje från den aktuella positionen till figurens första punkt, och sedan MÅSTE den ansluta linjerna genom att använda linjesammanbindningsstilen. Om en figur stängs genom att bearbeta EMR\_LINETO‑posten istället för EMR\_CLOSEFIGURE‑posten, används ändkaps för att skapa hörnet istället för en sammanbindning. EMR\_LINETO specificeras i avsnitt 2.3.5.13. EMR\_CLOSEFIGURE‑posten BÖR endast användas om det finns en öppen banaklammer i uppspelningsenhetens kontext. En figur i en bana är öppen om den inte uttryckligen stängs genom att bearbeta denna post.

Obs: En figur kan vara öppen även om den aktuella punkten och figurens startpunkt är samma. Efter bearbetning av EMR\_CLOSEFIGURE‑posten MÅSTE tillägg av en linje eller kurva till banan starta en ny figur.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCloseFigure()](#EmfCloseFigure--) | Initierar en ny instans av klassen `EmfCloseFigure`. |
### EmfCloseFigure() {#EmfCloseFigure--}
```
public EmfCloseFigure()
```


Initierar en ny instans av klassen `EmfCloseFigure`.

