---
title: "GifPlainTextRenderingBlock"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Gif-Plain-Text-Erweiterungsblock."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifPlainTextRenderingBlock extends GifBlock
```

Gif-Text-Erweiterungsblock. Die Text-Erweiterung enthält Textdaten und die Parameter, die erforderlich sind, um diese Daten in einfacher Form als Grafik darzustellen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock--) | Initialisiert eine neue Instanz der `GifPlainTextRenderingBlock`-Klasse. |
| [GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)](#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---) | Initialisiert eine neue Instanz der `GifPlainTextRenderingBlock`-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Das Text-Erweiterungslabel. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | Die Größe des Unterblocks. |
| [BLOCK_SIZE](#BLOCK-SIZE) | Die gesamte Blockgröße. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTextForegroundColorIndex()](#getTextForegroundColorIndex--) | Liest oder setzt den Index der Farbe in der globalen Farbpalette, die zum Zeichnen des Textvordergrunds verwendet wird. |
| [setTextForegroundColorIndex(byte value)](#setTextForegroundColorIndex-byte-) | Liest oder setzt den Index der Farbe in der globalen Farbpalette, die zum Zeichnen des Textvordergrunds verwendet wird. |
| [getTextBackgroundColorIndex()](#getTextBackgroundColorIndex--) | Liest oder setzt den Index der Farbe in der globalen Farbpalette, die zum Zeichnen des Texthintergrunds verwendet wird. |
| [setTextBackgroundColorIndex(byte value)](#setTextBackgroundColorIndex-byte-) | Liest oder setzt den Index der Farbe in der globalen Farbpalette, die zum Zeichnen des Texthintergrunds verwendet wird. |
| [getCharacterCellWidth()](#getCharacterCellWidth--) | Liest oder setzt die Breite der Zeichenzelle in Pixeln für jede Zelle im Raster. |
| [setCharacterCellWidth(byte value)](#setCharacterCellWidth-byte-) | Liest oder setzt die Breite der Zeichenzelle in Pixeln für jede Zelle im Raster. |
| [getCharacterCellHeight()](#getCharacterCellHeight--) | Liest oder setzt die Höhe der Zeichenzelle in Pixeln für jede Zelle im Raster. |
| [setCharacterCellHeight(byte value)](#setCharacterCellHeight-byte-) | Liest oder setzt die Höhe der Zeichenzelle in Pixeln für jede Zelle im Raster. |
| [getTextGridLeftPosition()](#getTextGridLeftPosition--) | Liest oder setzt die linke Position des Textrasters. |
| [setTextGridLeftPosition(int value)](#setTextGridLeftPosition-int-) | Liest oder setzt die linke Position des Textrasters. |
| [getTextGridTopPosition()](#getTextGridTopPosition--) | Liest oder setzt die obere Position des Textrasters. |
| [setTextGridTopPosition(int value)](#setTextGridTopPosition-int-) | Liest oder setzt die obere Position des Textrasters. |
| [getTextGridWidth()](#getTextGridWidth--) | Liest oder setzt die Textrasterbreite in Pixeln |
| [setTextGridWidth(int value)](#setTextGridWidth-int-) | Liest oder setzt die Textrasterbreite in Pixeln |
| [getTextGridHeight()](#getTextGridHeight--) | Liest oder setzt die Höhe des Textrasters in Pixeln |
| [setTextGridHeight(int value)](#setTextGridHeight-int-) | Liest oder setzt die Höhe des Textrasters in Pixeln |
| [getPlainTextData()](#getPlainTextData--) | Liest oder setzt die Klartextdaten. |
| [setPlainTextData(byte[] value)](#setPlainTextData-byte---) | Liest oder setzt die Klartextdaten. |
### GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock--}
```
public GifPlainTextRenderingBlock()
```


Initialisiert eine neue Instanz der `GifPlainTextRenderingBlock`-Klasse.

### GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data) {#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---}
```
public GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)
```


Initialisiert eine neue Instanz der `GifPlainTextRenderingBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textGridLeftPosition | int | Die linke Position des Textrasters. |
| textGridTopPosition | int | Die obere Position des Textrasters. |
| textGridWidth | int | Die Breite des Textrasters. |
| textGridHeight | int | Die Höhe des Textrasters. |
| characterCellWidth | byte | Die Breite der Zeichenzelle. |
| characterCellHeight | byte | Die Höhe der Zeichenzelle. |
| textForegroundColorIndex | byte | Der Index der Vordergrundfarbe. |
| textBackgroundColorIndex | byte | Der Index der Hintergrundfarbe. |
| Daten | byte[] | Die Klartextdaten. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Das Text-Erweiterungslabel.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


Die Größe des Unterblocks.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


Die gesamte Blockgröße.

### getTextForegroundColorIndex() {#getTextForegroundColorIndex--}
```
public byte getTextForegroundColorIndex()
```


Liest oder setzt den Index der Farbe in der globalen Farbpalette, die zum Zeichnen des Textvordergrunds verwendet wird.

Wert: Der Index der Vordergrundfarbe.

