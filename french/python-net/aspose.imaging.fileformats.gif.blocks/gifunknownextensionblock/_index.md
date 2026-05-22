---
title: "GifUnknownExtensionBlock Classe"
type: docs
weight: 60
url: /fr/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/
---

**Summary:** Gif Unknown Extension Block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifUnknownExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifUnknownExtensionBlock()](#GifUnknownExtensionBlock__1) | Initialise une nouvelle instance de la classe [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/). |
| [GifUnknownExtensionBlock(extension_label, data)](#GifUnknownExtensionBlock_extension_label_data_2) | Initialise une nouvelle instance de la classe [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introduiseur d'extension. |
| extension_label | System.Byte | r/w | Obtient ou définit le libellé d'extension du bloc. |
| is_changed | bool | r/w | Obtient ou définit une valeur indiquant si le bloc a changé et nécessite une sauvegarde. |
| unknown_data | System.Byte | r/w | Obtient ou définit les données inconnues. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Enregistre le bloc dans le flux spécifié. |


### Constructor: GifUnknownExtensionBlock() {#GifUnknownExtensionBlock__1}


```
 GifUnknownExtensionBlock() 
```

Initialise une nouvelle instance de la classe [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/).

### Constructor: GifUnknownExtensionBlock(extension_label, data) {#GifUnknownExtensionBlock_extension_label_data_2}


```
 GifUnknownExtensionBlock(extension_label, data) 
```

Initialise une nouvelle instance de la classe [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| extension_label | System.Byte | Le libellé d'extension. |
| données | System.Byte | Les données du bloc. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Enregistre le bloc dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données. |

