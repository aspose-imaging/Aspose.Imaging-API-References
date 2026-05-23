---
title: "IImageLoaderDescriptor Klasse"
type: docs
weight: 5350
url: /de/python-net/aspose.imaging/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageLoaderDescriptor

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Bestimmt, ob der Bildlader ein neues Bild aus dem angegebenen Stream lesen kann und optional die _loadOptions_ verwendet. |
| [create_instance()](#create_instance__2) | Erstellt eine neue Loader-Instanz. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Bestimmt, ob der Bildlader ein neues Bild aus dem angegebenen Stream lesen kann und optional die _loadOptions_ verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Der Stream-Container. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Dateiformatdetails, die durch _loadOptions_ angegeben werden. _loadOptions_ kann null sein. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn der von diesem Deskriptor erstellte Bildlader das Bild aus dem Stream lesen kann; andernfalls <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Erstellt eine neue Loader-Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Eine neue Loader-Instanz. |


