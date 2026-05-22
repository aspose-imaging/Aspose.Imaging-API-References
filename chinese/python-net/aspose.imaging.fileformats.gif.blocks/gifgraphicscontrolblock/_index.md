---
title: "GifGraphicsControlBlock 类"
type: docs
weight: 40
url: /zh/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---

**Summary:** Gif graphics control block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifGraphicsControlBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock__1) | 初始化 [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) 类的新实例。 |
| [GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method)](#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2) | 初始化 [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) 类的新实例。 |
| [GifGraphicsControlBlock(flags, delay_time, transparent_color_index)](#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3) | 初始化 [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | 指定块头大小。 |
| EXTENSION_INTRODUCER [static] | System.Byte | r | 扩展引入器。 |
| EXTENSION_LABEL [static] | System.Byte | r | 扩展标签。 |
| SUB_BLOCK_SIZE [static] | System.Byte | r | 获取子块大小。 |
| delay_time | int | r/w | 获取或设置帧延迟时间，以 1/100 秒为单位。 |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | r/w | 获取或设置处理方法。 |
| flags | System.Byte | r/w | 获取或设置标志。 |
| has_transparent_color | bool | r/w | 获取或设置一个值，指示图形控制块是否具有透明颜色。 |
| is_changed | bool | r/w | 获取或设置一个值，指示块是否已更改并需要保存。 |
| transparent_color_index | System.Byte | r/w | 获取或设置透明颜色索引。 |
| user_input_expected | bool | r/w | 获取或设置一个值，指示是否需要用户输入。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_flags(has_transparent_color, requires_user_input, disposal_method)](#create_flags_has_transparent_color_requires_user_input_disposal_method_1) | 创建标志。 |
| [save(stream)](#save_stream_2) | 将块保存到指定的流。 |


### Constructor: GifGraphicsControlBlock() {#GifGraphicsControlBlock__1}


```
 GifGraphicsControlBlock() 
```

初始化 [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) 类的新实例。

### Constructor: GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) {#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2}


```
 GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) 
```

初始化 [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| delay_time | int | 延迟时间，以 1/100 秒为单位。 |
| has_transparent_color | bool | 如果设置为 <c>true</c>，则 _transparentColorIndex_ 有效。 |
| transparent_color_index | System.Byte | 透明颜色索引。 |
| requires_user_input | bool | 如果设置为 <c>true</c>，则需要用户输入。 |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | 处置方法。 |

### Constructor: GifGraphicsControlBlock(flags, delay_time, transparent_color_index) {#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3}


```
 GifGraphicsControlBlock(flags, delay_time, transparent_color_index) 
```

初始化 [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| flags | System.Byte | 标志。 |
| delay_time | int | 延迟时间，以 1/100 秒为单位。 |
| transparent_color_index | System.Byte | 透明颜色索引。 |

### Method: create_flags(has_transparent_color, requires_user_input, disposal_method)  [static] {#create_flags_has_transparent_color_requires_user_input_disposal_method_1}


```
 create_flags(has_transparent_color, requires_user_input, disposal_method) 
```

创建标志。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| has_transparent_color | bool | 如果设置为 <c>true</c>，则 [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) 具有有效的透明颜色索引。 |
| requires_user_input | bool | 如果设置为 <c>true</c>，则需要用户输入。 |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | 处置方法。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | 生成的标志。 |


### Method: save(stream) {#save_stream_2}


```
 save(stream) 
```

将块保存到指定的流。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存数据的流。 |

