---
title: "EmfRop4"
second_title: "Aspose.Imaging for Java API 参考"
description: "一种四元光栅操作，用于指定位图前景色和背景色的三元光栅操作。"
type: docs
weight: 110
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfrop4/
---
**Inheritance:**
java.lang.Object
```
public final class EmfRop4
```

一种四元光栅操作，用于指定位图前景色和背景色的三元光栅操作。这些值定义了如何将源矩形的颜色数据与目标矩形的颜色数据合并。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfRop4(int dwordData)](#EmfRop4-int-) | 初始化 `EmfRop4` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBackgroundRop3()](#getBackgroundRop3--) | 获取背景 ROP3。 |
| [getForegroundRop3()](#getForegroundRop3--) | 获取前景 ROP3。 |
### EmfRop4(int dwordData) {#EmfRop4-int-}
```
public EmfRop4(int dwordData)
```


初始化 `EmfRop4` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dwordData | int | 该 dword 数据。 |

### getBackgroundRop3() {#getBackgroundRop3--}
```
public byte getBackgroundRop3()
```


获取背景 ROP3。该值是 WMF 三元光栅操作枚举（[MS-WMF] 第 2.1.1.31 节）中 24 位三元光栅操作值的无符号最高 8 位。此代码定义了如何将源位图和目标位图以及画刷图案的背景颜色数据进行合并。

值：背景 ROP3。

**Returns:**
byte
### getForegroundRop3() {#getForegroundRop3--}
```
public byte getForegroundRop3()
```


获取前景 ROP3。该值是 WMF 三元光栅操作枚举中 24 位三元光栅操作值的无符号最高 8 位。此代码定义了如何将源位图和目标位图以及画刷图案的前景颜色数据进行合并。

值：前景 ROP3。

**Returns:**
byte
