---
title: "TimeInterval"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Milisaniye cinsinden zaman aralığını temsil eder"
type: docs
weight: 50
url: /tr/java/com.aspose.imaging.imageoptions/timeinterval/
---
**Inheritance:**
java.lang.Object
```
public class TimeInterval
```

Milisaniye cinsinden zaman aralığını temsil eder
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TimeInterval(long from, long to)](#TimeInterval-long-long-) | Yeni bir [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) sınıfının bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFrom()](#getFrom--) | From milisaniyelerini alır. |
| [setFrom(long value)](#setFrom-long-) | From milisaniyelerini ayarlar. |
| [getTo()](#getTo--) | To milisaniyelerini alır. |
| [setTo(long value)](#setTo-long-) | To milisaniyelerini ayarlar. |

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


Yeni bir [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| başlangıç | long | From milisaniyeleri. |
| bitiş | long | Milisaniyelere. |

### getFrom() {#getFrom--}
```
public final long getFrom()
```


From milisaniyelerini alır.

**Returns:**
long
### setFrom(long value) {#setFrom-long-}
```
public final void setFrom(long value)
```


From milisaniyelerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getTo() {#getTo--}
```
public final long getTo()
```


To milisaniyelerini alır.

**Returns:**
long
### setTo(long value) {#setTo-long-}
```
public final void setTo(long value)
```


To milisaniyelerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

