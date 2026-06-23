---
title: "TimeInterval"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل الفاصل الزمني بالمللي ثانية"
type: docs
weight: 50
url: /ar/java/com.aspose.imaging.imageoptions/timeinterval/
---
**Inheritance:**
java.lang.Object
```
public class TimeInterval
```

يمثل الفاصل الزمني بالمللي ثانية
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TimeInterval(long from, long to)](#TimeInterval-long-long-) | يُنشئ مثيلاً جديدًا من الفئة [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFrom()](#getFrom--) | يحصل على From بالمللي ثانية. |
| [setFrom(long value)](#setFrom-long-) | يضبط From بالمللي ثانية. |
| [getTo()](#getTo--) | يحصل على To بالمللي ثانية. |
| [setTo(long value)](#setTo-long-) | يضبط To بالمللي ثانية. |

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


يُنشئ مثيلاً جديدًا من الفئة [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| من | long | From بالمللي ثانية. |
| إلى | long | To بالمللي ثانية. |

### getFrom() {#getFrom--}
```
public final long getFrom()
```


يحصل على From بالمللي ثانية.

**Returns:**
long
### setFrom(long value) {#setFrom-long-}
```
public final void setFrom(long value)
```


يضبط From بالمللي ثانية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getTo() {#getTo--}
```
public final long getTo()
```


يحصل على To بالمللي ثانية.

**Returns:**
long
### setTo(long value) {#setTo-long-}
```
public final void setTo(long value)
```


يضبط To بالمللي ثانية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

