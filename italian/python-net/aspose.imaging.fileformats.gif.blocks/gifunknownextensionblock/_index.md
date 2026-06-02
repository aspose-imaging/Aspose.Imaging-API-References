---
title: "GifUnknownExtensionBlock Classe"
type: docs
weight: 60
url: /it/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/
---

**Summary:** Gif Unknown Extension Block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifUnknownExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [GifUnknownExtensionBlock()](#GifUnknownExtensionBlock__1) | Inizializza una nuova istanza della classe [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/). |
| [GifUnknownExtensionBlock(extension_label, data)](#GifUnknownExtensionBlock_extension_label_data_2) | Inizializza una nuova istanza della classe [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introduttore di estensione. |
| extension_label | System.Byte | r/w | Ottiene o imposta l'etichetta di estensione del blocco. |
| is_changed | bool | r/w | Ottiene o imposta un valore che indica se il blocco è stato modificato e richiede il salvataggio. |
| unknown_data | System.Byte | r/w | Ottiene o imposta i dati sconosciuti. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [save(stream)](#save_stream_1) | Salva il blocco nello stream specificato. |


### Constructor: GifUnknownExtensionBlock() {#GifUnknownExtensionBlock__1}


```
 GifUnknownExtensionBlock() 
```

Inizializza una nuova istanza della classe [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/).

### Constructor: GifUnknownExtensionBlock(extension_label, data) {#GifUnknownExtensionBlock_extension_label_data_2}


```
 GifUnknownExtensionBlock(extension_label, data) 
```

Inizializza una nuova istanza della classe [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extension_label | System.Byte | L'etichetta di estensione. |
| dati | System.Byte | I dati del blocco. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Salva il blocco nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |

