---
title: "EmfPixelFormat"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_PIXELFORMAT 记录指定用于图形操作的像素格式。"
type: docs
weight: 83
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfpixelformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfPixelFormat extends EmfStateRecordType
```

EMR\_PIXELFORMAT 记录指定用于图形操作的像素格式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPixelFormat(EmfRecord source)](#EmfPixelFormat-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfPixelFormat` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPfd()](#getPfd--) | 获取或设置一个 PixelFormatDescriptor 对象（第 2.2.22 节），该对象指定像素格式数据。 |
| [setPfd(EmfPixelFormatDescriptor value)](#setPfd-com.aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor-) | 获取或设置一个 PixelFormatDescriptor 对象（第 2.2.22 节），该对象指定像素格式数据。 |
### EmfPixelFormat(EmfRecord source) {#EmfPixelFormat-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPixelFormat(EmfRecord source)
```


初始化 `EmfPixelFormat` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getPfd() {#getPfd--}
```
public EmfPixelFormatDescriptor getPfd()
```


获取或设置一个 PixelFormatDescriptor 对象（第 2.2.22 节），该对象指定像素格式数据。

**Returns:**
[EmfPixelFormatDescriptor](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor)
### setPfd(EmfPixelFormatDescriptor value) {#setPfd-com.aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor-}
```
public void setPfd(EmfPixelFormatDescriptor value)
```


获取或设置一个 PixelFormatDescriptor 对象（第 2.2.22 节），该对象指定像素格式数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPixelFormatDescriptor](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor) |  |

