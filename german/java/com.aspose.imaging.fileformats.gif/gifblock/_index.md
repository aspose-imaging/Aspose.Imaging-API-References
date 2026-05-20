---
title: "GifBlock"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Standard‑GIF‑Blockimplementierung."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.gif/gifblock/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
```
public abstract class GifBlock implements IGifBlock
```

Die Standard‑GIF‑Blockimplementierung.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GifBlock()](#GifBlock--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [EXTENSION_INTRODUCER](#EXTENSION-INTRODUCER) | Erweiterungs-Einleiter. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isChanged()](#isChanged--) | Liest oder setzt einen Wert, der angibt, ob der Block geändert wurde und gespeichert werden muss. |
| [setChanged(boolean value)](#setChanged-boolean-) | Liest oder setzt einen Wert, der angibt, ob der Block geändert wurde und gespeichert werden muss. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Speichert den Block in den angegebenen Stream. |
### GifBlock() {#GifBlock--}
```
public GifBlock()
```


### EXTENSION_INTRODUCER {#EXTENSION-INTRODUCER}
```
public static final byte EXTENSION_INTRODUCER
```


Erweiterungs-Einleiter.

### isChanged() {#isChanged--}
```
public boolean isChanged()
```


Liest oder setzt einen Wert, der angibt, ob der Block geändert wurde und gespeichert werden muss.

Wert: `true`, wenn der Block geändert wurde; andernfalls `false`.

**Returns:**
boolean
### setChanged(boolean value) {#setChanged-boolean-}
```
public void setChanged(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob der Block geändert wurde und gespeichert werden muss.

Wert: `true`, wenn der Block geändert wurde; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Speichert den Block in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | Der Stream, in den Daten gespeichert werden sollen. |

