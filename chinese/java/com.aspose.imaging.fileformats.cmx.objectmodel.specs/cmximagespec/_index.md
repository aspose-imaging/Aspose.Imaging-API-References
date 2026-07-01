---
title: "CmxImageSpec"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示为光栅图像指定的信息。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxImageSpec implements ICmxObjectSpec
```

表示为光栅图像指定的信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CmxImageSpec()](#CmxImageSpec--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBoundBox()](#getBoundBox--) | 获取边界框。 |
| [setBoundBox(RectangleF value)](#setBoundBox-com.aspose.imaging.RectangleF-) | 设置边界框。 |
| [getCropBox()](#getCropBox--) | 获取裁剪框。 |
| [setCropBox(RectangleF value)](#setCropBox-com.aspose.imaging.RectangleF-) | 设置裁剪框。 |
| [getMatrix()](#getMatrix--) | 获取变换矩阵。 |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.imaging.Matrix-) | 设置变换矩阵。 |
| [getImageType()](#getImageType--) | 获取图像的类型。 |
| [setImageType(int value)](#setImageType-int-) | 设置图像的类型。 |
| [getImages()](#getImages--) | 获取图像。 |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | 设置图像。 |
| [isCmx3Image()](#isCmx3Image--) | 获取指示此实例是否为 CMX3 图像的值。 |
| [setCmx3Image(boolean value)](#setCmx3Image-boolean-) | 设置指示此实例是否为 CMX3 图像的值。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [toArray()](#toArray--) |  |
| [equals(Object o)](#equals-java.lang.Object-) | 检查对象是否相等。 |
| [hashCode()](#hashCode--) | 获取当前对象的哈希码。 |
### CmxImageSpec() {#CmxImageSpec--}
```
public CmxImageSpec()
```


### getBoundBox() {#getBoundBox--}
```
public final RectangleF getBoundBox()
```


获取边界框。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bound box.
### setBoundBox(RectangleF value) {#setBoundBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundBox(RectangleF value)
```


设置边界框。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | 边界框。 |

### getCropBox() {#getCropBox--}
```
public final RectangleF getCropBox()
```


获取裁剪框。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the crop box.
### setCropBox(RectangleF value) {#setCropBox-com.aspose.imaging.RectangleF-}
```
public final void setCropBox(RectangleF value)
```


设置裁剪框。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | 裁剪框。 |

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


获取变换矩阵。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - the transformation matrix.
### setMatrix(Matrix value) {#setMatrix-com.aspose.imaging.Matrix-}
```
public final void setMatrix(Matrix value)
```


设置变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | 变换矩阵。 |

### getImageType() {#getImageType--}
```
public final int getImageType()
```


获取图像的类型。

**Returns:**
int - 图像的类型。
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


设置图像的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 图像的类型。 |

### getImages() {#getImages--}
```
public final CmxRasterImage[] getImages()
```


获取图像。

**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[] - 图像。
### setImages(CmxRasterImage[] value) {#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---}
```
public final void setImages(CmxRasterImage[] value)
```


设置图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CmxRasterImage\[\]](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage) | 图像。 |

### isCmx3Image() {#isCmx3Image--}
```
public final boolean isCmx3Image()
```


获取指示此实例是否为 CMX3 图像的值。

值：如果此实例是 CMX3 图像则为 `true`；否则为 `false`。

**Returns:**
boolean - 指示此实例是否为 CMX3 图像的值。
### setCmx3Image(boolean value) {#setCmx3Image-boolean-}
```
public final void setCmx3Image(boolean value)
```


设置指示此实例是否为 CMX3 图像的值。

值：如果此实例是 CMX3 图像则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示此实例是否为 CMX3 图像的值。 |

### toString() {#toString--}
```
public String toString()
```


返回表示此实例的字符串。

**Returns:**
java.lang.String - 表示此实例的字符串。
### toArray() {#toArray--}
```
public CmxRasterImage[] toArray()
```




**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[]
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


检查对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | java.lang.Object | 其他对象。 |

**Returns:**
boolean - 相等比较结果。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取当前对象的哈希码。

**Returns:**
int - 哈希码。
