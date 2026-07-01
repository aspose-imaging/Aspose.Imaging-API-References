---
title: "Jpeg2000LoadOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "JPEG2000 加载选项"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.imageloadoptions/jpeg2000loadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

JPEG2000 加载选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | 初始化 `Jpeg2000LoadOptions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | 获取以秒为单位的最大解码时间（此选项可用于内存非常慢的机器，以防在处理非常大的图像（分辨率超过5500x6500像素）时挂起）。 |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | 设置以秒为单位的最大解码时间（此选项可用于内存非常慢的机器，以防在处理非常大的图像（分辨率超过5500x6500像素）时挂起）。 |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | 获取瓦片的最大解码时间。 |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | 设置瓦片的最大解码时间。 |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


初始化 `Jpeg2000LoadOptions` 类的新实例。

### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


获取以秒为单位的最大解码时间（此选项可用于内存非常慢的机器，以防在处理非常大的图像（分辨率超过5500x6500像素）时挂起）。

**Returns:**
int - 最大解码时间。
### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


设置以秒为单位的最大解码时间（此选项可用于内存非常慢的机器，以防在处理非常大的图像（分辨率超过5500x6500像素）时挂起）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 最大解码时间。 |

### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


获取瓦片的最大解码时间。

值：瓦片的最大解码时间。

**Returns:**
int - 瓦片的最大解码时间。
### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


设置瓦片的最大解码时间。

值：瓦片的最大解码时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 瓦片的最大解码时间。 |

