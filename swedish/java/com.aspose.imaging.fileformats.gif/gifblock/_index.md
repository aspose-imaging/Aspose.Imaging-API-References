---
title: "GifBlock"
second_title: "Aspose.Imaging för Java API-referens"
description: "Standardimplementationen för gif-block."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.gif/gifblock/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
```
public abstract class GifBlock implements IGifBlock
```

Standardimplementationen för gif-block.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GifBlock()](#GifBlock--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EXTENSION_INTRODUCER](#EXTENSION-INTRODUCER) | Extension introducer. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isChanged()](#isChanged--) | Hämtar eller anger ett värde som indikerar om blocket har ändrats och kräver sparning. |
| [setChanged(boolean value)](#setChanged-boolean-) | Hämtar eller anger ett värde som indikerar om blocket har ändrats och kräver sparning. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Sparar blocket till den angivna strömmen. |
### GifBlock() {#GifBlock--}
```
public GifBlock()
```


### EXTENSION_INTRODUCER {#EXTENSION-INTRODUCER}
```
public static final byte EXTENSION_INTRODUCER
```


Extension introducer.

### isChanged() {#isChanged--}
```
public boolean isChanged()
```


Hämtar eller anger ett värde som indikerar om blocket har ändrats och kräver sparning.

Värde: `true` om blocket har ändrats; annars `false`.

**Returns:**
boolean
### setChanged(boolean value) {#setChanged-boolean-}
```
public void setChanged(boolean value)
```


Hämtar eller anger ett värde som indikerar om blocket har ändrats och kräver sparning.

Värde: `true` om blocket har ändrats; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Sparar blocket till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Strömmen att spara data till. |

