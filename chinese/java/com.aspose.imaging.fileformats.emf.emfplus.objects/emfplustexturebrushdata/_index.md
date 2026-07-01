---
title: "EmfPlusTextureBrushData"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 EmfPlusTextureBrushData 对象指定图形画刷的纹理图像。"
type: docs
weight: 77
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusTextureBrushData extends EmfPlusBaseBrushData
```

该 EmfPlusTextureBrushData 对象指定图形画刷的纹理图像。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | 获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。 |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | 获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。 |
| [getWrapMode()](#getWrapMode--) | 获取或设置一个来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，用于指定当图像小于填充区域时，如何在形状上重复纹理图像。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 获取或设置一个来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，用于指定当图像小于填充区域时，如何在形状上重复纹理图像。 |
| [getOptionalData()](#getOptionalData--) | 获取或设置一个可选的 EmfPlusTextureBrushOptionalData 对象（第 2.2.2.46 节），该对象指定纹理画笔的附加数据。 |
| [setOptionalData(EmfPlusTextureBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-) | 获取或设置一个可选的 EmfPlusTextureBrushOptionalData 对象（第 2.2.2.46 节），该对象指定纹理画笔的附加数据。 |
### EmfPlusTextureBrushData() {#EmfPlusTextureBrushData--}
```
public EmfPlusTextureBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。此值必须由 BrushData 标志（第 2.1.2.1 节）组成。以下标志与纹理画笔相关：BrushDataTransform、BrushDataIsGammaCorrected、BrushDataDoNotTransform。

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。此值必须由 BrushData 标志（第 2.1.2.1 节）组成。以下标志与纹理画笔相关：BrushDataTransform、BrushDataIsGammaCorrected、BrushDataDoNotTransform。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


获取或设置一个来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，用于指定当图像小于填充区域时，如何在形状上重复纹理图像。

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


获取或设置一个来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，用于指定当图像小于填充区域时，如何在形状上重复纹理图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusTextureBrushOptionalData getOptionalData()
```


获取或设置一个可选的 EmfPlusTextureBrushOptionalData 对象（第 2.2.2.46 节），该对象指定纹理画笔的附加数据。此字段的具体内容由 BrushDataFlags 字段的值决定。

**Returns:**
[EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata)
### setOptionalData(EmfPlusTextureBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-}
```
public void setOptionalData(EmfPlusTextureBrushOptionalData value)
```


获取或设置一个可选的 EmfPlusTextureBrushOptionalData 对象（第 2.2.2.46 节），该对象指定纹理画笔的附加数据。此字段的具体内容由 BrushDataFlags 字段的值决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata) |  |

