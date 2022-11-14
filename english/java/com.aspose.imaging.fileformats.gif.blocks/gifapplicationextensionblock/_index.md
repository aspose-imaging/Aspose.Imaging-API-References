---
title: GifApplicationExtensionBlock
second_title: Aspose.Imaging for Java API Reference
description: Gif application extension block.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifApplicationExtensionBlock extends GifBlock
```

Gif application extension block.
## Constructors

| Constructor | Description |
| --- | --- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock--) | Initializes a new instance of the `GifApplicationExtensionBlock` class. |
| [GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)](#GifApplicationExtensionBlock-java.lang.String-byte---byte---) | Initializes a new instance of the `GifApplicationExtensionBlock` class. |
## Fields

| Field | Description |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Specifies the block header size. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Extension label. |
| [BLOCK_SIZE](#BLOCK-SIZE) | Extension name + version block size |
| [APPLICATION_IDENTIFIER_SIZE](#APPLICATION-IDENTIFIER-SIZE) | Specifies the application identifier size. |
| [APPLICATION_AUTHENTICATION_CODE_SIZE](#APPLICATION-AUTHENTICATION-CODE-SIZE) | Specifies the application authentication code size. |
## Methods

| Method | Description |
| --- | --- |
| [getApplicationAuthenticationCode()](#getApplicationAuthenticationCode--) | Gets or sets the application authentication code. |
| [setApplicationAuthenticationCode(byte[] value)](#setApplicationAuthenticationCode-byte---) | Gets or sets the application authentication code. |
| [getApplicationIdentifier()](#getApplicationIdentifier--) | Gets or sets the application identifier. |
| [setApplicationIdentifier(String value)](#setApplicationIdentifier-java.lang.String-) | Gets or sets the application identifier. |
| [getApplicationData()](#getApplicationData--) | Gets or sets the application data. |
| [setApplicationData(byte[] value)](#setApplicationData-byte---) | Gets or sets the application data. |
### GifApplicationExtensionBlock() {#GifApplicationExtensionBlock--}
```
public GifApplicationExtensionBlock()
```


Initializes a new instance of the `GifApplicationExtensionBlock` class.

### GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData) {#GifApplicationExtensionBlock-java.lang.String-byte---byte---}
```
public GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)
```


Initializes a new instance of the `GifApplicationExtensionBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| applicationIdentifier | java.lang.String | The application identifier. |
| applicationAuthenticationCode | byte[] | The application authentication code. |
| applicationData | byte[] | The application data. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Specifies the block header size.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Extension label.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


Extension name + version block size

### APPLICATION_IDENTIFIER_SIZE {#APPLICATION-IDENTIFIER-SIZE}
```
public static final int APPLICATION_IDENTIFIER_SIZE
```


Specifies the application identifier size.

### APPLICATION_AUTHENTICATION_CODE_SIZE {#APPLICATION-AUTHENTICATION-CODE-SIZE}
```
public static final int APPLICATION_AUTHENTICATION_CODE_SIZE
```


Specifies the application authentication code size.

### getApplicationAuthenticationCode() {#getApplicationAuthenticationCode--}
```
public byte[] getApplicationAuthenticationCode()
```


Gets or sets the application authentication code.

Value: The application authentication code.

**Returns:**
byte[]
### setApplicationAuthenticationCode(byte[] value) {#setApplicationAuthenticationCode-byte---}
```
public void setApplicationAuthenticationCode(byte[] value)
```


Gets or sets the application authentication code.

Value: The application authentication code.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getApplicationIdentifier() {#getApplicationIdentifier--}
```
public String getApplicationIdentifier()
```


Gets or sets the application identifier.

Value: The application identifier.

**Returns:**
java.lang.String
### setApplicationIdentifier(String value) {#setApplicationIdentifier-java.lang.String-}
```
public void setApplicationIdentifier(String value)
```


Gets or sets the application identifier.

Value: The application identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getApplicationData() {#getApplicationData--}
```
public byte[] getApplicationData()
```


Gets or sets the application data.

Value: The application data.

**Returns:**
byte[]
### setApplicationData(byte[] value) {#setApplicationData-byte---}
```
public void setApplicationData(byte[] value)
```


Gets or sets the application data.

Value: The application data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

