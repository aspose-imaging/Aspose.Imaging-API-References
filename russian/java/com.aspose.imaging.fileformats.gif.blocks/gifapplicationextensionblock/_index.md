---
title: "GifApplicationExtensionBlock"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Блок расширения приложения Gif."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifApplicationExtensionBlock extends GifBlock
```

Блок расширения приложения Gif.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock--) | Инициализирует новый экземпляр класса `GifApplicationExtensionBlock`. |
| [GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)](#GifApplicationExtensionBlock-java.lang.String-byte---byte---) | Инициализирует новый экземпляр класса `GifApplicationExtensionBlock`. |
## Поля

| Поле | Описание |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Указывает размер заголовка блока. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Метка расширения. |
| [BLOCK_SIZE](#BLOCK-SIZE) | Размер блока имени расширения + версии |
| [APPLICATION_IDENTIFIER_SIZE](#APPLICATION-IDENTIFIER-SIZE) | Указывает размер идентификатора приложения. |
| [APPLICATION_AUTHENTICATION_CODE_SIZE](#APPLICATION-AUTHENTICATION-CODE-SIZE) | Указывает размер кода аутентификации приложения. |
## Методы

| Метод | Описание |
| --- | --- |
| [getApplicationAuthenticationCode()](#getApplicationAuthenticationCode--) | Получает или задает код аутентификации приложения. |
| [setApplicationAuthenticationCode(byte[] value)](#setApplicationAuthenticationCode-byte---) | Получает или задает код аутентификации приложения. |
| [getApplicationIdentifier()](#getApplicationIdentifier--) | Получает или задает идентификатор приложения. |
| [setApplicationIdentifier(String value)](#setApplicationIdentifier-java.lang.String-) | Получает или задает идентификатор приложения. |
| [getApplicationData()](#getApplicationData--) | Получает или задает данные приложения. |
| [setApplicationData(byte[] value)](#setApplicationData-byte---) | Получает или задает данные приложения. |
### GifApplicationExtensionBlock() {#GifApplicationExtensionBlock--}
```
public GifApplicationExtensionBlock()
```


Инициализирует новый экземпляр класса `GifApplicationExtensionBlock`.

### GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData) {#GifApplicationExtensionBlock-java.lang.String-byte---byte---}
```
public GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)
```


Инициализирует новый экземпляр класса `GifApplicationExtensionBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| applicationIdentifier | java.lang.String | Идентификатор приложения. |
| applicationAuthenticationCode | byte[] | Код аутентификации приложения. |
| applicationData | byte[] | Данные приложения. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Указывает размер заголовка блока.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Метка расширения.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


Размер блока имени расширения + версии

### APPLICATION_IDENTIFIER_SIZE {#APPLICATION-IDENTIFIER-SIZE}
```
public static final int APPLICATION_IDENTIFIER_SIZE
```


Указывает размер идентификатора приложения.

### APPLICATION_AUTHENTICATION_CODE_SIZE {#APPLICATION-AUTHENTICATION-CODE-SIZE}
```
public static final int APPLICATION_AUTHENTICATION_CODE_SIZE
```


Указывает размер кода аутентификации приложения.

### getApplicationAuthenticationCode() {#getApplicationAuthenticationCode--}
```
public byte[] getApplicationAuthenticationCode()
```


Получает или задает код аутентификации приложения.

Значение: Код аутентификации приложения.

**Returns:**
byte[]
### setApplicationAuthenticationCode(byte[] value) {#setApplicationAuthenticationCode-byte---}
```
public void setApplicationAuthenticationCode(byte[] value)
```


Получает или задает код аутентификации приложения.

Значение: Код аутентификации приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getApplicationIdentifier() {#getApplicationIdentifier--}
```
public String getApplicationIdentifier()
```


Получает или задает идентификатор приложения.

Значение: Идентификатор приложения.

**Returns:**
java.lang.String
### setApplicationIdentifier(String value) {#setApplicationIdentifier-java.lang.String-}
```
public void setApplicationIdentifier(String value)
```


Получает или задает идентификатор приложения.

Значение: Идентификатор приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getApplicationData() {#getApplicationData--}
```
public byte[] getApplicationData()
```


Получает или задает данные приложения.

Значение: Данные приложения.

**Returns:**
byte[]
### setApplicationData(byte[] value) {#setApplicationData-byte---}
```
public void setApplicationData(byte[] value)
```


Получает или задает данные приложения.

Значение: Данные приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

