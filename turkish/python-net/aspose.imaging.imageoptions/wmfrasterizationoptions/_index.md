---
title: "WmfRasterizationOptions Sınıfı"
type: docs
weight: 380
url: /tr/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/
---

**Summary:** The Wmf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions__1) | Yeni bir [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/) sınıfı örneği başlatır. |
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
| [render_mode](#render_mode1) | [WmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfrendermode/) | r/w | WMF render modunu alır veya ayarlar. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Yumuşatma modunu alır veya ayarlar. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Metin renderleme ipucunu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Geçerli örneğin yüzeysel bir kopyası olan yeni bir nesne oluşturur. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Bunu _vectorRasterizationOptions_ öğesine kopyalar. |


### Constructor: WmfRasterizationOptions() {#WmfRasterizationOptions__1}


```
 WmfRasterizationOptions() 
```

Yeni bir [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/) sınıfı örneği başlatır.

### Property: render_mode {#render_mode1}

WMF render modunu alır veya ayarlar.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


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

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Aspose.Imaging.Image.Load kullanmak, WMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Metin şekillere dönüştürülecek.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# Çizim yüzeyinin arka plan rengi.
	rasterizationOptions.background_color = Color.white_smoke
	# Sayfa boyutu.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Gömülü emf varsa, emf işlenir; aksi takdirde wmf işlenir.
	rasterizationOptions.render_mode = WmfRenderMode.AUTO
	saveOptions.vector_rasterization_options = rasterizationOptions
	wmfImage.save("test.output.svg", saveOptions)


```

