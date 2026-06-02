---
title: "IGifBlockLoaderDescriptor Klasse"
type: docs
weight: 110
url: /de/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/
---

**Summary:** Gif block Loader descriptor.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [can_load(stream_container)](#can_load_stream_container_1) | Bestimmt, ob der Loader die angegebenen Daten laden kann. |
| [load(stream_container, container_palette)](#load_stream_container_container_palette_2) | Lädt den GIF-Block. |


### Method: can_load(stream_container) {#can_load_stream_container_1}


```
 can_load(stream_container) 
```

Bestimmt, ob der Loader die angegebenen Daten laden kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Der Stream-Container, aus dem Daten geladen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> Loader kann die angegebenen Daten laden; andernfalls <c>false</c>. |


### Method: load(stream_container, container_palette) {#load_stream_container_container_palette_2}


```
 load(stream_container, container_palette) 
```

Lädt den GIF-Block.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Der Stream-Container. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Container-Palette. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Ein neuer GIF-Block. |


