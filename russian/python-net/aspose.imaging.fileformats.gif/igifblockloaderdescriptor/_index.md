---
title: "Класс IGifBlockLoaderDescriptor"
type: docs
weight: 110
url: /ru/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/
---

**Summary:** Gif block Loader descriptor.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container)](#can_load_stream_container_1) | Определяет, может ли загрузчик загрузить указанные данные. |
| [load(stream_container, container_palette)](#load_stream_container_container_palette_2) | Загружает gif‑блок. |


### Method: can_load(stream_container) {#can_load_stream_container_1}


```
 can_load(stream_container) 
```

Определяет, может ли загрузчик загрузить указанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Контейнер потока, из которого загружаются данные. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> загрузчик может загрузить указанные данные; иначе <c>false</c>. |


### Method: load(stream_container, container_palette) {#load_stream_container_container_palette_2}


```
 load(stream_container, container_palette) 
```

Загружает gif‑блок.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Контейнер потока. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Палитра контейнера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Новый gif‑блок. |


