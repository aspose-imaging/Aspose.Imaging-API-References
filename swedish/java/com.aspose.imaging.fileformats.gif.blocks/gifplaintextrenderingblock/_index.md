---
title: "GifPlainTextRenderingBlock"
second_title: "Aspose.Imaging för Java API-referens"
description: "Gif enkeltextutökning block."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifPlainTextRenderingBlock extends GifBlock
```

Gif textutökningsblock. Textutökningen innehåller textdata och de parametrar som behövs för att rendera den datan som en grafik, i en enkel form.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock--) | Initierar en ny instans av klassen `GifPlainTextRenderingBlock`. |
| [GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)](#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---) | Initierar en ny instans av klassen `GifPlainTextRenderingBlock`. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Etiketten för textutökningen. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | Storleken på delblocket. |
| [BLOCK_SIZE](#BLOCK-SIZE) | Den övergripande blockstorleken. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTextForegroundColorIndex()](#getTextForegroundColorIndex--) | Hämtar eller anger index för färgen i den globala färgpaletten som används för att rita textens förgrund. |
| [setTextForegroundColorIndex(byte value)](#setTextForegroundColorIndex-byte-) | Hämtar eller anger index för färgen i den globala färgpaletten som används för att rita textens förgrund. |
| [getTextBackgroundColorIndex()](#getTextBackgroundColorIndex--) | Hämtar eller anger index för färgen i den globala färgpaletten som används för att rita textens bakgrund. |
| [setTextBackgroundColorIndex(byte value)](#setTextBackgroundColorIndex-byte-) | Hämtar eller anger index för färgen i den globala färgpaletten som används för att rita textens bakgrund. |
| [getCharacterCellWidth()](#getCharacterCellWidth--) | Hämtar eller anger teckencellens bredd, i pixlar, för varje cell i rutnätet. |
| [setCharacterCellWidth(byte value)](#setCharacterCellWidth-byte-) | Hämtar eller anger teckencellens bredd, i pixlar, för varje cell i rutnätet. |
| [getCharacterCellHeight()](#getCharacterCellHeight--) | Hämtar eller anger teckencellens höjd, i pixlar, för varje cell i rutnätet. |
| [setCharacterCellHeight(byte value)](#setCharacterCellHeight-byte-) | Hämtar eller anger teckencellens höjd, i pixlar, för varje cell i rutnätet. |
| [getTextGridLeftPosition()](#getTextGridLeftPosition--) | Hämtar eller anger textrutnätets vänstra position. |
| [setTextGridLeftPosition(int value)](#setTextGridLeftPosition-int-) | Hämtar eller anger textrutnätets vänstra position. |
| [getTextGridTopPosition()](#getTextGridTopPosition--) | Hämtar eller anger textrutnätets övre position. |
| [setTextGridTopPosition(int value)](#setTextGridTopPosition-int-) | Hämtar eller anger textrutnätets övre position. |
| [getTextGridWidth()](#getTextGridWidth--) | Hämtar eller anger textrutnätets bredd i pixlar. |
| [setTextGridWidth(int value)](#setTextGridWidth-int-) | Hämtar eller anger textrutnätets bredd i pixlar. |
| [getTextGridHeight()](#getTextGridHeight--) | Hämtar eller anger textrutnätets höjd i pixlar. |
| [setTextGridHeight(int value)](#setTextGridHeight-int-) | Hämtar eller anger textrutnätets höjd i pixlar. |
| [getPlainTextData()](#getPlainTextData--) | Hämtar eller anger den rena textdata. |
| [setPlainTextData(byte[] value)](#setPlainTextData-byte---) | Hämtar eller anger den rena textdata. |
### GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock--}
```
public GifPlainTextRenderingBlock()
```


Initierar en ny instans av klassen `GifPlainTextRenderingBlock`.

### GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data) {#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---}
```
public GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)
```


Initierar en ny instans av klassen `GifPlainTextRenderingBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textGridLeftPosition | int | Textrutnätets vänstra position. |
| textGridTopPosition | int | Textrutnätets övre position. |
| textGridWidth | int | Textrutnätets bredd. |
| textGridHeight | int | Textrutnätets höjd. |
| characterCellWidth | byte | Teckencellens bredd. |
| characterCellHeight | byte | Teckencellens höjd. |
| textForegroundColorIndex | byte | Förgrundens färgindex. |
| textBackgroundColorIndex | byte | Den bakgrundsfärgindexen. |
| data | byte[] | Den enkla textdata. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Etiketten för textutökningen.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


Storleken på delblocket.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


Den övergripande blockstorleken.

### getTextForegroundColorIndex() {#getTextForegroundColorIndex--}
```
public byte getTextForegroundColorIndex()
```


Hämtar eller anger index för färgen i den globala färgpaletten som används för att rita textens förgrund.

