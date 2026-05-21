---
title: "EmfPlusRedEyeCorrectionEffect"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "RedEyeCorrectionEffect 对象指定图像中需要进行红眼校正的区域。"
type: docs
weight: 67
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusredeyecorrectioneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusRedEyeCorrectionEffect extends EmfPlusImageEffectsObjectType
```

RedEyeCorrectionEffect 对象指定图像中需要进行红眼校正的区域。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusRedEyeCorrectionEffect()](#EmfPlusRedEyeCorrectionEffect--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNumberOfAreas()](#getNumberOfAreas--) | 获取或设置一个 32 位有符号整数，指定 Areas 字段中的矩形数量。 |
| [setNumberOfAreas(int value)](#setNumberOfAreas-int-) | 获取或设置一个 32 位有符号整数，指定 Areas 字段中的矩形数量。 |
| [getAreas()](#getAreas--) | 获取或设置一个 NumberOfAreas WMF RectL 对象数组，详见 [MS-WMF] 第 2.2.2.19 节。 |
| [setAreas(Rectangle[] value)](#setAreas-com.aspose.imaging.Rectangle---) | 获取或设置一个 NumberOfAreas WMF RectL 对象数组，详见 [MS-WMF] 第 2.2.2.19 节。 |
### EmfPlusRedEyeCorrectionEffect() {#EmfPlusRedEyeCorrectionEffect--}
```
public EmfPlusRedEyeCorrectionEffect()
```


### getNumberOfAreas() {#getNumberOfAreas--}
```
public int getNumberOfAreas()
```


获取或设置一个 32 位有符号整数，指定 Areas 字段中的矩形数量。

值：区域的数量。

**Returns:**
int
### setNumberOfAreas(int value) {#setNumberOfAreas-int-}
```
public void setNumberOfAreas(int value)
```


获取或设置一个 32 位有符号整数，指定 Areas 字段中的矩形数量。

值：区域的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAreas() {#getAreas--}
```
public Rectangle[] getAreas()
```


获取或设置 An 数组的 NumberOfAreas WMF RectL 对象，指定于 [MS-WMF] 第 2.2.2.19 节。每个矩形指定位图图像的一个区域，红眼校正效果 SHOULD 应用于该区域。

值：区域。

**Returns:**
com.aspose.imaging.Rectangle[]
### setAreas(Rectangle[] value) {#setAreas-com.aspose.imaging.Rectangle---}
```
public void setAreas(Rectangle[] value)
```


获取或设置 An 数组的 NumberOfAreas WMF RectL 对象，指定于 [MS-WMF] 第 2.2.2.19 节。每个矩形指定位图图像的一个区域，红眼校正效果 SHOULD 应用于该区域。

值：区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

