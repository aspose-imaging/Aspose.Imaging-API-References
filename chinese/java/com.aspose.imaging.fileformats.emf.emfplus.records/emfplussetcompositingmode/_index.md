---
title: "EmfPlusSetCompositingMode"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该 EmfPlusSetCompositingMode 记录指定源颜色如何与背景颜色组合。"
type: docs
weight: 58
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetCompositingMode extends EmfPlusPropertyRecordType
```

该 EmfPlusSetCompositingMode 记录指定源颜色如何与背景颜色组合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusSetCompositingMode(EmfPlusRecord source)](#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusSetCompositingMode` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompositingMode()](#getCompositingMode--) | 获取或设置合成模式值，来自 CompositingMode 枚举（第 2.1.1.5 节）。 |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | 获取或设置合成模式值，来自 CompositingMode 枚举（第 2.1.1.5 节）。 |
### EmfPlusSetCompositingMode(EmfPlusRecord source) {#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetCompositingMode(EmfPlusRecord source)
```


初始化 `EmfPlusSetCompositingMode` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


获取或设置合成模式值，来自 CompositingMode 枚举（第 2.1.1.5 节）。合成可以表示为 alpha 混合的状态，可能开启或关闭。

值: 合成模式。

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


获取或设置合成模式值，来自 CompositingMode 枚举（第 2.1.1.5 节）。合成可以表示为 alpha 混合的状态，可能开启或关闭。

值: 合成模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

