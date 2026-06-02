---
title: "CdrRasterizationOptions Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.imaging.imageoptions/cdrrasterizationoptions/
---

**Summary:** With the ability to perform CDR image rasterization and set scale factors<br/>            for both X and Y dimensions, this API provides precise control over the<br/>            transformation process. Whether scaling for specific output requirements<br/>            or converting vector graphics to raster formats, you can leverage this<br/>            API for efficient and customizable CDR vector to raster image conversion.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.CdrRasterizationOptions

**Inheritance:** VectorRasterizationOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CdrRasterizationOptions()](#CdrRasterizationOptions__1) | Yeni bir [CdrRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/cdrrasterizationoptions/) sınıfı örneği başlatır. |
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
| scale_x | float | r/w | scale x'i alır veya ayarlar. |
| scale_y | float | r/w | scale y'i alır veya ayarlar. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Yumuşatma modunu alır veya ayarlar. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Metin renderleme ipucunu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Geçerli örneğin yüzeysel bir kopyası olan yeni bir nesne oluşturur. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Kopyalar. |


### Constructor: CdrRasterizationOptions() {#CdrRasterizationOptions__1}


```
 CdrRasterizationOptions() 
```

Yeni bir [CdrRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/cdrrasterizationoptions/) sınıfı örneği başlatır.

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

Kopyalar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | Vektör rasterleştirme seçenekleri. |

