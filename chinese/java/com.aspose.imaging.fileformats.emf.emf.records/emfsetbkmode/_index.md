---
title: "EmfSetBkMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETBKMODE 记录指定回放设备上下文的背景混合模式。"
type: docs
weight: 120
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetBkMode extends EmfStateRecordType
```

EMR\_SETBKMODE 记录指定回放设备上下文的背景混合模式。背景混合模式用于文本、交叉线画刷以及非实线的笔样式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetBkMode(EmfRecord source)](#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetBkMode` 类的新实例。 |
| [EmfSetBkMode()](#EmfSetBkMode--) | 初始化 `EmfSetBkMode` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | 获取或设置一个 32 位无符号整数，指定背景模式，并且必须位于 BackgroundMode（第 2.1.4 节）枚举中。 |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | 获取或设置一个 32 位无符号整数，指定背景模式，并且必须位于 BackgroundMode（第 2.1.4 节）枚举中。 |
### EmfSetBkMode(EmfRecord source) {#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetBkMode(EmfRecord source)
```


初始化 `EmfSetBkMode` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfSetBkMode() {#EmfSetBkMode--}
```
public EmfSetBkMode()
```


初始化 `EmfSetBkMode` 类的新实例。

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


获取或设置一个 32 位无符号整数，指定背景模式，并且必须位于 BackgroundMode（第 2.1.4 节）枚举中。

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


获取或设置一个 32 位无符号整数，指定背景模式，并且必须位于 BackgroundMode（第 2.1.4 节）枚举中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

