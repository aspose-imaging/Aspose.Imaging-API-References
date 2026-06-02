---
title: "EmfPolyTextOutW"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_POLYTEXTOUTW 记录使用当前字体和文本颜色绘制一个或多个 Unicode 文本字符串。"
type: docs
weight: 98
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutW extends EmfDrawingRecordType
```

EMR\_POLYTEXTOUTW 记录使用当前字体和文字颜色绘制一个或多个 Unicode 文本字符串。

输出使用的字体和文本颜色由回放设备上下文当前状态中的属性指定。应使用一系列 EMR\_EXTTEXTOUTW 记录（第 2.3.5.7 节）来模拟 EMR\_POLYTEXTOUTW，每个字符串对应一条记录。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPolyTextOutW(EmfRecord source)](#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfPolyTextOutW` 类的新实例。 |
| [EmfPolyTextOutW()](#EmfPolyTextOutW--) | 初始化 `EmfPolyTextOutW` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定设备单位中的边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定设备单位中的边界矩形。 |
| [getIGraphicsMode()](#getIGraphicsMode--) | 获取或设置一个 32 位无符号整数，指定当前图形模式，取自 GraphicsMode 枚举（第 2.1.16 节）。 |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | 获取或设置一个 32 位无符号整数，指定当前图形模式，取自 GraphicsMode 枚举（第 2.1.16 节）。 |
| [getExScale()](#getExScale--) | 获取或设置一个 32 位浮点值，指定 X 缩放比例（如果图形模式为 GM\\_COMPATIBLE，则从页面单位转换为 0.01mm 单位）。 |
| [setExScale(float value)](#setExScale-float-) | 获取或设置一个 32 位浮点值，指定 X 缩放比例（如果图形模式为 GM\\_COMPATIBLE，则从页面单位转换为 0.01mm 单位）。 |
| [getEyScale()](#getEyScale--) | 获取或设置一个 32 位浮点值，指定 Y 缩放比例（如果图形模式为 GM\\_COMPATIBLE，则从页面单位转换为 0.01mm 单位）。 |
| [setEyScale(float value)](#setEyScale-float-) | 获取或设置一个 32 位浮点值，指定 Y 缩放比例（如果图形模式为 GM\\_COMPATIBLE，则从页面单位转换为 0.01mm 单位）。 |
| [getWEmrText()](#getWEmrText--) | 获取或设置一个 EmrText 对象数组（第 2.2.5 节），该数组以 16 位 Unicode UTF16-LE 字符指定输出字符串，并包含文本属性和间距值。 |
| [setWEmrText(EmfText[] value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | 获取或设置一个 EmrText 对象数组（第 2.2.5 节），该数组以 16 位 Unicode UTF16-LE 字符指定输出字符串，并包含文本属性和间距值。 |
### EmfPolyTextOutW(EmfRecord source) {#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutW(EmfRecord source)
```


初始化 `EmfPolyTextOutW` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfPolyTextOutW() {#EmfPolyTextOutW--}
```
public EmfPolyTextOutW()
```


初始化 `EmfPolyTextOutW` 类的新实例。

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定设备单位中的边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定设备单位中的边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


获取或设置一个 32 位无符号整数，指定当前图形模式，取自 GraphicsMode 枚举（第 2.1.16 节）。

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


获取或设置一个 32 位无符号整数，指定当前图形模式，取自 GraphicsMode 枚举（第 2.1.16 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


获取或设置一个 32 位浮点值，指定 X 缩放比例（如果图形模式为 GM\\_COMPATIBLE，则从页面单位转换为 0.01mm 单位）。

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


获取或设置一个 32 位浮点值，指定 X 缩放比例（如果图形模式为 GM\\_COMPATIBLE，则从页面单位转换为 0.01mm 单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


获取或设置一个 32 位浮点值，指定 Y 缩放比例（如果图形模式为 GM\\_COMPATIBLE，则从页面单位转换为 0.01mm 单位）。

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


获取或设置一个 32 位浮点值，指定 Y 缩放比例（如果图形模式为 GM\\_COMPATIBLE，则从页面单位转换为 0.01mm 单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getWEmrText() {#getWEmrText--}
```
public EmfText[] getWEmrText()
```


获取或设置一个 EmrText 对象数组（第 2.2.5 节），该数组以 16 位 Unicode UTF16-LE 字符指定输出字符串，并包含文本属性和间距值。EmrText 对象的数量由 cStrings 指定。

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setWEmrText(EmfText[] value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setWEmrText(EmfText[] value)
```


获取或设置一个 EmrText 对象数组（第 2.2.5 节），该数组以 16 位 Unicode UTF16-LE 字符指定输出字符串，并包含文本属性和间距值。EmrText 对象的数量由 cStrings 指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

