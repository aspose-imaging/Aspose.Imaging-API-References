---
title: "GifUnknownExtensionBlock-klass"
type: docs
weight: 60
url: /sv/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/
---

**Summary:** Gif Unknown Extension Block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifUnknownExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifUnknownExtensionBlock()](#GifUnknownExtensionBlock__1) | Initierar en ny instans av klassen [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/). |
| [GifUnknownExtensionBlock(extension_label, data)](#GifUnknownExtensionBlock_extension_label_data_2) | Initierar en ny instans av klassen [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EXTENSION_INTRODUCER [statisk] | System.Byte | r | Extension‑introducer. |
| extension_label | System.Byte | r/w | Hämtar eller anger blockets extensionsetikett. |
| is_changed | bool | r/w | Hämtar eller anger ett värde som indikerar om blocket har ändrats och kräver sparning. |
| unknown_data | System.Byte | r/w | Hämtar eller anger den okända datan. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Sparar blocket till den angivna strömmen. |


### Constructor: GifUnknownExtensionBlock() {#GifUnknownExtensionBlock__1}


```
 GifUnknownExtensionBlock() 
```

Initierar en ny instans av klassen [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/).

### Constructor: GifUnknownExtensionBlock(extension_label, data) {#GifUnknownExtensionBlock_extension_label_data_2}


```
 GifUnknownExtensionBlock(extension_label, data) 
```

Initierar en ny instans av klassen [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extension_label | System.Byte | Extensionsetiketten. |
| data | System.Byte | Blockdata. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Sparar blocket till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara data till. |

