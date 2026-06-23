---
title: "FileOpenSource"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示用于打开的文件源。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.sources/fileopensource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

表示用于打开的文件源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | 初始化 `FileOpenSource` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFilePath()](#getFilePath--) | 获取要打开的文件路径。 |
| [isTemporal()](#isTemporal--) | 获取指示文件是否为临时文件的值。 |
| [getStreamContainer()](#getStreamContainer--) | 获取流容器。 |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


初始化 `FileOpenSource` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 要打开的文件路径。 |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


获取要打开的文件路径。

值：要打开的文件路径。

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


获取指示文件是否为临时文件的值。

值：如果文件为临时文件则为 `true`；否则为 `false`。

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


获取流容器。

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

请谨慎使用。检索后您需要释放流容器。
