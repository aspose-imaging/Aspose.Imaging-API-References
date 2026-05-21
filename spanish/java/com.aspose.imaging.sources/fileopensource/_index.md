---
title: "FileOpenSource"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa una fuente de archivo para apertura."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.sources/fileopensource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

Representa una fuente de archivo para apertura.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | Inicializa una nueva instancia de la clase `FileOpenSource`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFilePath()](#getFilePath--) | Obtiene la ruta del archivo para abrir. |
| [isTemporal()](#isTemporal--) | Obtiene un valor que indica si el archivo será temporal. |
| [getStreamContainer()](#getStreamContainer--) | Obtiene el contenedor de flujo. |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


Inicializa una nueva instancia de la clase `FileOpenSource`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo para abrir. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Obtiene la ruta del archivo para abrir.

Valor: La ruta del archivo para abrir.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Obtiene un valor que indica si el archivo será temporal.

Valor: `true` si el archivo será temporal; de lo contrario, `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Obtiene el contenedor de flujo.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Usar con precaución. Necesitará disponer del contenedor de flujo después de la recuperación.
