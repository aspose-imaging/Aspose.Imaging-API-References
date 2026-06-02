---
title: "IImageMask Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/
---

**Summary:** Describes a mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.IImageMask

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Bu maskenin piksel cinsinden sınırlarını alır. |
| height | int | r | Bu maskenin piksel cinsinden yüksekliğini alır. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Maskenin seçilen kısmının piksel cinsinden sınırlarını alır. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | Bu maskeyi oluşturmak için kullanılan kaynak görüntüyü, varsa, alır. |
| width | int | r | Bu maskenin piksel cinsinden genişliğini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_2) | Belirtilen pikselin opaklığını bayt hassasiyetiyle alır. |
| [is_opaque(x, y)](#is_opaque_x_y_3) | Belirtilen pikselin opak olup olmadığını kontrol eder. |
| [is_transparent(x, y)](#is_transparent_x_y_4) | Belirtilen pikselin şeffaf olup olmadığını kontrol eder. |


### Method: clone() {#clone__1}


```
 clone() 
```

Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Object |  |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_2}


```
 get_byte_opacity(x, y) 
```

Belirtilen pikselin opaklığını bayt hassasiyetiyle alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | Belirtilen pikselin opaklığını temsil eden bayt değeri. |


### Method: is_opaque(x, y) {#is_opaque_x_y_3}


```
 is_opaque(x, y) 
```

Belirtilen pikselin opak olup olmadığını kontrol eder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen piksel opak ise true; aksi takdirde false. |


### Method: is_transparent(x, y) {#is_transparent_x_y_4}


```
 is_transparent(x, y) 
```

Belirtilen pikselin şeffaf olup olmadığını kontrol eder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen piksel şeffaf ise true; aksi takdirde false. |


