---
title: "Clase GifApplicationExtensionBlock"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---

**Summary:** Gif application extension block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifApplicationExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock__1) | Inicializa una nueva instancia de la clase [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/). |
| [GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data)](#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2) | Inicializa una nueva instancia de la clase [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| APPLICATION_AUTHENTICATION_CODE_SIZE [static] | int | r | Especifica el tamaño del código de autenticación de la aplicación. |
| APPLICATION_IDENTIFIER_SIZE [static] | int | r | Especifica el tamaño del identificador de la aplicación. |
| BLOCK_HEADER_SIZE [static] | int | r | Especifica el tamaño del encabezado del bloque. |
| BLOCK_SIZE [static] | System.Byte | r | Tamaño del bloque de nombre + versión de la extensión |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introducción de extensión. |
| EXTENSION_LABEL [static] | System.Byte | r | Etiqueta de la extensión. |
| application_authentication_code | System.Byte | r/w | Obtiene o establece el código de autenticación de la aplicación. |
| application_data | System.Byte | r/w | Obtiene o establece los datos de la aplicación. |
| application_identifier | string | r/w | Obtiene o establece el identificador de la aplicación. |
| is_changed | bool | r/w | Obtiene o establece un valor que indica si el bloque ha cambiado y requiere guardado. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream)](#save_stream_1) | Guarda el bloque en el flujo especificado. |


### Constructor: GifApplicationExtensionBlock() {#GifApplicationExtensionBlock__1}


```
 GifApplicationExtensionBlock() 
```

Inicializa una nueva instancia de la clase [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/).

### Constructor: GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) {#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2}


```
 GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) 
```

Inicializa una nueva instancia de la clase [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| application_identifier | string | El identificador de la aplicación. |
| application_authentication_code | System.Byte | El código de autenticación de la aplicación. |
| application_data | System.Byte | Los datos de la aplicación. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Guarda el bloque en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos. |

