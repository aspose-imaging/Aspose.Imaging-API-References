---
title: "Classe IImageLoaderDescriptor"
type: docs
weight: 5350
url: /it/python-net/aspose.imaging/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageLoaderDescriptor

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Determina se il caricatore di immagini può leggere una nuova immagine dallo stream specificato e opzionalmente usando _loadOptions_. |
| [create_instance()](#create_instance__2) | Crea una nuova istanza del caricatore. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Determina se il caricatore di immagini può leggere una nuova immagine dallo stream specificato e opzionalmente usando _loadOptions_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Il contenitore dello stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | I dettagli del formato file specificati da _loadOptions_. _loadOptions_ può essere null. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se il caricatore di immagini creato da questo descrittore può leggere l'immagine dallo stream; altrimenti, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crea una nuova istanza del caricatore.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Una nuova istanza del caricatore. |


