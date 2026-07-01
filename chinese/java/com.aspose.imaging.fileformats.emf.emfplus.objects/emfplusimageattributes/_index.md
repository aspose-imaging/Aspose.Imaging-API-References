---
title: "EmfPlusImageAttributes"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusImageAttributes 对象指定在渲染过程中如何操作位图图像的颜色。"
type: docs
weight: 48
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImageAttributes extends EmfPlusGraphicsObjectType
```

EmfPlusImageAttributes 对象指定在渲染过程中如何操作位图图像的颜色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | 获取或设置一个 32 位无符号整数，指定如何使用 WrapMode 枚举（第 2.1.1.34 节）中的值来处理边缘条件。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 获取或设置一个 32 位无符号整数，指定如何使用 WrapMode 枚举（第 2.1.1.34 节）中的值来处理边缘条件。 |
| [getClampArgb32Color()](#getClampArgb32Color--) | 获取或设置 EmfPlusARGB（第 2.2.2.1 节）对象，指定当 WrapMode 值为 WrapModeClamp 时使用的边缘颜色。 |
| [setClampArgb32Color(int value)](#setClampArgb32Color-int-) | 获取或设置 EmfPlusARGB（第 2.2.2.1 节）对象，指定当 WrapMode 值为 WrapModeClamp 时使用的边缘颜色。 |
| [getObjectClamp()](#getObjectClamp--) | 获取或设置一个 32 位有符号整数，指定对象的夹持行为。 |
| [setObjectClamp(int value)](#setObjectClamp-int-) | 获取或设置一个 32 位有符号整数，指定对象的夹持行为。 |
### EmfPlusImageAttributes() {#EmfPlusImageAttributes--}
```
public EmfPlusImageAttributes()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


获取或设置一个 32 位无符号整数，指定如何使用 WrapMode 枚举（第 2.1.1.34 节）中的值来处理边缘条件。

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


获取或设置一个 32 位无符号整数，指定如何使用 WrapMode 枚举（第 2.1.1.34 节）中的值来处理边缘条件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getClampArgb32Color() {#getClampArgb32Color--}
```
public int getClampArgb32Color()
```


获取或设置 EmfPlusARGB（第 2.2.2.1 节）对象，指定当 WrapMode 值为 WrapModeClamp 时使用的边缘颜色。当 EmfPlusDrawImage（第 2.3.4.8 节）记录处理的源矩形大于图像本身时，该颜色可见。

**Returns:**
int
### setClampArgb32Color(int value) {#setClampArgb32Color-int-}
```
public void setClampArgb32Color(int value)
```


获取或设置 EmfPlusARGB（第 2.2.2.1 节）对象，指定当 WrapMode 值为 WrapModeClamp 时使用的边缘颜色。当 EmfPlusDrawImage（第 2.3.4.8 节）记录处理的源矩形大于图像本身时，该颜色可见。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getObjectClamp() {#getObjectClamp--}
```
public int getObjectClamp()
```


获取或设置一个 32 位有符号整数，指定对象的夹持行为。该值在此对象应用于正在绘制的图像之前不会使用。此值必须是下表中定义的值之一。

**Returns:**
int
### setObjectClamp(int value) {#setObjectClamp-int-}
```
public void setObjectClamp(int value)
```


获取或设置一个 32 位有符号整数，指定对象的夹持行为。该值在此对象应用于正在绘制的图像之前不会使用。此值必须是下表中定义的值之一。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

