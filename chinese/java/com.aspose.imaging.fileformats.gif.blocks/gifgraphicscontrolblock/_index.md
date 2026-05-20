---
title: "GifGraphicsControlBlock"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Gif 图形控制块."
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifGraphicsControlBlock extends GifBlock
```

Gif 图形控制块.
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock--) | 初始化 `GifGraphicsControlBlock` 类的新实例。 |
| [GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)](#GifGraphicsControlBlock-byte-int-byte-) | 初始化 `GifGraphicsControlBlock` 类的新实例。 |
| [GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)](#GifGraphicsControlBlock-int-boolean-byte-boolean-int-) | 初始化 `GifGraphicsControlBlock` 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | 指定块头大小。 |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | 扩展标签。 |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | 获取子块大小。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDelayTime()](#getDelayTime--) | 获取或设置以 1/100 秒表示的帧延迟时间。 |
| [setDelayTime(int value)](#setDelayTime-int-) | 获取或设置以 1/100 秒表示的帧延迟时间。 |
| [getFlags()](#getFlags--) | 获取或设置标志。 |
| [setFlags(byte value)](#setFlags-byte-) | 获取或设置标志。 |
| [getTransparentColorIndex()](#getTransparentColorIndex--) | 获取或设置透明颜色索引。 |
| [setTransparentColorIndex(byte value)](#setTransparentColorIndex-byte-) | 获取或设置透明颜色索引。 |
| [getDisposalMethod()](#getDisposalMethod--) | 获取或设置处理方式。 |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | 获取或设置处理方式。 |
| [getUserInputExpected()](#getUserInputExpected--) | 获取或设置指示是否期望用户输入的值。 |
| [setUserInputExpected(boolean value)](#setUserInputExpected-boolean-) | 获取或设置指示是否期望用户输入的值。 |
| [hasTransparentColor()](#hasTransparentColor--) | 获取或设置指示图形控制块是否具有透明颜色的值。 |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | 获取或设置指示图形控制块是否具有透明颜色的值。 |
| [createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)](#createFlags-boolean-boolean-int-) | 创建标志。 |
### GifGraphicsControlBlock() {#GifGraphicsControlBlock--}
```
public GifGraphicsControlBlock()
```


初始化 `GifGraphicsControlBlock` 类的新实例。

### GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex) {#GifGraphicsControlBlock-byte-int-byte-}
```
public GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)
```


初始化 `GifGraphicsControlBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 标志 | byte | 标志。 |
| delayTime | int | 以 1/100 秒表示的延迟时间。 |
| transparentColorIndex | byte | 透明颜色索引。 |

### GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod) {#GifGraphicsControlBlock-int-boolean-byte-boolean-int-}
```
public GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)
```


初始化 `GifGraphicsControlBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| delayTime | int | 以 1/100 秒表示的延迟时间。 |
| hasTransparentColor | boolean | 如果设置为 `true`，则 `transparentColorIndex` 有效。 |
| transparentColorIndex | byte | 透明颜色索引。 |
| requiresUserInput | boolean | 如果设置为 `true`，则期望用户输入。 |
| disposalMethod | int | 释放方法。 |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


指定块头大小。

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


扩展标签。

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


获取子块大小。

### getDelayTime() {#getDelayTime--}
```
public int getDelayTime()
```


获取或设置以 1/100 秒表示的帧延迟时间。

**Returns:**
int
### setDelayTime(int value) {#setDelayTime-int-}
```
public void setDelayTime(int value)
```


获取或设置以 1/100 秒表示的帧延迟时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFlags() {#getFlags--}
```
public byte getFlags()
```


获取或设置标志。

值：标志。

**Returns:**
byte
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


获取或设置标志。

值：标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getTransparentColorIndex() {#getTransparentColorIndex--}
```
public byte getTransparentColorIndex()
```


获取或设置透明颜色索引。

值：透明颜色索引。

**Returns:**
byte
### setTransparentColorIndex(byte value) {#setTransparentColorIndex-byte-}
```
public void setTransparentColorIndex(byte value)
```


获取或设置透明颜色索引。

值：透明颜色索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


获取或设置处理方式。

值：释放方法。

**Returns:**
int
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public void setDisposalMethod(int value)
```


获取或设置处理方式。

值：释放方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getUserInputExpected() {#getUserInputExpected--}
```
public boolean getUserInputExpected()
```


获取或设置指示是否期望用户输入的值。

值：如果期望用户输入则为 `true`；否则为 `false`。

**Returns:**
boolean
### setUserInputExpected(boolean value) {#setUserInputExpected-boolean-}
```
public void setUserInputExpected(boolean value)
```


获取或设置指示是否期望用户输入的值。

值：如果期望用户输入则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


获取或设置指示图形控制块是否具有透明颜色的值。

值：如果图形控制块具有透明颜色则为 `true`；否则为 `false`。

**Returns:**
boolean
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


获取或设置指示图形控制块是否具有透明颜色的值。

值：如果图形控制块具有透明颜色则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod) {#createFlags-boolean-boolean-int-}
```
public static byte createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)
```


创建标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hasTransparentColor | boolean | 如果设置为 `true`，则 `GifGraphicsControlBlock` 具有有效的透明颜色索引。 |
| requiresUserInput | boolean | 如果设置为 `true`，则期望用户输入。 |
| disposalMethod | int | 释放方法。 |

**Returns:**
byte - 生成的标志。
