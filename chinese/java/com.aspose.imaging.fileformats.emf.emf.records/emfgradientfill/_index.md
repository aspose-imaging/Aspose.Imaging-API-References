---
title: "EmfGradientFill"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_GRADIENTFILL 记录指定使用颜色渐变填充矩形或三角形。"
type: docs
weight: 65
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfGradientFill extends EmfDrawingRecordType
```

EMR\_GRADIENTFILL 记录指定使用颜色渐变填充矩形或三角形。

EMR\_GRADIENTFILL 记录指定三角形的三个顶点应使用平滑的颜色渐变填充图形。[85] EMR\_GRADIENTFILL 记录指定矩形的左上角和右下角顶点应使用平滑的颜色渐变填充图形。GradientFill 枚举中有两种渐变填充模式可用于绘制矩形。在 GRADIENT\_FILL\_RECT\_H 模式下，矩形从左到右填充。在 GRADIENT\_FILL\_RECT\_V 模式下，矩形从上到下填充。注意 EMR\_GRADIENTFILL 记录必须忽略 TriVertex 对象中的 Alpha 字段。紧随 EMR\_GRADIENTFILL 记录之后的 EMR\_ALPHABLEND 记录（第 2.3.1.1 节）可用于对填充区域应用 alpha 透明度渐变。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfGradientFill(EmfRecord source)](#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfGradientFill` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以包含-包含的设备单位指定边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以包含-包含的设备单位指定边界矩形。 |
| [getNVer()](#getNVer--) | 获取或设置一个 32 位无符号整数，指定顶点数。 |
| [setNVer(int value)](#setNVer-int-) | 获取或设置一个 32 位无符号整数，指定顶点数。 |
| [getNTri()](#getNTri--) | 获取或设置一个 32 位无符号整数，指定要填充的矩形或三角形的数量。 |
| [setNTri(int value)](#setNTri-int-) | 获取或设置一个 32 位无符号整数，指定要填充的矩形或三角形的数量。 |
| [getUlMode()](#getUlMode--) | 获取或设置一个 32 位无符号整数，指定渐变填充模式。 |
| [setUlMode(int value)](#setUlMode-int-) | 获取或设置一个 32 位无符号整数，指定渐变填充模式。 |
| [getVertexData()](#getVertexData--) | 获取或设置对象，这些对象指定矩形或三角形的顶点以及对应的颜色。 |
| [setVertexData(EmfVertexData value)](#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-) | 获取或设置对象，这些对象指定矩形或三角形的顶点以及对应的颜色。 |
### EmfGradientFill(EmfRecord source) {#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGradientFill(EmfRecord source)
```


初始化 `EmfGradientFill` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以包含-包含的设备单位指定边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以包含-包含的设备单位指定边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNVer() {#getNVer--}
```
public int getNVer()
```


获取或设置一个 32 位无符号整数，指定顶点数。

**Returns:**
int
### setNVer(int value) {#setNVer-int-}
```
public void setNVer(int value)
```


获取或设置一个 32 位无符号整数，指定顶点数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getNTri() {#getNTri--}
```
public int getNTri()
```


获取或设置一个 32 位无符号整数，指定要填充的矩形或三角形的数量。

**Returns:**
int
### setNTri(int value) {#setNTri-int-}
```
public void setNTri(int value)
```


获取或设置一个 32 位无符号整数，指定要填充的矩形或三角形的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getUlMode() {#getUlMode--}
```
public int getUlMode()
```


获取或设置一个 32 位无符号整数，指定渐变填充模式。该值必须位于 GradientFill 枚举中（第 2.1.15 节）。

**Returns:**
int
### setUlMode(int value) {#setUlMode-int-}
```
public void setUlMode(int value)
```


获取或设置一个 32 位无符号整数，指定渐变填充模式。该值必须位于 GradientFill 枚举中（第 2.1.15 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getVertexData() {#getVertexData--}
```
public EmfVertexData getVertexData()
```


获取或设置对象，这些对象指定矩形或三角形的顶点以及对应的颜色。

**Returns:**
[EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata)
### setVertexData(EmfVertexData value) {#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-}
```
public void setVertexData(EmfVertexData value)
```


获取或设置对象，这些对象指定矩形或三角形的顶点以及对应的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata) |  |

