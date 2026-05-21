---
title: "FileStreamContainer"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Вспомогательный класс для обработки файловых потоков."
type: docs
weight: 46
url: /ru/java/com.aspose.imaging/filestreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Вспомогательный класс для обработки файловых потоков.
## Методы

| Метод | Описание |
| --- | --- |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.imaging.FileStreamContainer-) | Выполняет явное преобразование из `com.aspose.imaging.FileStreamContainer` в `System.IO.Stream`. |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.imaging.FileStreamContainer-) | Выполняет явное преобразование из `com.aspose.imaging.FileStreamContainer` в `System.IO.FileStream`. |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Создаёт новый файловый поток. |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Открывает существующий файловый поток. |
| [isTemporal()](#isTemporal--) | Получает или задаёт значение, указывающее, является ли поток временным. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Задаёт значение, указывающее, является ли поток временным. |
| [isCreated()](#isCreated--) | Получает значение, указывающее, был ли поток создан явно. |
| [getFilePath()](#getFilePath--) | Получает путь к файлу. |
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.Stream to_Stream(FileStreamContainer fileStreamContainer)
```


Выполняет явное преобразование из `com.aspose.imaging.FileStreamContainer` в `System.IO.Stream`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | Контейнер файлового потока. |

**Returns:**
com.aspose.ms.System.IO.Stream — результат преобразования.
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream(FileStreamContainer fileStreamContainer)
```


Выполняет явное преобразование из `com.aspose.imaging.FileStreamContainer` в `System.IO.FileStream`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | Контейнер файлового потока. |

**Returns:**
com.aspose.ms.System.IO.FileStream - Результат преобразования.
### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Создаёт новый файловый поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileLocation | java.lang.String | Расположение файла. |
| isTemporal | boolean | Если установить значение `true`, контейнер файлового потока будет временным. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


Открывает существующий файловый поток. Если файловый поток не существует, выбрасывается соответствующее исключение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileLocation | java.lang.String | Расположение файла. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Получает или задаёт значение, указывающее, является ли поток временным.

**Returns:**
boolean — `true`, если поток временный; иначе `false`.

Временный поток удалит себя при освобождении. Если поток основан на памяти, это свойство не оказывает влияния. Поток может быть помечен как временный или постоянный в случае, если он был создан явно, иначе будет выброшено соответствующее исключение.
### setTemporal(boolean value) {#setTemporal-boolean-}
```
public void setTemporal(boolean value)
```


Задаёт значение, указывающее, является ли поток временным.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | `true`, если поток временный; иначе `false`. |

Временный поток удалит себя при освобождении. Если поток основан на памяти, это свойство не оказывает влияния. Поток может быть помечен как временный или постоянный в случае, если он был создан явно, иначе будет выброшено соответствующее исключение. |

### isCreated() {#isCreated--}
```
public boolean isCreated()
```


Получает значение, указывающее, был ли поток создан явно.

**Returns:**
boolean — `true`, если поток был создан явно; иначе `false`.
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Получает путь к файлу.

**Returns:**
java.lang.String — путь к файлу.
