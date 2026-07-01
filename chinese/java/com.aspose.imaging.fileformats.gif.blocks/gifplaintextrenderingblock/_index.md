---
title: "GifPlainTextRenderingBlock"
second_title: "Aspose.Imaging for Java API 参考"
description: "Gif 纯文本扩展块。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifPlainTextRenderingBlock extends GifBlock
```

Gif 纯文本扩展块。纯文本扩展包含文本数据以及将这些数据渲染为图形所需的参数，形式简洁。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock--) | 初始化 `GifPlainTextRenderingBlock` 类的新实例。 |
| [GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)](#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---) | 初始化 `GifPlainTextRenderingBlock` 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | 纯文本扩展标签。 |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | 子块的大小。 |
| [BLOCK_SIZE](#BLOCK-SIZE) | 整体块的大小。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextForegroundColorIndex()](#getTextForegroundColorIndex--) | 获取或设置用于绘制文本前景的全局颜色调色板中颜色的索引。 |
| [setTextForegroundColorIndex(byte value)](#setTextForegroundColorIndex-byte-) | 获取或设置用于绘制文本前景的全局颜色调色板中颜色的索引。 |
| [getTextBackgroundColorIndex()](#getTextBackgroundColorIndex--) | 获取或设置用于绘制文本背景的全局颜色调色板中颜色的索引。 |
| [setTextBackgroundColorIndex(byte value)](#setTextBackgroundColorIndex-byte-) | 获取或设置用于绘制文本背景的全局颜色调色板中颜色的索引。 |
| [getCharacterCellWidth()](#getCharacterCellWidth--) | 获取或设置网格中每个单元格的字符单元宽度（像素）。 |
| [setCharacterCellWidth(byte value)](#setCharacterCellWidth-byte-) | 获取或设置网格中每个单元格的字符单元宽度（像素）。 |
| [getCharacterCellHeight()](#getCharacterCellHeight--) | 获取或设置网格中每个单元格的字符单元高度（像素）。 |
| [setCharacterCellHeight(byte value)](#setCharacterCellHeight-byte-) | 获取或设置网格中每个单元格的字符单元高度（像素）。 |
| [getTextGridLeftPosition()](#getTextGridLeftPosition--) | 获取或设置文本网格的左侧位置。 |
| [setTextGridLeftPosition(int value)](#setTextGridLeftPosition-int-) | 获取或设置文本网格的左侧位置。 |
| [getTextGridTopPosition()](#getTextGridTopPosition--) | 获取或设置文本网格的顶部位置。 |
| [setTextGridTopPosition(int value)](#setTextGridTopPosition-int-) | 获取或设置文本网格的顶部位置。 |
| [getTextGridWidth()](#getTextGridWidth--) | 获取或设置文本网格的宽度（像素） |
| [setTextGridWidth(int value)](#setTextGridWidth-int-) | 获取或设置文本网格的宽度（像素） |
| [getTextGridHeight()](#getTextGridHeight--) | 获取或设置文本网格的高度（像素） |
| [setTextGridHeight(int value)](#setTextGridHeight-int-) | 获取或设置文本网格的高度（像素） |
| [getPlainTextData()](#getPlainTextData--) | 获取或设置纯文本数据。 |
| [setPlainTextData(byte[] value)](#setPlainTextData-byte---) | 获取或设置纯文本数据。 |
### GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock--}
```
public GifPlainTextRenderingBlock()
```


初始化 `GifPlainTextRenderingBlock` 类的新实例。

### GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data) {#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---}
```
public GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)
```


初始化 `GifPlainTextRenderingBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textGridLeftPosition | int | 文本网格左侧位置。 |
| textGridTopPosition | int | 文本网格顶部位置。 |
| textGridWidth | int | 文本网格宽度。 |
| textGridHeight | int | 文本网格高度。 |
| characterCellWidth | byte | 字符单元格宽度。 |
| characterCellHeight | byte | 字符单元格高度。 |
| textForegroundColorIndex | byte | 前景色索引。 |
| textBackgroundColorIndex | byte | 背景色索引。 |
| 数据 | byte[] | 纯文本数据。 |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


纯文本扩展标签。

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


子块的大小。

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


整体块的大小。

