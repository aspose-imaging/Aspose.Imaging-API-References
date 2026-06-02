---
title: "IImageLoaderDescriptor"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le descripteur du chargeur d'image spécifiant les propriétés du chargeur."
type: docs
weight: 134
url: /fr/java/com.aspose.imaging/iimageloaderdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Le descripteur de chargeur d'image spécifiant les propriétés du chargeur. Le descripteur de chargeur est utilisé pour surmonter la nécessité de contenir chaque instance de chargeur d'image en mémoire et les problèmes de multithreading.
## Méthodes

| Méthode | Description |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Détermine si le chargeur d'image peut lire une nouvelle image depuis le flux spécifié et éventuellement en utilisant le `loadOptions`. |
| [createInstance()](#createInstance--) | Crée une nouvelle instance du chargeur. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Détermine si le chargeur d'image peut lire une nouvelle image depuis le flux spécifié et éventuellement en utilisant le `loadOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les détails du format de fichier spécifiés par le `loadOptions`. Le `loadOptions` peut être nul. |

**Returns:**
booléen - `true` si le chargeur d'image créé par ce descripteur peut lire l'image depuis le flux ; sinon, `false`.
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Crée une nouvelle instance du chargeur.

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - A new loader instance.
