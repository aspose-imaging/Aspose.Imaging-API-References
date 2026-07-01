---
title: "EmfRestoreDc"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_RESTOREDC 记录将回放设备上下文恢复到指定状态。"
type: docs
weight: 109
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfRestoreDc extends EmfStateRecordType
```

EMR\_RESTOREDC 记录将回放设备上下文恢复到指定状态。回放设备上下文通过弹出先前 EMR\_SAVEDC 记录（第 2.3.11 节）创建的堆栈中的状态信息来恢复。

该栈可以包含多个回放设备上下文实例的状态信息。当状态被恢复时，所有较近期保存的状态实例必须被丢弃。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfRestoreDc(EmfRecord source)](#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfRestoreDc` 类的新实例。 |
| [EmfRestoreDc()](#EmfRestoreDc--) | 初始化 `EmfRestoreDc` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSavedDc()](#getSavedDc--) | 获取或设置一个 32 位有符号整数，该整数指定相对于当前状态要恢复的已保存状态。 |
| [setSavedDc(int value)](#setSavedDc-int-) | 获取或设置一个 32 位有符号整数，该整数指定相对于当前状态要恢复的已保存状态。 |
### EmfRestoreDc(EmfRecord source) {#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRestoreDc(EmfRecord source)
```


初始化 `EmfRestoreDc` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfRestoreDc() {#EmfRestoreDc--}
```
public EmfRestoreDc()
```


初始化 `EmfRestoreDc` 类的新实例。

### getSavedDc() {#getSavedDc--}
```
public int getSavedDc()
```


获取或设置一个 32 位有符号整数，该整数指定相对于当前状态要恢复的已保存状态。此值必须为负；\\u20131 表示堆栈中最近保存的状态，\\u20132 表示其前一个状态，依此类推。

**Returns:**
int
### setSavedDc(int value) {#setSavedDc-int-}
```
public void setSavedDc(int value)
```


获取或设置一个 32 位有符号整数，该整数指定相对于当前状态要恢复的已保存状态。此值必须为负；\\u20131 表示堆栈中最近保存的状态，\\u20132 表示其前一个状态，依此类推。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

