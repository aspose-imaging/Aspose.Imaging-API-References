---
title: GifUnknownExtensionBlock Class
type: docs
weight: 60
url: /python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/
---

Gif Unknown Extension Block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifUnknownExtensionBlock

**Inheritance:** IGifBlock, GifBlock

**Aspose.Imaging Version:** 23.6

The GifUnknownExtensionBlock type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [GifUnknownExtensionBlock()](#GifUnknownExtensionBlock__0) | Initializes a new instance of the [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/) class. |
| [GifUnknownExtensionBlock(extension_label, data)](#GifUnknownExtensionBlock_extension_label_data_1) | Initializes a new instance of the [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| is_changed | bool | r/w | Gets or sets a value indicating whether block has changed and requires save. |
| EXTENSION_INTRODUCER [static] | byte | r | Extension introducer. |
| extension_label | byte | r/w | Gets or sets the block's extension label. |
| unknown_data | byte | r/w | Gets or sets the unknown data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_2) | Saves the block to the specified stream. |

### GifUnknownExtensionBlock() {#GifUnknownExtensionBlock__0}


```
 GifUnknownExtensionBlock() 
```

Initializes a new instance of the [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/) class.

### GifUnknownExtensionBlock(extension_label, data) {#GifUnknownExtensionBlock_extension_label_data_1}


```
 GifUnknownExtensionBlock(extension_label, data) 
```

Initializes a new instance of the [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| extension_label | byte | The extension label. |
| data | byte | The block data. |

### save(stream) {#save_stream_2}


```
 save(stream) 
```

Saves the block to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save data to. |

