---
title: GifBlock
second_title: Aspose.Imaging for Java API Reference
description: The default gif block implementation.
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.gif/gifblock/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
```
public abstract class GifBlock implements IGifBlock
```

The default gif block implementation.
## Constructors

| Constructor | Description |
| --- | --- |
| [GifBlock()](#GifBlock--) |  |
## Fields

| Field | Description |
| --- | --- |
| [EXTENSION_INTRODUCER](#EXTENSION-INTRODUCER) | Extension introducer. |
## Methods

| Method | Description |
| --- | --- |
| [isChanged()](#isChanged--) | Gets or sets a value indicating whether block has changed and requires save. |
| [setChanged(boolean value)](#setChanged-boolean-) | Gets or sets a value indicating whether block has changed and requires save. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the block to the specified stream. |
### GifBlock() {#GifBlock--}
```
public GifBlock()
```


### EXTENSION_INTRODUCER {#EXTENSION-INTRODUCER}
```
public static final byte EXTENSION_INTRODUCER
```


Extension introducer.

### isChanged() {#isChanged--}
```
public boolean isChanged()
```


Gets or sets a value indicating whether block has changed and requires save.

Value: `true` if block has changed; otherwise, `false`.

**Returns:**
boolean
### setChanged(boolean value) {#setChanged-boolean-}
```
public void setChanged(boolean value)
```


Gets or sets a value indicating whether block has changed and requires save.

Value: `true` if block has changed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Saves the block to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to save data to. |

