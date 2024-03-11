---
title: FileStreamContainer
second_title: Aspose.Imaging for Java API Reference
description: Helper for file stream processing.
type: docs
weight: 46
url: /java/com.aspose.imaging/filestreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Helper for file stream processing.
## Methods

| Method | Description |
| --- | --- |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.imaging.FileStreamContainer-) | Performs an explicit conversion from `com.aspose.imaging.FileStreamContainer` to `System.IO.Stream`. |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.imaging.FileStreamContainer-) | Performs an explicit conversion from `com.aspose.imaging.FileStreamContainer` to `System.IO.FileStream`. |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Creates a new file stream. |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Opens an existing file stream. |
| [isTemporal()](#isTemporal--) | Gets or sets a value indicating whether stream is temporal. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Sets a value indicating whether stream is temporal. |
| [isCreated()](#isCreated--) | Gets a value indicating whether stream was created explicitly. |
| [getFilePath()](#getFilePath--) | Gets the file path. |
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.Stream to_Stream(FileStreamContainer fileStreamContainer)
```


Performs an explicit conversion from `com.aspose.imaging.FileStreamContainer` to `System.IO.Stream`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | The file stream container. |

**Returns:**
com.aspose.ms.System.IO.Stream - The result of the conversion.
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream(FileStreamContainer fileStreamContainer)
```


Performs an explicit conversion from `com.aspose.imaging.FileStreamContainer` to `System.IO.FileStream`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | The file stream container. |

**Returns:**
com.aspose.ms.System.IO.FileStream - The result of the conversion.
### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Creates a new file stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileLocation | java.lang.String | The file location. |
| isTemporal | boolean | If set to `true` the file stream container is temporal. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


Opens an existing file stream. If file stream does not exist the appropriate exception is thrown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileLocation | java.lang.String | The file location. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Gets or sets a value indicating whether stream is temporal.

**Returns:**
boolean - `true` if stream is temporal; otherwise, `false`.

A temporal stream will remove itself when disposed. If the stream is memory based this property has no effect. The stream can be marked as temporal or persistent in case it was created explicitly otherwise the appropriate exception is thrown.
### setTemporal(boolean value) {#setTemporal-boolean-}
```
public void setTemporal(boolean value)
```


Sets a value indicating whether stream is temporal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if stream is temporal; otherwise, `false`.

A temporal stream will remove itself when disposed. If the stream is memory based this property has no effect. The stream can be marked as temporal or persistent in case it was created explicitly otherwise the appropriate exception is thrown. |

### isCreated() {#isCreated--}
```
public boolean isCreated()
```


Gets a value indicating whether stream was created explicitly.

**Returns:**
boolean - `true` if stream was created explicitly; otherwise, `false`.
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Gets the file path.

**Returns:**
java.lang.String - The file path.