**Returns:**
byte
### setTextForegroundColorIndex(byte value) {#setTextForegroundColorIndex-byte-}
```
public void setTextForegroundColorIndex(byte value)
```


Liest oder setzt den Index der Farbe in der globalen Farbpalette, die zum Zeichnen des Textvordergrunds verwendet wird.

Wert: Der Index der Vordergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getTextBackgroundColorIndex() {#getTextBackgroundColorIndex--}
```
public byte getTextBackgroundColorIndex()
```


Liest oder setzt den Index der Farbe in der globalen Farbpalette, die zum Zeichnen des Texthintergrunds verwendet wird.

Wert: Der Index der Hintergrundfarbe.

**Returns:**
byte
### setTextBackgroundColorIndex(byte value) {#setTextBackgroundColorIndex-byte-}
```
public void setTextBackgroundColorIndex(byte value)
```


Liest oder setzt den Index der Farbe in der globalen Farbpalette, die zum Zeichnen des Texthintergrunds verwendet wird.

Wert: Der Index der Hintergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCharacterCellWidth() {#getCharacterCellWidth--}
```
public byte getCharacterCellWidth()
```


Liest oder setzt die Breite der Zeichenzelle in Pixeln für jede Zelle im Raster.

Wert: Die Breite der Zeichenzelle.

**Returns:**
byte
### setCharacterCellWidth(byte value) {#setCharacterCellWidth-byte-}
```
public void setCharacterCellWidth(byte value)
```


Liest oder setzt die Breite der Zeichenzelle in Pixeln für jede Zelle im Raster.

Wert: Die Breite der Zeichenzelle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCharacterCellHeight() {#getCharacterCellHeight--}
```
public byte getCharacterCellHeight()
```


Liest oder setzt die Höhe der Zeichenzelle in Pixeln für jede Zelle im Raster.

Wert: Die Höhe der Zeichenzelle.

**Returns:**
byte
### setCharacterCellHeight(byte value) {#setCharacterCellHeight-byte-}
```
public void setCharacterCellHeight(byte value)
```


Liest oder setzt die Höhe der Zeichenzelle in Pixeln für jede Zelle im Raster.

Wert: Die Höhe der Zeichenzelle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getTextGridLeftPosition() {#getTextGridLeftPosition--}
```
public int getTextGridLeftPosition()
```


Liest oder setzt die linke Position des Textrasters.

Wert: Die linke Position des Textgitters.

Dies ist eine Spaltennummer, in Pixeln, der linken Kante des Textgitters, bezogen auf die linke Kante des logischen Bildschirms.

**Returns:**
int
### setTextGridLeftPosition(int value) {#setTextGridLeftPosition-int-}
```
public void setTextGridLeftPosition(int value)
```


Liest oder setzt die linke Position des Textrasters.

Wert: Die linke Position des Textgitters.

Dies ist eine Spaltennummer, in Pixeln, der linken Kante des Textgitters, bezogen auf die linke Kante des logischen Bildschirms.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTextGridTopPosition() {#getTextGridTopPosition--}
```
public int getTextGridTopPosition()
```


Liest oder setzt die obere Position des Textrasters.

Wert: Die obere Position des Textgitters.

Dies ist eine Zeilennummer, in Pixeln, der oberen Kante des Textgitters, bezogen auf die obere Kante des logischen Bildschirms.

**Returns:**
int
### setTextGridTopPosition(int value) {#setTextGridTopPosition-int-}
```
public void setTextGridTopPosition(int value)
```


Liest oder setzt die obere Position des Textrasters.

Wert: Die obere Position des Textgitters.

Dies ist eine Zeilennummer, in Pixeln, der oberen Kante des Textgitters, bezogen auf die obere Kante des logischen Bildschirms.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTextGridWidth() {#getTextGridWidth--}
```
public int getTextGridWidth()
```


Liest oder setzt die Textrasterbreite in Pixeln

Wert: Die Breite des Textgitters in Pixeln.

**Returns:**
int
### setTextGridWidth(int value) {#setTextGridWidth-int-}
```
public void setTextGridWidth(int value)
```


Liest oder setzt die Textrasterbreite in Pixeln

Wert: Die Breite des Textgitters in Pixeln.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTextGridHeight() {#getTextGridHeight--}
```
public int getTextGridHeight()
```


Liest oder setzt die Höhe des Textrasters in Pixeln

Wert: Die Höhe des Textgitters in Pixeln.

**Returns:**
int
### setTextGridHeight(int value) {#setTextGridHeight-int-}
```
public void setTextGridHeight(int value)
```


Liest oder setzt die Höhe des Textrasters in Pixeln

Wert: Die Höhe des Textgitters in Pixeln.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPlainTextData() {#getPlainTextData--}
```
public byte[] getPlainTextData()
```


Liest oder setzt die Klartextdaten.

Wert: Die Klartextdaten.

**Returns:**
byte[]
### setPlainTextData(byte[] value) {#setPlainTextData-byte---}
```
public void setPlainTextData(byte[] value)
```


Liest oder setzt die Klartextdaten.

Wert: Die Klartextdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

