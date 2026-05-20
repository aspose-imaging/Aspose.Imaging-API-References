---
title: "TimeInterval"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt das Zeitintervall in Millisekunden dar"
type: docs
weight: 50
url: /de/java/com.aspose.imaging.imageoptions/timeinterval/
---
**Inheritance:**
java.lang.Object
```
public class TimeInterval
```

Stellt das Zeitintervall in Millisekunden dar
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TimeInterval(long from, long to)](#TimeInterval-long-long-) | Initialisiert eine neue Instanz der Klasse [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFrom()](#getFrom--) | Liest From Millisekunden. |
| [setFrom(long value)](#setFrom-long-) | Setzt From Millisekunden. |
| [getTo()](#getTo--) | Liest To Millisekunden. |
| [setTo(long value)](#setTo-long-) | Setzt To Millisekunden. |

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


Initialisiert eine neue Instanz der Klasse [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| von | long | From Millisekunden. |
| zu | long | In Millisekunden. |

### getFrom() {#getFrom--}
```
public final long getFrom()
```


Liest From Millisekunden.

**Returns:**
long
### setFrom(long value) {#setFrom-long-}
```
public final void setFrom(long value)
```


Setzt From Millisekunden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getTo() {#getTo--}
```
public final long getTo()
```


Liest To Millisekunden.

**Returns:**
long
### setTo(long value) {#setTo-long-}
```
public final void setTo(long value)
```


Setzt To Millisekunden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

