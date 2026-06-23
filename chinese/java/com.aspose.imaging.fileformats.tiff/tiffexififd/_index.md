---
title: "TiffExifIfd"
second_title: "Aspose.Imaging for Java API 参考"
description: "TIFF Exif 图像文件目录类。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.tiff/tiffexififd/
---
**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

TIFF Exif 图像文件目录类。

封装指向 Exif IFD 的指针。互操作性，Exif IFD 的结构与 TIFF 中指定的 IFD 相同。然而，通常它不包含像 TIFF 那样的图像数据。更多细节请参阅 http://www.exiv2.org/tags.html 和 http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | 初始化 `TiffExifIfd` 类的新实例。 |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | 初始化 `TiffExifIfd` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [hasValue()](#hasValue--) | 获取一个值，指示此实例是否具有值。 |
| [getOffset()](#getOffset--) | 获取或设置指向 EXIF IFD 的指针。 |
| [setOffset(long value)](#setOffset-long-) | 获取或设置指向 EXIF IFD 的指针。 |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


初始化 `TiffExifIfd` 类的新实例。

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


初始化 `TiffExifIfd` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | ifdOffset | long | 指向 Exif IFD 的指针。 |

互操作性，Exif IFD 的结构与 TIFF 中指定的 IFD 相同。然而，通常它不包含像 TIFF 那样的图像数据。 |

### hasValue() {#hasValue--}
```
public boolean hasValue()
```


获取一个值，指示此实例是否具有值。

**Returns:**
boolean - 如果此实例有值则为 `true`；否则为 `false`。
### getOffset() {#getOffset--}
```
public long getOffset()
```


获取或设置指向 EXIF IFD 的指针。

**Returns:**
long - 指向 EXIF IFD 的指针。
### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


获取或设置指向 EXIF IFD 的指针。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 指向 EXIF IFD 的指针。 |

