---
title: "GifUnknownExtensionBlock 类"
type: docs
weight: 60
url: /zh/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/
---

**Summary:** Gif Unknown Extension Block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifUnknownExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [GifUnknownExtensionBlock()](#GifUnknownExtensionBlock__1) | 初始化 [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/) 类的新实例。 |
| [GifUnknownExtensionBlock(extension_label, data)](#GifUnknownExtensionBlock_extension_label_data_2) | 初始化 [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| EXTENSION_INTRODUCER [static] | System.Byte | r | 扩展引入器。 |
| extension_label | System.Byte | r/w | 获取或设置块的扩展标签。 |
| is_changed | bool | r/w | 获取或设置一个值，指示块是否已更改并需要保存。 |
| unknown_data | System.Byte | r/w | 获取或设置未知数据。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [save(stream)](#save_stream_1) | 将块保存到指定的流。 |


### Constructor: GifUnknownExtensionBlock() {#GifUnknownExtensionBlock__1}


```
 GifUnknownExtensionBlock() 
```

初始化 [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/) 类的新实例。

### Constructor: GifUnknownExtensionBlock(extension_label, data) {#GifUnknownExtensionBlock_extension_label_data_2}


```
 GifUnknownExtensionBlock(extension_label, data) 
```

初始化 [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| extension_label | System.Byte | 扩展标签。 |
| 数据 | System.Byte | 块数据。 |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

将块保存到指定的流。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存数据的流。 |

