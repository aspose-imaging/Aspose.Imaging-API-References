---
title: "GifGraphicsControlBlock"
second_title: "Aspose.Imaging för Java API-referens"
description: "Gif-grafikstyrningsblock."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifGraphicsControlBlock extends GifBlock
```

Gif-grafikstyrningsblock.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock--) | Initierar en ny instans av klassen `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)](#GifGraphicsControlBlock-byte-int-byte-) | Initierar en ny instans av klassen `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)](#GifGraphicsControlBlock-int-boolean-byte-boolean-int-) | Initierar en ny instans av klassen `GifGraphicsControlBlock`. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Anger blockhuvudets storlek. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Etikett för tillägg. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | Hämtar storleken på subblocket. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDelayTime()](#getDelayTime--) | Hämtar eller anger fördröjningstiden för ramen uttryckt i 1/100 sekunder. |
| [setDelayTime(int value)](#setDelayTime-int-) | Hämtar eller anger fördröjningstiden för ramen uttryckt i 1/100 sekunder. |
| [getFlags()](#getFlags--) | Hämtar eller anger flaggorna. |
| [setFlags(byte value)](#setFlags-byte-) | Hämtar eller anger flaggorna. |
| [getTransparentColorIndex()](#getTransparentColorIndex--) | Hämtar eller anger den transparenta färgindexen. |
| [setTransparentColorIndex(byte value)](#setTransparentColorIndex-byte-) | Hämtar eller anger den transparenta färgindexen. |
| [getDisposalMethod()](#getDisposalMethod--) | Hämtar eller anger borttagningsmetoden. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Hämtar eller anger borttagningsmetoden. |
| [getUserInputExpected()](#getUserInputExpected--) | Hämtar eller anger ett värde som indikerar om användarinmatning förväntas. |
| [setUserInputExpected(boolean value)](#setUserInputExpected-boolean-) | Hämtar eller anger ett värde som indikerar om användarinmatning förväntas. |
| [hasTransparentColor()](#hasTransparentColor--) | Hämtar eller anger ett värde som indikerar om grafikstyrningsblocket har transparent färg. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Hämtar eller anger ett värde som indikerar om grafikstyrningsblocket har transparent färg. |
| [createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)](#createFlags-boolean-boolean-int-) | Skapar flaggorna. |
### GifGraphicsControlBlock() {#GifGraphicsControlBlock--}
```
public GifGraphicsControlBlock()
```


Initierar en ny instans av klassen `GifGraphicsControlBlock`.

### GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex) {#GifGraphicsControlBlock-byte-int-byte-}
```
public GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)
```


Initierar en ny instans av klassen `GifGraphicsControlBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flaggor | byte | Flaggorna. |
| delayTime | int | Fördröjningstiden uttryckt i 1/100 sekunder. |
| transparentColorIndex | byte | Den transparenta färgindexen. |

### GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod) {#GifGraphicsControlBlock-int-boolean-byte-boolean-int-}
```
public GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)
```


Initierar en ny instans av klassen `GifGraphicsControlBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| delayTime | int | Fördröjningstiden uttryckt i 1/100 sekunder. |
| hasTransparentColor | boolean | om den är satt till `true` är `transparentColorIndex` giltig. |
| transparentColorIndex | byte | Den transparenta färgindexen. |
| requiresUserInput | boolean | om den är satt till `true` förväntas användarinmatning. |
| disposalMethod | int | Dispositionsmetoden. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Anger blockhuvudets storlek.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Etikett för tillägg.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


Hämtar storleken på subblocket.

### getDelayTime() {#getDelayTime--}
```
public int getDelayTime()
```


Hämtar eller anger fördröjningstiden för ramen uttryckt i 1/100 sekunder.

**Returns:**
int
### setDelayTime(int value) {#setDelayTime-int-}
```
public void setDelayTime(int value)
```


Hämtar eller anger fördröjningstiden för ramen uttryckt i 1/100 sekunder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFlags() {#getFlags--}
```
public byte getFlags()
```


Hämtar eller anger flaggorna.

Värde: Flaggor.

**Returns:**
byte
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Hämtar eller anger flaggorna.

Värde: Flaggor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getTransparentColorIndex() {#getTransparentColorIndex--}
```
public byte getTransparentColorIndex()
```


Hämtar eller anger den transparenta färgindexen.

Värde: Det transparenta färgindexet.

**Returns:**
byte
### setTransparentColorIndex(byte value) {#setTransparentColorIndex-byte-}
```
public void setTransparentColorIndex(byte value)
```


Hämtar eller anger den transparenta färgindexen.

Värde: Det transparenta färgindexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Hämtar eller anger borttagningsmetoden.

Värde: Dispositionsmetoden.

**Returns:**
int
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public void setDisposalMethod(int value)
```


Hämtar eller anger borttagningsmetoden.

Värde: Dispositionsmetoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getUserInputExpected() {#getUserInputExpected--}
```
public boolean getUserInputExpected()
```


Hämtar eller anger ett värde som indikerar om användarinmatning förväntas.

Värde: `true` om användarinmatning förväntas; annars `false`.

**Returns:**
boolean
### setUserInputExpected(boolean value) {#setUserInputExpected-boolean-}
```
public void setUserInputExpected(boolean value)
```


Hämtar eller anger ett värde som indikerar om användarinmatning förväntas.

Värde: `true` om användarinmatning förväntas; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Hämtar eller anger ett värde som indikerar om grafikstyrningsblocket har transparent färg.

Värde: `true` om grafikstyrningsblocket har transparent färg; annars `false`.

**Returns:**
boolean
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Hämtar eller anger ett värde som indikerar om grafikstyrningsblocket har transparent färg.

Värde: `true` om grafikstyrningsblocket har transparent färg; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod) {#createFlags-boolean-boolean-int-}
```
public static byte createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)
```


Skapar flaggorna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hasTransparentColor | boolean | om den är satt till `true` har `GifGraphicsControlBlock` ett giltigt transparent färgindex. |
| requiresUserInput | boolean | om den är satt till `true` förväntas användarinmatning. |
| disposalMethod | int | Dispositionsmetoden. |

**Returns:**
byte - De genererade flaggorna.
