---
title: "TimeInterval"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta l'intervallo di tempo in millisecondi"
type: docs
weight: 50
url: /it/java/com.aspose.imaging.imageoptions/timeinterval/
---
**Inheritance:**
java.lang.Object
```
public class TimeInterval
```

Rappresenta l'intervallo di tempo in millisecondi
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TimeInterval(long from, long to)](#TimeInterval-long-long-) | Inizializza una nuova istanza della classe [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFrom()](#getFrom--) | Ottiene From in millisecondi. |
| [setFrom(long value)](#setFrom-long-) | Imposta From in millisecondi. |
| [getTo()](#getTo--) | Ottiene To in millisecondi. |
| [setTo(long value)](#setTo-long-) | Imposta To in millisecondi. |

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


Inizializza una nuova istanza della classe [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| da | long | From millisecondi. |
| a | long | In millisecondi. |

### getFrom() {#getFrom--}
```
public final long getFrom()
```


Ottiene From in millisecondi.

**Returns:**
long
### setFrom(long value) {#setFrom-long-}
```
public final void setFrom(long value)
```


Imposta From in millisecondi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getTo() {#getTo--}
```
public final long getTo()
```


Ottiene To in millisecondi.

**Returns:**
long
### setTo(long value) {#setTo-long-}
```
public final void setTo(long value)
```


Imposta To in millisecondi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

