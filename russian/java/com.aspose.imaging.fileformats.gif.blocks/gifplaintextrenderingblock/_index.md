---
title: "GifPlainTextRenderingBlock"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Блок расширения простого текста Gif."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifPlainTextRenderingBlock extends GifBlock
```

Блок расширения простого текста Gif. Расширение простого текста содержит текстовые данные и параметры, необходимые для отображения этих данных в виде графики в простой форме.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock--) | Инициализирует новый экземпляр класса `GifPlainTextRenderingBlock`. |
| [GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)](#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---) | Инициализирует новый экземпляр класса `GifPlainTextRenderingBlock`. |
## Поля

| Поле | Описание |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Метка расширения простого текста. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | Размер субблока. |
| [BLOCK_SIZE](#BLOCK-SIZE) | Общий размер блока. |
## Методы

| Метод | Описание |
| --- | --- |
| [getTextForegroundColorIndex()](#getTextForegroundColorIndex--) | Получает или задает индекс цвета в глобальной палитре, используемый для отрисовки переднего плана текста. |
| [setTextForegroundColorIndex(byte value)](#setTextForegroundColorIndex-byte-) | Получает или задает индекс цвета в глобальной палитре, используемый для отрисовки переднего плана текста. |
| [getTextBackgroundColorIndex()](#getTextBackgroundColorIndex--) | Получает или задает индекс цвета в глобальной палитре, используемый для отрисовки фона текста. |
| [setTextBackgroundColorIndex(byte value)](#setTextBackgroundColorIndex-byte-) | Получает или задает индекс цвета в глобальной палитре, используемый для отрисовки фона текста. |
| [getCharacterCellWidth()](#getCharacterCellWidth--) | Получает или задает ширину ячейки символа в пикселях для каждой ячейки сетки. |
| [setCharacterCellWidth(byte value)](#setCharacterCellWidth-byte-) | Получает или задает ширину ячейки символа в пикселях для каждой ячейки сетки. |
| [getCharacterCellHeight()](#getCharacterCellHeight--) | Получает или задает высоту ячейки символа в пикселях для каждой ячейки сетки. |
| [setCharacterCellHeight(byte value)](#setCharacterCellHeight-byte-) | Получает или задает высоту ячейки символа в пикселях для каждой ячейки сетки. |
| [getTextGridLeftPosition()](#getTextGridLeftPosition--) | Получает или задает левую позицию текстовой сетки. |
| [setTextGridLeftPosition(int value)](#setTextGridLeftPosition-int-) | Получает или задает левую позицию текстовой сетки. |
| [getTextGridTopPosition()](#getTextGridTopPosition--) | Получает или задает верхнюю позицию текстовой сетки. |
| [setTextGridTopPosition(int value)](#setTextGridTopPosition-int-) | Получает или задает верхнюю позицию текстовой сетки. |
| [getTextGridWidth()](#getTextGridWidth--) | Получает или задает ширину текстовой сетки в пикселях |
| [setTextGridWidth(int value)](#setTextGridWidth-int-) | Получает или задает ширину текстовой сетки в пикселях |
| [getTextGridHeight()](#getTextGridHeight--) | Получает или задает высоту текстовой сетки в пикселях. |
| [setTextGridHeight(int value)](#setTextGridHeight-int-) | Получает или задает высоту текстовой сетки в пикселях. |
| [getPlainTextData()](#getPlainTextData--) | Получает или задает данные простого текста. |
| [setPlainTextData(byte[] value)](#setPlainTextData-byte---) | Получает или задает данные простого текста. |
### GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock--}
```
public GifPlainTextRenderingBlock()
```


Инициализирует новый экземпляр класса `GifPlainTextRenderingBlock`.

### GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data) {#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---}
```
public GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)
```


Инициализирует новый экземпляр класса `GifPlainTextRenderingBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| textGridLeftPosition | int | Левая позиция текстовой сетки. |
| textGridTopPosition | int | Верхняя позиция текстовой сетки. |
| textGridWidth | int | Ширина текстовой сетки. |
| textGridHeight | int | Высота текстовой сетки. |
| characterCellWidth | byte | Ширина ячейки символа. |
| characterCellHeight | byte | Высота ячейки символа. |
| textForegroundColorIndex | byte | Индекс цвета переднего плана. |
| textBackgroundColorIndex | byte | Индекс фонового цвета. |
| данные | byte[] | Данные простого текста. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Метка расширения простого текста.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


Размер субблока.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


Общий размер блока.

### getTextForegroundColorIndex() {#getTextForegroundColorIndex--}
```
public byte getTextForegroundColorIndex()
```


