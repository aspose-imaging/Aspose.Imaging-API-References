---
title: "EmfPlusRotateWorldTransform"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusRotateWorldTransform 记录对当前世界空间变换执行旋转。"
type: docs
weight: 50
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusRotateWorldTransform extends EmfPlusTerminalServerRecordType
```

EmfPlusRotateWorldTransform 记录对当前世界空间变换执行旋转。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusRotateWorldTransform(EmfPlusRecord source)](#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusRotateWorldTransform` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | 获取一个值，指示是否为[post multiplied matrix]。 |
| [getAngle()](#getAngle--) | 获取或设置一个 32 位浮点值，指定以度为单位的旋转角度。 |
| [setAngle(float value)](#setAngle-float-) | 获取或设置一个 32 位浮点值，指定以度为单位的旋转角度。 |
### EmfPlusRotateWorldTransform(EmfPlusRecord source) {#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRotateWorldTransform(EmfPlusRecord source)
```


初始化 `EmfPlusRotateWorldTransform` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


获取一个值，指示是否为[post multiplied matrix]。如果设置，变换矩阵应后乘。如果清除，应前乘。

值：`true` 表示[post multiplied matrix]；否则为 `false`。

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public float getAngle()
```


获取或设置一个 32 位浮点值，指定以度为单位的旋转角度。该操作通过从以下图示构建新的变换矩阵来执行：
---------------------------------
| sin(Angle) | cos(Angle) | 0 |
| cos(Angle) | sin(Angle) | 0 |
---------------------------------

图 2：旋转变换矩阵

当前世界空间变换将与此矩阵相乘，结果成为新的当前世界空间变换。Flags 字段决定乘法的顺序。

值：角度。

**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


获取或设置一个 32 位浮点值，指定以度为单位的旋转角度。该操作通过从以下图示构建新的变换矩阵来执行：
---------------------------------
| sin(Angle) | cos(Angle) | 0 |
| cos(Angle) | sin(Angle) | 0 |
---------------------------------

图 2：旋转变换矩阵

当前世界空间变换将与此矩阵相乘，结果成为新的当前世界空间变换。Flags 字段决定乘法的顺序。

值：角度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

