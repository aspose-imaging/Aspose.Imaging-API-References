---
title: "FileStreamContainer"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe d'aide pour le traitement des flux de fichiers."
type: docs
weight: 46
url: /fr/java/com.aspose.imaging/filestreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Classe d'aide pour le traitement des flux de fichiers.
## Méthodes

| Méthode | Description |
| --- | --- |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.imaging.FileStreamContainer-) | Effectue une conversion explicite de `com.aspose.imaging.FileStreamContainer` vers `System.IO.Stream`. |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.imaging.FileStreamContainer-) | Effectue une conversion explicite de `com.aspose.imaging.FileStreamContainer` vers `System.IO.FileStream`. |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Crée un nouveau flux de fichier. |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Ouvre un flux de fichier existant. |
| [isTemporal()](#isTemporal--) | Obtient ou définit une valeur indiquant si le flux est temporel. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Définit une valeur indiquant si le flux est temporel. |
| [isCreated()](#isCreated--) | Obtient une valeur indiquant si le flux a été créé explicitement. |
| [getFilePath()](#getFilePath--) | Obtient le chemin du fichier. |
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.Stream to_Stream(FileStreamContainer fileStreamContainer)
```


Effectue une conversion explicite de `com.aspose.imaging.FileStreamContainer` vers `System.IO.Stream`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | Le conteneur de flux de fichier. |

**Returns:**
com.aspose.ms.System.IO.Stream - Le résultat de la conversion.
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream(FileStreamContainer fileStreamContainer)
```


Effectue une conversion explicite de `com.aspose.imaging.FileStreamContainer` vers `System.IO.FileStream`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | Le conteneur de flux de fichier. |

**Returns:**
com.aspose.ms.System.IO.FileStream - Le résultat de la conversion.
### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Crée un nouveau flux de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileLocation | java.lang.String | L'emplacement du fichier. |
| isTemporal | boolean | Si défini sur `true`, le conteneur du flux de fichier est temporel. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


Ouvre un flux de fichier existant. Si le flux de fichier n'existe pas, l'exception appropriée est levée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileLocation | java.lang.String | L'emplacement du fichier. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Obtient ou définit une valeur indiquant si le flux est temporel.

**Returns:**
booléen - `true` si le flux est temporel ; sinon, `false`.

Un flux temporel se supprimera lorsqu'il sera libéré. Si le flux est basé en mémoire, cette propriété n'a aucun effet. Le flux peut être marqué comme temporel ou persistant dans le cas où il a été créé explicitement, sinon l'exception appropriée est levée.
### setTemporal(boolean value) {#setTemporal-boolean-}
```
public void setTemporal(boolean value)
```


Définit une valeur indiquant si le flux est temporel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | `true` si le flux est temporel ; sinon, `false`. |

Un flux temporel se supprimera lorsqu'il sera libéré. Si le flux est basé en mémoire, cette propriété n'a aucun effet. Le flux peut être marqué comme temporel ou persistant dans le cas où il a été créé explicitement, sinon l'exception appropriée est levée. |

### isCreated() {#isCreated--}
```
public boolean isCreated()
```


Obtient une valeur indiquant si le flux a été créé explicitement.

**Returns:**
booléen - `true` si le flux a été créé explicitement ; sinon, `false`.
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Obtient le chemin du fichier.

**Returns:**
java.lang.String - Le chemin du fichier.
