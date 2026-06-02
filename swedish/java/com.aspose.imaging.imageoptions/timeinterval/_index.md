---
title: "TimeInterval"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar tidsintervallet i millisekunder"
type: docs
weight: 50
url: /sv/java/com.aspose.imaging.imageoptions/timeinterval/
---
**Inheritance:**
java.lang.Object
```
public class TimeInterval
```

Representerar tidsintervallet i millisekunder
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TimeInterval(long from, long to)](#TimeInterval-long-long-) | Initierar en ny instans av klassen [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFrom()](#getFrom--) | Hämtar Från millisekunder. |
| [setFrom(long value)](#setFrom-long-) | Ställer in Från millisekunder. |
| [getTo()](#getTo--) | Hämtar Till millisekunder. |
| [setTo(long value)](#setTo-long-) | Ställer in Till millisekunder. |

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


Initierar en ny instans av klassen [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| från | long | Från millisekunder. |
| till | long | Till millisekunder. |

### getFrom() {#getFrom--}
```
public final long getFrom()
```


Hämtar Från millisekunder.

**Returns:**
long
### setFrom(long value) {#setFrom-long-}
```
public final void setFrom(long value)
```


Ställer in Från millisekunder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getTo() {#getTo--}
```
public final long getTo()
```


Hämtar Till millisekunder.

**Returns:**
long
### setTo(long value) {#setTo-long-}
```
public final void setTo(long value)
```


Ställer in Till millisekunder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

