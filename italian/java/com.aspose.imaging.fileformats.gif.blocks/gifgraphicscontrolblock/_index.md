---
title: "GifGraphicsControlBlock"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Blocco di controllo grafico Gif."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifGraphicsControlBlock extends GifBlock
```

Blocco di controllo grafico Gif.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock--) | Inizializza una nuova istanza della classe `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)](#GifGraphicsControlBlock-byte-int-byte-) | Inizializza una nuova istanza della classe `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)](#GifGraphicsControlBlock-int-boolean-byte-boolean-int-) | Inizializza una nuova istanza della classe `GifGraphicsControlBlock`. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Specifica la dimensione dell'intestazione del blocco. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Etichetta dell'estensione. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | Ottiene la dimensione del sotto-blocco. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDelayTime()](#getDelayTime--) | Ottiene o imposta il tempo di ritardo del fotogramma espresso in 1/100 di secondo. |
| [setDelayTime(int value)](#setDelayTime-int-) | Ottiene o imposta il tempo di ritardo del fotogramma espresso in 1/100 di secondo. |
| [getFlags()](#getFlags--) | Ottiene o imposta le flag. |
| [setFlags(byte value)](#setFlags-byte-) | Ottiene o imposta le flag. |
| [getTransparentColorIndex()](#getTransparentColorIndex--) | Ottiene o imposta l'indice del colore trasparente. |
| [setTransparentColorIndex(byte value)](#setTransparentColorIndex-byte-) | Ottiene o imposta l'indice del colore trasparente. |
| [getDisposalMethod()](#getDisposalMethod--) | Ottiene o imposta il metodo di smaltimento. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Ottiene o imposta il metodo di smaltimento. |
| [getUserInputExpected()](#getUserInputExpected--) | Ottiene o imposta un valore che indica se è previsto l'input dell'utente. |
| [setUserInputExpected(boolean value)](#setUserInputExpected-boolean-) | Ottiene o imposta un valore che indica se è previsto l'input dell'utente. |
| [hasTransparentColor()](#hasTransparentColor--) | Ottiene o imposta un valore che indica se il blocco di controllo grafico ha un colore trasparente. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Ottiene o imposta un valore che indica se il blocco di controllo grafico ha un colore trasparente. |
| [createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)](#createFlags-boolean-boolean-int-) | Crea le flag. |
### GifGraphicsControlBlock() {#GifGraphicsControlBlock--}
```
public GifGraphicsControlBlock()
```


Inizializza una nuova istanza della classe `GifGraphicsControlBlock`.

### GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex) {#GifGraphicsControlBlock-byte-int-byte-}
```
public GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)
```


Inizializza una nuova istanza della classe `GifGraphicsControlBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flag | byte | I flag. |
| delayTime | int | Il tempo di ritardo espresso in 1/100 di secondo. |
| transparentColorIndex | byte | L'indice del colore trasparente. |

### GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod) {#GifGraphicsControlBlock-int-boolean-byte-boolean-int-}
```
public GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)
```


Inizializza una nuova istanza della classe `GifGraphicsControlBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| delayTime | int | Il tempo di ritardo espresso in 1/100 di secondo. |
| hasTransparentColor | boolean | se impostato su `true` il `transparentColorIndex` è valido. |
| transparentColorIndex | byte | L'indice del colore trasparente. |
| requiresUserInput | boolean | se impostato su `true` è previsto l'input dell'utente. |
| disposalMethod | int | Il metodo di smaltimento. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Specifica la dimensione dell'intestazione del blocco.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Etichetta dell'estensione.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


Ottiene la dimensione del sotto-blocco.

### getDelayTime() {#getDelayTime--}
```
public int getDelayTime()
```


Ottiene o imposta il tempo di ritardo del fotogramma espresso in 1/100 di secondo.

**Returns:**
int
### setDelayTime(int value) {#setDelayTime-int-}
```
public void setDelayTime(int value)
```


Ottiene o imposta il tempo di ritardo del fotogramma espresso in 1/100 di secondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFlags() {#getFlags--}
```
public byte getFlags()
```


Ottiene o imposta le flag.

Valore: I flag.

**Returns:**
byte
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Ottiene o imposta le flag.

Valore: I flag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getTransparentColorIndex() {#getTransparentColorIndex--}
```
public byte getTransparentColorIndex()
```


Ottiene o imposta l'indice del colore trasparente.

Valore: L'indice del colore trasparente.

**Returns:**
byte
### setTransparentColorIndex(byte value) {#setTransparentColorIndex-byte-}
```
public void setTransparentColorIndex(byte value)
```


Ottiene o imposta l'indice del colore trasparente.

Valore: L'indice del colore trasparente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Ottiene o imposta il metodo di smaltimento.

Valore: Il metodo di smaltimento.

**Returns:**
int
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public void setDisposalMethod(int value)
```


Ottiene o imposta il metodo di smaltimento.

Valore: Il metodo di smaltimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getUserInputExpected() {#getUserInputExpected--}
```
public boolean getUserInputExpected()
```


Ottiene o imposta un valore che indica se è previsto l'input dell'utente.

Valore: `true` se è previsto l'input dell'utente; altrimenti, `false`.

**Returns:**
boolean
### setUserInputExpected(boolean value) {#setUserInputExpected-boolean-}
```
public void setUserInputExpected(boolean value)
```


Ottiene o imposta un valore che indica se è previsto l'input dell'utente.

Valore: `true` se è previsto l'input dell'utente; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Ottiene o imposta un valore che indica se il blocco di controllo grafico ha un colore trasparente.

Valore: `true` se il blocco di controllo grafico ha colore trasparente; altrimenti, `false`.

**Returns:**
boolean
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Ottiene o imposta un valore che indica se il blocco di controllo grafico ha un colore trasparente.

Valore: `true` se il blocco di controllo grafico ha colore trasparente; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod) {#createFlags-boolean-boolean-int-}
```
public static byte createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)
```


Crea le flag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hasTransparentColor | boolean | se impostato su `true` il `GifGraphicsControlBlock` ha un indice di colore trasparente valido. |
| requiresUserInput | boolean | se impostato su `true` è previsto l'input dell'utente. |
| disposalMethod | int | Il metodo di smaltimento. |

**Returns:**
byte - I flag generati.
