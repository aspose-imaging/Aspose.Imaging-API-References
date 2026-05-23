---
title: "Classe GifApplicationExtensionBlock"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---

**Summary:** Gif application extension block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifApplicationExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock__1) | Inizializza una nuova istanza della classe [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/). |
| [GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data)](#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2) | Inizializza una nuova istanza della classe [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| APPLICATION_AUTHENTICATION_CODE_SIZE [static] | int | r | Specifica la dimensione del codice di autenticazione dell'applicazione. |
| APPLICATION_IDENTIFIER_SIZE [static] | int | r | Specifica la dimensione dell'identificatore dell'applicazione. |
| BLOCK_HEADER_SIZE [static] | int | r | Specifica la dimensione dell'intestazione del blocco. |
| BLOCK_SIZE [static] | System.Byte | r | Dimensione del blocco nome estensione + versione |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introduttore di estensione. |
| EXTENSION_LABEL [static] | System.Byte | r | Etichetta dell'estensione. |
| application_authentication_code | System.Byte | r/w | Ottiene o imposta il codice di autenticazione dell'applicazione. |
| application_data | System.Byte | r/w | Ottiene o imposta i dati dell'applicazione. |
| application_identifier | string | r/w | Ottiene o imposta l'identificatore dell'applicazione. |
| is_changed | bool | r/w | Ottiene o imposta un valore che indica se il blocco è stato modificato e richiede il salvataggio. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [save(stream)](#save_stream_1) | Salva il blocco nello stream specificato. |


### Constructor: GifApplicationExtensionBlock() {#GifApplicationExtensionBlock__1}


```
 GifApplicationExtensionBlock() 
```

Inizializza una nuova istanza della classe [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/).

### Constructor: GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) {#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2}


```
 GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) 
```

Inizializza una nuova istanza della classe [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| application_identifier | string | L'identificatore dell'applicazione. |
| application_authentication_code | System.Byte | Il codice di autenticazione dell'applicazione. |
| application_data | System.Byte | I dati dell'applicazione. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Salva il blocco nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |

