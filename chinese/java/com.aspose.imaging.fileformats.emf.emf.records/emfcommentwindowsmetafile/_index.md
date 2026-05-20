---
title: "EmfCommentWindowsMetaFile"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_COMMENT_WINDOWS_METAFILE 记录指定嵌入的 WMF 元文件中的图像。"
type: docs
weight: 33
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentWindowsMetaFile extends EmfCommentPublicRecordType
```

该 EMR\_COMMENT\_WINDOWS\_METAFILE 记录指定嵌入 WMF 元文件中的图像。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCommentWindowsMetaFile(EmfRecord source)](#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCommentWindowsMetaFile` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) | 获取或设置一个 16 位无符号整数，该整数指定 WMF 元文件版本，以支持设备无关位图 (DIB)，来源于 WMF MetafileVersion 枚举（[MS-WMF] 第 2.1.1.19 节）。 |
| [setVersion(short value)](#setVersion-short-) | 获取或设置一个 16 位无符号整数，该整数指定 WMF 元文件版本，以支持设备无关位图 (DIB)，来源于 WMF MetafileVersion 枚举（[MS-WMF] 第 2.1.1.19 节）。 |
| [getChecksum()](#getChecksum--) | 获取或设置一个 32 位无符号整数，该整数指定此记录的校验和。 |
| [setChecksum(int value)](#setChecksum-int-) | 获取或设置一个 32 位无符号整数，该整数指定此记录的校验和。 |
| [getFlags()](#getFlags--) | 获取或设置一个 32 位值，该值必须为 0x00000000 并且必须被忽略。 |
| [setFlags(int value)](#setFlags-int-) | 获取或设置一个 32 位值，该值必须为 0x00000000 并且必须被忽略。 |
| [getWinMetafileSize()](#getWinMetafileSize--) | 获取或设置一个 32 位无符号整数，该整数指定 WinMetafile 字段中 WMF 元文件的大小（以字节为单位）。 |
| [setWinMetafileSize(int value)](#setWinMetafileSize-int-) | 获取或设置一个 32 位无符号整数，该整数指定 WinMetafile 字段中 WMF 元文件的大小（以字节为单位）。 |
| [getWinMetafile()](#getWinMetafile--) | 获取或设置一个包含 WMF 元文件的缓冲区。 |
| [setWinMetafile(MetaImage value)](#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-) | 获取或设置一个包含 WMF 元文件的缓冲区。 |
### EmfCommentWindowsMetaFile(EmfRecord source) {#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentWindowsMetaFile(EmfRecord source)
```


初始化 `EmfCommentWindowsMetaFile` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getVersion() {#getVersion--}
```
public short getVersion()
```


获取或设置一个 16 位无符号整数，该整数指定 WMF 元文件版本，以支持设备无关位图 (DIB)，来源于 WMF MetafileVersion 枚举（[MS-WMF] 第 2.1.1.19 节）。

**Returns:**
short
### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


获取或设置一个 16 位无符号整数，该整数指定 WMF 元文件版本，以支持设备无关位图 (DIB)，来源于 WMF MetafileVersion 枚举（[MS-WMF] 第 2.1.1.19 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


获取或设置一个 32 位无符号整数，该整数指定此记录的校验和。

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


获取或设置一个 32 位无符号整数，该整数指定此记录的校验和。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


获取或设置一个 32 位值，该值必须为 0x00000000 并且必须被忽略。

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


获取或设置一个 32 位值，该值必须为 0x00000000 并且必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getWinMetafileSize() {#getWinMetafileSize--}
```
public int getWinMetafileSize()
```


获取或设置一个 32 位无符号整数，该整数指定 WinMetafile 字段中 WMF 元文件的大小（以字节为单位）。

**Returns:**
int
### setWinMetafileSize(int value) {#setWinMetafileSize-int-}
```
public void setWinMetafileSize(int value)
```


获取或设置一个 32 位无符号整数，该整数指定 WinMetafile 字段中 WMF 元文件的大小（以字节为单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getWinMetafile() {#getWinMetafile--}
```
public MetaImage getWinMetafile()
```


获取或设置一个包含 WMF 元文件的缓冲区。

**Returns:**
[MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
### setWinMetafile(MetaImage value) {#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-}
```
public void setWinMetafile(MetaImage value)
```


获取或设置一个包含 WMF 元文件的缓冲区。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage) |  |

