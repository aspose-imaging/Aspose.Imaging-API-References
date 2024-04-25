---
title: GifPlainTextRenderingBlock
second_title: Aspose.Imaging for Java API Reference
description: Gif plain text extension block.
type: docs
weight: 14
url: /com.aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifPlainTextRenderingBlock extends GifBlock
```

Gif plain text extension block. The plain text extension contains textual data and the parameters necessary to render that data as a graphic, in a simple form.
## Constructors

| Constructor | Description |
| --- | --- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock--) | Initializes a new instance of the `GifPlainTextRenderingBlock` class. |
| [GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)](#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---) | Initializes a new instance of the `GifPlainTextRenderingBlock` class. |
## Fields

| Field | Description |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | The plain text extension label. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | The size of the sub block. |
| [BLOCK_SIZE](#BLOCK-SIZE) | The overall block size. |
## Methods

| Method | Description |
| --- | --- |
| [getTextForegroundColorIndex()](#getTextForegroundColorIndex--) | Gets or sets the index of the color in the global color palette used to draw the text foreground. |
| [setTextForegroundColorIndex(byte value)](#setTextForegroundColorIndex-byte-) | Gets or sets the index of the color in the global color palette used to draw the text foreground. |
| [getTextBackgroundColorIndex()](#getTextBackgroundColorIndex--) | Gets or sets the index of the color in the global color palette used to draw the text background. |
| [setTextBackgroundColorIndex(byte value)](#setTextBackgroundColorIndex-byte-) | Gets or sets the index of the color in the global color palette used to draw the text background. |
| [getCharacterCellWidth()](#getCharacterCellWidth--) | Gets or sets the character cell width, in pixels, of each cell in the grid. |
| [setCharacterCellWidth(byte value)](#setCharacterCellWidth-byte-) | Gets or sets the character cell width, in pixels, of each cell in the grid. |
| [getCharacterCellHeight()](#getCharacterCellHeight--) | Gets or sets the character cell height, in pixels, of each cell in the grid. |
| [setCharacterCellHeight(byte value)](#setCharacterCellHeight-byte-) | Gets or sets the character cell height, in pixels, of each cell in the grid. |
| [getTextGridLeftPosition()](#getTextGridLeftPosition--) | Gets or sets the text grid left position. |
| [setTextGridLeftPosition(int value)](#setTextGridLeftPosition-int-) | Gets or sets the text grid left position. |
| [getTextGridTopPosition()](#getTextGridTopPosition--) | Gets or sets the text grid top position. |
| [setTextGridTopPosition(int value)](#setTextGridTopPosition-int-) | Gets or sets the text grid top position. |
| [getTextGridWidth()](#getTextGridWidth--) | Gets or sets the text grid with in pixels |
| [setTextGridWidth(int value)](#setTextGridWidth-int-) | Gets or sets the text grid with in pixels |
| [getTextGridHeight()](#getTextGridHeight--) | Gets or sets the text grid height in pixels |
| [setTextGridHeight(int value)](#setTextGridHeight-int-) | Gets or sets the text grid height in pixels |
| [getPlainTextData()](#getPlainTextData--) | Gets or sets the plain text data. |
| [setPlainTextData(byte[] value)](#setPlainTextData-byte---) | Gets or sets the plain text data. |
### GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock--}
```
public GifPlainTextRenderingBlock()
```


Initializes a new instance of the `GifPlainTextRenderingBlock` class.

### GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data) {#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---}
```
public GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)
```


Initializes a new instance of the `GifPlainTextRenderingBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textGridLeftPosition | int | The text grid left position. |
| textGridTopPosition | int | The text grid top position. |
| textGridWidth | int | The text grid width. |
| textGridHeight | int | The text grid height. |
| characterCellWidth | byte | The character cell width. |
| characterCellHeight | byte | The character cell height. |
| textForegroundColorIndex | byte | The foreground color index. |
| textBackgroundColorIndex | byte | The background color index. |
| data | byte[] | The plain text data. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


The plain text extension label.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


The size of the sub block.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


The overall block size.

### getTextForegroundColorIndex() {#getTextForegroundColorIndex--}
```
public byte getTextForegroundColorIndex()
```