Värde: Den förgrundsfärgindexen.

**Returns:**
byte
### setTextForegroundColorIndex(byte value) {#setTextForegroundColorIndex-byte-}
```
public void setTextForegroundColorIndex(byte value)
```


Hämtar eller anger index för färgen i den globala färgpaletten som används för att rita textens förgrund.

Värde: Den förgrundsfärgindexen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getTextBackgroundColorIndex() {#getTextBackgroundColorIndex--}
```
public byte getTextBackgroundColorIndex()
```


Hämtar eller anger index för färgen i den globala färgpaletten som används för att rita textens bakgrund.

Värde: Den bakgrundsfärgindexen.

**Returns:**
byte
### setTextBackgroundColorIndex(byte value) {#setTextBackgroundColorIndex-byte-}
```
public void setTextBackgroundColorIndex(byte value)
```


Hämtar eller anger index för färgen i den globala färgpaletten som används för att rita textens bakgrund.

Värde: Den bakgrundsfärgindexen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCharacterCellWidth() {#getCharacterCellWidth--}
```
public byte getCharacterCellWidth()
```


Hämtar eller anger teckencellens bredd, i pixlar, för varje cell i rutnätet.

Värde: Bredden på teckencellen.

**Returns:**
byte
### setCharacterCellWidth(byte value) {#setCharacterCellWidth-byte-}
```
public void setCharacterCellWidth(byte value)
```


Hämtar eller anger teckencellens bredd, i pixlar, för varje cell i rutnätet.

Värde: Bredden på teckencellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCharacterCellHeight() {#getCharacterCellHeight--}
```
public byte getCharacterCellHeight()
```


Hämtar eller anger teckencellens höjd, i pixlar, för varje cell i rutnätet.

Värde: Höjden på teckencellen.

**Returns:**
byte
### setCharacterCellHeight(byte value) {#setCharacterCellHeight-byte-}
```
public void setCharacterCellHeight(byte value)
```


Hämtar eller anger teckencellens höjd, i pixlar, för varje cell i rutnätet.

Värde: Höjden på teckencellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getTextGridLeftPosition() {#getTextGridLeftPosition--}
```
public int getTextGridLeftPosition()
```


Hämtar eller anger textrutnätets vänstra position.

Värde: Textrutans vänstra position.

Detta är ett kolumnnummer, i pixlar, för den vänstra kanten av textrutnätet, i förhållande till den vänstra kanten av den logiska skärmen.

**Returns:**
int
### setTextGridLeftPosition(int value) {#setTextGridLeftPosition-int-}
```
public void setTextGridLeftPosition(int value)
```


Hämtar eller anger textrutnätets vänstra position.

Värde: Textrutans vänstra position.

Detta är ett kolumnnummer, i pixlar, för den vänstra kanten av textrutnätet, i förhållande till den vänstra kanten av den logiska skärmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTextGridTopPosition() {#getTextGridTopPosition--}
```
public int getTextGridTopPosition()
```


Hämtar eller anger textrutnätets övre position.

Värde: Textrutans övre position.

Detta är ett radnummer, i pixlar, för den övre kanten av textrutnätet, i förhållande till den övre kanten av den logiska skärmen.

**Returns:**
int
### setTextGridTopPosition(int value) {#setTextGridTopPosition-int-}
```
public void setTextGridTopPosition(int value)
```


Hämtar eller anger textrutnätets övre position.

Värde: Textrutans övre position.

Detta är ett radnummer, i pixlar, för den övre kanten av textrutnätet, i förhållande till den övre kanten av den logiska skärmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTextGridWidth() {#getTextGridWidth--}
```
public int getTextGridWidth()
```


Hämtar eller anger textrutnätets bredd i pixlar.

Värde: Textrutans bredd i pixlar.

**Returns:**
int
### setTextGridWidth(int value) {#setTextGridWidth-int-}
```
public void setTextGridWidth(int value)
```


Hämtar eller anger textrutnätets bredd i pixlar.

Värde: Textrutans bredd i pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTextGridHeight() {#getTextGridHeight--}
```
public int getTextGridHeight()
```


Hämtar eller anger textrutnätets höjd i pixlar.

Värde: Textrutans höjd i pixlar.

**Returns:**
int
### setTextGridHeight(int value) {#setTextGridHeight-int-}
```
public void setTextGridHeight(int value)
```


Hämtar eller anger textrutnätets höjd i pixlar.

Värde: Textrutans höjd i pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPlainTextData() {#getPlainTextData--}
```
public byte[] getPlainTextData()
```


Hämtar eller anger den rena textdata.

Värde: Den enkla textdata.

**Returns:**
byte[]
### setPlainTextData(byte[] value) {#setPlainTextData-byte---}
```
public void setPlainTextData(byte[] value)
```


Hämtar eller anger den rena textdata.

Värde: Den enkla textdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

