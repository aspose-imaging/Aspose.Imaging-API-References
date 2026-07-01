---
title: "EmfPlusBlendBase"
second_title: "Aspose.Imaging for Java API 参考"
description: "blend objects 的基对象。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public abstract class EmfPlusBlendBase extends EmfPlusStructureObjectType
```

blend objects 的基对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusBlendBase()](#EmfPlusBlendBase--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlendPositions()](#getBlendPositions--) | 获取或设置混合位置，一个包含 PositionCount 个 32 位浮点值的数组，这些值指定沿渐变线的距离比例。 |
| [setBlendPositions(float[] value)](#setBlendPositions-float---) | 获取或设置混合位置，一个包含 PositionCount 个 32 位浮点值的数组，这些值指定沿渐变线的距离比例。 |
### EmfPlusBlendBase() {#EmfPlusBlendBase--}
```
public EmfPlusBlendBase()
```


### getBlendPositions() {#getBlendPositions--}
```
public float[] getBlendPositions()
```


获取或设置混合位置，一个包含 PositionCount 个 32 位浮点值的数组，这些值指定沿渐变线的距离比例。每个元素必须是介于 0.0 和 1.0（含）之间的数字。对于线性渐变画刷，0.0 表示起始点，1.0 表示结束点。对于路径渐变画刷，0.0 表示中点，1.0 表示端点。

**Returns:**
float[]
### setBlendPositions(float[] value) {#setBlendPositions-float---}
```
public void setBlendPositions(float[] value)
```


获取或设置混合位置，一个包含 PositionCount 个 32 位浮点值的数组，这些值指定沿渐变线的距离比例。每个元素必须是介于 0.0 和 1.0（含）之间的数字。对于线性渐变画刷，0.0 表示起始点，1.0 表示结束点。对于路径渐变画刷，0.0 表示中点，1.0 表示端点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float[] |  |

