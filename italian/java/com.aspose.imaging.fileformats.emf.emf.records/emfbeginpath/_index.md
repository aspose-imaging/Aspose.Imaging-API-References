---
title: "EmfBeginPath"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Questo record apre una parentesi di percorso nel contesto del dispositivo di riproduzione corrente."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfBeginPath extends EmfPathBracketRecordType
```

Questo record apre una parentesi di percorso nel contesto del dispositivo di riproduzione corrente. Dopo che una parentesi di percorso è aperta, un'applicazione può iniziare a elaborare i record per definire i punti che si trovano nel percorso. Un'applicazione DEVE chiudere una parentesi di percorso aperta elaborando il record EMR\_ENDPATH. Quando un'applicazione elabora il record EMR\_BEGINPATH, tutti i percorsi precedenti DEVONO essere scartati dal contesto del dispositivo di riproduzione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfBeginPath()](#EmfBeginPath--) | Inizializza una nuova istanza della classe `EmfBeginPath`. |
### EmfBeginPath() {#EmfBeginPath--}
```
public EmfBeginPath()
```


Inizializza una nuova istanza della classe `EmfBeginPath`.

