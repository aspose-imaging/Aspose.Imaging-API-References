---
title: "GifApplicationExtensionBlock"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Gif uygulama uzantı bloğu."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifApplicationExtensionBlock extends GifBlock
```

Gif uygulama uzantı bloğu.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock--) | `GifApplicationExtensionBlock` sınıfının yeni bir örneğini başlatır. |
| [GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)](#GifApplicationExtensionBlock-java.lang.String-byte---byte---) | `GifApplicationExtensionBlock` sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Blok başlık boyutunu belirtir. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Uzantı etiketi. |
| [BLOCK_SIZE](#BLOCK-SIZE) | Uzantı adı + sürüm blok boyutu |
| [APPLICATION_IDENTIFIER_SIZE](#APPLICATION-IDENTIFIER-SIZE) | Uygulama tanımlayıcı boyutunu belirtir. |
| [APPLICATION_AUTHENTICATION_CODE_SIZE](#APPLICATION-AUTHENTICATION-CODE-SIZE) | Uygulama kimlik doğrulama kodu boyutunu belirtir. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getApplicationAuthenticationCode()](#getApplicationAuthenticationCode--) | Uygulama kimlik doğrulama kodunu alır veya ayarlar. |
| [setApplicationAuthenticationCode(byte[] value)](#setApplicationAuthenticationCode-byte---) | Uygulama kimlik doğrulama kodunu alır veya ayarlar. |
| [getApplicationIdentifier()](#getApplicationIdentifier--) | Uygulama tanımlayıcısını alır veya ayarlar. |
| [setApplicationIdentifier(String value)](#setApplicationIdentifier-java.lang.String-) | Uygulama tanımlayıcısını alır veya ayarlar. |
| [getApplicationData()](#getApplicationData--) | Uygulama verisini alır veya ayarlar. |
| [setApplicationData(byte[] value)](#setApplicationData-byte---) | Uygulama verisini alır veya ayarlar. |
### GifApplicationExtensionBlock() {#GifApplicationExtensionBlock--}
```
public GifApplicationExtensionBlock()
```


`GifApplicationExtensionBlock` sınıfının yeni bir örneğini başlatır.

### GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData) {#GifApplicationExtensionBlock-java.lang.String-byte---byte---}
```
public GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)
```


`GifApplicationExtensionBlock` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| applicationIdentifier | java.lang.String | Uygulama tanımlayıcısı. |
| applicationAuthenticationCode | byte[] | Uygulama kimlik doğrulama kodu. |
| applicationData | byte[] | Uygulama verisi. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Blok başlık boyutunu belirtir.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Uzantı etiketi.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


Uzantı adı + sürüm blok boyutu

### APPLICATION_IDENTIFIER_SIZE {#APPLICATION-IDENTIFIER-SIZE}
```
public static final int APPLICATION_IDENTIFIER_SIZE
```


Uygulama tanımlayıcı boyutunu belirtir.

### APPLICATION_AUTHENTICATION_CODE_SIZE {#APPLICATION-AUTHENTICATION-CODE-SIZE}
```
public static final int APPLICATION_AUTHENTICATION_CODE_SIZE
```


Uygulama kimlik doğrulama kodu boyutunu belirtir.

### getApplicationAuthenticationCode() {#getApplicationAuthenticationCode--}
```
public byte[] getApplicationAuthenticationCode()
```


Uygulama kimlik doğrulama kodunu alır veya ayarlar.

Değer: Uygulama kimlik doğrulama kodu.

**Returns:**
byte[]
### setApplicationAuthenticationCode(byte[] value) {#setApplicationAuthenticationCode-byte---}
```
public void setApplicationAuthenticationCode(byte[] value)
```


Uygulama kimlik doğrulama kodunu alır veya ayarlar.

Değer: Uygulama kimlik doğrulama kodu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getApplicationIdentifier() {#getApplicationIdentifier--}
```
public String getApplicationIdentifier()
```


Uygulama tanımlayıcısını alır veya ayarlar.

Değer: Uygulama tanımlayıcısı.

**Returns:**
java.lang.String
### setApplicationIdentifier(String value) {#setApplicationIdentifier-java.lang.String-}
```
public void setApplicationIdentifier(String value)
```


Uygulama tanımlayıcısını alır veya ayarlar.

Değer: Uygulama tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getApplicationData() {#getApplicationData--}
```
public byte[] getApplicationData()
```


Uygulama verisini alır veya ayarlar.

Değer: Uygulama verisi.

**Returns:**
byte[]
### setApplicationData(byte[] value) {#setApplicationData-byte---}
```
public void setApplicationData(byte[] value)
```


Uygulama verisini alır veya ayarlar.

Değer: Uygulama verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