### getTextForegroundColorIndex() {#getTextForegroundColorIndex--}
```
public byte getTextForegroundColorIndex()
```


获取或设置用于绘制文本前景的全局颜色调色板中颜色的索引。

值：前景色索引。

**Returns:**
byte
### setTextForegroundColorIndex(byte value) {#setTextForegroundColorIndex-byte-}
```
public void setTextForegroundColorIndex(byte value)
```


获取或设置用于绘制文本前景的全局颜色调色板中颜色的索引。

值：前景色索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getTextBackgroundColorIndex() {#getTextBackgroundColorIndex--}
```
public byte getTextBackgroundColorIndex()
```


获取或设置用于绘制文本背景的全局颜色调色板中颜色的索引。

值：背景色索引。

**Returns:**
byte
### setTextBackgroundColorIndex(byte value) {#setTextBackgroundColorIndex-byte-}
```
public void setTextBackgroundColorIndex(byte value)
```


获取或设置用于绘制文本背景的全局颜色调色板中颜色的索引。

值：背景色索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCharacterCellWidth() {#getCharacterCellWidth--}
```
public byte getCharacterCellWidth()
```


获取或设置网格中每个单元格的字符单元宽度（像素）。

值：字符单元格宽度。

**Returns:**
byte
### setCharacterCellWidth(byte value) {#setCharacterCellWidth-byte-}
```
public void setCharacterCellWidth(byte value)
```


获取或设置网格中每个单元格的字符单元宽度（像素）。

值：字符单元格宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCharacterCellHeight() {#getCharacterCellHeight--}
```
public byte getCharacterCellHeight()
```


获取或设置网格中每个单元格的字符单元高度（像素）。

值：字符单元格高度。

**Returns:**
byte
### setCharacterCellHeight(byte value) {#setCharacterCellHeight-byte-}
```
public void setCharacterCellHeight(byte value)
```


获取或设置网格中每个单元格的字符单元高度（像素）。

值：字符单元格高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getTextGridLeftPosition() {#getTextGridLeftPosition--}
```
public int getTextGridLeftPosition()
```


获取或设置文本网格的左侧位置。

值：文本网格左侧位置。

这是文本网格左边缘相对于逻辑屏幕左边缘的列号（单位为像素）。

**Returns:**
int
### setTextGridLeftPosition(int value) {#setTextGridLeftPosition-int-}
```
public void setTextGridLeftPosition(int value)
```


获取或设置文本网格的左侧位置。

值：文本网格左侧位置。

这是文本网格左边缘相对于逻辑屏幕左边缘的列号（单位为像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTextGridTopPosition() {#getTextGridTopPosition--}
```
public int getTextGridTopPosition()
```


获取或设置文本网格的顶部位置。

值：文本网格顶部位置。

这是文本网格顶部相对于逻辑屏幕顶部的行号（单位为像素）。

**Returns:**
int
### setTextGridTopPosition(int value) {#setTextGridTopPosition-int-}
```
public void setTextGridTopPosition(int value)
```


获取或设置文本网格的顶部位置。

值：文本网格顶部位置。

这是文本网格顶部相对于逻辑屏幕顶部的行号（单位为像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTextGridWidth() {#getTextGridWidth--}
```
public int getTextGridWidth()
```


获取或设置文本网格的宽度（像素）

值：文本网格宽度（像素）。

**Returns:**
int
### setTextGridWidth(int value) {#setTextGridWidth-int-}
```
public void setTextGridWidth(int value)
```


获取或设置文本网格的宽度（像素）

值：文本网格宽度（像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTextGridHeight() {#getTextGridHeight--}
```
public int getTextGridHeight()
```


获取或设置文本网格的高度（像素）

值：文本网格高度（像素）。

**Returns:**
int
### setTextGridHeight(int value) {#setTextGridHeight-int-}
```
public void setTextGridHeight(int value)
```


获取或设置文本网格的高度（像素）

值：文本网格高度（像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPlainTextData() {#getPlainTextData--}
```
public byte[] getPlainTextData()
```


获取或设置纯文本数据。

值：纯文本数据。

**Returns:**
byte[]
### setPlainTextData(byte[] value) {#setPlainTextData-byte---}
```
public void setPlainTextData(byte[] value)
```


获取或设置纯文本数据。

值：纯文本数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

