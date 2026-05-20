---
title: "EmfSaveDc"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "在先前的 EMR_SAVEDC 记录保存的状态堆栈上保存回放设备上下文的当前状态（如果有）。"
type: docs
weight: 112
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSaveDc extends EmfStateRecordType
```

在先前的 EMR\_SAVEDC 记录保存的状态堆栈上保存回放设备上下文的当前状态（如果有）。该状态包括图形属性和对象，包括当前选中的位图、画刷、调色板、字体、笔和区域。使用 EMR\_RESTOREDC 记录来恢复状态。此 EMF 记录不指定任何参数。

该堆栈可以包含多个回放设备上下文实例的状态信息。当状态被恢复时，所有更近期保存的状态实例必须被丢弃。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSaveDc(EmfRecord source)](#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSaveDc` 类的新实例。 |
| [EmfSaveDc()](#EmfSaveDc--) | 初始化 `EmfSaveDc` 类的新实例。 |
### EmfSaveDc(EmfRecord source) {#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSaveDc(EmfRecord source)
```


初始化 `EmfSaveDc` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfSaveDc() {#EmfSaveDc--}
```
public EmfSaveDc()
```


初始化 `EmfSaveDc` 类的新实例。

