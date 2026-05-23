---
title: "Classe IGifBlockLoaderDescriptor"
type: docs
weight: 110
url: /it/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/
---

**Summary:** Gif block Loader descriptor.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [can_load(stream_container)](#can_load_stream_container_1) | Determina se il loader può caricare i dati specificati. |
| [load(stream_container, container_palette)](#load_stream_container_container_palette_2) | Carica il blocco gif. |


### Method: can_load(stream_container) {#can_load_stream_container_1}


```
 can_load(stream_container) 
```

Determina se il loader può caricare i dati specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Il contenitore di stream da cui caricare i dati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> il loader può caricare i dati specificati; altrimenti, <c>false</c>. |


### Method: load(stream_container, container_palette) {#load_stream_container_container_palette_2}


```
 load(stream_container, container_palette) 
```

Carica il blocco gif.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Il contenitore dello stream. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza del contenitore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Un nuovo blocco gif. |


