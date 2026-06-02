---
title: "GifPlainTextRenderingBlock"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Bloque de extensión de texto plano Gif."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifPlainTextRenderingBlock extends GifBlock
```

Bloque de extensión de texto plano Gif. La extensión de texto plano contiene datos textuales y los parámetros necesarios para representar esos datos como un gráfico, en una forma simple.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock--) | Inicializa una nueva instancia de la clase `GifPlainTextRenderingBlock`. |
| [GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)](#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---) | Inicializa una nueva instancia de la clase `GifPlainTextRenderingBlock`. |
## Campos

| Campo | Descripción |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | La etiqueta de extensión de texto plano. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | El tamaño del subbloque. |
| [BLOCK_SIZE](#BLOCK-SIZE) | El tamaño total del bloque. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTextForegroundColorIndex()](#getTextForegroundColorIndex--) | Obtiene o establece el índice del color en la paleta de colores global utilizada para dibujar el primer plano del texto. |
| [setTextForegroundColorIndex(byte value)](#setTextForegroundColorIndex-byte-) | Obtiene o establece el índice del color en la paleta de colores global utilizada para dibujar el primer plano del texto. |
| [getTextBackgroundColorIndex()](#getTextBackgroundColorIndex--) | Obtiene o establece el índice del color en la paleta de colores global utilizada para dibujar el fondo del texto. |
| [setTextBackgroundColorIndex(byte value)](#setTextBackgroundColorIndex-byte-) | Obtiene o establece el índice del color en la paleta de colores global utilizada para dibujar el fondo del texto. |
| [getCharacterCellWidth()](#getCharacterCellWidth--) | Obtiene o establece el ancho de la celda de caracteres, en píxeles, de cada celda en la cuadrícula. |
| [setCharacterCellWidth(byte value)](#setCharacterCellWidth-byte-) | Obtiene o establece el ancho de la celda de caracteres, en píxeles, de cada celda en la cuadrícula. |
| [getCharacterCellHeight()](#getCharacterCellHeight--) | Obtiene o establece la altura de la celda de caracteres, en píxeles, de cada celda en la cuadrícula. |
| [setCharacterCellHeight(byte value)](#setCharacterCellHeight-byte-) | Obtiene o establece la altura de la celda de caracteres, en píxeles, de cada celda en la cuadrícula. |
| [getTextGridLeftPosition()](#getTextGridLeftPosition--) | Obtiene o establece la posición izquierda de la cuadrícula de texto. |
| [setTextGridLeftPosition(int value)](#setTextGridLeftPosition-int-) | Obtiene o establece la posición izquierda de la cuadrícula de texto. |
| [getTextGridTopPosition()](#getTextGridTopPosition--) | Obtiene o establece la posición superior de la cuadrícula de texto. |
| [setTextGridTopPosition(int value)](#setTextGridTopPosition-int-) | Obtiene o establece la posición superior de la cuadrícula de texto. |
| [getTextGridWidth()](#getTextGridWidth--) | Obtiene o establece la cuadrícula de texto con en píxeles |
| [setTextGridWidth(int value)](#setTextGridWidth-int-) | Obtiene o establece la cuadrícula de texto con en píxeles |
| [getTextGridHeight()](#getTextGridHeight--) | Obtiene o establece la altura de la cuadrícula de texto en píxeles |
| [setTextGridHeight(int value)](#setTextGridHeight-int-) | Obtiene o establece la altura de la cuadrícula de texto en píxeles |
| [getPlainTextData()](#getPlainTextData--) | Obtiene o establece los datos de texto sin formato. |
| [setPlainTextData(byte[] value)](#setPlainTextData-byte---) | Obtiene o establece los datos de texto sin formato. |
### GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock--}
```
public GifPlainTextRenderingBlock()
```


Inicializa una nueva instancia de la clase `GifPlainTextRenderingBlock`.

### GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data) {#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---}
```
public GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)
```


Inicializa una nueva instancia de la clase `GifPlainTextRenderingBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textGridLeftPosition | int | La posición izquierda de la cuadrícula de texto. |
| textGridTopPosition | int | La posición superior de la cuadrícula de texto. |
| textGridWidth | int | El ancho de la cuadrícula de texto. |
| textGridHeight | int | La altura de la cuadrícula de texto. |
| characterCellWidth | byte | El ancho de la celda de caracteres. |
| characterCellHeight | byte | La altura de la celda de caracteres. |
| textForegroundColorIndex | byte | El índice del color de primer plano. |
| textBackgroundColorIndex | byte | El índice de color de fondo. |
| datos | byte[] | Los datos de texto sin formato. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


La etiqueta de extensión de texto plano.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


El tamaño del subbloque.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


El tamaño total del bloque.

### getTextForegroundColorIndex() {#getTextForegroundColorIndex--}
```
public byte getTextForegroundColorIndex()
```


Obtiene o establece el índice del color en la paleta de colores global utilizada para dibujar el primer plano del texto.

Valor: El índice de color de primer plano.

