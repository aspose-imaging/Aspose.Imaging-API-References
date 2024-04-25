---
title: Configuration
second_title: Aspose.Imaging for Java API Reference
description: The memory management global configuration
type: docs
weight: 10
url: /com.aspose.imaging.memorymanagement/configuration/
---
**Inheritance:**
java.lang.Object
```
public final class Configuration
```

The memory management global configuration
## Methods

| Method | Description |
| --- | --- |
| [getBufferSizeHint()](#getBufferSizeHint--) | Gets the buffer size hint which is defined max allowed size for all internal buffers. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Sets the buffer size hint which is defined max allowed size for all internal buffers. |
### getBufferSizeHint() {#getBufferSizeHint--}
```
public static int getBufferSizeHint()
```


Gets the buffer size hint which is defined max allowed size for all internal buffers.

Value: The buffer size hint, in megabytes. Non-positive value means no memory limitation for internal buffers

**Returns:**
int - the buffer size hint which is defined max allowed size for all internal buffers.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public static void setBufferSizeHint(int value)
```


Sets the buffer size hint which is defined max allowed size for all internal buffers.

Value: The buffer size hint, in megabytes. Non-positive value means no memory limitation for internal buffers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the buffer size hint which is defined max allowed size for all internal buffers. |