Получает или задает индекс цвета в глобальной палитре, используемый для отрисовки переднего плана текста.

Значение: Индекс цвета переднего плана.

**Returns:**
byte
### setTextForegroundColorIndex(byte value) {#setTextForegroundColorIndex-byte-}
```
public void setTextForegroundColorIndex(byte value)
```


Получает или задает индекс цвета в глобальной палитре, используемый для отрисовки переднего плана текста.

Значение: Индекс цвета переднего плана.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getTextBackgroundColorIndex() {#getTextBackgroundColorIndex--}
```
public byte getTextBackgroundColorIndex()
```


Получает или задает индекс цвета в глобальной палитре, используемый для отрисовки фона текста.

Значение: Индекс фонового цвета.

**Returns:**
byte
### setTextBackgroundColorIndex(byte value) {#setTextBackgroundColorIndex-byte-}
```
public void setTextBackgroundColorIndex(byte value)
```


Получает или задает индекс цвета в глобальной палитре, используемый для отрисовки фона текста.

Значение: Индекс фонового цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCharacterCellWidth() {#getCharacterCellWidth--}
```
public byte getCharacterCellWidth()
```


Получает или задает ширину ячейки символа в пикселях для каждой ячейки сетки.

Значение: Ширина ячейки символа.

**Returns:**
byte
### setCharacterCellWidth(byte value) {#setCharacterCellWidth-byte-}
```
public void setCharacterCellWidth(byte value)
```


Получает или задает ширину ячейки символа в пикселях для каждой ячейки сетки.

Значение: Ширина ячейки символа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCharacterCellHeight() {#getCharacterCellHeight--}
```
public byte getCharacterCellHeight()
```


Получает или задает высоту ячейки символа в пикселях для каждой ячейки сетки.

Значение: Высота ячейки символа.

**Returns:**
byte
### setCharacterCellHeight(byte value) {#setCharacterCellHeight-byte-}
```
public void setCharacterCellHeight(byte value)
```


Получает или задает высоту ячейки символа в пикселях для каждой ячейки сетки.

Значение: Высота ячейки символа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getTextGridLeftPosition() {#getTextGridLeftPosition--}
```
public int getTextGridLeftPosition()
```


Получает или задает левую позицию текстовой сетки.

Значение: Позиция слева сетки текста.

Это номер столбца в пикселях левого края сетки текста относительно левого края логического экрана.

**Returns:**
int
### setTextGridLeftPosition(int value) {#setTextGridLeftPosition-int-}
```
public void setTextGridLeftPosition(int value)
```


Получает или задает левую позицию текстовой сетки.

Значение: Позиция слева сетки текста.

Это номер столбца в пикселях левого края сетки текста относительно левого края логического экрана.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTextGridTopPosition() {#getTextGridTopPosition--}
```
public int getTextGridTopPosition()
```


Получает или задает верхнюю позицию текстовой сетки.

Значение: Позиция сверху сетки текста.

Это номер строки в пикселях верхнего края сетки текста относительно верхнего края логического экрана.

**Returns:**
int
### setTextGridTopPosition(int value) {#setTextGridTopPosition-int-}
```
public void setTextGridTopPosition(int value)
```


Получает или задает верхнюю позицию текстовой сетки.

Значение: Позиция сверху сетки текста.

Это номер строки в пикселях верхнего края сетки текста относительно верхнего края логического экрана.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTextGridWidth() {#getTextGridWidth--}
```
public int getTextGridWidth()
```


Получает или задает ширину текстовой сетки в пикселях

Значение: Ширина сетки текста в пикселях.

**Returns:**
int
### setTextGridWidth(int value) {#setTextGridWidth-int-}
```
public void setTextGridWidth(int value)
```


Получает или задает ширину текстовой сетки в пикселях

Значение: Ширина сетки текста в пикселях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTextGridHeight() {#getTextGridHeight--}
```
public int getTextGridHeight()
```


Получает или задает высоту текстовой сетки в пикселях.

Значение: Высота сетки текста в пикселях.

**Returns:**
int
### setTextGridHeight(int value) {#setTextGridHeight-int-}
```
public void setTextGridHeight(int value)
```


Получает или задает высоту текстовой сетки в пикселях.

Значение: Высота сетки текста в пикселях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPlainTextData() {#getPlainTextData--}
```
public byte[] getPlainTextData()
```


Получает или задает данные простого текста.

Значение: Данные простого текста.

**Returns:**
byte[]
### setPlainTextData(byte[] value) {#setPlainTextData-byte---}
```
public void setPlainTextData(byte[] value)
```


Получает или задает данные простого текста.

Значение: Данные простого текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

