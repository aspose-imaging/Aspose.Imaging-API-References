---
title: "EmfGlsBoundedRecord"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 EMR_GLSBOUNDEDRECORD 记录指定一个用于输出的带有边界矩形的 OpenGL 函数。"
type: docs
weight: 63
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsBoundedRecord extends EmfOpenGlRecordType
```

EMR\_GLSBOUNDEDRECORD 记录指定带有输出边界矩形的 OpenGL 函数。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfGlsBoundedRecord(EmfRecord source)](#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfGlsBoundedRecord` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义执行 OpenGL 函数产生的输出的边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义执行 OpenGL 函数产生的输出的边界矩形。 |
| [getCbData()](#getCbData--) | 获取或设置一个 32 位无符号整数，指定 Data 字段的大小（以字节为单位）。 |
| [setCbData(int value)](#setCbData-int-) | 获取或设置一个 32 位无符号整数，指定 Data 字段的大小（以字节为单位）。 |
| [getData()](#getData--) | 获取或设置一个可选的字节数组，长度为 cbData，指定 OpenGL 函数的数据。 |
| [setData(byte[] value)](#setData-byte---) | 获取或设置一个可选的字节数组，长度为 cbData，指定 OpenGL 函数的数据。 |
### EmfGlsBoundedRecord(EmfRecord source) {#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsBoundedRecord(EmfRecord source)
```


初始化 `EmfGlsBoundedRecord` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义执行 OpenGL 函数产生的输出的边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义执行 OpenGL 函数产生的输出的边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


获取或设置一个 32 位无符号整数，指定 Data 字段的大小（以字节为单位）。如果该值为零，则此记录不附加任何数据。

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


获取或设置一个 32 位无符号整数，指定 Data 字段的大小（以字节为单位）。如果该值为零，则此记录不附加任何数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


获取或设置一个可选的字节数组，长度为 cbData，指定 OpenGL 函数的数据。

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


获取或设置一个可选的字节数组，长度为 cbData，指定 OpenGL 函数的数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

