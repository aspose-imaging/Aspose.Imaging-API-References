---
title: "EmfPlusSetAntiAliasMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 EmfPlusSetAntiAliasMode 记录指定文本输出的抗锯齿模式。"
type: docs
weight: 54
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetAntiAliasMode extends EmfPlusPropertyRecordType
```

该 EmfPlusSetAntiAliasMode 记录指定文本输出的抗锯齿模式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusSetAntiAliasMode(EmfPlusRecord source)](#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusSetAntiAliasMode` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | 获取或设置平滑模式。 |
| [setSmoothingMode(byte value)](#setSmoothingMode-byte-) | 获取或设置平滑模式。 |
| [getAntiAliasing()](#getAntiAliasing--) | 获取或设置指示是否启用[anti aliasing]的值。 |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | 获取或设置指示是否启用[anti aliasing]的值。 |
### EmfPlusSetAntiAliasMode(EmfPlusRecord source) {#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetAntiAliasMode(EmfPlusRecord source)
```


初始化 `EmfPlusSetAntiAliasMode` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getSmoothingMode() {#getSmoothingMode--}
```
public byte getSmoothingMode()
```


获取或设置平滑模式。（7 位）：平滑模式值，来自 SmoothingMode 枚举（第 2.1.1.28 节）

值：平滑模式。

**Returns:**
byte
### setSmoothingMode(byte value) {#setSmoothingMode-byte-}
```
public void setSmoothingMode(byte value)
```


获取或设置平滑模式。（7 位）：平滑模式值，来自 SmoothingMode 枚举（第 2.1.1.28 节）

值：平滑模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getAntiAliasing() {#getAntiAliasing--}
```
public boolean getAntiAliasing()
```


获取或设置指示是否启用[anti aliasing]的值。如果设置，则应执行抗锯齿；如果未设置，则不应执行抗锯齿。

值：如果[anti aliasing]为 `true`；否则为 `false`。

**Returns:**
boolean
### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public void setAntiAliasing(boolean value)
```


获取或设置指示是否启用[anti aliasing]的值。如果设置，则应执行抗锯齿；如果未设置，则不应执行抗锯齿。

值：如果[anti aliasing]为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

