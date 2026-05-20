---
title: "GifApplicationExtensionBlock"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Gif-Anwendungserweiterungsblock."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifApplicationExtensionBlock extends GifBlock
```

Gif-Anwendungserweiterungsblock.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock--) | Initialisiert eine neue Instanz der Klasse `GifApplicationExtensionBlock`. |
| [GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)](#GifApplicationExtensionBlock-java.lang.String-byte---byte---) | Initialisiert eine neue Instanz der Klasse `GifApplicationExtensionBlock`. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Gibt die Größe des Blockkopfes an. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Erweiterungsbezeichnung. |
| [BLOCK_SIZE](#BLOCK-SIZE) | Erweiterungsname + Versionsblockgröße |
| [APPLICATION_IDENTIFIER_SIZE](#APPLICATION-IDENTIFIER-SIZE) | Gibt die Größe des Anwendungsidentifikators an. |
| [APPLICATION_AUTHENTICATION_CODE_SIZE](#APPLICATION-AUTHENTICATION-CODE-SIZE) | Gibt die Größe des Anwendungsauthentifizierungscodes an. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getApplicationAuthenticationCode()](#getApplicationAuthenticationCode--) | Liest oder setzt den Anwendungsauthentifizierungscode. |
| [setApplicationAuthenticationCode(byte[] value)](#setApplicationAuthenticationCode-byte---) | Liest oder setzt den Anwendungsauthentifizierungscode. |
| [getApplicationIdentifier()](#getApplicationIdentifier--) | Liest oder setzt die Anwendungskennung. |
| [setApplicationIdentifier(String value)](#setApplicationIdentifier-java.lang.String-) | Liest oder setzt die Anwendungskennung. |
| [getApplicationData()](#getApplicationData--) | Liest oder setzt die Anwendungsdaten. |
| [setApplicationData(byte[] value)](#setApplicationData-byte---) | Liest oder setzt die Anwendungsdaten. |
### GifApplicationExtensionBlock() {#GifApplicationExtensionBlock--}
```
public GifApplicationExtensionBlock()
```


Initialisiert eine neue Instanz der Klasse `GifApplicationExtensionBlock`.

### GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData) {#GifApplicationExtensionBlock-java.lang.String-byte---byte---}
```
public GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)
```


Initialisiert eine neue Instanz der Klasse `GifApplicationExtensionBlock`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| applicationIdentifier | java.lang.String | Die Anwendungskennung. |
| applicationAuthenticationCode | byte[] | Der Authentifizierungscode der Anwendung. |
| applicationData | byte[] | Die Anwendungsdaten. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Gibt die Größe des Blockkopfes an.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Erweiterungsbezeichnung.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


Erweiterungsname + Versionsblockgröße

### APPLICATION_IDENTIFIER_SIZE {#APPLICATION-IDENTIFIER-SIZE}
```
public static final int APPLICATION_IDENTIFIER_SIZE
```


Gibt die Größe des Anwendungsidentifikators an.

### APPLICATION_AUTHENTICATION_CODE_SIZE {#APPLICATION-AUTHENTICATION-CODE-SIZE}
```
public static final int APPLICATION_AUTHENTICATION_CODE_SIZE
```


Gibt die Größe des Anwendungsauthentifizierungscodes an.

### getApplicationAuthenticationCode() {#getApplicationAuthenticationCode--}
```
public byte[] getApplicationAuthenticationCode()
```


Liest oder setzt den Anwendungsauthentifizierungscode.

Wert: Der Authentifizierungscode der Anwendung.

**Returns:**
byte[]
### setApplicationAuthenticationCode(byte[] value) {#setApplicationAuthenticationCode-byte---}
```
public void setApplicationAuthenticationCode(byte[] value)
```


Liest oder setzt den Anwendungsauthentifizierungscode.

Wert: Der Authentifizierungscode der Anwendung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getApplicationIdentifier() {#getApplicationIdentifier--}
```
public String getApplicationIdentifier()
```


Liest oder setzt die Anwendungskennung.

Wert: Die Anwendungskennung.

**Returns:**
java.lang.String
### setApplicationIdentifier(String value) {#setApplicationIdentifier-java.lang.String-}
```
public void setApplicationIdentifier(String value)
```


Liest oder setzt die Anwendungskennung.

Wert: Die Anwendungskennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getApplicationData() {#getApplicationData--}
```
public byte[] getApplicationData()
```


Liest oder setzt die Anwendungsdaten.

Wert: Die Anwendungsdaten.

**Returns:**
byte[]
### setApplicationData(byte[] value) {#setApplicationData-byte---}
```
public void setApplicationData(byte[] value)
```


Liest oder setzt die Anwendungsdaten.

Wert: Die Anwendungsdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

