---
title: "EmfRasterizationOptions Sınıfı"
type: docs
weight: 100
url: /tr/python-net/aspose.imaging.imageoptions/emfrasterizationoptions/
---

**Summary:** The Emf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.EmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions__1) | EmfRasterizationOptions sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Arka plan rengini alır veya ayarlar. |
| border_x | float | r/w | Sınır X'i alır veya ayarlar. |
| border_y | float | r/w | Sınır Y'yi alır veya ayarlar. |
| center_drawing | bool | r/w | Orta çizim olup olmadığını gösteren bir değeri alır veya ayarlar. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ön plan rengini alır veya ayarlar. |
| page_height | float | r/w | Sayfa yüksekliğini alır veya ayarlar.<br/>            Değer 0 ise, kaynak görüntünün en‑boy oranı korunur. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Sayfa boyutunu alır veya ayarlar.<br/>            Eğer [SizeF](/imaging/python-net/aspose.imaging/sizef/) boyutlarından biri 0 ise, kaynak görüntünün en‑boy oranı korunur. |
| page_width | float | r/w | Sayfa genişliğini alır veya ayarlar.<br/>            Değer 0 ise, kaynak görüntünün en‑boy oranı korunur. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Konumlandırmayı alır veya ayarlar. |
| render_mode | [EmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.emf/emfrendermode/) | r/w | Render modunu alır veya ayarlar. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Yumuşatma modunu alır veya ayarlar. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Metin renderleme ipucunu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Geçerli örneğin yüzeysel bir kopyası olan yeni bir nesne oluşturur. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Bunu _vectorRasterizationOptions_ öğesine kopyalar. |


### Constructor: EmfRasterizationOptions() {#EmfRasterizationOptions__1}


```
 EmfRasterizationOptions() 
```

EmfRasterizationOptions sınıfının yeni bir örneğini başlatır.

### Method: clone() {#clone__1}


```
 clone() 
```

Geçerli örneğin yüzeysel bir kopyası olan yeni bir nesne oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Object | Bu örneğin yüzeysel bir kopyası olan yeni bir nesne. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Bunu _vectorRasterizationOptions_ öğesine kopyalar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | vectorRasterizationOptions |