**Returns:**
byte
### setTextForegroundColorIndex(byte value) {#setTextForegroundColorIndex-byte-}
```
public void setTextForegroundColorIndex(byte value)
```


Obtiene o establece el índice del color en la paleta de colores global utilizada para dibujar el primer plano del texto.

Valor: El índice de color de primer plano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getTextBackgroundColorIndex() {#getTextBackgroundColorIndex--}
```
public byte getTextBackgroundColorIndex()
```


Obtiene o establece el índice del color en la paleta de colores global utilizada para dibujar el fondo del texto.

Valor: El índice de color de fondo.

**Returns:**
byte
### setTextBackgroundColorIndex(byte value) {#setTextBackgroundColorIndex-byte-}
```
public void setTextBackgroundColorIndex(byte value)
```


Obtiene o establece el índice del color en la paleta de colores global utilizada para dibujar el fondo del texto.

Valor: El índice de color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCharacterCellWidth() {#getCharacterCellWidth--}
```
public byte getCharacterCellWidth()
```


Obtiene o establece el ancho de la celda de caracteres, en píxeles, de cada celda en la cuadrícula.

Valor: El ancho de la celda de carácter.

**Returns:**
byte
### setCharacterCellWidth(byte value) {#setCharacterCellWidth-byte-}
```
public void setCharacterCellWidth(byte value)
```


Obtiene o establece el ancho de la celda de caracteres, en píxeles, de cada celda en la cuadrícula.

Valor: El ancho de la celda de carácter.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCharacterCellHeight() {#getCharacterCellHeight--}
```
public byte getCharacterCellHeight()
```


Obtiene o establece la altura de la celda de caracteres, en píxeles, de cada celda en la cuadrícula.

Valor: La altura de la celda de carácter.

**Returns:**
byte
### setCharacterCellHeight(byte value) {#setCharacterCellHeight-byte-}
```
public void setCharacterCellHeight(byte value)
```


Obtiene o establece la altura de la celda de caracteres, en píxeles, de cada celda en la cuadrícula.

Valor: La altura de la celda de carácter.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getTextGridLeftPosition() {#getTextGridLeftPosition--}
```
public int getTextGridLeftPosition()
```


Obtiene o establece la posición izquierda de la cuadrícula de texto.

Valor: La posición izquierda de la cuadrícula de texto.

Este es un número de columna, en píxeles, del borde izquierdo de la cuadrícula de texto, con respecto al borde izquierdo de la pantalla lógica.

**Returns:**
int
### setTextGridLeftPosition(int value) {#setTextGridLeftPosition-int-}
```
public void setTextGridLeftPosition(int value)
```


Obtiene o establece la posición izquierda de la cuadrícula de texto.

Valor: La posición izquierda de la cuadrícula de texto.

Este es un número de columna, en píxeles, del borde izquierdo de la cuadrícula de texto, con respecto al borde izquierdo de la pantalla lógica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTextGridTopPosition() {#getTextGridTopPosition--}
```
public int getTextGridTopPosition()
```


Obtiene o establece la posición superior de la cuadrícula de texto.

Valor: La posición superior de la cuadrícula de texto.

Este es un número de fila, en píxeles, del borde superior de la cuadrícula de texto, con respecto al borde superior de la pantalla lógica.

**Returns:**
int
### setTextGridTopPosition(int value) {#setTextGridTopPosition-int-}
```
public void setTextGridTopPosition(int value)
```


Obtiene o establece la posición superior de la cuadrícula de texto.

Valor: La posición superior de la cuadrícula de texto.

Este es un número de fila, en píxeles, del borde superior de la cuadrícula de texto, con respecto al borde superior de la pantalla lógica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTextGridWidth() {#getTextGridWidth--}
```
public int getTextGridWidth()
```


Obtiene o establece la cuadrícula de texto con en píxeles

Valor: El ancho de la cuadrícula de texto en píxeles.

**Returns:**
int
### setTextGridWidth(int value) {#setTextGridWidth-int-}
```
public void setTextGridWidth(int value)
```


Obtiene o establece la cuadrícula de texto con en píxeles

Valor: El ancho de la cuadrícula de texto en píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTextGridHeight() {#getTextGridHeight--}
```
public int getTextGridHeight()
```


Obtiene o establece la altura de la cuadrícula de texto en píxeles

Valor: La altura de la cuadrícula de texto en píxeles.

**Returns:**
int
### setTextGridHeight(int value) {#setTextGridHeight-int-}
```
public void setTextGridHeight(int value)
```


Obtiene o establece la altura de la cuadrícula de texto en píxeles

Valor: La altura de la cuadrícula de texto en píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPlainTextData() {#getPlainTextData--}
```
public byte[] getPlainTextData()
```


Obtiene o establece los datos de texto sin formato.

Valor: Los datos de texto sin formato.

**Returns:**
byte[]
### setPlainTextData(byte[] value) {#setPlainTextData-byte---}
```
public void setPlainTextData(byte[] value)
```


Obtiene o establece los datos de texto sin formato.

Valor: Los datos de texto sin formato.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

