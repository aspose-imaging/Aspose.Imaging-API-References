---
title: "IImageLoaderDescriptor klass"
type: docs
weight: 5350
url: /sv/python-net/aspose.imaging/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageLoaderDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Bestämmer om bildläsaren kan läsa en ny bild från den angivna strömmen och eventuellt med _loadOptions_. |
| [create_instance()](#create_instance__2) | Skapar en ny laddarinstans. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Bestämmer om bildläsaren kan läsa en ny bild från den angivna strömmen och eventuellt med _loadOptions_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Strömbehållaren. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Filformatdetaljerna som specificerats av _loadOptions_. _loadOptions_ kan vara null. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bildläsaren som skapats av denna beskrivare kan läsa bild från strömmen; annars <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Skapar en ny laddarinstans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | En ny laddarinstans. |


