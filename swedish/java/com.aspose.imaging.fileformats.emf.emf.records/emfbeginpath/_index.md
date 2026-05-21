---
title: "EmfBeginPath"
second_title: "Aspose.Imaging för Java API-referens"
description: "Denna post öppnar en sökvägsparentes i den aktuella uppspelningsenhetens kontext."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfBeginPath extends EmfPathBracketRecordType
```

Denna post öppnar en sökvägsparentes i den aktuella uppspelningsenhetskontexten. När en sökvägsparentes är öppen kan ett program börja bearbeta poster för att definiera de punkter som ligger i sökvägen. Ett program MÅSTE stänga en öppen sökvägsparentes genom att bearbeta EMR\_ENDPATH‑posten. När ett program bearbetar EMR\_BEGINPATH‑posten MÅSTE alla tidigare sökvägar kasseras från uppspelningsenhetskontexten.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfBeginPath()](#EmfBeginPath--) | Initierar en ny instans av klassen `EmfBeginPath`. |
### EmfBeginPath() {#EmfBeginPath--}
```
public EmfBeginPath()
```


Initierar en ny instans av klassen `EmfBeginPath`.

