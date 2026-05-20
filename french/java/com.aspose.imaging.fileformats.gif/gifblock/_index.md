---
title: "GifBlock"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'implémentation par défaut du bloc gif."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.gif/gifblock/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
```
public abstract class GifBlock implements IGifBlock
```

L'implémentation par défaut du bloc gif.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GifBlock()](#GifBlock--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [EXTENSION_INTRODUCER](#EXTENSION-INTRODUCER) | Introduiseur d'extension. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isChanged()](#isChanged--) | Obtient ou définit une valeur indiquant si le bloc a été modifié et nécessite d'être enregistré. |
| [setChanged(boolean value)](#setChanged-boolean-) | Obtient ou définit une valeur indiquant si le bloc a été modifié et nécessite d'être enregistré. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Enregistre le bloc dans le flux spécifié. |
### GifBlock() {#GifBlock--}
```
public GifBlock()
```


### EXTENSION_INTRODUCER {#EXTENSION-INTRODUCER}
```
public static final byte EXTENSION_INTRODUCER
```


Introduiseur d'extension.

### isChanged() {#isChanged--}
```
public boolean isChanged()
```


Obtient ou définit une valeur indiquant si le bloc a été modifié et nécessite d'être enregistré.

Valeur : `true` si le bloc a été modifié ; sinon, `false`.

**Returns:**
boolean
### setChanged(boolean value) {#setChanged-boolean-}
```
public void setChanged(boolean value)
```


Obtient ou définit une valeur indiquant si le bloc a été modifié et nécessite d'être enregistré.

Valeur : `true` si le bloc a été modifié ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Enregistre le bloc dans le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream | Le flux dans lequel enregistrer les données. |

