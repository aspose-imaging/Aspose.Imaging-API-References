---
title: "EmfSetMapperFlags"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_SETMAPPERFLAGS 记录指定由字体映射器执行的逻辑字体与物理字体匹配过程的参数。"
type: docs
weight: 131
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetMapperFlags extends EmfStateRecordType
```

EMR\_SETMAPPERFLAGS 记录指定字体映射器执行的将逻辑字体匹配到物理字体过程的参数。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetMapperFlags(EmfRecord source)](#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetMapperFlags` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFlags()](#getFlags--) | 获取或设置一个 32 位无符号整数，用于指定字体匹配过程的参数。 |
| [setFlags(int value)](#setFlags-int-) | 获取或设置一个 32 位无符号整数，用于指定字体匹配过程的参数。 |
### EmfSetMapperFlags(EmfRecord source) {#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetMapperFlags(EmfRecord source)
```


初始化 `EmfSetMapperFlags` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getFlags() {#getFlags--}
```
public int getFlags()
```


获取或设置一个 32 位无符号整数，用于指定字体匹配过程的参数。

0x00000001 字体映射器 应仅选择与输出设备纵横比匹配的字体，正如在回放设备上下文中当前定义的那样。

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


获取或设置一个 32 位无符号整数，用于指定字体匹配过程的参数。

0x00000001 字体映射器 应仅选择与输出设备纵横比匹配的字体，正如在回放设备上下文中当前定义的那样。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

