---
title: "EmfPlusTextureBrushOptionalData"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 EmfPlusTextureBrushOptionalData 对象指定纹理画刷的可选数据。"
type: docs
weight: 78
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusTextureBrushOptionalData extends EmfPlusStructureObjectType
```

该 EmfPlusTextureBrushOptionalData 对象指定纹理画刷的可选数据。

注意 此对象的每个字段都是可选的，可能不会出现在 EmfPlusTextureBrushData 对象（第 2.2.2.45 节）的 OptionalData 字段中，具体取决于其 BrushDataFlags 字段中设置的 BrushData 标志（第 2.1.2.1 节）。虽然不实际列出每一种可能的字段出现或缺失的组合，但本节规定了它们在对象中的相对顺序。实现者负责确定在给定的元文件记录中实际存在哪些字段，并分别且适当地对各字段的数据进行解组。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定纹理画刷的世界空间到设备空间的变换。 |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定纹理画刷的世界空间到设备空间的变换。 |
| [getImageObject()](#getImageObject--) | 获取或设置一个可选的 EmfPlusImage 对象（第 2.2.1.4 节），该对象指定画刷纹理。 |
| [setImageObject(EmfPlusImage value)](#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-) | 获取或设置一个可选的 EmfPlusImage 对象（第 2.2.1.4 节），该对象指定画刷纹理。 |
### EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData--}
```
public EmfPlusTextureBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定纹理画刷的世界空间到设备空间的变换。如果在 EmfPlusTextureBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则此字段必须存在。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定纹理画刷的世界空间到设备空间的变换。如果在 EmfPlusTextureBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getImageObject() {#getImageObject--}
```
public EmfPlusImage getImageObject()
```


获取或设置一个可选的 EmfPlusImage 对象（第 2.2.1.4 节），该对象指定画刷纹理。如果定义此纹理画刷的 EmfPlusObject 记录（第 2.3.5.1 节）的大小足以容纳除 EmfPlusTextureBrushData 对象的必需字段之外的 EmfPlusImage 对象（以及可选的 EmfPlusTransformMatrix 对象），则此字段必须存在。

**Returns:**
[EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)
### setImageObject(EmfPlusImage value) {#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-}
```
public void setImageObject(EmfPlusImage value)
```


获取或设置一个可选的 EmfPlusImage 对象（第 2.2.1.4 节），该对象指定画刷纹理。如果定义此纹理画刷的 EmfPlusObject 记录（第 2.3.5.1 节）的大小足以容纳除 EmfPlusTextureBrushData 对象的必需字段之外的 EmfPlusImage 对象（以及可选的 EmfPlusTransformMatrix 对象），则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) |  |

