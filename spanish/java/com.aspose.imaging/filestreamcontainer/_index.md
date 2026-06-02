---
title: "FileStreamContainer"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Auxiliar para el procesamiento de flujos de archivo."
type: docs
weight: 46
url: /es/java/com.aspose.imaging/filestreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Auxiliar para el procesamiento de flujos de archivo.
## Métodos

| Método | Descripción |
| --- | --- |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.imaging.FileStreamContainer-) | Realiza una conversión explícita de `com.aspose.imaging.FileStreamContainer` a `System.IO.Stream`. |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.imaging.FileStreamContainer-) | Realiza una conversión explícita de `com.aspose.imaging.FileStreamContainer` a `System.IO.FileStream`. |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Crea un nuevo flujo de archivo. |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Abre un flujo de archivo existente. |
| [isTemporal()](#isTemporal--) | Obtiene o establece un valor que indica si el flujo es temporal. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Establece un valor que indica si el flujo es temporal. |
| [isCreated()](#isCreated--) | Obtiene un valor que indica si el flujo fue creado explícitamente. |
| [getFilePath()](#getFilePath--) | Obtiene la ruta del archivo. |
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.Stream to_Stream(FileStreamContainer fileStreamContainer)
```


Realiza una conversión explícita de `com.aspose.imaging.FileStreamContainer` a `System.IO.Stream`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | El contenedor de flujo de archivo. |

**Returns:**
com.aspose.ms.System.IO.Stream - El resultado de la conversión.
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream(FileStreamContainer fileStreamContainer)
```


Realiza una conversión explícita de `com.aspose.imaging.FileStreamContainer` a `System.IO.FileStream`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | El contenedor de flujo de archivo. |

**Returns:**
com.aspose.ms.System.IO.FileStream - El resultado de la conversión.
### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Crea un nuevo flujo de archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileLocation | java.lang.String | La ubicación del archivo. |
| isTemporal | boolean | Si se establece en `true`, el contenedor del flujo de archivo es temporal. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


Abre un flujo de archivo existente. Si el flujo de archivo no existe, se lanza la excepción correspondiente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileLocation | java.lang.String | La ubicación del archivo. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Obtiene o establece un valor que indica si el flujo es temporal.

**Returns:**
booleano - `true` si el flujo es temporal; de lo contrario, `false`.

Un flujo temporal se eliminará a sí mismo cuando se libere. Si el flujo es basado en memoria, esta propiedad no tiene efecto. El flujo puede marcarse como temporal o persistente en caso de que se haya creado explícitamente; de lo contrario, se lanza la excepción correspondiente.
### setTemporal(boolean value) {#setTemporal-boolean-}
```
public void setTemporal(boolean value)
```


Establece un valor que indica si el flujo es temporal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | `true` si el flujo es temporal; de lo contrario, `false`. |

Un flujo temporal se eliminará a sí mismo cuando se libere. Si el flujo es basado en memoria, esta propiedad no tiene efecto. El flujo puede marcarse como temporal o persistente en caso de que se haya creado explícitamente; de lo contrario, se lanza la excepción correspondiente. |

### isCreated() {#isCreated--}
```
public boolean isCreated()
```


Obtiene un valor que indica si el flujo fue creado explícitamente.

**Returns:**
booleano - `true` si el flujo se creó explícitamente; de lo contrario, `false`.
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Obtiene la ruta del archivo.

**Returns:**
java.lang.String - La ruta del archivo.
