---
title: "BitmapV5Header"
second_title: "Aspose.Imaging for Java API 参考"
description: "BitmapV5Header 结构是位图信息头文件。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.bmp/bitmapv5header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader), [com.aspose.imaging.fileformats.bmp.BitmapV4Header](../../com.aspose.imaging.fileformats.bmp/bitmapv4header)
```
public class BitmapV5Header extends BitmapV4Header
```

BitmapV5Header 结构是位图信息头文件。它是 BITMAPINFOHEADER 结构的扩展版本。

如果 bV5Height 为负，表示自上而下的 DIB，则 bV5Compression 必须是 BI\_RGB 或 BI\_BITFIELDS。自上而下的 DIB 不能被压缩。独立颜色管理接口 (ICM) 2.0 允许将国际色彩联盟 (ICC) 色彩配置文件链接或嵌入到 DIB（DIB）中。有关更多信息，请参阅 Using Structures。当 DIB 加载到内存时，配置文件数据（如果存在）应位于颜色表之后，bV5ProfileData 应提供从 BITMAPV5HEADER 结构开始到配置文件数据的偏移量。存储在 bV5ProfileData 中的值将不同于对 BITMAPV5HEADER 参数使用 sizeof 运算符返回的值，因为 bV5ProfileData 是从 BITMAPV5HEADER 结构起始位置到配置文件数据起始位置的字节偏移量。（位图位在内存中不跟随颜色表）。应用程序应在将 DIB 加载到内存后修改 bV5ProfileData 成员。对于打包的 DIB，配置文件数据应像文件格式一样位于位图位之后。bV5ProfileData 成员仍应给出从 BITMAPV5HEADER 起始位置到配置文件数据的偏移量。仅当 bV5Size 等于 BITMAPV5HEADER 的大小且 bV5CSType 等于 PROFILE\_EMBEDDED 或 PROFILE\_LINKED 时，应用程序才应访问配置文件数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BitmapV5Header()](#BitmapV5Header--) | 初始化 `BitmapV5Header` 类的新实例。 |
| [BitmapV5Header(byte[] bytes)](#BitmapV5Header-byte---) | 初始化 `BitmapV5Header` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIntent()](#getIntent--) | 获取位图的渲染意图。 |
| [setIntent(long value)](#setIntent-long-) | 设置位图的渲染意图。 |
| [getProfileData()](#getProfileData--) | 获取配置文件数据。 |
| [setProfileData(long value)](#setProfileData-long-) | 设置配置文件数据。 |
| [getProfileSize()](#getProfileSize--) | 获取配置文件的大小。 |
| [setProfileSize(long value)](#setProfileSize-long-) | 设置配置文件的大小。 |
| [getReserved()](#getReserved--) | 获取保留成员。 |
| [setReserved(long value)](#setReserved-long-) | 设置保留成员。 |
### BitmapV5Header() {#BitmapV5Header--}
```
public BitmapV5Header()
```


初始化 `BitmapV5Header` 类的新实例。

### BitmapV5Header(byte[] bytes) {#BitmapV5Header-byte---}
```
public BitmapV5Header(byte[] bytes)
```


初始化 `BitmapV5Header` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字节 | byte[] | 字节。 |

### getIntent() {#getIntent--}
```
public long getIntent()
```


获取位图的渲染意图。

**Returns:**
long - 意图。
### setIntent(long value) {#setIntent-long-}
```
public void setIntent(long value)
```


设置位图的渲染意图。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 意图。 |

### getProfileData() {#getProfileData--}
```
public long getProfileData()
```


获取配置文件数据。

**Returns:**
long - 配置文件数据。
### setProfileData(long value) {#setProfileData-long-}
```
public void setProfileData(long value)
```


设置配置文件数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 配置文件数据。 |

### getProfileSize() {#getProfileSize--}
```
public long getProfileSize()
```


获取配置文件的大小。

**Returns:**
long - 配置文件的大小。
### setProfileSize(long value) {#setProfileSize-long-}
```
public void setProfileSize(long value)
```


设置配置文件的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 配置文件的大小。 |

### getReserved() {#getReserved--}
```
public long getReserved()
```


获取保留成员。

**Returns:**
long - 保留值。
### setReserved(long value) {#setReserved-long-}
```
public void setReserved(long value)
```


设置保留成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 保留值。 |

