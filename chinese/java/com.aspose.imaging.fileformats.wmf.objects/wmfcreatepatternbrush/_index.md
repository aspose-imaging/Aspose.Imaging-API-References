---
title: "WmfCreatePatternBrush"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "META_CREATEPATTERNBRUSH 记录创建一个使用位图指定的图案的画笔对象。"
type: docs
weight: 23
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePatternBrush extends WmfGraphicObject
```

META\_CREATEPATTERNBRUSH 记录创建一个使用位图指定的图案的画笔对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfCreatePatternBrush()](#WmfCreatePatternBrush--) | WMFs 记录。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitmap()](#getBitmap--) | 获取或设置位图。 |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | 获取或设置位图。 |
| [getReserved()](#getReserved--) | 获取或设置保留字段。 |
| [setReserved(byte[] value)](#setReserved-byte---) | 获取或设置保留字段。 |
| [getPattern()](#getPattern--) | 获取或设置图案。 |
| [setPattern(byte[] value)](#setPattern-byte---) | 获取或设置图案。 |
### WmfCreatePatternBrush() {#WmfCreatePatternBrush--}
```
public WmfCreatePatternBrush()
```


WMFs 记录。

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


获取或设置位图。

值：指定画笔图案的位图。

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


获取或设置位图。

值：指定画笔图案的位图。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

### getReserved() {#getReserved--}
```
public byte[] getReserved()
```


获取或设置保留字段。

值：保留字段。此字段必须被忽略。

**Returns:**
byte[]
### setReserved(byte[] value) {#setReserved-byte---}
```
public void setReserved(byte[] value)
```


获取或设置保留字段。

值：保留字段。此字段必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getPattern() {#getPattern--}
```
public byte[] getPattern()
```


获取或设置图案。

值：一个可变长度的字节数组，定义组成画笔图案的位图像素数据。此字段的长度（以字节为单位）可以根据位图参数按如下方式计算。

**Returns:**
byte[]
### setPattern(byte[] value) {#setPattern-byte---}
```
public void setPattern(byte[] value)
```


获取或设置图案。

值：一个可变长度的字节数组，定义组成画笔图案的位图像素数据。此字段的长度（以字节为单位）可以根据位图参数按如下方式计算。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

