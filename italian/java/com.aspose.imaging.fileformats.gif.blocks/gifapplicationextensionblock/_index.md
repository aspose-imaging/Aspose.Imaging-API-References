---
title: "GifApplicationExtensionBlock"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Blocco di estensione dell'applicazione Gif."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifApplicationExtensionBlock extends GifBlock
```

Blocco di estensione dell'applicazione Gif.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock--) | Inizializza una nuova istanza della classe `GifApplicationExtensionBlock`. |
| [GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)](#GifApplicationExtensionBlock-java.lang.String-byte---byte---) | Inizializza una nuova istanza della classe `GifApplicationExtensionBlock`. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Specifica la dimensione dell'intestazione del blocco. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Etichetta dell'estensione. |
| [BLOCK_SIZE](#BLOCK-SIZE) | Dimensione del blocco nome estensione + versione |
| [APPLICATION_IDENTIFIER_SIZE](#APPLICATION-IDENTIFIER-SIZE) | Specifica la dimensione dell'identificatore dell'applicazione. |
| [APPLICATION_AUTHENTICATION_CODE_SIZE](#APPLICATION-AUTHENTICATION-CODE-SIZE) | Specifica la dimensione del codice di autenticazione dell'applicazione. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getApplicationAuthenticationCode()](#getApplicationAuthenticationCode--) | Ottiene o imposta il codice di autenticazione dell'applicazione. |
| [setApplicationAuthenticationCode(byte[] value)](#setApplicationAuthenticationCode-byte---) | Ottiene o imposta il codice di autenticazione dell'applicazione. |
| [getApplicationIdentifier()](#getApplicationIdentifier--) | Ottiene o imposta l'identificatore dell'applicazione. |
| [setApplicationIdentifier(String value)](#setApplicationIdentifier-java.lang.String-) | Ottiene o imposta l'identificatore dell'applicazione. |
| [getApplicationData()](#getApplicationData--) | Ottiene o imposta i dati dell'applicazione. |
| [setApplicationData(byte[] value)](#setApplicationData-byte---) | Ottiene o imposta i dati dell'applicazione. |
### GifApplicationExtensionBlock() {#GifApplicationExtensionBlock--}
```
public GifApplicationExtensionBlock()
```


Inizializza una nuova istanza della classe `GifApplicationExtensionBlock`.

### GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData) {#GifApplicationExtensionBlock-java.lang.String-byte---byte---}
```
public GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)
```


Inizializza una nuova istanza della classe `GifApplicationExtensionBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| applicationIdentifier | java.lang.String | L'identificatore dell'applicazione. |
| applicationAuthenticationCode | byte[] | Il codice di autenticazione dell'applicazione. |
| applicationData | byte[] | I dati dell'applicazione. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Specifica la dimensione dell'intestazione del blocco.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Etichetta dell'estensione.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


Dimensione del blocco nome estensione + versione

### APPLICATION_IDENTIFIER_SIZE {#APPLICATION-IDENTIFIER-SIZE}
```
public static final int APPLICATION_IDENTIFIER_SIZE
```


Specifica la dimensione dell'identificatore dell'applicazione.

### APPLICATION_AUTHENTICATION_CODE_SIZE {#APPLICATION-AUTHENTICATION-CODE-SIZE}
```
public static final int APPLICATION_AUTHENTICATION_CODE_SIZE
```


Specifica la dimensione del codice di autenticazione dell'applicazione.

### getApplicationAuthenticationCode() {#getApplicationAuthenticationCode--}
```
public byte[] getApplicationAuthenticationCode()
```


Ottiene o imposta il codice di autenticazione dell'applicazione.

Valore: Il codice di autenticazione dell'applicazione.

**Returns:**
byte[]
### setApplicationAuthenticationCode(byte[] value) {#setApplicationAuthenticationCode-byte---}
```
public void setApplicationAuthenticationCode(byte[] value)
```


Ottiene o imposta il codice di autenticazione dell'applicazione.

Valore: Il codice di autenticazione dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getApplicationIdentifier() {#getApplicationIdentifier--}
```
public String getApplicationIdentifier()
```


Ottiene o imposta l'identificatore dell'applicazione.

Valore: L'identificatore dell'applicazione.

**Returns:**
java.lang.String
### setApplicationIdentifier(String value) {#setApplicationIdentifier-java.lang.String-}
```
public void setApplicationIdentifier(String value)
```


Ottiene o imposta l'identificatore dell'applicazione.

Valore: L'identificatore dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getApplicationData() {#getApplicationData--}
```
public byte[] getApplicationData()
```


Ottiene o imposta i dati dell'applicazione.

Valore: I dati dell'applicazione.

**Returns:**
byte[]
### setApplicationData(byte[] value) {#setApplicationData-byte---}
```
public void setApplicationData(byte[] value)
```


Ottiene o imposta i dati dell'applicazione.

Valore: I dati dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

