---
title: FileOpenSource
second_title: Aspose.Imaging for Java API Reference
description: Represents a file source for opening.
type: docs
weight: 11
url: /java/com.aspose.imaging.sources/fileopensource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

Represents a file source for opening.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | Initializes a new instance of the `FileOpenSource` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFilePath()](#getFilePath--) | Gets the file path to open. |
| [isTemporal()](#isTemporal--) | Gets a value indicating whether file will be temporal. |
| [getStreamContainer()](#getStreamContainer--) | Gets the stream container. |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


Initializes a new instance of the `FileOpenSource` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to open. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Gets the file path to open.

Value: The file path to open.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Gets a value indicating whether file will be temporal.

Value: `true` if file will be temporal; otherwise, `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Gets the stream container.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Use with caution. You will need to dispose the stream container after retrieval.
