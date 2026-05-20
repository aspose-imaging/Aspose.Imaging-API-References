---
title: "GifBlock"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'implementazione predefinita del blocco gif."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.gif/gifblock/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
```
public abstract class GifBlock implements IGifBlock
```

L'implementazione predefinita del blocco gif.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GifBlock()](#GifBlock--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [EXTENSION_INTRODUCER](#EXTENSION-INTRODUCER) | Introduttore dell'estensione. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isChanged()](#isChanged--) | Ottiene o imposta un valore che indica se il blocco è stato modificato e richiede il salvataggio. |
| [setChanged(boolean value)](#setChanged-boolean-) | Ottiene o imposta un valore che indica se il blocco è stato modificato e richiede il salvataggio. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Salva il blocco nello stream specificato. |
### GifBlock() {#GifBlock--}
```
public GifBlock()
```


### EXTENSION_INTRODUCER {#EXTENSION-INTRODUCER}
```
public static final byte EXTENSION_INTRODUCER
```


Introduttore dell'estensione.

### isChanged() {#isChanged--}
```
public boolean isChanged()
```


Ottiene o imposta un valore che indica se il blocco è stato modificato e richiede il salvataggio.

Valore: `true` se il blocco è stato modificato; altrimenti, `false`.

**Returns:**
boolean
### setChanged(boolean value) {#setChanged-boolean-}
```
public void setChanged(boolean value)
```


Ottiene o imposta un valore che indica se il blocco è stato modificato e richiede il salvataggio.

Valore: `true` se il blocco è stato modificato; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Salva il blocco nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.OutputStream | Lo stream su cui salvare i dati. |

