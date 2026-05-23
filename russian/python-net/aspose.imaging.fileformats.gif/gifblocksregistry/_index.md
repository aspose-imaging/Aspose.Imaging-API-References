---
title: "GifBlocksRegistry Класс"
type: docs
weight: 30
url: /ru/python-net/aspose.imaging.fileformats.gif/gifblocksregistry/
---

**Summary:** Represents the gif blocks openers registry.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifBlocksRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IGifBlockLoaderDescriptor[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | r | Получает зарегистрированные дескрипторы. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Получает первый поддерживаемый дескриптор открывателя. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Получает первый поддерживаемый дескриптор по его имени типа. |
| [load_block_by_first_supported_descriptor(stream, container_palette)](#load_block_by_first_supported_descriptor_stream_container_palette_3) | Загружает gif‑блок, используя первый найденный открыватель, подходящий для указанного _stream_. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Регистрирует открыватель. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Снимает регистрацию с открывателя. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Получает первый поддерживаемый дескриптор открывателя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Дескриптор открывателя gif‑блока или null, если для такого потока не поддерживается дескриптор открывателя. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Получает первый поддерживаемый дескриптор по его имени типа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| descriptor_type_name | string | Имя типа дескриптора. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Первый найденный дескриптор открывателя или null, если такой дескриптор не найден. |


### Method: load_block_by_first_supported_descriptor(stream, container_palette)  [static] {#load_block_by_first_supported_descriptor_stream_container_palette_3}


```
 load_block_by_first_supported_descriptor(stream, container_palette) 
```

Загружает gif‑блок, используя первый найденный открыватель, подходящий для указанного _stream_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Палитра контейнера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Загруженный gif‑блок или null, если открыватель не найден. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Регистрирует открыватель.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Дескриптор открывателя для регистрации. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Снимает регистрацию с открывателя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Дескриптор открывателя для снятия регистрации. |

