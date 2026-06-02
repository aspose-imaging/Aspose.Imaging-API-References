---
title: "Jpeg2000LoadOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
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
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | 获取以秒为单位的最大解码时间（此选项可在内存非常慢的机器上使用，以防在处理非常大的图像时挂起——分辨率超过 5500x6500 像素）。 |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | 设置以秒为单位的最大解码时间（此选项可在内存非常慢的机器上使用，以防在处理非常大的图像时挂起——分辨率超过 5500x6500 像素）。 |
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


获取以秒为单位的最大解码时间（此选项可在内存非常慢的机器上使用，以防在处理非常大的图像时挂起——分辨率超过 5500x6500 像素）。

**Returns:**
int - 最大解码时间。
### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


设置以秒为单位的最大解码时间（此选项可在内存非常慢的机器上使用，以防在处理非常大的图像时挂起——分辨率超过 5500x6500 像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 最大解码时间。 |

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
| value | int | 瓦片的最大解码时间。 |

