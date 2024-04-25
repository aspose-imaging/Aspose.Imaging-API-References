---
title: TimeInterval
second_title: Aspose.Imaging for Java API Reference
description: Represents the time interval in milliseconds
type: docs
weight: 48
url: /com.aspose.imaging.imageoptions/timeinterval/
---
**Inheritance:**
java.lang.Object
```
public class TimeInterval
```

Represents the time interval in milliseconds
## Constructors

| Constructor | Description |
| --- | --- |
| [TimeInterval(long from, long to)](#TimeInterval-long-long-) | Initializes a new instance of the [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFrom()](#getFrom--) | Gets From milliseconds. |
| [setFrom(long value)](#setFrom-long-) | Sets From milliseconds. |
| [getTo()](#getTo--) | Gets To milliseconds. |
| [setTo(long value)](#setTo-long-) | Sets To milliseconds. |

## Example: Export of part of animation from GIF image based on time interval.

``` java
try (Image image = Image.load("Animation.gif"))
{
    GifOptions options = new GifOptions();
    options.setFullFrame(true);
    final MultiPageOptions multiPageOptions = new MultiPageOptions();
    multiPageOptions.setMode(MultiPageMode.TimeInterval);
    multiPageOptions.setTimeInterval(new TimeInterval(0, 400));
    options.setMultiPageOptions(multiPageOptions);

    image.save("PartOfAnimation.gif", options);
}
```

### TimeInterval(long from, long to) {#TimeInterval-long-long-}
```
public TimeInterval(long from, long to)
```


Initializes a new instance of the [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | long | From milliseconds. |
| to | long | To milliseconds. |

### getFrom() {#getFrom--}
```
public final long getFrom()
```


Gets From milliseconds.

**Returns:**
long
### setFrom(long value) {#setFrom-long-}
```
public final void setFrom(long value)
```


Sets From milliseconds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getTo() {#getTo--}
```
public final long getTo()
```


Gets To milliseconds.

**Returns:**
long
### setTo(long value) {#setTo-long-}
```
public final void setTo(long value)
```


Sets To milliseconds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

