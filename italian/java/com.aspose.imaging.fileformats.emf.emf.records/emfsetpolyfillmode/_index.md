---
title: "EmfSetPolyFillMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETPOLYFILLMODE definisce la modalità di riempimento del poligono."
type: docs
weight: 136
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetPolyFillMode extends EmfStateRecordType
```

Il record EMR\_SETPOLYFILLMODE definisce la modalità di riempimento del poligono.

In generale, le modalità differiscono solo nei casi in cui un poligono complesso e sovrapposto DEVE essere riempito; ad esempio, un poligono a cinque lati che forma una stella a cinque punte con un pentagono al centro. In tali casi, la modalità ALTERNATE DOVREBBE riempire ogni altra regione racchiusa all'interno del poligono (i punti della stella), ma la modalità WINDING DOVREBBE riempire tutte le regioni (i punti della stella e il pentagono). Quando la modalità di riempimento è ALTERNATE, l'area tra i lati del poligono numerati dispari e pari su ogni linea di scansione DOVREBBE essere riempita. Cioè, l'area tra il primo e il secondo lato DOVREBBE essere riempita, e tra il terzo e il quarto lato, e così via. Quando la modalità di riempimento è WINDING, qualsiasi regione che ha un valore di winding non nullo DOVREBBE essere riempita. Il valore di winding è il numero di volte in cui una penna usata per disegnare il poligono attraverserebbe la regione. La direzione di ogni bordo del poligono è significativa.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetPolyFillMode(EmfRecord source)](#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetPolyFillMode`. |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode--) | Inizializza una nuova istanza della classe `EmfSetPolyFillMode`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPolygonFillMode()](#getPolygonFillMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di riempimento del poligono e DEVE essere nell'enumerazione PolygonFillMode (sezione 2.1.27). |
| [setPolygonFillMode(int value)](#setPolygonFillMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di riempimento del poligono e DEVE essere nell'enumerazione PolygonFillMode (sezione 2.1.27). |
### EmfSetPolyFillMode(EmfRecord source) {#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPolyFillMode(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetPolyFillMode`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfSetPolyFillMode() {#EmfSetPolyFillMode--}
```
public EmfSetPolyFillMode()
```


Inizializza una nuova istanza della classe `EmfSetPolyFillMode`.

### getPolygonFillMode() {#getPolygonFillMode--}
```
public int getPolygonFillMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di riempimento del poligono e DEVE essere nell'enumerazione PolygonFillMode (sezione 2.1.27).

**Returns:**
int
### setPolygonFillMode(int value) {#setPolygonFillMode-int-}
```
public void setPolygonFillMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di riempimento del poligono e DEVE essere nell'enumerazione PolygonFillMode (sezione 2.1.27).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

