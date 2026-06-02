---
title: "FileOpenSource"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente une source de fichier pour l'ouverture."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.sources/fileopensource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

Représente une source de fichier pour l'ouverture.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | Initialise une nouvelle instance de la classe `FileOpenSource`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFilePath()](#getFilePath--) | Obtient le chemin du fichier à ouvrir. |
| [isTemporal()](#isTemporal--) | Obtient une valeur indiquant si le fichier sera temporaire. |
| [getStreamContainer()](#getStreamContainer--) | Obtient le conteneur de flux. |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


Initialise une nouvelle instance de la classe `FileOpenSource`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier à ouvrir. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Obtient le chemin du fichier à ouvrir.

Valeur : le chemin du fichier à ouvrir.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Obtient une valeur indiquant si le fichier sera temporaire.

Valeur : `true` si le fichier sera temporaire ; sinon, `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Obtient le conteneur de flux.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Utilisez avec précaution. Vous devrez libérer le conteneur de flux après récupération.
