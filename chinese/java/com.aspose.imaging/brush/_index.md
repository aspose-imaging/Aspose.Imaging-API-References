---
title: "Brush"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "基础画刷类。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging/brush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class Brush extends DisposableObject
```

基础画刷类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Brush()](#Brush--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOpacity()](#getOpacity--) | 获取画笔的不透明度。 |
| [setOpacity(float value)](#setOpacity-float-) | 设置画笔的不透明度。 |
| [deepClone()](#deepClone--) | 创建当前 `Brush` 的新深度克隆。 |
| [equals(Object o)](#equals-java.lang.Object-) | 检查对象是否相等。 |
| [hashCode()](#hashCode--) | 获取当前对象的哈希码。 |
### Brush() {#Brush--}
```
public Brush()
```


### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


获取画笔的不透明度。该值应在 0 到 1 之间。值为 0 表示画笔完全可见，值为 1 表示画笔完全不透明。

**Returns:**
float - 画笔不透明度值。
### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


设置画笔的不透明度。该值应在 0 到 1 之间。值为 0 表示画笔完全可见，值为 1 表示画笔完全不透明。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 画笔不透明度值。 |

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


创建当前 `Brush` 的新深度克隆。

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A new `Brush` which is the deep clone of this `Brush` instance.
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
