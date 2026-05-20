---
title: "GifPlainTextRenderingBlock"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Blocco di estensione testo semplice Gif."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifPlainTextRenderingBlock extends GifBlock
```

Blocco di estensione di testo semplice Gif. L'estensione di testo semplice contiene dati testuali e i parametri necessari per renderizzare tali dati come grafica, in forma semplice.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock--) | Inizializza una nuova istanza della classe `GifPlainTextRenderingBlock`. |
| [GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)](#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---) | Inizializza una nuova istanza della classe `GifPlainTextRenderingBlock`. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | L'etichetta dell'estensione di testo semplice. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | La dimensione del sotto-blocco. |
| [BLOCK_SIZE](#BLOCK-SIZE) | La dimensione complessiva del blocco. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTextForegroundColorIndex()](#getTextForegroundColorIndex--) | Ottiene o imposta l'indice del colore nella tavolozza dei colori globale usato per disegnare il primo piano del testo. |
| [setTextForegroundColorIndex(byte value)](#setTextForegroundColorIndex-byte-) | Ottiene o imposta l'indice del colore nella tavolozza dei colori globale usato per disegnare il primo piano del testo. |
| [getTextBackgroundColorIndex()](#getTextBackgroundColorIndex--) | Ottiene o imposta l'indice del colore nella tavolozza dei colori globale usato per disegnare lo sfondo del testo. |
| [setTextBackgroundColorIndex(byte value)](#setTextBackgroundColorIndex-byte-) | Ottiene o imposta l'indice del colore nella tavolozza dei colori globale usato per disegnare lo sfondo del testo. |
| [getCharacterCellWidth()](#getCharacterCellWidth--) | Ottiene o imposta la larghezza della cella carattere, in pixel, di ogni cella nella griglia. |
| [setCharacterCellWidth(byte value)](#setCharacterCellWidth-byte-) | Ottiene o imposta la larghezza della cella carattere, in pixel, di ogni cella nella griglia. |
| [getCharacterCellHeight()](#getCharacterCellHeight--) | Ottiene o imposta l'altezza della cella carattere, in pixel, di ogni cella nella griglia. |
| [setCharacterCellHeight(byte value)](#setCharacterCellHeight-byte-) | Ottiene o imposta l'altezza della cella carattere, in pixel, di ogni cella nella griglia. |
| [getTextGridLeftPosition()](#getTextGridLeftPosition--) | Ottiene o imposta la posizione sinistra della griglia di testo. |
| [setTextGridLeftPosition(int value)](#setTextGridLeftPosition-int-) | Ottiene o imposta la posizione sinistra della griglia di testo. |
| [getTextGridTopPosition()](#getTextGridTopPosition--) | Ottiene o imposta la posizione superiore della griglia di testo. |
| [setTextGridTopPosition(int value)](#setTextGridTopPosition-int-) | Ottiene o imposta la posizione superiore della griglia di testo. |
| [getTextGridWidth()](#getTextGridWidth--) | Ottiene o imposta la larghezza della griglia di testo in pixel. |
| [setTextGridWidth(int value)](#setTextGridWidth-int-) | Ottiene o imposta la larghezza della griglia di testo in pixel. |
| [getTextGridHeight()](#getTextGridHeight--) | Ottiene o imposta l'altezza della griglia di testo in pixel. |
| [setTextGridHeight(int value)](#setTextGridHeight-int-) | Ottiene o imposta l'altezza della griglia di testo in pixel. |
| [getPlainTextData()](#getPlainTextData--) | Ottiene o imposta i dati di testo semplice. |
| [setPlainTextData(byte[] value)](#setPlainTextData-byte---) | Ottiene o imposta i dati di testo semplice. |
### GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock--}
```
public GifPlainTextRenderingBlock()
```


Inizializza una nuova istanza della classe `GifPlainTextRenderingBlock`.

### GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data) {#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---}
```
public GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)
```


Inizializza una nuova istanza della classe `GifPlainTextRenderingBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textGridLeftPosition | int | La posizione sinistra della griglia di testo. |
| textGridTopPosition | int | La posizione superiore della griglia di testo. |
| textGridWidth | int | La larghezza della griglia di testo. |
| textGridHeight | int | L'altezza della griglia di testo. |
| characterCellWidth | byte | La larghezza della cella carattere. |
| characterCellHeight | byte | L'altezza della cella carattere. |
| textForegroundColorIndex | byte | L'indice del colore di primo piano. |
| textBackgroundColorIndex | byte | L'indice del colore di sfondo. |
| dati | byte[] | I dati di testo semplice. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


L'etichetta dell'estensione di testo semplice.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


La dimensione del sotto-blocco.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


La dimensione complessiva del blocco.

### getTextForegroundColorIndex() {#getTextForegroundColorIndex--}
```
public byte getTextForegroundColorIndex()
```


Ottiene o imposta l'indice del colore nella tavolozza dei colori globale usato per disegnare il primo piano del testo.

Valore: l'indice del colore di primo piano.

