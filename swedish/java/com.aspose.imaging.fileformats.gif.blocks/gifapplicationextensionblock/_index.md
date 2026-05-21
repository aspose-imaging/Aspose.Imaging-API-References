---
title: "GifApplicationExtensionBlock"
second_title: "Aspose.Imaging för Java API-referens"
description: "Gif-applikationsutökning block."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifApplicationExtensionBlock extends GifBlock
```

Gif-applikationsutökning block.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock--) | Initierar en ny instans av klassen `GifApplicationExtensionBlock`. |
| [GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)](#GifApplicationExtensionBlock-java.lang.String-byte---byte---) | Initierar en ny instans av klassen `GifApplicationExtensionBlock`. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Anger blockhuvudets storlek. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Etikett för tillägg. |
| [BLOCK_SIZE](#BLOCK-SIZE) | Tilläggsnamn + versionsblockets storlek |
| [APPLICATION_IDENTIFIER_SIZE](#APPLICATION-IDENTIFIER-SIZE) | Anger storleken på programidentifieraren. |
| [APPLICATION_AUTHENTICATION_CODE_SIZE](#APPLICATION-AUTHENTICATION-CODE-SIZE) | Anger storleken på programautentiseringskoden. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getApplicationAuthenticationCode()](#getApplicationAuthenticationCode--) | Hämtar eller anger programautentiseringskoden. |
| [setApplicationAuthenticationCode(byte[] value)](#setApplicationAuthenticationCode-byte---) | Hämtar eller anger programautentiseringskoden. |
| [getApplicationIdentifier()](#getApplicationIdentifier--) | Hämtar eller anger programidentifieraren. |
| [setApplicationIdentifier(String value)](#setApplicationIdentifier-java.lang.String-) | Hämtar eller anger programidentifieraren. |
| [getApplicationData()](#getApplicationData--) | Hämtar eller anger programdata. |
| [setApplicationData(byte[] value)](#setApplicationData-byte---) | Hämtar eller anger programdata. |
### GifApplicationExtensionBlock() {#GifApplicationExtensionBlock--}
```
public GifApplicationExtensionBlock()
```


Initierar en ny instans av klassen `GifApplicationExtensionBlock`.

### GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData) {#GifApplicationExtensionBlock-java.lang.String-byte---byte---}
```
public GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)
```


Initierar en ny instans av klassen `GifApplicationExtensionBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| applicationIdentifier | java.lang.String | Programidentifieraren. |
| applicationAuthenticationCode | byte[] | Programautentiseringskoden. |
| applicationData | byte[] | Programdata. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Anger blockhuvudets storlek.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Etikett för tillägg.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


Tilläggsnamn + versionsblockets storlek

### APPLICATION_IDENTIFIER_SIZE {#APPLICATION-IDENTIFIER-SIZE}
```
public static final int APPLICATION_IDENTIFIER_SIZE
```


Anger storleken på programidentifieraren.

### APPLICATION_AUTHENTICATION_CODE_SIZE {#APPLICATION-AUTHENTICATION-CODE-SIZE}
```
public static final int APPLICATION_AUTHENTICATION_CODE_SIZE
```


Anger storleken på programautentiseringskoden.

### getApplicationAuthenticationCode() {#getApplicationAuthenticationCode--}
```
public byte[] getApplicationAuthenticationCode()
```


Hämtar eller anger programautentiseringskoden.

Värde: Programautentiseringskoden.

**Returns:**
byte[]
### setApplicationAuthenticationCode(byte[] value) {#setApplicationAuthenticationCode-byte---}
```
public void setApplicationAuthenticationCode(byte[] value)
```


Hämtar eller anger programautentiseringskoden.

Värde: Programautentiseringskoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getApplicationIdentifier() {#getApplicationIdentifier--}
```
public String getApplicationIdentifier()
```


Hämtar eller anger programidentifieraren.

Värde: Programidentifieraren.

**Returns:**
java.lang.String
### setApplicationIdentifier(String value) {#setApplicationIdentifier-java.lang.String-}
```
public void setApplicationIdentifier(String value)
```


Hämtar eller anger programidentifieraren.

Värde: Programidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getApplicationData() {#getApplicationData--}
```
public byte[] getApplicationData()
```


Hämtar eller anger programdata.

Värde: Programdata.

**Returns:**
byte[]
### setApplicationData(byte[] value) {#setApplicationData-byte---}
```
public void setApplicationData(byte[] value)
```


Hämtar eller anger programdata.

Värde: Programdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

