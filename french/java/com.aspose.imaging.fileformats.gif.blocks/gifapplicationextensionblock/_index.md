---
title: "GifApplicationExtensionBlock"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Bloc d'extension d'application Gif."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifApplicationExtensionBlock extends GifBlock
```

Bloc d'extension d'application Gif.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock--) | Initialise une nouvelle instance de la classe `GifApplicationExtensionBlock`. |
| [GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)](#GifApplicationExtensionBlock-java.lang.String-byte---byte---) | Initialise une nouvelle instance de la classe `GifApplicationExtensionBlock`. |
## Champs

| Champ | Description |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Spécifie la taille de l'en-tête du bloc. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Étiquette d'extension. |
| [BLOCK_SIZE](#BLOCK-SIZE) | Taille du bloc du nom d'extension + version |
| [APPLICATION_IDENTIFIER_SIZE](#APPLICATION-IDENTIFIER-SIZE) | Spécifie la taille de l'identifiant de l'application. |
| [APPLICATION_AUTHENTICATION_CODE_SIZE](#APPLICATION-AUTHENTICATION-CODE-SIZE) | Spécifie la taille du code d'authentification de l'application. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getApplicationAuthenticationCode()](#getApplicationAuthenticationCode--) | Obtient ou définit le code d'authentification de l'application. |
| [setApplicationAuthenticationCode(byte[] value)](#setApplicationAuthenticationCode-byte---) | Obtient ou définit le code d'authentification de l'application. |
| [getApplicationIdentifier()](#getApplicationIdentifier--) | Obtient ou définit l'identifiant de l'application. |
| [setApplicationIdentifier(String value)](#setApplicationIdentifier-java.lang.String-) | Obtient ou définit l'identifiant de l'application. |
| [getApplicationData()](#getApplicationData--) | Obtient ou définit les données de l'application. |
| [setApplicationData(byte[] value)](#setApplicationData-byte---) | Obtient ou définit les données de l'application. |
### GifApplicationExtensionBlock() {#GifApplicationExtensionBlock--}
```
public GifApplicationExtensionBlock()
```


Initialise une nouvelle instance de la classe `GifApplicationExtensionBlock`.

### GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData) {#GifApplicationExtensionBlock-java.lang.String-byte---byte---}
```
public GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)
```


Initialise une nouvelle instance de la classe `GifApplicationExtensionBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| applicationIdentifier | java.lang.String | L'identifiant de l'application. |
| applicationAuthenticationCode | byte[] | Le code d'authentification de l'application. |
| applicationData | byte[] | Les données de l'application. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Spécifie la taille de l'en-tête du bloc.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Étiquette d'extension.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


Taille du bloc du nom d'extension + version

### APPLICATION_IDENTIFIER_SIZE {#APPLICATION-IDENTIFIER-SIZE}
```
public static final int APPLICATION_IDENTIFIER_SIZE
```


Spécifie la taille de l'identifiant de l'application.

### APPLICATION_AUTHENTICATION_CODE_SIZE {#APPLICATION-AUTHENTICATION-CODE-SIZE}
```
public static final int APPLICATION_AUTHENTICATION_CODE_SIZE
```


Spécifie la taille du code d'authentification de l'application.

### getApplicationAuthenticationCode() {#getApplicationAuthenticationCode--}
```
public byte[] getApplicationAuthenticationCode()
```


Obtient ou définit le code d'authentification de l'application.

Valeur: le code d'authentification de l'application.

**Returns:**
byte[]
### setApplicationAuthenticationCode(byte[] value) {#setApplicationAuthenticationCode-byte---}
```
public void setApplicationAuthenticationCode(byte[] value)
```


Obtient ou définit le code d'authentification de l'application.

Valeur: le code d'authentification de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getApplicationIdentifier() {#getApplicationIdentifier--}
```
public String getApplicationIdentifier()
```


Obtient ou définit l'identifiant de l'application.

Valeur: l'identifiant de l'application.

**Returns:**
java.lang.String
### setApplicationIdentifier(String value) {#setApplicationIdentifier-java.lang.String-}
```
public void setApplicationIdentifier(String value)
```


Obtient ou définit l'identifiant de l'application.

Valeur: l'identifiant de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getApplicationData() {#getApplicationData--}
```
public byte[] getApplicationData()
```


Obtient ou définit les données de l'application.

Valeur: les données de l'application.

**Returns:**
byte[]
### setApplicationData(byte[] value) {#setApplicationData-byte---}
```
public void setApplicationData(byte[] value)
```


Obtient ou définit les données de l'application.

Valeur: les données de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

