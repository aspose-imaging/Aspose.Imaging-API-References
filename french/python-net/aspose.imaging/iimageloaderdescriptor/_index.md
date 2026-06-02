---
title: "Classe IImageLoaderDescriptor"
type: docs
weight: 5350
url: /fr/python-net/aspose.imaging/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageLoaderDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Détermine si le chargeur d'image peut lire une nouvelle image depuis le flux spécifié et éventuellement en utilisant les _loadOptions_. |
| [create_instance()](#create_instance__2) | Crée une nouvelle instance du chargeur. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Détermine si le chargeur d'image peut lire une nouvelle image depuis le flux spécifié et éventuellement en utilisant les _loadOptions_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le conteneur de flux. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Les détails du format de fichier spécifiés par les _loadOptions_. Les _loadOptions_ peuvent être null. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si le chargeur d'image créé par ce descripteur peut lire l'image depuis le flux ; sinon, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crée une nouvelle instance du chargeur.

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Une nouvelle instance du chargeur. |


