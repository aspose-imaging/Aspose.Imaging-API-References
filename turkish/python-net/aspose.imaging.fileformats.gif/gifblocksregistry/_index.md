---
title: "GifBlocksRegistry Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.imaging.fileformats.gif/gifblocksregistry/
---

**Summary:** Represents the gif blocks openers registry.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifBlocksRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IGifBlockLoaderDescriptor[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | r | Kayıtlı tanımlayıcıları alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | İlk desteklenen açıcı tanımlayıcısını alır. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Tür adıyla ilk desteklenen tanımlayıcıyı alır. |
| [load_block_by_first_supported_descriptor(stream, container_palette)](#load_block_by_first_supported_descriptor_stream_container_palette_3) | Belirtilen _stream_ için uygun bulunan ilk açıcıyı kullanarak gif bloğunu yükler. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Açıcıyı kaydeder. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Açıcı kaydını siler. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

İlk desteklenen açıcı tanımlayıcısını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Gif bloğu açıcı tanımlayıcısı; böyle bir akış için desteklenen bir açıcı tanımlayıcısı yoksa null. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Tür adıyla ilk desteklenen tanımlayıcıyı alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| descriptor_type_name | string | Tanımlayıcı tür adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Bulunan ilk açıcı tanımlayıcısı; böyle bir tanımlayıcı bulunamazsa null. |


### Method: load_block_by_first_supported_descriptor(stream, container_palette)  [static] {#load_block_by_first_supported_descriptor_stream_container_palette_3}


```
 load_block_by_first_supported_descriptor(stream, container_palette) 
```

Belirtilen _stream_ için uygun bulunan ilk açıcıyı kullanarak gif bloğunu yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Kapsayıcı palet. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Yüklenen gif bloğu; açıcı bulunamazsa null. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Açıcıyı kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Kaydedilecek açıcı tanımlayıcısı. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Açıcı kaydını siler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Kaydı silinecek açıcı tanımlayıcısı. |

