---
title: "IGifBlockLoaderDescriptor Sınıfı"
type: docs
weight: 110
url: /tr/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/
---

**Summary:** Gif block Loader descriptor.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [can_load(stream_container)](#can_load_stream_container_1) | Yükleyicinin belirtilen veriyi yükleyip yükleyemeyeceğini belirler. |
| [load(stream_container, container_palette)](#load_stream_container_container_palette_2) | Gif bloğunu yükler. |


### Method: can_load(stream_container) {#can_load_stream_container_1}


```
 can_load(stream_container) 
```

Yükleyicinin belirtilen veriyi yükleyip yükleyemeyeceğini belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Verinin yükleneceği akış konteyneri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> yükleyici belirtilen veriyi yükleyebilir; aksi takdirde <c>false</c>. |


### Method: load(stream_container, container_palette) {#load_stream_container_container_palette_2}


```
 load(stream_container, container_palette) 
```

Gif bloğunu yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Akış kapsayıcısı. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Kapsayıcı palet. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Yeni bir gif bloğu. |


