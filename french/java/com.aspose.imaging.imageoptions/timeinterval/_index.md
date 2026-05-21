---
title: "TimeInterval"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente l'intervalle de temps en millisecondes"
type: docs
weight: 50
url: /fr/java/com.aspose.imaging.imageoptions/timeinterval/
---
**Inheritance:**
java.lang.Object
```
public class TimeInterval
```

Représente l'intervalle de temps en millisecondes
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TimeInterval(long from, long to)](#TimeInterval-long-long-) | Initialise une nouvelle instance de la classe [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFrom()](#getFrom--) | Obtient From en millisecondes. |
| [setFrom(long value)](#setFrom-long-) | Définit From en millisecondes. |
| [getTo()](#getTo--) | Obtient To en millisecondes. |
| [setTo(long value)](#setTo-long-) | Définit To en millisecondes. |

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


Initialise une nouvelle instance de la classe [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| de | long | From millisecondes. |
| à | long | En millisecondes. |

### getFrom() {#getFrom--}
```
public final long getFrom()
```


Obtient From en millisecondes.

**Returns:**
long
### setFrom(long value) {#setFrom-long-}
```
public final void setFrom(long value)
```


Définit From en millisecondes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getTo() {#getTo--}
```
public final long getTo()
```


Obtient To en millisecondes.

**Returns:**
long
### setTo(long value) {#setTo-long-}
```
public final void setTo(long value)
```


Définit To en millisecondes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

