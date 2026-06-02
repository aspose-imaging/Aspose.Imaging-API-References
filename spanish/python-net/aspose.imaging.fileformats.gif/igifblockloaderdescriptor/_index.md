---
title: "Clase IGifBlockLoaderDescriptor"
type: docs
weight: 110
url: /es/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/
---

**Summary:** Gif block Loader descriptor.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [can_load(stream_container)](#can_load_stream_container_1) | Determina si el cargador puede cargar los datos especificados. |
| [load(stream_container, container_palette)](#load_stream_container_container_palette_2) | Carga el bloque gif. |


### Method: can_load(stream_container) {#can_load_stream_container_1}


```
 can_load(stream_container) 
```

Determina si el cargador puede cargar los datos especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | El contenedor de flujo del que cargar los datos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> cargador puede cargar los datos especificados; de lo contrario, <c>false</c>. |


### Method: load(stream_container, container_palette) {#load_stream_container_container_palette_2}


```
 load(stream_container, container_palette) 
```

Carga el bloque gif.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | El contenedor del flujo. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta del contenedor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Un nuevo bloque gif. |


