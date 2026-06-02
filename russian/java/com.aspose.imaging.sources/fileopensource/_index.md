---
title: "FileOpenSource"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет файловый источник для открытия."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.sources/fileopensource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

Представляет файловый источник для открытия.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | Инициализирует новый экземпляр класса `FileOpenSource`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFilePath()](#getFilePath--) | Получает путь к файлу для открытия. |
| [isTemporal()](#isTemporal--) | Получает значение, указывающее, будет ли файл временным. |
| [getStreamContainer()](#getStreamContainer--) | Получает контейнер потока. |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


Инициализирует новый экземпляр класса `FileOpenSource`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу для открытия. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Получает путь к файлу для открытия.

Значение: Путь к файлу для открытия.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Получает значение, указывающее, будет ли файл временным.

Значение: `true`, если файл будет временным; иначе `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Получает контейнер потока.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Используйте с осторожностью. После получения вам потребуется освободить контейнер потока.
