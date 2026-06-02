---
title: "IImageCreatorDescriptor"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le descripteur du créateur d'image spécifiant les propriétés du créateur."
type: docs
weight: 129
url: /fr/java/com.aspose.imaging/iimagecreatordescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Le descripteur du créateur d'image spécifiant les propriétés du créateur. Le descripteur du créateur est utilisé pour surmonter la nécessité de contenir chaque instance de créateur d'image en mémoire et les problèmes de multithreading.
## Méthodes

| Méthode | Description |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.imaging.ImageOptionsBase-) | Détermine si le créateur d'image peut créer une nouvelle image en utilisant le `imageOptions`. |
| [createInstance()](#createInstance--) | Crée une nouvelle instance de créateur. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Détermine si le créateur d'image peut créer une nouvelle image en utilisant le `imageOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options d'image. |

**Returns:**
booléen - `true` si le créateur d'image créé par ce descripteur peut créer des données d'image en utilisant le `imageOptions` spécifié ; sinon, `false`.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Crée une nouvelle instance de créateur.

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - A new creator instance.
