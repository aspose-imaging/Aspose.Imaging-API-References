---
title: "EmfPlusBitmapData"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusBitmapData 对象指定带有像素数据的位图图像。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusBitmapData extends EmfPlusBaseBitmapData
```

EmfPlusBitmapData 对象指定带有像素数据的位图图像。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColors()](#getColors--) | 获取或设置 调色板颜色 Colors（可变）：一个可选的 `EmfPlusPalette` 对象（第 2.2.2.28 节），指定像素数据中使用的颜色调色板。 |
| [setColors(EmfPlusPalette value)](#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | 获取或设置 调色板颜色 Colors（可变）：一个可选的 `EmfPlusPalette` 对象（第 2.2.2.28 节），指定像素数据中使用的颜色调色板。 |
| [getPixelData()](#getPixelData--) | 获取或设置 像素数据 PixelData（可变）：一个字节数组，指定像素数据。 |
| [setPixelData(byte[] value)](#setPixelData-byte---) | 获取或设置 像素数据 PixelData（可变）：一个字节数组，指定像素数据。 |
### EmfPlusBitmapData() {#EmfPlusBitmapData--}
```
public EmfPlusBitmapData()
```


### getColors() {#getColors--}
```
public EmfPlusPalette getColors()
```


获取或设置 调色板颜色 Colors（可变）：一个可选的 `EmfPlusPalette` 对象（第 2.2.2.28 节），指定像素数据中使用的颜色调色板。如果在 `EmfPlusBitmap` 对象的 PixelFormat 字段中设置了 I 标志，则此字段 MUST 存在。

值: 颜色。

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setColors(EmfPlusPalette value) {#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setColors(EmfPlusPalette value)
```


获取或设置 调色板颜色 Colors（可变）：一个可选的 `EmfPlusPalette` 对象（第 2.2.2.28 节），指定像素数据中使用的颜色调色板。如果在 `EmfPlusBitmap` 对象的 PixelFormat 字段中设置了 I 标志，则此字段 MUST 存在。

值: 颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

### getPixelData() {#getPixelData--}
```
public byte[] getPixelData()
```


获取或设置 像素数据 PixelData（可变）：一个字节数组，指定像素数据。此数据的大小和格式可根据 EmfPlusBitmap 对象中的字段计算，包括来自 `Consts.EmfPlusPixelFormat` 枚举（第 2.1.1.25 节）的像素格式。

值：像素数据。

**Returns:**
byte[]
### setPixelData(byte[] value) {#setPixelData-byte---}
```
public void setPixelData(byte[] value)
```


获取或设置 像素数据 PixelData（可变）：一个字节数组，指定像素数据。此数据的大小和格式可根据 EmfPlusBitmap 对象中的字段计算，包括来自 `Consts.EmfPlusPixelFormat` 枚举（第 2.1.1.25 节）的像素格式。

值：像素数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

