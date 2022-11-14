---
title: Jpeg2000LoadOptions
second_title: Aspose.Imaging for Java API Reference
description: JPEG2000 load options
type: docs
weight: 12
url: /java/com.aspose.imaging.imageloadoptions/jpeg2000loadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

JPEG2000 load options
## Constructors

| Constructor | Description |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | Initializes a new instance of the `Jpeg2000LoadOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | Gets the maximum decoding time in seconds (this option can be used on very slow on memory machines to prevent hanging on process on very big images - resolution more than 5500x6500 pixels). |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | Sets the maximum decoding time in seconds (this option can be used on very slow on memory machines to prevent hanging on process on very big images - resolution more than 5500x6500 pixels). |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | Gets the maximum decoding time for tile. |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | Sets the maximum decoding time for tile. |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


Initializes a new instance of the `Jpeg2000LoadOptions` class.

### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


Gets the maximum decoding time in seconds (this option can be used on very slow on memory machines to prevent hanging on process on very big images - resolution more than 5500x6500 pixels).

**Returns:**
int - The maximum decoding time.
### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


Sets the maximum decoding time in seconds (this option can be used on very slow on memory machines to prevent hanging on process on very big images - resolution more than 5500x6500 pixels).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The maximum decoding time. |

### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


Gets the maximum decoding time for tile.

Value: The maximum decoding time for tile.

**Returns:**
int - the maximum decoding time for tile.
### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


Sets the maximum decoding time for tile.

Value: The maximum decoding time for tile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the maximum decoding time for tile. |