**Returns:**
byte
### setTextForegroundColorIndex(byte value) {#setTextForegroundColorIndex-byte-}
```
public void setTextForegroundColorIndex(byte value)
```


Ottiene o imposta l'indice del colore nella tavolozza dei colori globale usato per disegnare il primo piano del testo.

Valore: l'indice del colore di primo piano.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getTextBackgroundColorIndex() {#getTextBackgroundColorIndex--}
```
public byte getTextBackgroundColorIndex()
```


Ottiene o imposta l'indice del colore nella tavolozza dei colori globale usato per disegnare lo sfondo del testo.

Valore: l'indice del colore di sfondo.

**Returns:**
byte
### setTextBackgroundColorIndex(byte value) {#setTextBackgroundColorIndex-byte-}
```
public void setTextBackgroundColorIndex(byte value)
```


Ottiene o imposta l'indice del colore nella tavolozza dei colori globale usato per disegnare lo sfondo del testo.

Valore: l'indice del colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCharacterCellWidth() {#getCharacterCellWidth--}
```
public byte getCharacterCellWidth()
```


Ottiene o imposta la larghezza della cella carattere, in pixel, di ogni cella nella griglia.

Valore: la larghezza della cella del carattere.

**Returns:**
byte
### setCharacterCellWidth(byte value) {#setCharacterCellWidth-byte-}
```
public void setCharacterCellWidth(byte value)
```


Ottiene o imposta la larghezza della cella carattere, in pixel, di ogni cella nella griglia.

Valore: la larghezza della cella del carattere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCharacterCellHeight() {#getCharacterCellHeight--}
```
public byte getCharacterCellHeight()
```


Ottiene o imposta l'altezza della cella carattere, in pixel, di ogni cella nella griglia.

Valore: l'altezza della cella del carattere.

**Returns:**
byte
### setCharacterCellHeight(byte value) {#setCharacterCellHeight-byte-}
```
public void setCharacterCellHeight(byte value)
```


Ottiene o imposta l'altezza della cella carattere, in pixel, di ogni cella nella griglia.

Valore: l'altezza della cella del carattere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getTextGridLeftPosition() {#getTextGridLeftPosition--}
```
public int getTextGridLeftPosition()
```


Ottiene o imposta la posizione sinistra della griglia di testo.

Valore: la posizione sinistra della griglia di testo.

Questo è un numero di colonna, in pixel, del bordo sinistro della griglia di testo, rispetto al bordo sinistro dello schermo logico.

**Returns:**
int
### setTextGridLeftPosition(int value) {#setTextGridLeftPosition-int-}
```
public void setTextGridLeftPosition(int value)
```


Ottiene o imposta la posizione sinistra della griglia di testo.

Valore: la posizione sinistra della griglia di testo.

Questo è un numero di colonna, in pixel, del bordo sinistro della griglia di testo, rispetto al bordo sinistro dello schermo logico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTextGridTopPosition() {#getTextGridTopPosition--}
```
public int getTextGridTopPosition()
```


Ottiene o imposta la posizione superiore della griglia di testo.

Valore: la posizione superiore della griglia di testo.

Questo è un numero di riga, in pixel, del bordo superiore della griglia di testo, rispetto al bordo superiore dello schermo logico.

**Returns:**
int
### setTextGridTopPosition(int value) {#setTextGridTopPosition-int-}
```
public void setTextGridTopPosition(int value)
```


Ottiene o imposta la posizione superiore della griglia di testo.

Valore: la posizione superiore della griglia di testo.

Questo è un numero di riga, in pixel, del bordo superiore della griglia di testo, rispetto al bordo superiore dello schermo logico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTextGridWidth() {#getTextGridWidth--}
```
public int getTextGridWidth()
```


Ottiene o imposta la larghezza della griglia di testo in pixel.

Valore: la larghezza della griglia di testo in pixel.

**Returns:**
int
### setTextGridWidth(int value) {#setTextGridWidth-int-}
```
public void setTextGridWidth(int value)
```


Ottiene o imposta la larghezza della griglia di testo in pixel.

Valore: la larghezza della griglia di testo in pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTextGridHeight() {#getTextGridHeight--}
```
public int getTextGridHeight()
```


Ottiene o imposta l'altezza della griglia di testo in pixel.

Valore: l'altezza della griglia di testo in pixel.

**Returns:**
int
### setTextGridHeight(int value) {#setTextGridHeight-int-}
```
public void setTextGridHeight(int value)
```


Ottiene o imposta l'altezza della griglia di testo in pixel.

Valore: l'altezza della griglia di testo in pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPlainTextData() {#getPlainTextData--}
```
public byte[] getPlainTextData()
```


Ottiene o imposta i dati di testo semplice.

Valore: i dati di testo semplice.

**Returns:**
byte[]
### setPlainTextData(byte[] value) {#setPlainTextData-byte---}
```
public void setPlainTextData(byte[] value)
```


Ottiene o imposta i dati di testo semplice.

Valore: i dati di testo semplice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

