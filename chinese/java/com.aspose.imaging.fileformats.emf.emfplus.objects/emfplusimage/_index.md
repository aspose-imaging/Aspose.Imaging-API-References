---
title: "EmfPlusImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusImage 对象指定以位图或元文件形式的图形图像。"
type: docs
weight: 47
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImage extends EmfPlusGraphicsObjectType
```

EmfPlusImage 对象指定以位图或元文件形式的图形图像。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusImage()](#EmfPlusImage--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getImageData()](#getImageData--) | 获取或设置 Image data 变量长度数据，该数据定义了 Type 字段中指定的图像数据。 |
| [setImageData(EmfPlusBaseImageData value)](#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-) | 获取或设置 Image data 变量长度数据，该数据定义了 Type 字段中指定的图像数据。 |
| [getType()](#getType--) | 获取或设置 image type，一个 32 位无符号整数，指定 ImageData 字段中的数据类型。 |
| [setType(int value)](#setType-int-) | 获取或设置 image type，一个 32 位无符号整数，指定 ImageData 字段中的数据类型。 |
### EmfPlusImage() {#EmfPlusImage--}
```
public EmfPlusImage()
```


### getImageData() {#getImageData--}
```
public EmfPlusBaseImageData getImageData()
```


获取或设置 Image data 变量长度数据，该数据定义了 Type 字段中指定的图像数据。该数据的内容和格式可能因每种 image type 而异。

**Returns:**
[EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
### setImageData(EmfPlusBaseImageData value) {#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-}
```
public void setImageData(EmfPlusBaseImageData value)
```


获取或设置 Image data 变量长度数据，该数据定义了 Type 字段中指定的图像数据。该数据的内容和格式可能因每种 image type 而异。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata) |  |

### getType() {#getType--}
```
public int getType()
```


获取或设置 image type，一个 32 位无符号整数，指定 ImageData 字段中的数据类型。此值必须在 ImageDataType 枚举中定义（第 2.1.1.15 节）。

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


获取或设置 image type，一个 32 位无符号整数，指定 ImageData 字段中的数据类型。此值必须在 ImageDataType 枚举中定义（第 2.1.1.15 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

