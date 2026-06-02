---
title: "EmfColorCorrectPalette"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_COLORCORRECTPALETTE specifica come correggere le voci di un oggetto palette logica utilizzando i valori WCS 1.0."
type: docs
weight: 23
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfColorCorrectPalette extends EmfObjectManipulationRecordType
```

Il record EMR\_COLORCORRECTPALETTE specifica come correggere le voci di un oggetto palette logica usando i valori WCS 1.0.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfColorCorrectPalette(EmfRecord source)](#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfColorCorrectPalette`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhPalette()](#getIhPalette--) | Ottiene un intero senza segno a 32 bit che specifica l'indice di un oggetto palette logica (sezione 2.2.17) nella Tabella Oggetti EMF (sezione 3.1.1.1). |
| [setIhPalette(int value)](#setIhPalette-int-) | Imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto palette logica (sezione 2.2.17) nella Tabella Oggetti EMF (sezione 3.1.1.1). |
| [getNFirstEntry()](#getNFirstEntry--) | Ottiene un intero senza segno a 32 bit che specifica l'indice della prima voce da correggere. |
| [setNFirstEntry(int value)](#setNFirstEntry-int-) | Imposta un intero senza segno a 32 bit che specifica l'indice della prima voce da correggere. |
| [getNPalEntries()](#getNPalEntries--) | Ottiene un intero senza segno a 32 bit che specifica il numero di voci della palette da correggere. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Imposta un intero senza segno a 32 bit che specifica il numero di voci della palette da correggere. |
### EmfColorCorrectPalette(EmfRecord source) {#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorCorrectPalette(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfColorCorrectPalette`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getIhPalette() {#getIhPalette--}
```
public int getIhPalette()
```


Ottiene un intero senza segno a 32 bit che specifica l'indice di un oggetto palette logica (sezione 2.2.17) nella Tabella Oggetti EMF (sezione 3.1.1.1).

**Returns:**
int
### setIhPalette(int value) {#setIhPalette-int-}
```
public void setIhPalette(int value)
```


Imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto palette logica (sezione 2.2.17) nella Tabella Oggetti EMF (sezione 3.1.1.1).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getNFirstEntry() {#getNFirstEntry--}
```
public int getNFirstEntry()
```


Ottiene un intero senza segno a 32 bit che specifica l'indice della prima voce da correggere.

**Returns:**
int
### setNFirstEntry(int value) {#setNFirstEntry-int-}
```
public void setNFirstEntry(int value)
```


Imposta un intero senza segno a 32 bit che specifica l'indice della prima voce da correggere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Ottiene un intero senza segno a 32 bit che specifica il numero di voci della palette da correggere.

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Imposta un intero senza segno a 32 bit che specifica il numero di voci della palette da correggere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

