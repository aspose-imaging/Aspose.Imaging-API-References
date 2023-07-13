---
title: GifGraphicsControlBlock Class
type: docs
weight: 40
url: /python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---

Gif graphics control block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifGraphicsControlBlock

**Inheritance:** IGifBlock, GifBlock

**Aspose.Imaging Version:** 23.6

The GifGraphicsControlBlock type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock__0) | Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class. |
| [GifGraphicsControlBlock(flags, delay_time, transparent_color_index)](#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_1) | Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class. |
| [GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method)](#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2) | Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| is_changed | bool | r/w | Gets or sets a value indicating whether block has changed and requires save. |
| EXTENSION_INTRODUCER [static] | byte | r | Extension introducer. |
| delay_time | ushort | r/w | Gets or sets the frame delay time expressed in 1/100 seconds. |
| flags | byte | r/w | Gets or sets the flags. |
| transparent_color_index | byte | r/w | Gets or sets the transparent color index. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod) | r/w | Gets or sets the disposal method. |
| user_input_expected | bool | r/w | Gets or sets a value indicating whether user input is expected. |
| has_transparent_color | bool | r/w | Gets or sets a value indicating whether graphics control block has transparent color. |
| BLOCK_HEADER_SIZE [static] | int | r | Specifies the block header size. |
| EXTENSION_LABEL [static] | byte | r | Extension label. |
| SUB_BLOCK_SIZE [static] | byte | r | Gets the sub-block size. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_3) | Saves the block to the specified stream. |
| [create_flags(has_transparent_color, requires_user_input, disposal_method)](#create_flags_has_transparent_color_requires_user_input_disposal_method_4) | Creates the flags. |

### GifGraphicsControlBlock() {#GifGraphicsControlBlock__0}


```
 GifGraphicsControlBlock() 
```

Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class.

### GifGraphicsControlBlock(flags, delay_time, transparent_color_index) {#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_1}


```
 GifGraphicsControlBlock(flags, delay_time, transparent_color_index) 
```

Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| flags | byte | The flags. |
| delay_time | ushort | The delay time expressed in 1/100 seconds. |
| transparent_color_index | byte | The transparent color index. |

### GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) {#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2}


```
 GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) 
```

Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| delay_time | ushort | The delay time expressed in 1/100 seconds. |
| has_transparent_color | bool | if set to <c>true</c> the <paramref name="transparentColorIndex" /> is valid. |
| transparent_color_index | byte | The transparent color index. |
| requires_user_input | bool | if set to <c>true</c> the user input is expected. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod) | The disposal method. |

### save(stream) {#save_stream_3}


```
 save(stream) 
```

Saves the block to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save data to. |

### create_flags(has_transparent_color, requires_user_input, disposal_method)  [static] {#create_flags_has_transparent_color_requires_user_input_disposal_method_4}


```
 create_flags(has_transparent_color, requires_user_input, disposal_method) 
```

Creates the flags.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| has_transparent_color | bool | if set to <c>true</c> the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) has valid transparent color index. |
| requires_user_input | bool | if set to <c>true</c> the user input is expected. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod) | The disposal method. |

**Returns**

| Type | Description |
| :- | :- |
| byte | The generated flags. |


