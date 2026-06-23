---
title: "FileStreamContainer"
second_title: "Aspose.Imaging for Java API 参考"
description: "用于文件流处理的辅助类。"
type: docs
weight: 46
url: /zh/java/com.aspose.imaging/filestreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

用于文件流处理的辅助类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.imaging.FileStreamContainer-) | 执行从 `com.aspose.imaging.FileStreamContainer` 到 `System.IO.Stream` 的显式转换。 |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.imaging.FileStreamContainer-) | 执行从 `com.aspose.imaging.FileStreamContainer` 到 `System.IO.FileStream` 的显式转换。 |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | 创建一个新的文件流。 |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | 打开一个已存在的文件流。 |
| [isTemporal()](#isTemporal--) | 获取或设置指示流是否为临时的值。 |
| [setTemporal(boolean value)](#setTemporal-boolean-) | 设置指示流是否为临时的值。 |
| [isCreated()](#isCreated--) | 获取指示流是否被显式创建的值。 |
| [getFilePath()](#getFilePath--) | 获取文件路径。 |
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.Stream to_Stream(FileStreamContainer fileStreamContainer)
```


执行从 `com.aspose.imaging.FileStreamContainer` 到 `System.IO.Stream` 的显式转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | 文件流容器。 |

**Returns:**
com.aspose.ms.System.IO.Stream - 转换的结果。
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream(FileStreamContainer fileStreamContainer)
```


执行从 `com.aspose.imaging.FileStreamContainer` 到 `System.IO.FileStream` 的显式转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | 文件流容器。 |

**Returns:**
com.aspose.ms.System.IO.FileStream - 转换的结果。
### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


创建一个新的文件流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileLocation | java.lang.String | 文件位置。 |
| isTemporal | boolean | 如果设置为 `true`，文件流容器为临时的。 |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


打开一个已存在的文件流。如果文件流不存在，将抛出相应的异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileLocation | java.lang.String | 文件位置。 |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


获取或设置指示流是否为临时的值。

**Returns:**
boolean - 如果流是临时的则为 `true`；否则为 `false`。

临时流在释放时会自行删除。如果流是基于内存的，则此属性无效。若流是显式创建的，则可以将其标记为临时或持久，否则将抛出相应的异常。
### setTemporal(boolean value) {#setTemporal-boolean-}
```
public void setTemporal(boolean value)
```


设置指示流是否为临时的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | `true` 表示流是临时的；否则为 `false`。 |

临时流在释放时会自行删除。如果流是基于内存的，则此属性无效。若流是显式创建的，则可以将其标记为临时或持久，否则将抛出相应的异常。 |

### isCreated() {#isCreated--}
```
public boolean isCreated()
```


获取指示流是否被显式创建的值。

**Returns:**
boolean - 如果流是显式创建的则为 `true`；否则为 `false`。
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


获取文件路径。

**Returns:**
java.lang.String - 文件路径。
