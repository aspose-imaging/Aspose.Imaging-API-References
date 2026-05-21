---
title: "GifApplicationExtensionBlock"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Bloque de extensión de aplicación Gif."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifApplicationExtensionBlock extends GifBlock
```

Bloque de extensión de aplicación Gif.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock--) | Inicializa una nueva instancia de la clase `GifApplicationExtensionBlock`. |
| [GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)](#GifApplicationExtensionBlock-java.lang.String-byte---byte---) | Inicializa una nueva instancia de la clase `GifApplicationExtensionBlock`. |
## Campos

| Campo | Descripción |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Especifica el tamaño del encabezado del bloque. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Etiqueta de extensión. |
| [BLOCK_SIZE](#BLOCK-SIZE) | Tamaño del bloque de nombre de extensión + versión |
| [APPLICATION_IDENTIFIER_SIZE](#APPLICATION-IDENTIFIER-SIZE) | Especifica el tamaño del identificador de la aplicación. |
| [APPLICATION_AUTHENTICATION_CODE_SIZE](#APPLICATION-AUTHENTICATION-CODE-SIZE) | Especifica el tamaño del código de autenticación de la aplicación. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getApplicationAuthenticationCode()](#getApplicationAuthenticationCode--) | Obtiene o establece el código de autenticación de la aplicación. |
| [setApplicationAuthenticationCode(byte[] value)](#setApplicationAuthenticationCode-byte---) | Obtiene o establece el código de autenticación de la aplicación. |
| [getApplicationIdentifier()](#getApplicationIdentifier--) | Obtiene o establece el identificador de la aplicación. |
| [setApplicationIdentifier(String value)](#setApplicationIdentifier-java.lang.String-) | Obtiene o establece el identificador de la aplicación. |
| [getApplicationData()](#getApplicationData--) | Obtiene o establece los datos de la aplicación. |
| [setApplicationData(byte[] value)](#setApplicationData-byte---) | Obtiene o establece los datos de la aplicación. |
### GifApplicationExtensionBlock() {#GifApplicationExtensionBlock--}
```
public GifApplicationExtensionBlock()
```


Inicializa una nueva instancia de la clase `GifApplicationExtensionBlock`.

### GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData) {#GifApplicationExtensionBlock-java.lang.String-byte---byte---}
```
public GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)
```


Inicializa una nueva instancia de la clase `GifApplicationExtensionBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| applicationIdentifier | java.lang.String | El identificador de la aplicación. |
| applicationAuthenticationCode | byte[] | El código de autenticación de la aplicación. |
| applicationData | byte[] | Los datos de la aplicación. |

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

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


Tamaño del bloque de nombre de extensión + versión

### APPLICATION_IDENTIFIER_SIZE {#APPLICATION-IDENTIFIER-SIZE}
```
public static final int APPLICATION_IDENTIFIER_SIZE
```


Especifica el tamaño del identificador de la aplicación.

### APPLICATION_AUTHENTICATION_CODE_SIZE {#APPLICATION-AUTHENTICATION-CODE-SIZE}
```
public static final int APPLICATION_AUTHENTICATION_CODE_SIZE
```


Especifica el tamaño del código de autenticación de la aplicación.

### getApplicationAuthenticationCode() {#getApplicationAuthenticationCode--}
```
public byte[] getApplicationAuthenticationCode()
```


Obtiene o establece el código de autenticación de la aplicación.

Valor: El código de autenticación de la aplicación.

**Returns:**
byte[]
### setApplicationAuthenticationCode(byte[] value) {#setApplicationAuthenticationCode-byte---}
```
public void setApplicationAuthenticationCode(byte[] value)
```


Obtiene o establece el código de autenticación de la aplicación.

Valor: El código de autenticación de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getApplicationIdentifier() {#getApplicationIdentifier--}
```
public String getApplicationIdentifier()
```


Obtiene o establece el identificador de la aplicación.

Valor: El identificador de la aplicación.

**Returns:**
java.lang.String
### setApplicationIdentifier(String value) {#setApplicationIdentifier-java.lang.String-}
```
public void setApplicationIdentifier(String value)
```


Obtiene o establece el identificador de la aplicación.

Valor: El identificador de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getApplicationData() {#getApplicationData--}
```
public byte[] getApplicationData()
```


Obtiene o establece los datos de la aplicación.

Valor: Los datos de la aplicación.

**Returns:**
byte[]
### setApplicationData(byte[] value) {#setApplicationData-byte---}
```
public void setApplicationData(byte[] value)
```


Obtiene o establece los datos de la aplicación.

Valor: Los datos de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

