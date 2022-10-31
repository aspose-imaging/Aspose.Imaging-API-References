---
title: GifGraphicsControlBlock
second_title: Aspose.Imaging for Java API Reference
description: Gif graphics control block.
type: docs
weight: 13
url: /java/com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifGraphicsControlBlock extends GifBlock
```

Gif graphics control block.
## Constructors

| Constructor | Description |
| --- | --- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock--) | Initializes a new instance of the `GifGraphicsControlBlock` class. |
| [GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)](#GifGraphicsControlBlock-byte-int-byte-) | Initializes a new instance of the `GifGraphicsControlBlock` class. |
| [GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)](#GifGraphicsControlBlock-int-boolean-byte-boolean-int-) | Initializes a new instance of the `GifGraphicsControlBlock` class. |
## Fields

| Field | Description |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Specifies the block header size. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Extension label. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | Gets the sub-block size. |
## Methods

| Method | Description |
| --- | --- |
| [getDelayTime()](#getDelayTime--) | Gets or sets the frame delay time expressed in 1/100 seconds. |
| [setDelayTime(int value)](#setDelayTime-int-) | Gets or sets the frame delay time expressed in 1/100 seconds. |
| [getFlags()](#getFlags--) | Gets or sets the flags. |
| [setFlags(byte value)](#setFlags-byte-) | Gets or sets the flags. |
| [getTransparentColorIndex()](#getTransparentColorIndex--) | Gets or sets the transparent color index. |
| [setTransparentColorIndex(byte value)](#setTransparentColorIndex-byte-) | Gets or sets the transparent color index. |
| [getDisposalMethod()](#getDisposalMethod--) | Gets or sets the disposal method. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Gets or sets the disposal method. |
| [getUserInputExpected()](#getUserInputExpected--) | Gets or sets a value indicating whether user input is expected. |
| [setUserInputExpected(boolean value)](#setUserInputExpected-boolean-) | Gets or sets a value indicating whether user input is expected. |
| [hasTransparentColor()](#hasTransparentColor--) | Gets or sets a value indicating whether graphics control block has transparent color. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Gets or sets a value indicating whether graphics control block has transparent color. |
| [createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)](#createFlags-boolean-boolean-int-) | Creates the flags. |
### GifGraphicsControlBlock() {#GifGraphicsControlBlock--}
```
public GifGraphicsControlBlock()
```


Initializes a new instance of the `GifGraphicsControlBlock` class.

### GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex) {#GifGraphicsControlBlock-byte-int-byte-}
```
public GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)
```


Initializes a new instance of the `GifGraphicsControlBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | byte | The flags. |
| delayTime | int | The delay time expressed in 1/100 seconds. |
| transparentColorIndex | byte | The transparent color index. |

### GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod) {#GifGraphicsControlBlock-int-boolean-byte-boolean-int-}
```
public GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)
```


Initializes a new instance of the `GifGraphicsControlBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delayTime | int | The delay time expressed in 1/100 seconds. |
| hasTransparentColor | boolean | if set to `true` the `transparentColorIndex` is valid. |
| transparentColorIndex | byte | The transparent color index. |
| requiresUserInput | boolean | if set to `true` the user input is expected. |
| disposalMethod | int | The disposal method. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Specifies the block header size.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Extension label.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


Gets the sub-block size.

### getDelayTime() {#getDelayTime--}
```
public int getDelayTime()
```


Gets or sets the frame delay time expressed in 1/100 seconds.

**Returns:**
int
### setDelayTime(int value) {#setDelayTime-int-}
```
public void setDelayTime(int value)
```


Gets or sets the frame delay time expressed in 1/100 seconds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFlags() {#getFlags--}
```
public byte getFlags()
```


Gets or sets the flags.

Value: The flags.

**Returns:**
byte
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Gets or sets the flags.

Value: The flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTransparentColorIndex() {#getTransparentColorIndex--}
```
public byte getTransparentColorIndex()
```


Gets or sets the transparent color index.

Value: The transparent color index.

**Returns:**
byte
### setTransparentColorIndex(byte value) {#setTransparentColorIndex-byte-}
```
public void setTransparentColorIndex(byte value)
```


Gets or sets the transparent color index.

Value: The transparent color index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Gets or sets the disposal method.

Value: The disposal method.

**Returns:**
int
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public void setDisposalMethod(int value)
```


Gets or sets the disposal method.

Value: The disposal method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUserInputExpected() {#getUserInputExpected--}
```
public boolean getUserInputExpected()
```


Gets or sets a value indicating whether user input is expected.

Value: `true` if user input is expected; otherwise, `false`.

**Returns:**
boolean
### setUserInputExpected(boolean value) {#setUserInputExpected-boolean-}
```
public void setUserInputExpected(boolean value)
```


Gets or sets a value indicating whether user input is expected.

Value: `true` if user input is expected; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Gets or sets a value indicating whether graphics control block has transparent color.

Value: `true` if graphics control block has transparent color; otherwise, `false`.

**Returns:**
boolean
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Gets or sets a value indicating whether graphics control block has transparent color.

Value: `true` if graphics control block has transparent color; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod) {#createFlags-boolean-boolean-int-}
```
public static byte createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)
```


Creates the flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hasTransparentColor | boolean | if set to `true` the `GifGraphicsControlBlock` has valid transparent color index. |
| requiresUserInput | boolean | if set to `true` the user input is expected. |
| disposalMethod | int | The disposal method. |

**Returns:**
byte - The generated flags.