Gets or sets the index of the color in the global color palette used to draw the text foreground.

Value: The foreground color index.

**Returns:**
byte
### setTextForegroundColorIndex(byte value) {#setTextForegroundColorIndex-byte-}
```
public void setTextForegroundColorIndex(byte value)
```


Gets or sets the index of the color in the global color palette used to draw the text foreground.

Value: The foreground color index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextBackgroundColorIndex() {#getTextBackgroundColorIndex--}
```
public byte getTextBackgroundColorIndex()
```


Gets or sets the index of the color in the global color palette used to draw the text background.

Value: The background color index.

**Returns:**
byte
### setTextBackgroundColorIndex(byte value) {#setTextBackgroundColorIndex-byte-}
```
public void setTextBackgroundColorIndex(byte value)
```


Gets or sets the index of the color in the global color palette used to draw the text background.

Value: The background color index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCharacterCellWidth() {#getCharacterCellWidth--}
```
public byte getCharacterCellWidth()
```


Gets or sets the character cell width, in pixels, of each cell in the grid.

Value: The character cell width.

**Returns:**
byte
### setCharacterCellWidth(byte value) {#setCharacterCellWidth-byte-}
```
public void setCharacterCellWidth(byte value)
```


Gets or sets the character cell width, in pixels, of each cell in the grid.

Value: The character cell width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCharacterCellHeight() {#getCharacterCellHeight--}
```
public byte getCharacterCellHeight()
```


Gets or sets the character cell height, in pixels, of each cell in the grid.

Value: The character cell height.

**Returns:**
byte
### setCharacterCellHeight(byte value) {#setCharacterCellHeight-byte-}
```
public void setCharacterCellHeight(byte value)
```


Gets or sets the character cell height, in pixels, of each cell in the grid.

Value: The character cell height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextGridLeftPosition() {#getTextGridLeftPosition--}
```
public int getTextGridLeftPosition()
```


Gets or sets the text grid left position.

Value: The text grid left position.

This is a column number, in pixels, of the left edge of the text grid, with respect to the left edge of the logical screen.

**Returns:**
int
### setTextGridLeftPosition(int value) {#setTextGridLeftPosition-int-}
```
public void setTextGridLeftPosition(int value)
```


Gets or sets the text grid left position.

Value: The text grid left position.

This is a column number, in pixels, of the left edge of the text grid, with respect to the left edge of the logical screen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextGridTopPosition() {#getTextGridTopPosition--}
```
public int getTextGridTopPosition()
```


Gets or sets the text grid top position.

Value: The text grid top position.

This is a row number, in pixels, of the top edge of the text grid, with respect to the top edge of the logical screen.

**Returns:**
int
### setTextGridTopPosition(int value) {#setTextGridTopPosition-int-}
```
public void setTextGridTopPosition(int value)
```


Gets or sets the text grid top position.

Value: The text grid top position.

This is a row number, in pixels, of the top edge of the text grid, with respect to the top edge of the logical screen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextGridWidth() {#getTextGridWidth--}
```
public int getTextGridWidth()
```


Gets or sets the text grid with in pixels

Value: The text grid width in pixels.

**Returns:**
int
### setTextGridWidth(int value) {#setTextGridWidth-int-}
```
public void setTextGridWidth(int value)
```


Gets or sets the text grid with in pixels

Value: The text grid width in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextGridHeight() {#getTextGridHeight--}
```
public int getTextGridHeight()
```


Gets or sets the text grid height in pixels

Value: The text grid height in pixels.

**Returns:**
int
### setTextGridHeight(int value) {#setTextGridHeight-int-}
```
public void setTextGridHeight(int value)
```


Gets or sets the text grid height in pixels

Value: The text grid height in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlainTextData() {#getPlainTextData--}
```
public byte[] getPlainTextData()
```


Gets or sets the plain text data.

Value: The plain text data.

**Returns:**
byte[]
### setPlainTextData(byte[] value) {#setPlainTextData-byte---}
```
public void setPlainTextData(byte[] value)
```


Gets or sets the plain text data.

Value: The plain text data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

