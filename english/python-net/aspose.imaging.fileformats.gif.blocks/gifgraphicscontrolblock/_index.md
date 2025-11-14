---
title: GifGraphicsControlBlock Class
type: docs
weight: 40
url: /python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---

**Summary:** Gif graphics control block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifGraphicsControlBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock__1) | Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class. |
| [GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method)](#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2) | Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class. |
| [GifGraphicsControlBlock(flags, delay_time, transparent_color_index)](#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3) | Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Specifies the block header size. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Extension introducer. |
| EXTENSION_LABEL [static] | System.Byte | r | Extension label. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | Gets the sub-block size. |
| delay_time | int | r/w | Gets or sets the frame delay time expressed in 1/100 seconds. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | r/w | Gets or sets the disposal method. |
| flags | System.Byte | r/w | Gets or sets the flags. |
| has_transparent_color | bool | r/w | Gets or sets a value indicating whether graphics control block has transparent color. |
| is_changed | bool | r/w | Gets or sets a value indicating whether block has changed and requires save. |
| transparent_color_index | System.Byte | r/w | Gets or sets the transparent color index. |
| user_input_expected | bool | r/w | Gets or sets a value indicating whether user input is expected. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_flags(has_transparent_color, requires_user_input, disposal_method)](#create_flags_has_transparent_color_requires_user_input_disposal_method_1) | Creates the flags. |
| [save(stream)](#save_stream_2) | Saves the block to the specified stream. |


### Constructor: GifGraphicsControlBlock() {#GifGraphicsControlBlock__1}


```
 GifGraphicsControlBlock() 
```

Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class.

### Constructor: GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) {#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2}


```
 GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) 
```

Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| delay_time | int | The delay time expressed in 1/100 seconds. |
| has_transparent_color | bool | if set to <c>true</c> the _transparentColorIndex_ is valid. |
| transparent_color_index | System.Byte | The transparent color index. |
| requires_user_input | bool | if set to <c>true</c> the user input is expected. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | The disposal method. |

### Constructor: GifGraphicsControlBlock(flags, delay_time, transparent_color_index) {#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3}


```
 GifGraphicsControlBlock(flags, delay_time, transparent_color_index) 
```

Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| flags | System.Byte | The flags. |
| delay_time | int | The delay time expressed in 1/100 seconds. |
| transparent_color_index | System.Byte | The transparent color index. |

### Method: create_flags(has_transparent_color, requires_user_input, disposal_method)  [static] {#create_flags_has_transparent_color_requires_user_input_disposal_method_1}


```
 create_flags(has_transparent_color, requires_user_input, disposal_method) 
```

Creates the flags.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| has_transparent_color | bool | if set to <c>true</c> the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) has valid transparent color index. |
| requires_user_input | bool | if set to <c>true</c> the user input is expected. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | The disposal method. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | The generated flags. |


### Method: save(stream) {#save_stream_2}


```
 save(stream) 
```

Saves the block to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save data to. |

