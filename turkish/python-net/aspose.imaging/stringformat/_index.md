---
title: "StringFormat Sınıfı"
type: docs
weight: 7370
url: /tr/python-net/aspose.imaging/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormat

**Inheritance:** DisposableObject

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Yeni bir [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi başlatır. |
| [StringFormat(format)](#StringFormat_format_2) | Belirtilen mevcut [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesinden yeni bir [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi başlatır. |
| [StringFormat(options)](#StringFormat_options_3) | Belirtilen [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enum değeri ve dil ile yeni bir [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Dikey düzlemde metin hizalama bilgilerini alır veya ayarlar. |
| custom_char_ident | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Özel karakter kimliğini alır veya ayarlar. |
| digit_substitution_language | int | r/w | Yerel rakamların batı rakamlarıyla değiştirildiği durumda kullanılan dili alır veya ayarlar. |
| digit_substitution_method | [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | r/w | Rakam ikamesi için kullanılacak yöntemi alır veya ayarlar. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| first_tab_offset | float | r | Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısını alır. |
| format_flags | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | r/w | Biçimlendirme bilgilerini içeren bir [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enum değerini alır veya ayarlar. |
| generic_default [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Genel bir varsayılan [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi alır. |
| generic_typographic [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Genel bir tipografik [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi alır. |
| hotkey_prefix | [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | r/w | Bu [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi için [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) nesnesini alır veya ayarlar. |
| line_alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Yatay düzlemde satır hizalamasını alır veya ayarlar. |
| tab_stops | float[] | r | [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/) özelliği tarafından belirtilen birimlerde sekme durakları arasındaki mesafelerin bir dizisini alır. |
| trimming | [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | r/w | Bu [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi için [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) enum değerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_flags(options)](#create_from_flags_options_1) | Belirtilen [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enum değeri ve dil ile yeni bir [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi başlatır. |
| [create_from_format(format)](#create_from_format_format_2) | Belirtilen mevcut [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesinden yeni bir [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi başlatır. |
| [deep_clone()](#deep_clone__3) | Bu [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesinin derin bir kopyasını oluşturur. |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_4) | Bu [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi için sekme duraklarını ayarlar. |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Yeni bir [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi başlatır.

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Belirtilen mevcut [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesinden yeni bir [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Yeni [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesini başlatmak için kullanılacak [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi. |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Belirtilen [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enum değeri ve dil ile yeni bir [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Yeni [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi için [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enum değeri. |

### Method: create_from_flags(options)  [static] {#create_from_flags_options_1}


```
 create_from_flags(options) 
```

Belirtilen [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enum değeri ve dil ile yeni bir [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Yeni [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi için [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enum değeri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: create_from_format(format)  [static] {#create_from_format_format_2}


```
 create_from_format(format) 
```

Belirtilen mevcut [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesinden yeni bir [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Yeni [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesini başlatmak için kullanılacak [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: deep_clone() {#deep_clone__3}


```
 deep_clone() 
```

Bu [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesinin derin bir kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Mevcut [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesinin derin kopyası. |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_4}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Bu [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) nesnesi için sekme duraklarını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| first_tab_offset | float | Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısı. |
| tab_stops | float[] | Sekme durakları arasındaki mesafelerin, [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/) özelliği tarafından belirtilen birimlerdeki bir dizisi. |

