---
title: "EmfCloseFigure"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Questo record chiude una figura aperta in un percorso."
type: docs
weight: 22
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfCloseFigure extends EmfPathBracketRecordType
```

Questo record chiude una figura aperta in un percorso. L'elaborazione del record EMR\_CLOSEFIGURE DEVE chiudere la figura disegnando una linea dalla posizione corrente al primo punto della figura, e poi DEVE collegare le linee usando lo stile di giunzione delle linee. Se una figura viene chiusa elaborando il record EMR\_LINETO invece del record EMR\_CLOSEFIGURE, vengono usati i cappucci finali per creare l'angolo invece di una giunzione. EMR\_LINETO è specificato nella sezione 2.3.5.13. Il record EMR\_CLOSEFIGURE DOVREBBE essere usato solo se esiste una parentesi di percorso aperta nel contesto del dispositivo di riproduzione. Una figura in un percorso è aperta a meno che non sia esplicitamente chiusa elaborando questo record.

Nota: una figura può essere aperta anche se il punto corrente e il punto di partenza della figura sono gli stessi. Dopo l'elaborazione del record EMR\_CLOSEFIGURE, l'aggiunta di una linea o di una curva al percorso DEVE avviare una nuova figura.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCloseFigure()](#EmfCloseFigure--) | Inizializza una nuova istanza della classe `EmfCloseFigure`. |
### EmfCloseFigure() {#EmfCloseFigure--}
```
public EmfCloseFigure()
```


Inizializza una nuova istanza della classe `EmfCloseFigure`.

