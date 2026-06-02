---
title: "EmfFrameRgn"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_FRAMERGN 记录使用指定的画刷在指定的区域周围绘制边框。"
type: docs
weight: 62
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfframergn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFrameRgn extends EmfDrawingRecordType
```

EMR_FRAMERGN 记录使用指定的画刷在指定区域周围绘制边框。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfFrameRgn(EmfRecord source)](#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfFrameRgn` 类的新实例。 |
| [EmfFrameRgn()](#EmfFrameRgn--) | 初始化 [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定边界矩形。 |
| [getRgnDataSize()](#getRgnDataSize--) | 获取或设置一个指定区域数据大小（以字节为单位）的 32 位无符号整数。 |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | 获取或设置一个指定区域数据大小（以字节为单位）的 32 位无符号整数。 |
| [getIhBrush()](#getIhBrush--) | 获取或设置一个 32 位无符号整数，该整数指定画刷 EMF 对象表索引。 |
| [setIhBrush(int value)](#setIhBrush-int-) | 获取或设置一个 32 位无符号整数，该整数指定画刷 EMF 对象表索引。 |
| [getWidth()](#getWidth--) | 获取或设置一个 32 位有符号整数，该整数指定垂直画刷笔画的宽度（逻辑单位）。 |
| [setWidth(int value)](#setWidth-int-) | 获取或设置一个 32 位有符号整数，该整数指定垂直画刷笔画的宽度（逻辑单位）。 |
| [getHeight()](#getHeight--) | 获取或设置一个 32 位有符号整数，该整数指定水平画刷笔画的高度（逻辑单位）。 |
| [setHeight(int value)](#setHeight-int-) | 获取或设置一个 32 位有符号整数，该整数指定水平画刷笔画的高度（逻辑单位）。 |
| [getRgnData()](#getRgnData--) | 获取或设置一个 RgnDataSize 长度的字节数组，该数组指定逻辑单位中的 RegionData 对象 |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | 获取或设置一个 RgnDataSize 长度的字节数组，该数组指定逻辑单位中的 RegionData 对象 |
### EmfFrameRgn(EmfRecord source) {#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFrameRgn(EmfRecord source)
```


初始化 `EmfFrameRgn` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfFrameRgn() {#EmfFrameRgn--}
```
public EmfFrameRgn()
```


初始化 [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn) 类的新实例。

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


获取或设置一个指定区域数据大小（以字节为单位）的 32 位无符号整数。

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


获取或设置一个指定区域数据大小（以字节为单位）的 32 位无符号整数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


获取或设置一个 32 位无符号整数，该整数指定画刷 EMF 对象表索引。

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


获取或设置一个 32 位无符号整数，该整数指定画刷 EMF 对象表索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


获取或设置一个 32 位有符号整数，该整数指定垂直画刷笔画的宽度（逻辑单位）。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


获取或设置一个 32 位有符号整数，该整数指定垂直画刷笔画的宽度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


获取或设置一个 32 位有符号整数，该整数指定水平画刷笔画的高度（逻辑单位）。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


获取或设置一个 32 位有符号整数，该整数指定水平画刷笔画的高度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


获取或设置一个 RgnDataSize 长度的字节数组，该数组指定逻辑单位中的 RegionData 对象

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


获取或设置一个 RgnDataSize 长度的字节数组，该数组指定逻辑单位中的 RegionData 对象

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

