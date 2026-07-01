---
title: "EmfGradientRectangle"
second_title: "Aspose.Imaging for Java API 参考"
description: "GradientRectangle 对象使用 TriVertex 对象（第 2.2.26 节）在 EMR_GRADIENTFILL 记录（第 2.3.5.12 节）中定义一个矩形。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfGradientRectangle extends EmfObject
```

GradientRectangle 对象在 EMR\_GRADIENTFILL 记录（第 2.3.5.12 节）中使用 TriVertex 对象（第 2.2.26 节）定义一个矩形。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfGradientRectangle()](#EmfGradientRectangle--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getUpperLeft()](#getUpperLeft--) | 获取或设置一个索引，指向 TriVertex 对象数组中指定矩形左上顶点的元素。 |
| [setUpperLeft(int value)](#setUpperLeft-int-) | 获取或设置一个索引，指向 TriVertex 对象数组中指定矩形左上顶点的元素。 |
| [getLowerRight()](#getLowerRight--) | 获取或设置一个索引，指向 TriVertex 对象数组中指定矩形右下顶点的元素。 |
| [setLowerRight(int value)](#setLowerRight-int-) | 获取或设置一个索引，指向 TriVertex 对象数组中指定矩形右下顶点的元素。 |
### EmfGradientRectangle() {#EmfGradientRectangle--}
```
public EmfGradientRectangle()
```


### getUpperLeft() {#getUpperLeft--}
```
public int getUpperLeft()
```


获取或设置一个索引，指向 TriVertex 对象数组中指定矩形左上顶点的元素。该索引必须小于数组的大小，由 EMR\\_GRADIENTFILL 记录的 nVer 字段定义。

**Returns:**
int
### setUpperLeft(int value) {#setUpperLeft-int-}
```
public void setUpperLeft(int value)
```


获取或设置一个索引，指向 TriVertex 对象数组中指定矩形左上顶点的元素。该索引必须小于数组的大小，由 EMR\\_GRADIENTFILL 记录的 nVer 字段定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLowerRight() {#getLowerRight--}
```
public int getLowerRight()
```


获取或设置一个索引，指向 TriVertex 对象数组中指定矩形右下顶点的元素。该索引必须小于数组的大小，由 EMR\\_GRADIENTFILL 记录的 nVer 字段定义。

**Returns:**
int
### setLowerRight(int value) {#setLowerRight-int-}
```
public void setLowerRight(int value)
```


获取或设置一个索引，指向 TriVertex 对象数组中指定矩形右下顶点的元素。该索引必须小于数组的大小，由 EMR\\_GRADIENTFILL 记录的 nVer 字段定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

