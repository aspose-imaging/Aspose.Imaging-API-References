---
title: "Clase GifUnknownExtensionBlock"
type: docs
weight: 60
url: /es/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/
---

**Summary:** Gif Unknown Extension Block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifUnknownExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GifUnknownExtensionBlock()](#GifUnknownExtensionBlock__1) | Inicializa una nueva instancia de la clase [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/). |
| [GifUnknownExtensionBlock(extension_label, data)](#GifUnknownExtensionBlock_extension_label_data_2) | Inicializa una nueva instancia de la clase [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introducción de extensión. |
| extension_label | System.Byte | r/w | Obtiene o establece la etiqueta de extensión del bloque. |
| is_changed | bool | r/w | Obtiene o establece un valor que indica si el bloque ha cambiado y requiere guardado. |
| unknown_data | System.Byte | r/w | Obtiene o establece los datos desconocidos. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream)](#save_stream_1) | Guarda el bloque en el flujo especificado. |


### Constructor: GifUnknownExtensionBlock() {#GifUnknownExtensionBlock__1}


```
 GifUnknownExtensionBlock() 
```

Inicializa una nueva instancia de la clase [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/).

### Constructor: GifUnknownExtensionBlock(extension_label, data) {#GifUnknownExtensionBlock_extension_label_data_2}


```
 GifUnknownExtensionBlock(extension_label, data) 
```

Inicializa una nueva instancia de la clase [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extension_label | System.Byte | La etiqueta de extensión. |
| datos | System.Byte | Los datos del bloque. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Guarda el bloque en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos. |

