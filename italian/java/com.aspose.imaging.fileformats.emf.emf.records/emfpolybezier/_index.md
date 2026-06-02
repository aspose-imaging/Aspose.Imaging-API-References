---
title: "EmfPolyBezier"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_POLYBEZIER specifica una o più curve di Bézier."
type: docs
weight: 85
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezier extends EmfPolyShape
```

Il record EMR\_POLYBEZIER specifica una o più curve di Bézier.

Le curve di Bézier cubiche sono definite utilizzando i punti finali e i punti di controllo specificati dal campo aPoints. La prima curva è tracciata dal primo punto al quarto punto, usando il secondo e il terzo punto come punti di controllo. Ogni curva successiva nella sequenza richiede esattamente tre punti aggiuntivi: il punto finale della curva precedente è usato come punto di partenza, i due punti successivi nella sequenza sono punti di controllo, e il terzo è il punto finale. Le curve di Bézier cubiche DOVREBBERO essere disegnate usando la penna corrente
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPolyBezier(EmfRecord source)](#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfPolyBezier`. |
| [EmfPolyBezier()](#EmfPolyBezier--) | Inizializza una nuova istanza della classe `EmfPolyBezier`. |
### EmfPolyBezier(EmfRecord source) {#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezier(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfPolyBezier`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfPolyBezier() {#EmfPolyBezier--}
```
public EmfPolyBezier()
```


Inizializza una nuova istanza della classe `EmfPolyBezier`.

