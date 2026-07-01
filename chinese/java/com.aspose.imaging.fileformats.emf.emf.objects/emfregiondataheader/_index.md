---
title: "EmfRegionDataHeader"
second_title: "Aspose.Imaging for Java API 参考"
description: "RegionDataHeader 对象描述 RegionData 对象的属性。"
type: docs
weight: 34
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionDataHeader extends EmfObject
```

RegionDataHeader 对象描述 RegionData 对象的属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSize()](#getSize--) | 获取一个 32 位无符号整数，指定此对象的大小（以字节为单位）。 |
| [setSize(int value)](#setSize-int-) | 设置一个 32 位无符号整数，指定此对象的大小（以字节为单位）。 |
| [getType()](#getType--) | 获取一个 32 位无符号整数，指定区域类型。 |
| [setType(int value)](#setType-int-) | 设置一个 32 位无符号整数，指定区域类型。 |
| [getCountRects()](#getCountRects--) | 获取一个 32 位无符号整数，指定此区域中的矩形数量。 |
| [setCountRects(int value)](#setCountRects-int-) | 设置一个 32 位无符号整数，指定此区域中的矩形数量。 |
| [getRgnSize()](#getRgnSize--) | 获取一个 32 位无符号整数，指定矩形缓冲区的大小（以字节为单位）。 |
| [setRgnSize(int value)](#setRgnSize-int-) | 设置一个 32 位无符号整数，指定矩形缓冲区的大小（以字节为单位）。 |
| [getBounds()](#getBounds--) | 获取一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定区域的边界。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 设置一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定区域的边界。 |
### EmfRegionDataHeader() {#EmfRegionDataHeader--}
```
public EmfRegionDataHeader()
```


### getSize() {#getSize--}
```
public int getSize()
```


获取一个 32 位无符号整数，指定此对象的大小（以字节为单位）。此值必须为 0x00000020。

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


设置一个 32 位无符号整数，指定此对象的大小（以字节为单位）。此值必须为 0x00000020。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getType() {#getType--}
```
public int getType()
```


获取一个 32 位无符号整数，指定区域类型。此值应为 RDH\_RECTANGLES (0x00000001)。

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


设置一个 32 位无符号整数，指定区域类型。此值应为 RDH\_RECTANGLES (0x00000001)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCountRects() {#getCountRects--}
```
public int getCountRects()
```


获取一个 32 位无符号整数，指定此区域中的矩形数量。

**Returns:**
int
### setCountRects(int value) {#setCountRects-int-}
```
public void setCountRects(int value)
```


设置一个 32 位无符号整数，指定此区域中的矩形数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRgnSize() {#getRgnSize--}
```
public int getRgnSize()
```


获取一个 32 位无符号整数，指定矩形缓冲区的大小（以字节为单位）。

**Returns:**
int
### setRgnSize(int value) {#setRgnSize-int-}
```
public void setRgnSize(int value)
```


设置一个 32 位无符号整数，指定矩形缓冲区的大小（以字节为单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定区域的边界。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


设置一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定区域的边界。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

