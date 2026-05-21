---
title: "EmfSelectPalette"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SELECTPALETTE specifica una palette logica per il contesto del dispositivo di riproduzione."
type: docs
weight: 117
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSelectPalette extends EmfObjectManipulationRecordType
```

Il record EMR\_SELECTPALETTE specifica una tavolozza logica per il contesto di dispositivo di riproduzione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSelectPalette(EmfRecord source)](#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSelectPalette`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhPal()](#getIhPal--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto LogPalette (sezione 2.2.17) nella tabella degli oggetti EMF o il valore DEFAULT\_PALETTE, che è l'indice di una tavolozza di oggetti predefiniti dall'enumerazione StockObject (sezione 2.1.31). |
| [setIhPal(int value)](#setIhPal-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto LogPalette (sezione 2.2.17) nella tabella degli oggetti EMF o il valore DEFAULT\_PALETTE, che è l'indice di una tavolozza di oggetti predefiniti dall'enumerazione StockObject (sezione 2.1.31). |
### EmfSelectPalette(EmfRecord source) {#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectPalette(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSelectPalette`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto LogPalette (sezione 2.2.17) nella tabella degli oggetti EMF o il valore DEFAULT\_PALETTE, che è l'indice di una tavolozza di oggetti predefiniti dall'enumerazione StockObject (sezione 2.1.31).

Questo valore NON DEVE essere zero né l'indice di alcun altro oggetto predefinito.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto LogPalette (sezione 2.2.17) nella tabella degli oggetti EMF o il valore DEFAULT\_PALETTE, che è l'indice di una tavolozza di oggetti predefiniti dall'enumerazione StockObject (sezione 2.1.31).

Questo valore NON DEVE essere zero né l'indice di alcun altro oggetto predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

