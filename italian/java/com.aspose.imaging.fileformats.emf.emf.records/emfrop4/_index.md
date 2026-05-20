---
title: "EmfRop4"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Un'operazione raster quaternaria che specifica operazioni raster ternarie per i colori di primo piano e di sfondo di una bitmap."
type: docs
weight: 110
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfrop4/
---
**Inheritance:**
java.lang.Object
```
public final class EmfRop4
```

Un'operazione raster quaternaria, che specifica operazioni raster ternarie per i colori di primo piano e di sfondo di una bitmap. Questi valori definiscono come i dati colore del rettangolo sorgente devono essere combinati con i dati colore del rettangolo di destinazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfRop4(int dwordData)](#EmfRop4-int-) | Inizializza una nuova istanza della classe `EmfRop4`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBackgroundRop3()](#getBackgroundRop3--) | Ottiene il ROP3 di sfondo. |
| [getForegroundRop3()](#getForegroundRop3--) | Ottiene il ROP3 di primo piano. |
### EmfRop4(int dwordData) {#EmfRop4-int-}
```
public EmfRop4(int dwordData)
```


Inizializza una nuova istanza della classe `EmfRop4`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dwordData | int | I dati dword. |

### getBackgroundRop3() {#getBackgroundRop3--}
```
public byte getBackgroundRop3()
```


Ottiene il ROP3 di sfondo. Gli 8 bit più significativi non firmati di un valore di operazione raster ternaria a 24 bit dall'enumerazione WMF Ternary Raster Operation ([MS-WMF] sezione 2.1.1.31). Questo codice definisce come combinare i dati del colore di sfondo delle bitmap sorgente e destinazione e il modello di pennello.

Valore: Il ROP3 di sfondo.

**Returns:**
byte
### getForegroundRop3() {#getForegroundRop3--}
```
public byte getForegroundRop3()
```


Ottiene il ROP3 di primo piano. Gli 8 bit più significativi non firmati di un valore di operazione raster ternaria a 24 bit dall'enumerazione WMF Ternary Raster Operation. Questo codice definisce come combinare i dati del colore di primo piano delle bitmap sorgente e destinazione e il modello di pennello.

Valore: Il ROP3 di primo piano.

**Returns:**
byte
