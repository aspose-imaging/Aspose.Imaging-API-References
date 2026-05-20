---
title: "EmfMetafileHeaderExtension1"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfMetafileHeaderExtension1 记录是用于 EMF 元文件第一扩展的头部记录。"
type: docs
weight: 71
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
```
public class EmfMetafileHeaderExtension1 extends EmfMetafileHeader
```

EmfMetafileHeaderExtension1 记录是用于 EMF 元文件首次扩展的头记录。紧随 EmfHeaderExtension1 字段之后，其余字段为可选，可以任意顺序出现。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfMetafileHeaderExtension1(EmfMetafileHeader header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | 初始化 `EmfMetafileHeaderExtension1` 类的新实例。 |
| [EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-) | 初始化 `EmfMetafileHeaderExtension1` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEmfHeaderExtension1()](#getEmfHeaderExtension1--) | 获取或设置一个 HeaderExtension1 对象，该对象指定元文件中图像的附加信息。 |
| [setEmfHeaderExtension1(EmfHeaderExtension1 value)](#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-) | 获取或设置一个 HeaderExtension1 对象，该对象指定元文件中图像的附加信息。 |
| [getEmfPixelFormatBuffer()](#getEmfPixelFormatBuffer--) | 获取或设置一个可选的字节数组，包含 EMF 像素格式描述符，该描述符不需要与 EmfMetafileHeaderExtension1 记录的固定部分或 EMF 描述字符串连续。 |
| [setEmfPixelFormatBuffer(byte[] value)](#setEmfPixelFormatBuffer-byte---) | 获取或设置一个可选的字节数组，包含 EMF 像素格式描述符，该描述符不需要与 EmfMetafileHeaderExtension1 记录的固定部分或 EMF 描述字符串连续。 |
### EmfMetafileHeaderExtension1(EmfMetafileHeader header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeader header)
```


初始化 `EmfMetafileHeaderExtension1` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | 头部。 |

### EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)
```


初始化 `EmfMetafileHeaderExtension1` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| header | [EmfMetafileHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | 头部。 |

### getEmfHeaderExtension1() {#getEmfHeaderExtension1--}
```
public EmfHeaderExtension1 getEmfHeaderExtension1()
```


获取或设置一个 HeaderExtension1 对象，该对象指定元文件中图像的附加信息。

**Returns:**
[EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1)
### setEmfHeaderExtension1(EmfHeaderExtension1 value) {#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-}
```
public void setEmfHeaderExtension1(EmfHeaderExtension1 value)
```


获取或设置一个 HeaderExtension1 对象，该对象指定元文件中图像的附加信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1) |  |

### getEmfPixelFormatBuffer() {#getEmfPixelFormatBuffer--}
```
public byte[] getEmfPixelFormatBuffer()
```


获取或设置一个可选的字节数组，包含 EMF 像素格式描述符，该描述符不需要与 EmfMetafileHeaderExtension1 记录的固定部分或 EMF 描述字符串连续。因此，此缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须忽略。

**Returns:**
byte[]
### setEmfPixelFormatBuffer(byte[] value) {#setEmfPixelFormatBuffer-byte---}
```
public void setEmfPixelFormatBuffer(byte[] value)
```


获取或设置一个可选的字节数组，包含 EMF 像素格式描述符，该描述符不需要与 EmfMetafileHeaderExtension1 记录的固定部分或 EMF 描述字符串连续。因此，此缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

