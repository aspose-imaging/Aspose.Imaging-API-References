---
title: "EmfPlusMetafile"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusMetafileData 对象指定包含图形图像的元文件。"
type: docs
weight: 55
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusMetafile extends EmfPlusBaseImageData
```

EmfPlusMetafileData 对象指定包含图形图像的元文件。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusMetafile()](#EmfPlusMetafile--) | 初始化 `EmfPlusMetafile` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 获取或设置一个 32 位无符号整数，指定嵌入在 MetafileData 字段中的元文件类型。 |
| [setType(int value)](#setType-int-) | 获取或设置一个 32 位无符号整数，指定嵌入在 MetafileData 字段中的元文件类型。 |
| [getMetafileDataSize()](#getMetafileDataSize--) | 获取或设置一个 32 位无符号整数，指定 MetafileData 字段中元文件数据的字节大小。 |
| [setMetafileDataSize(int value)](#setMetafileDataSize-int-) | 获取或设置一个 32 位无符号整数，指定 MetafileData 字段中元文件数据的字节大小。 |
| [getMetafileData()](#getMetafileData--) | 获取或设置可变长度数据，指定嵌入的元文件。 |
| [setMetafileData(byte[] value)](#setMetafileData-byte---) | 获取或设置可变长度数据，指定嵌入的元文件。 |
### EmfPlusMetafile() {#EmfPlusMetafile--}
```
public EmfPlusMetafile()
```


初始化 `EmfPlusMetafile` 类的新实例。

### getType() {#getType--}
```
public int getType()
```


获取或设置一个 32 位无符号整数，指定嵌入在 MetafileData 字段中的元文件类型。此值必须在 MetafileDataType 枚举（第 2.1.1.21 节）中定义。

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


获取或设置一个 32 位无符号整数，指定嵌入在 MetafileData 字段中的元文件类型。此值必须在 MetafileDataType 枚举（第 2.1.1.21 节）中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMetafileDataSize() {#getMetafileDataSize--}
```
public int getMetafileDataSize()
```


获取或设置一个 32 位无符号整数，指定 MetafileData 字段中元文件数据的字节大小。

**Returns:**
int
### setMetafileDataSize(int value) {#setMetafileDataSize-int-}
```
public void setMetafileDataSize(int value)
```


获取或设置一个 32 位无符号整数，指定 MetafileData 字段中元文件数据的字节大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMetafileData() {#getMetafileData--}
```
public byte[] getMetafileData()
```


获取或设置可变长度数据，指定嵌入的元文件。数据的内容和格式可能因每种元文件类型而异。

图形图像由 EmfPlusImage 对象（第 2.2.1.4 节）指定。如果在其 Type 字段中指定了 ImageTypeMetafile，则 EmfPlusMetafile 对象必须存在于 EmfPlusImage 对象的 ImageData 字段中。此对象是通用的，用于不同类型的数据，包括：WMF 元文件 [MS-WMF]；可放置的 WMF 元文件；EMF 元文件 [MS-EMF]；仅指定 EMF+ 记录的 EMF+ 元文件；以及同时指定 EMF+ 和 EMF 记录的 EMF+ 元文件。请参阅第 2.2.2 节以获取其他结构对象的规范。

**Returns:**
byte[]
### setMetafileData(byte[] value) {#setMetafileData-byte---}
```
public void setMetafileData(byte[] value)
```


获取或设置可变长度数据，指定嵌入的元文件。数据的内容和格式可能因每种元文件类型而异。

图形图像由 EmfPlusImage 对象（第 2.2.1.4 节）指定。如果在其 Type 字段中指定了 ImageTypeMetafile，则 EmfPlusMetafile 对象必须存在于 EmfPlusImage 对象的 ImageData 字段中。此对象是通用的，用于不同类型的数据，包括：WMF 元文件 [MS-WMF]；可放置的 WMF 元文件；EMF 元文件 [MS-EMF]；仅指定 EMF+ 记录的 EMF+ 元文件；以及同时指定 EMF+ 和 EMF 记录的 EMF+ 元文件。请参阅第 2.2.2 节以获取其他结构对象的规范。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

