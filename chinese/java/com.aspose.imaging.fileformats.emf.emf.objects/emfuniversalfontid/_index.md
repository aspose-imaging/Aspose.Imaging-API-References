---
title: "EmfUniversalFontId"
second_title: "Aspose.Imaging for Java API 参考"
description: "UniversalFontId 对象定义了一种在 EMF 元文件中识别字体的机制。"
type: docs
weight: 37
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfUniversalFontId extends EmfObject
```

UniversalFontId 对象定义了一种在 EMF 元文件中识别字体的机制。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfUniversalFontId()](#EmfUniversalFontId--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChecksum()](#getChecksum--) | 获取或设置一个 32 位无符号整数，作为字体的校验和。 |
| [setChecksum(int value)](#setChecksum-int-) | 获取或设置一个 32 位无符号整数，作为字体的校验和。 |
| [getIndex()](#getIndex--) | 获取或设置一个 32 位无符号整数，作为与字体对象关联的索引。 |
| [setIndex(int value)](#setIndex-int-) | 获取或设置一个 32 位无符号整数，作为与字体对象关联的索引。 |
### EmfUniversalFontId() {#EmfUniversalFontId--}
```
public EmfUniversalFontId()
```


### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


获取或设置一个 32 位无符号整数，作为字体的校验和。校验和值具有以下含义。0x00000000 对象是设备字体。0x00000001 对象是已安装在客户端机器上并被 PostScript 打印机驱动程序枚举为设备字体的 Type 1 字体。0x00000002 对象不是字体，而是 Type 1 光栅化器。3 \\u2264 value 对象是位图、矢量或 TrueType 字体，或由 Type 1 光栅化器创建的 Type 1 光栅化字体。

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


获取或设置一个 32 位无符号整数，作为字体的校验和。校验和值具有以下含义。0x00000000 对象是设备字体。0x00000001 对象是已安装在客户端机器上并被 PostScript 打印机驱动程序枚举为设备字体的 Type 1 字体。0x00000002 对象不是字体，而是 Type 1 光栅化器。3 \\u2264 value 对象是位图、矢量或 TrueType 字体，或由 Type 1 光栅化器创建的 Type 1 光栅化字体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getIndex() {#getIndex--}
```
public int getIndex()
```


获取或设置一个 32 位无符号整数，该整数是与字体对象关联的索引。此字段的含义由字体类型决定。

**Returns:**
int
### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


获取或设置一个 32 位无符号整数，该整数是与字体对象关联的索引。此字段的含义由字体类型决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

