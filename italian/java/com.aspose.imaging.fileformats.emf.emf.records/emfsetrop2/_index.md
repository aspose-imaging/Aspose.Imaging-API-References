---
title: "EmfSetRop2"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETROP2 definisce una modalità di operazione raster binaria."
type: docs
weight: 137
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetRop2 extends EmfStateRecordType
```

Il record EMR\_SETROP2 definisce una modalità di operazione raster binaria.

Le modalità di miscelazione delle operazioni raster binarie definiscono come combinare i colori di sorgente e destinazione durante il disegno con la penna corrente. Le modalità di miscelazione sono codici di operazione raster binari, che rappresentano tutte le possibili funzioni booleane di due variabili, utilizzando le operazioni binarie AND, OR e XOR (OR esclusivo), e l'operazione unaria NOT. La modalità di miscelazione è valida solo per dispositivi raster; non è disponibile per dispositivi vettoriali.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetRop2(EmfRecord source)](#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetRop2`. |
| [EmfSetRop2()](#EmfSetRop2--) | Inizializza una nuova istanza della classe `EmfSetRop2`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRop2Mode()](#getRop2Mode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di operazione raster e DEVE appartenere all'enumerazione WMF Binary Raster Op ([MS-WMF] sezione 2.1.1.2). |
| [setRop2Mode(int value)](#setRop2Mode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di operazione raster e DEVE appartenere all'enumerazione WMF Binary Raster Op ([MS-WMF] sezione 2.1.1.2). |
### EmfSetRop2(EmfRecord source) {#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetRop2(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetRop2`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfSetRop2() {#EmfSetRop2--}
```
public EmfSetRop2()
```


Inizializza una nuova istanza della classe `EmfSetRop2`.

### getRop2Mode() {#getRop2Mode--}
```
public int getRop2Mode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di operazione raster e DEVE appartenere all'enumerazione WMF Binary Raster Op ([MS-WMF] sezione 2.1.1.2).

**Returns:**
int
### setRop2Mode(int value) {#setRop2Mode-int-}
```
public void setRop2Mode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di operazione raster e DEVE appartenere all'enumerazione WMF Binary Raster Op ([MS-WMF] sezione 2.1.1.2).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

