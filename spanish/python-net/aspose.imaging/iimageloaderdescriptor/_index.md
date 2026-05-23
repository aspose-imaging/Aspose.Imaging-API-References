---
title: "Clase IImageLoaderDescriptor"
type: docs
weight: 5350
url: /es/python-net/aspose.imaging/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageLoaderDescriptor

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Determina si el cargador de imágenes puede leer una nueva imagen del flujo especificado y opcionalmente usando _loadOptions_. |
| [create_instance()](#create_instance__2) | Crea una nueva instancia del cargador. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Determina si el cargador de imágenes puede leer una nueva imagen del flujo especificado y opcionalmente usando _loadOptions_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | El contenedor del flujo. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Los detalles del formato de archivo especificados por _loadOptions_. _loadOptions_ puede ser nulo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si el cargador de imágenes creado por este descriptor puede leer la imagen del flujo; de lo contrario, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crea una nueva instancia del cargador.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Una nueva instancia del cargador. |


