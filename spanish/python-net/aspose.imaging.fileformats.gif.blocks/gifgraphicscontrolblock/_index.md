---
title: "Clase GifGraphicsControlBlock"
type: docs
weight: 40
url: /es/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---

**Summary:** Gif graphics control block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifGraphicsControlBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock__1) | Inicializa una nueva instancia de la clase [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
| [GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method)](#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2) | Inicializa una nueva instancia de la clase [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
| [GifGraphicsControlBlock(flags, delay_time, transparent_color_index)](#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3) | Inicializa una nueva instancia de la clase [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Especifica el tamaño del encabezado del bloque. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introducción de extensión. |
| EXTENSION_LABEL [static] | System.Byte | r | Etiqueta de la extensión. |
| SUB_BLOCK_SIZE [estático] | System.Byte | r | Obtiene el tamaño del subbloque. |
| delay_time | int | r/w | Obtiene o establece el tiempo de retardo del fotograma expresado en 1/100 segundos. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | r/w | Obtiene o establece el método de eliminación. |
| banderas | System.Byte | r/w | Obtiene o establece las banderas. |
| has_transparent_color | bool | r/w | Obtiene o establece un valor que indica si el bloque de control gráfico tiene color transparente. |
| is_changed | bool | r/w | Obtiene o establece un valor que indica si el bloque ha cambiado y requiere guardado. |
| transparent_color_index | System.Byte | r/w | Obtiene o establece el índice de color transparente. |
| user_input_expected | bool | r/w | Obtiene o establece un valor que indica si se espera la entrada del usuario. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_flags(has_transparent_color, requires_user_input, disposal_method)](#create_flags_has_transparent_color_requires_user_input_disposal_method_1) | Crea las banderas. |
| [save(stream)](#save_stream_2) | Guarda el bloque en el flujo especificado. |


### Constructor: GifGraphicsControlBlock() {#GifGraphicsControlBlock__1}


```
 GifGraphicsControlBlock() 
```

Inicializa una nueva instancia de la clase [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

### Constructor: GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) {#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2}


```
 GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) 
```

Inicializa una nueva instancia de la clase [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| delay_time | int | El tiempo de retardo expresado en centésimas de segundo. |
| has_transparent_color | bool | si se establece en <c>true</c> el _transparentColorIndex_ es válido. |
| transparent_color_index | System.Byte | El índice de color transparente. |
| requires_user_input | bool | si se establece en <c>true</c> se espera la entrada del usuario. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | El método de eliminación. |

### Constructor: GifGraphicsControlBlock(flags, delay_time, transparent_color_index) {#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3}


```
 GifGraphicsControlBlock(flags, delay_time, transparent_color_index) 
```

Inicializa una nueva instancia de la clase [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| banderas | System.Byte | Los indicadores. |
| delay_time | int | El tiempo de retardo expresado en centésimas de segundo. |
| transparent_color_index | System.Byte | El índice de color transparente. |

### Method: create_flags(has_transparent_color, requires_user_input, disposal_method)  [static] {#create_flags_has_transparent_color_requires_user_input_disposal_method_1}


```
 create_flags(has_transparent_color, requires_user_input, disposal_method) 
```

Crea las banderas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| has_transparent_color | bool | si se establece en <c>true</c> el [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) tiene un índice de color transparente válido. |
| requires_user_input | bool | si se establece en <c>true</c> se espera la entrada del usuario. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | El método de eliminación. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Byte | Los indicadores generados. |


### Method: save(stream) {#save_stream_2}


```
 save(stream) 
```

Guarda el bloque en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos. |

