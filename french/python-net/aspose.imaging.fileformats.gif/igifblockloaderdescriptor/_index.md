---
title: "IGifBlockLoaderDescriptor Classe"
type: docs
weight: 110
url: /fr/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/
---

**Summary:** Gif block Loader descriptor.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container)](#can_load_stream_container_1) | Détermine si le chargeur peut charger les données spécifiées. |
| [load(stream_container, container_palette)](#load_stream_container_container_palette_2) | Charge le bloc gif. |


### Method: can_load(stream_container) {#can_load_stream_container_1}


```
 can_load(stream_container) 
```

Détermine si le chargeur peut charger les données spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le conteneur de flux à partir duquel charger les données. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> le chargeur peut charger les données spécifiées ; sinon, <c>false</c>. |


### Method: load(stream_container, container_palette) {#load_stream_container_container_palette_2}


```
 load(stream_container, container_palette) 
```

Charge le bloc gif.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le conteneur de flux. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette du conteneur. |

**Returns**

| Type | Description |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Un nouveau bloc gif. |


