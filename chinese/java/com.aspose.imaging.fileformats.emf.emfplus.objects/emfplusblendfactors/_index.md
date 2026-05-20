---
title: "EmfPlusBlendFactors"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusBlendFactors 对象指定渐变画笔的混合模式的位置信息和因子。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
```
public final class EmfPlusBlendFactors extends EmfPlusBlendBase
```

EmfPlusBlendFactors 对象指定渐变画笔的混合模式的位置信息和因子。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusBlendFactors()](#EmfPlusBlendFactors--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlendFactors()](#getBlendFactors--) | 获取或设置一个由 PositionCount 个 32 位浮点值组成的数组，用于指定 BlendPositions 字段中定义的位置处的颜色比例。 |
| [setBlendFactors(float[] value)](#setBlendFactors-float---) | 获取或设置一个由 PositionCount 个 32 位浮点值组成的数组，用于指定 BlendPositions 字段中定义的位置处的颜色比例。 |
### EmfPlusBlendFactors() {#EmfPlusBlendFactors--}
```
public EmfPlusBlendFactors()
```


### getBlendFactors() {#getBlendFactors--}
```
public float[] getBlendFactors()
```


获取或设置一个由 PositionCount 个 32 位浮点值组成的数组，用于指定 BlendPositions 字段中定义的位置处的颜色比例。每个值必须是介于 0.0 到 1.0（含）之间的数字。

**Returns:**
float[]
### setBlendFactors(float[] value) {#setBlendFactors-float---}
```
public void setBlendFactors(float[] value)
```


获取或设置一个由 PositionCount 个 32 位浮点值组成的数组，用于指定 BlendPositions 字段中定义的位置处的颜色比例。每个值必须是介于 0.0 到 1.0（含）之间的数字。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |

