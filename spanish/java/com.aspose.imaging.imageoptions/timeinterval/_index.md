---
title: "TimeInterval"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el intervalo de tiempo en milisegundos"
type: docs
weight: 50
url: /es/java/com.aspose.imaging.imageoptions/timeinterval/
---
**Inheritance:**
java.lang.Object
```
public class TimeInterval
```

Representa el intervalo de tiempo en milisegundos
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TimeInterval(long from, long to)](#TimeInterval-long-long-) | Inicializa una nueva instancia de la clase [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFrom()](#getFrom--) | Obtiene From milisegundos. |
| [setFrom(long value)](#setFrom-long-) | Establece From milisegundos. |
| [getTo()](#getTo--) | Obtiene To milisegundos. |
| [setTo(long value)](#setTo-long-) | Establece To milisegundos. |

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


Inicializa una nueva instancia de la clase [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| de | long | From milisegundos. |
| a | long | A milisegundos. |

### getFrom() {#getFrom--}
```
public final long getFrom()
```


Obtiene From milisegundos.

**Returns:**
long
### setFrom(long value) {#setFrom-long-}
```
public final void setFrom(long value)
```


Establece From milisegundos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getTo() {#getTo--}
```
public final long getTo()
```


Obtiene To milisegundos.

**Returns:**
long
### setTo(long value) {#setTo-long-}
```
public final void setTo(long value)
```


Establece To milisegundos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

