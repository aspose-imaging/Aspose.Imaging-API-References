---
title: "IGifBlockLoaderDescriptor klass"
type: docs
weight: 110
url: /sv/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/
---

**Summary:** Gif block Loader descriptor.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container)](#can_load_stream_container_1) | Bestämmer om laddaren kan läsa in den angivna datan. |
| [load(stream_container, container_palette)](#load_stream_container_container_palette_2) | Läser in gif-blocket. |


### Method: can_load(stream_container) {#can_load_stream_container_1}


```
 can_load(stream_container) 
```

Bestämmer om laddaren kan läsa in den angivna datan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Strömbehållaren att läsa data från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> laddaren kan läsa in den angivna datan; annars, <c>false</c>. |


### Method: load(stream_container, container_palette) {#load_stream_container_container_palette_2}


```
 load(stream_container, container_palette) 
```

Läser in gif-blocket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Strömbehållaren. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Behållarpaletten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Ett nytt gif-block. |


