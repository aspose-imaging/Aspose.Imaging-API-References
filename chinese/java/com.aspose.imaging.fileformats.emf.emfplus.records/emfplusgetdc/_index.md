---
title: "EmfPlusGetDc"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusGetDC 记录指定应处理元文件中随后遇到的 EMF 记录。"
type: docs
weight: 39
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusGetDc extends EmfPlusControlRecordType
```

EmfPlusGetDC 记录指定应处理元文件中随后遇到的 EMF 记录。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusGetDc(EmfPlusRecord source)](#EmfPlusGetDc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusGetDc` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFlags()](#getFlags--) | 获取或设置未使用的 16 位无符号整数。 |
| [setFlags(short value)](#setFlags-short-) | 获取或设置未使用的 16 位无符号整数。 |
### EmfPlusGetDc(EmfPlusRecord source) {#EmfPlusGetDc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusGetDc(EmfPlusRecord source)
```


初始化 `EmfPlusGetDc` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getFlags() {#getFlags--}
```
public short getFlags()
```


获取或设置未使用的 16 位无符号整数。此字段应设置为零，并且在接收时必须被忽略。

**Returns:**
短
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


获取或设置未使用的 16 位无符号整数。此字段应设置为零，并且在接收时必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

