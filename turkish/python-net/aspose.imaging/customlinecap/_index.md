---
title: "CustomLineCap Sınıfı"
type: docs
weight: 1350
url: /tr/python-net/aspose.imaging/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CustomLineCap

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Belirtilen dış hat ve dolgu ile [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) sınıfının yeni bir örneğini başlatır. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Belirtilen dış hat ve dolgu ile belirtilen mevcut [LineCap](/imaging/python-net/aspose.imaging/linecap/) enum'undan [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) sınıfının yeni bir örneğini başlatır. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Belirtilen dış hat, dolgu ve iç boşluk ile belirtilen mevcut [LineCap](/imaging/python-net/aspose.imaging/linecap/) enum'undan [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Bu [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) temel alınan [LineCap](/imaging/python-net/aspose.imaging/linecap/) enum'ını alır veya ayarlar. |
| base_inset | float | r/w | Kap ile çizgi arasındaki mesafeyi alır veya ayarlar. |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Özel kap için dolguyu tanımlayan nesneyi alır veya ayarlar. |
| stroke_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Bu [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) nesnesini oluşturan çizgilerin nasıl birleştirileceğini belirleyen [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) enum'ını alır veya ayarlar. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Özel kapağın dış hatını tanımlayan nesneyi alır veya ayarlar. |
| width_scale | float | r/w | Bu [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) sınıfı nesnesini, nesnenin genişliğine göre ölçeklendirme miktarını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Bu özel kapağı oluşturan çizgileri başlatmak ve sonlandırmak için kullanılan kapları alır. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Bu özel kapağı oluşturan çizgileri başlatmak ve sonlandırmak için kullanılan kapları ayarlar. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Belirtilen dış hat ve dolgu ile [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Özel kap için dolguyu tanımlayan bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nesnesi. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Özel kap için dış hatı tanımlayan bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nesnesi. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Belirtilen dış hat ve dolgu ile belirtilen mevcut [LineCap](/imaging/python-net/aspose.imaging/linecap/) enum'undan [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Özel kap için dolguyu tanımlayan bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nesnesi. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Özel kap için dış hatı tanımlayan bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nesnesi. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Özel kapağı oluşturmak için kullanılacak çizgi kapağı. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Belirtilen dış hat, dolgu ve iç boşluk ile belirtilen mevcut [LineCap](/imaging/python-net/aspose.imaging/linecap/) enum'undan [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Özel kap için dolguyu tanımlayan bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nesnesi. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Özel kap için dış hatı tanımlayan bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nesnesi. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Özel kapağı oluşturmak için kullanılacak çizgi kapağı. |
| base_inset | float | Kap ile çizgi arasındaki mesafe. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Bu özel kapağı oluşturan çizgileri başlatmak ve sonlandırmak için kullanılan kapları alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| start_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | Bu kap içinde bir çizginin başlangıcında kullanılan [LineCap](/imaging/python-net/aspose.imaging/linecap/) enum'ı. |
| end_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | Bu kap içinde bir çizginin sonunda kullanılan [LineCap](/imaging/python-net/aspose.imaging/linecap/) enum'ı. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Bu özel kapağı oluşturan çizgileri başlatmak ve sonlandırmak için kullanılan kapları ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Bu kap içinde bir çizginin başlangıcında kullanılan [LineCap](/imaging/python-net/aspose.imaging/linecap/) enum'ı. |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Bu kap içinde bir çizginin sonunda kullanılan [LineCap](/imaging/python-net/aspose.imaging/linecap/) enum'ı. |

