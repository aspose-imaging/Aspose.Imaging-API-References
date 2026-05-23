---
title: "Font Sınıfı"
type: docs
weight: 4830
url: /tr/python-net/aspose.imaging/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Font

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Belirtilen bir boyut kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) olarak ayarlanır, grafik birimi [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/) olarak belirlenir, font stili ise [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/) olarak ayarlanır. |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Belirtilen bir boyut ve stil kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) olarak ayarlanır, grafik birimi ise [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/) olarak belirlenir. |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Belirtilen bir boyut, stil ve birim kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Belirtilen bir boyut, stil, birim ve karakter kümesi kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Belirtilen bir boyut ve birim kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) olarak ayarlanır, stil ise [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/) olarak belirlenir. |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Belirtilen mevcut [Font](/imaging/python-net/aspose.imaging/font/) ve [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) enumerasyonunu kullanan yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bold | bool | r | Bu [Font](/imaging/python-net/aspose.imaging/font/) kalın olup olmadığını gösteren bir değer alır. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | r | Bu [Font](/imaging/python-net/aspose.imaging/font/) tarafından kullanılan karakter kümesini belirten bir bayt değeri alır. |
| italic | bool | r | Bu [Font](/imaging/python-net/aspose.imaging/font/) eğik mi olduğunu gösteren bir değer alır. |
| name | string | r | Bu [Font](/imaging/python-net/aspose.imaging/font/) yüz adını alır. |
| size | float | r | Bu [Font](/imaging/python-net/aspose.imaging/font/) için, [Font.unit](/imaging/python-net/aspose.imaging/font/) özelliği tarafından belirtilen birimlerde ölçülen em-boyutunu alır. |
| strikeout | bool | r | Bu [Font](/imaging/python-net/aspose.imaging/font/) üzerinde yatay bir çizgi belirtiyor mu olduğunu gösteren bir değer alır. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | r | Bu [Font](/imaging/python-net/aspose.imaging/font/) için stil bilgilerini alır. |
| underline | bool | r | Bu [Font](/imaging/python-net/aspose.imaging/font/) altı çizili mi olduğunu gösteren bir değer alır. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r | Bu [Font](/imaging/python-net/aspose.imaging/font/) için ölçü birimini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_prototype(prototype, new_style)](#create_from_prototype_prototype_new_style_1) | Belirtilen mevcut [Font](/imaging/python-net/aspose.imaging/font/) ve [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) enumerasyonunu kullanan yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. |
| [create_with_size(font_name, em_size)](#create_with_size_font_name_em_size_2) | Belirtilen bir boyut kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) olarak ayarlanır, grafik birimi [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/) olarak belirlenir, font stili ise [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/) olarak ayarlanır. |
| [create_with_size_style(font_name, em_size, style)](#create_with_size_style_font_name_em_size_style_3) | Belirtilen bir boyut ve stil kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) olarak ayarlanır, grafik birimi ise [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/) olarak belirlenir. |
| [create_with_size_unit(font_name, em_size, unit)](#create_with_size_unit_font_name_em_size_unit_4) | Belirtilen bir boyut ve birim kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) olarak ayarlanır, stil ise [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/) olarak belirlenir. |
| [deep_clone()](#deep_clone__5) | Bu [Font](/imaging/python-net/aspose.imaging/font/) nesnesinin tam bir derin kopyasını oluşturur. |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Belirtilen bir boyut kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) olarak ayarlanır, grafik birimi [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/) olarak belirlenir, font stili ise [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/) olarak ayarlanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) adının dize temsili. |
| em_size | float | Yeni fontun puan cinsinden em-boyutu. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Belirtilen bir boyut ve stil kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) olarak ayarlanır, grafik birimi ise [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/) olarak belirlenir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) adının dize temsili. |
| em_size | float | Yeni fontun puan cinsinden em-boyutu. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Yeni fontun [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) özelliği. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Belirtilen bir boyut, stil ve birim kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) adının dize temsili. |
| em_size | float | Yeni fontun, _unit_ parametresi tarafından belirtilen birimlerdeki em-boyutu. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Yeni fontun [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) özelliği. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Yeni fontun [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) birimi. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Belirtilen bir boyut, stil, birim ve karakter kümesi kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) adının dize temsili. |
| em_size | float | Yeni fontun, _unit_ parametresi tarafından belirtilen birimlerdeki em-boyutu. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Yeni fontun [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) özelliği. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Yeni fontun [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) birimi. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Bu font için kullanılacak bir karakter kümesi. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Belirtilen bir boyut ve birim kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) olarak ayarlanır, stil ise [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/) olarak belirlenir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) adının dize temsili. |
| em_size | float | Yeni fontun, _unit_ parametresi tarafından belirtilen birimlerdeki em-boyutu. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Yeni fontun [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) birimi. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Belirtilen mevcut [Font](/imaging/python-net/aspose.imaging/font/) ve [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) enumerasyonunu kullanan yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | Yeni [Font](/imaging/python-net/aspose.imaging/font/) oluşturulacak mevcut [Font](/imaging/python-net/aspose.imaging/font/). |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Yeni [Font](/imaging/python-net/aspose.imaging/font/) üzerine uygulanacak [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/). [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) enumarasyonunun birden fazla değeri OR operatörü ile birleştirilebilir. |

### Method: create_from_prototype(prototype, new_style)  [static] {#create_from_prototype_prototype_new_style_1}


```
 create_from_prototype(prototype, new_style) 
```

Belirtilen mevcut [Font](/imaging/python-net/aspose.imaging/font/) ve [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) enumerasyonunu kullanan yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | Yeni [Font](/imaging/python-net/aspose.imaging/font/) oluşturulacak mevcut [Font](/imaging/python-net/aspose.imaging/font/). |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Yeni [Font](/imaging/python-net/aspose.imaging/font/) üzerine uygulanacak [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/). [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) enumarasyonunun birden fazla değeri OR operatörü ile birleştirilebilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size(font_name, em_size)  [static] {#create_with_size_font_name_em_size_2}


```
 create_with_size(font_name, em_size) 
```

Belirtilen bir boyut kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) olarak ayarlanır, grafik birimi [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/) olarak belirlenir, font stili ise [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/) olarak ayarlanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) adının dize temsili. |
| em_size | float | Yeni fontun puan cinsinden em-boyutu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_style(font_name, em_size, style)  [static] {#create_with_size_style_font_name_em_size_style_3}


```
 create_with_size_style(font_name, em_size, style) 
```

Belirtilen bir boyut ve stil kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) olarak ayarlanır, grafik birimi ise [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/) olarak belirlenir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) adının dize temsili. |
| em_size | float | Yeni fontun puan cinsinden em-boyutu. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Yeni fontun [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) özelliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_unit(font_name, em_size, unit)  [static] {#create_with_size_unit_font_name_em_size_unit_4}


```
 create_with_size_unit(font_name, em_size, unit) 
```

Belirtilen bir boyut ve birim kullanarak yeni bir [Font](/imaging/python-net/aspose.imaging/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) olarak ayarlanır, stil ise [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/) olarak belirlenir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) adının dize temsili. |
| em_size | float | Yeni fontun, _unit_ parametresi tarafından belirtilen birimlerdeki em-boyutu. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Yeni fontun [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) birimi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Bu [Font](/imaging/python-net/aspose.imaging/font/) nesnesinin tam bir derin kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) | Bu yöntemin oluşturduğu [Font](/imaging/python-net/aspose.imaging/font/). |


