---
title: "EmfSetPaletteEntries"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETPALETTEENTRIES definisce i valori di colore RGB in un intervallo di voci per un oggetto LogPalette esistente nella sezione 2.2.17."
type: docs
weight: 134
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetPaletteEntries extends EmfObjectManipulationRecordType
```

Il record EMR\_SETPALETTEENTRIES definisce i valori di colore RGB in un intervallo di voci per un oggetto LogPalette esistente (sezione 2.2.17).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetPaletteEntries(EmfRecord source)](#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetPaletteEntries`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhPal()](#getIhPal--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della palette EMF Object Table. |
| [setIhPal(int value)](#setIhPal-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della palette EMF Object Table. |
| [getStart()](#getStart--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della prima voce da impostare. |
| [setStart(int value)](#setStart-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della prima voce da impostare. |
| [getNumberofEntries()](#getNumberofEntries--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di voci. |
| [setNumberofEntries(int value)](#setNumberofEntries-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di voci. |
| [getArgb32PalEntries()](#getArgb32PalEntries--) | Ottiene o imposta un array di oggetti LogPaletteEntry (sezione 2.2.18), di lunghezza NumberOfEntries, che specifica i dati delle voci della palette. |
| [setArgb32PalEntries(int[] value)](#setArgb32PalEntries-int---) | Ottiene o imposta un array di oggetti LogPaletteEntry (sezione 2.2.18), di lunghezza NumberOfEntries, che specifica i dati delle voci della palette. |
### EmfSetPaletteEntries(EmfRecord source) {#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPaletteEntries(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetPaletteEntries`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della palette EMF Object Table.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della palette EMF Object Table.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStart() {#getStart--}
```
public int getStart()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della prima voce da impostare.

**Returns:**
int
### setStart(int value) {#setStart-int-}
```
public void setStart(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della prima voce da impostare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getNumberofEntries() {#getNumberofEntries--}
```
public int getNumberofEntries()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di voci.

**Returns:**
int
### setNumberofEntries(int value) {#setNumberofEntries-int-}
```
public void setNumberofEntries(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di voci.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getArgb32PalEntries() {#getArgb32PalEntries--}
```
public int[] getArgb32PalEntries()
```


Ottiene o imposta un array di oggetti LogPaletteEntry (sezione 2.2.18), di lunghezza NumberOfEntries, che specifica i dati delle voci della palette. I membri Values non contengono alcun valore.

**Returns:**
int[]
### setArgb32PalEntries(int[] value) {#setArgb32PalEntries-int---}
```
public void setArgb32PalEntries(int[] value)
```


Ottiene o imposta un array di oggetti LogPaletteEntry (sezione 2.2.18), di lunghezza NumberOfEntries, che specifica i dati delle voci della palette. I membri Values non contengono alcun valore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

