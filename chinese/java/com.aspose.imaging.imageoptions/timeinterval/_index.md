---
title: "TimeInterval"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示以毫秒为单位的时间间隔"
type: docs
weight: 50
url: /zh/java/com.aspose.imaging.imageoptions/timeinterval/
---
**Inheritance:**
java.lang.Object
```
public class TimeInterval
```

表示以毫秒为单位的时间间隔
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TimeInterval(long from, long to)](#TimeInterval-long-long-) | 初始化一个新的 [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFrom()](#getFrom--) | 获取 From 毫秒。 |
| [setFrom(long value)](#setFrom-long-) | 设置 From 毫秒。 |
| [getTo()](#getTo--) | 获取 To 毫秒。 |
| [setTo(long value)](#setTo-long-) | 设置 To 毫秒。 |

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


初始化一个新的 [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 从 | long | 起始毫秒。 |
| 至 | long | 结束毫秒。 |

### getFrom() {#getFrom--}
```
public final long getFrom()
```


获取 From 毫秒。

**Returns:**
long
### setFrom(long value) {#setFrom-long-}
```
public final void setFrom(long value)
```


设置 From 毫秒。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### getTo() {#getTo--}
```
public final long getTo()
```


获取 To 毫秒。

**Returns:**
long
### setTo(long value) {#setTo-long-}
```
public final void setTo(long value)
```


设置 To 毫秒。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

