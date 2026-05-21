---
title: "GifGraphicsControlBlock"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Bloque de control gráfico Gif."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifGraphicsControlBlock extends GifBlock
```

Bloque de control gráfico Gif.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock--) | Inicializa una nueva instancia de la clase `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)](#GifGraphicsControlBlock-byte-int-byte-) | Inicializa una nueva instancia de la clase `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)](#GifGraphicsControlBlock-int-boolean-byte-boolean-int-) | Inicializa una nueva instancia de la clase `GifGraphicsControlBlock`. |
## Campos

| Campo | Descripción |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Especifica el tamaño del encabezado del bloque. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Etiqueta de extensión. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | Obtiene el tamaño del subbloque. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDelayTime()](#getDelayTime--) | Obtiene o establece el tiempo de retardo del fotograma expresado en 1/100 segundos. |
| [setDelayTime(int value)](#setDelayTime-int-) | Obtiene o establece el tiempo de retardo del fotograma expresado en 1/100 segundos. |
| [getFlags()](#getFlags--) | Obtiene o establece las banderas. |
| [setFlags(byte value)](#setFlags-byte-) | Obtiene o establece las banderas. |
| [getTransparentColorIndex()](#getTransparentColorIndex--) | Obtiene o establece el índice de color transparente. |
| [setTransparentColorIndex(byte value)](#setTransparentColorIndex-byte-) | Obtiene o establece el índice de color transparente. |
| [getDisposalMethod()](#getDisposalMethod--) | Obtiene o establece el método de eliminación. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Obtiene o establece el método de eliminación. |
| [getUserInputExpected()](#getUserInputExpected--) | Obtiene o establece un valor que indica si se espera la entrada del usuario. |
| [setUserInputExpected(boolean value)](#setUserInputExpected-boolean-) | Obtiene o establece un valor que indica si se espera la entrada del usuario. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtiene o establece un valor que indica si el bloque de control gráfico tiene color transparente. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Obtiene o establece un valor que indica si el bloque de control gráfico tiene color transparente. |
| [createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)](#createFlags-boolean-boolean-int-) | Crea las banderas. |
### GifGraphicsControlBlock() {#GifGraphicsControlBlock--}
```
public GifGraphicsControlBlock()
```


Inicializa una nueva instancia de la clase `GifGraphicsControlBlock`.

### GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex) {#GifGraphicsControlBlock-byte-int-byte-}
```
public GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)
```


Inicializa una nueva instancia de la clase `GifGraphicsControlBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| banderas | byte | Los indicadores. |
| delayTime | int | El tiempo de retardo expresado en 1/100 segundos. |
| transparentColorIndex | byte | El índice de color transparente. |

### GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod) {#GifGraphicsControlBlock-int-boolean-byte-boolean-int-}
```
public GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)
```


Inicializa una nueva instancia de la clase `GifGraphicsControlBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| delayTime | int | El tiempo de retardo expresado en 1/100 segundos. |
| hasTransparentColor | boolean | si se establece en `true` el `transparentColorIndex` es válido. |
| transparentColorIndex | byte | El índice de color transparente. |
| requiresUserInput | boolean | si se establece en `true` se espera la entrada del usuario. |
| disposalMethod | int | El método de eliminación. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Especifica el tamaño del encabezado del bloque.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Etiqueta de extensión.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


Obtiene el tamaño del subbloque.

### getDelayTime() {#getDelayTime--}
```
public int getDelayTime()
```


Obtiene o establece el tiempo de retardo del fotograma expresado en 1/100 segundos.

**Returns:**
int
### setDelayTime(int value) {#setDelayTime-int-}
```
public void setDelayTime(int value)
```


Obtiene o establece el tiempo de retardo del fotograma expresado en 1/100 segundos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFlags() {#getFlags--}
```
public byte getFlags()
```


Obtiene o establece las banderas.

Valor: Los indicadores.

**Returns:**
byte
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Obtiene o establece las banderas.

Valor: Los indicadores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getTransparentColorIndex() {#getTransparentColorIndex--}
```
public byte getTransparentColorIndex()
```


Obtiene o establece el índice de color transparente.

Valor: El índice de color transparente.

**Returns:**
byte
### setTransparentColorIndex(byte value) {#setTransparentColorIndex-byte-}
```
public void setTransparentColorIndex(byte value)
```


Obtiene o establece el índice de color transparente.

Valor: El índice de color transparente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Obtiene o establece el método de eliminación.

Valor: El método de eliminación.

**Returns:**
int
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public void setDisposalMethod(int value)
```


Obtiene o establece el método de eliminación.

Valor: El método de eliminación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getUserInputExpected() {#getUserInputExpected--}
```
public boolean getUserInputExpected()
```


Obtiene o establece un valor que indica si se espera la entrada del usuario.

Valor: `true` si se espera la entrada del usuario; de lo contrario, `false`.

**Returns:**
boolean
### setUserInputExpected(boolean value) {#setUserInputExpected-boolean-}
```
public void setUserInputExpected(boolean value)
```


Obtiene o establece un valor que indica si se espera la entrada del usuario.

Valor: `true` si se espera la entrada del usuario; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtiene o establece un valor que indica si el bloque de control gráfico tiene color transparente.

Valor: `true` si el bloque de control gráfico tiene color transparente; de lo contrario, `false`.

**Returns:**
boolean
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Obtiene o establece un valor que indica si el bloque de control gráfico tiene color transparente.

Valor: `true` si el bloque de control gráfico tiene color transparente; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod) {#createFlags-boolean-boolean-int-}
```
public static byte createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)
```


Crea las banderas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hasTransparentColor | boolean | si se establece en `true` el `GifGraphicsControlBlock` tiene un índice de color transparente válido. |
| requiresUserInput | boolean | si se establece en `true` se espera la entrada del usuario. |
| disposalMethod | int | El método de eliminación. |

**Returns:**
byte - Los indicadores generados.
