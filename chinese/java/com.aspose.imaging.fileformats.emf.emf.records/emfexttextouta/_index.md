---
title: "EmfExtTextOutA"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_EXTTEXTOUTA 记录使用当前字体和文本颜色绘制 ASCII 文本字符串。"
type: docs
weight: 56
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtTextOutA extends EmfDrawingRecordType
```

EMR_EXTTEXTOUTA 记录使用当前字体和文本颜色绘制 ASCII 文本字符串。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfExtTextOutA(EmfRecord source)](#EmfExtTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfExtTextOutA` 类的新实例。 |
| [EmfExtTextOutA()](#EmfExtTextOutA--) | 初始化 [EmfExtTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节）。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节）。 |
| [getIGraphicsMode()](#getIGraphicsMode--) | 获取或设置一个 32 位无符号整数，指定来自 GraphicsMode 枚举（第 2.1.16 节）的图形模式。 |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | 获取或设置一个 32 位无符号整数，指定来自 GraphicsMode 枚举（第 2.1.16 节）的图形模式。 |
| [getExScale()](#getExScale--) | 获取或设置一个 32 位浮点值，指定沿 X 轴的比例因子，用于将页面空间单位转换为 0.01 毫米单位。 |
| [setExScale(float value)](#setExScale-float-) | 获取或设置一个 32 位浮点值，指定沿 X 轴的比例因子，用于将页面空间单位转换为 0.01 毫米单位。 |
| [getEyScale()](#getEyScale--) | 获取或设置一个 32 位浮点值，指定沿 Y 轴的比例因子，用于将页面空间单位转换为 0.01 毫米单位。 |
| [setEyScale(float value)](#setEyScale-float-) | 获取或设置一个 32 位浮点值，指定沿 Y 轴的比例因子，用于将页面空间单位转换为 0.01 毫米单位。 |
| [getAEmrText()](#getAEmrText--) | 获取或设置一个 EmrText 对象（第 2.2.5 节），该对象指定 8 位 ASCII 字符的输出字符串、文本属性和间距值。 |
| [setAEmrText(EmfText value)](#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-) | 获取或设置一个 EmrText 对象（第 2.2.5 节），该对象指定 8 位 ASCII 字符的输出字符串、文本属性和间距值。 |
### EmfExtTextOutA(EmfRecord source) {#EmfExtTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtTextOutA(EmfRecord source)
```


初始化 `EmfExtTextOutA` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfExtTextOutA() {#EmfExtTextOutA--}
```
public EmfExtTextOutA()
```


初始化 [EmfExtTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta) 类的新实例。

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节）。该对象未使用，接收时必须忽略。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节）。该对象未使用，接收时必须忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


获取或设置一个 32 位无符号整数，指定来自 GraphicsMode 枚举（第 2.1.16 节）的图形模式。

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


获取或设置一个 32 位无符号整数，指定来自 GraphicsMode 枚举（第 2.1.16 节）的图形模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


获取或设置一个 32 位浮点值，指定沿 X 轴的比例因子，用于将页面空间单位转换为 0.01 毫米单位。仅当 iGraphicsMode 指定的图形模式为 GM\_COMPATIBLE 时才应使用此值。

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


获取或设置一个 32 位浮点值，指定沿 X 轴的比例因子，用于将页面空间单位转换为 0.01 毫米单位。仅当 iGraphicsMode 指定的图形模式为 GM\_COMPATIBLE 时才应使用此值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


获取或设置一个 32 位浮点值，指定沿 Y 轴的比例因子，用于将页面空间单位转换为 0.01 毫米单位。仅当 iGraphicsMode 指定的图形模式为 GM\_COMPATIBLE 时才应使用此值。

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


获取或设置一个 32 位浮点值，指定沿 Y 轴的比例因子，用于将页面空间单位转换为 0.01 毫米单位。仅当 iGraphicsMode 指定的图形模式为 GM\_COMPATIBLE 时才应使用此值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getAEmrText() {#getAEmrText--}
```
public EmfText getAEmrText()
```


获取或设置一个 EmrText 对象（第 2.2.5 节），该对象指定 8 位 ASCII 字符的输出字符串、文本属性和间距值。

**Returns:**
[EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext)
### setAEmrText(EmfText value) {#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-}
```
public void setAEmrText(EmfText value)
```


获取或设置一个 EmrText 对象（第 2.2.5 节），该对象指定 8 位 ASCII 字符的输出字符串、文本属性和间距值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

