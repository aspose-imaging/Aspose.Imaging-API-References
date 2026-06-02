---
title: "Figure Sınıfı"
type: docs
weight: 4770
url: /tr/python-net/aspose.imaging/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Figure

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Figure()](#Figure__1) | Yeni bir [Figure](/imaging/python-net/aspose.imaging/figure/) örneği başlatır.<br/>            JSON serileştirmesi için gereken bir yapıcı. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Nesnenin sınırlarını alır veya ayarlar. |
| is_closed | bool | r/w | Bu şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. Kapalı bir şekil, yalnızca ilk ve son şeklin şekilleri sürekli olduğunda fark yaratır. <br/>            İlk şeklin ilk noktası, <br/>            son şeklin son noktasından düz bir çizgiyle bağlanacaktır. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Tüm şekil segmentlerini alır. |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | r | Şekilleri alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Şekle bir şekil ekler. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Şekle bir dizi şekil ekler. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Nesnenin sınırlarını alır. |
| [remove_shape(shape)](#remove_shape_shape_5) | Şekilden bir şekil kaldırır. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Şekilden bir dizi şekil kaldırır. |
| reverse() | Bu şeklin şekil sırasını ve şekil nokta sırasını tersine çevirir. |
| [transform(transform)](#transform_transform_7) | Belirtilen dönüşümü şekle uygular. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Yeni bir [Figure](/imaging/python-net/aspose.imaging/figure/) örneği başlatır.<br/>            JSON serileştirmesi için gereken bir yapıcı.

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Şekle bir şekil ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | Eklenecek şekil. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...

**[Example # 2](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Şekle bir dizi şekil ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | Eklenecek şekiller. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Nesnenin sınırlarını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Sınırlar hesaplanmadan önce uygulanacak matris. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Tahmini nesne sınırları. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Nesnenin sınırlarını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Sınırlar hesaplanmadan önce uygulanacak matris. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Nesne için kullanılacak kalem. Bu, nesnenin sınır boyutunu etkileyebilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Tahmini nesne sınırları. |


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Şekilden bir şekil kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | Kaldırılacak şekil. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Şekilden bir dizi şekil kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | Kaldırılacak şekil aralığı. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Belirtilen dönüşümü şekle uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Uygulanacak dönüşüm. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Bir dosya akışı örneği oluştur
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# TiffOptions sınıfının bir örneğini oluşturun ve çeşitli özelliklerini ayarlayın
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# ImageOptions örneği için kaynağı ayarlayın
	tiffOptions.source = StreamSource(stream)
	# Image sınıfının bir örneğini oluşturun
	with Image.create(tiffOptions, 500, 500) as image:
		# Graphics sınıfının bir örneğini oluştur ve başlat.
		graphics = Graphics(image)
		# Graphics yüzeyini temizle.
		graphics.clear(Color.wheat);
		# GraphicsPath sınıfının bir örneğini oluşturun
		graphics_path = GraphicsPath()
		# Figure sınıfının bir örneğini oluşturun
		figure = Figure()
		# Figure nesnesine Şekiller ekleyin
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Figure nesnesini GraphicsPath'e ekleyin
		graphics_path.add_figure(figure)
		# Siyah renkli Pen nesnesiyle yolu çizin
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# Tüm değişiklikleri kaydedin.
		image.save()


```

### This example creates a new Image and draws a variety of shapes using figures and `GraphicsPath` on the `Image` surface {#example_16}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, Rectangle, Size
from aspose.imaging import Point, PointF, Pen
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.shapes import EllipseShape, PieShape, ArcShape, PolygonShape, RectangleShape
from os.path import join as path_join

#BmpOptions sınıfının bir örneğini oluşturur ve çeşitli özelliklerini ayarlar            
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#FileCreateSource sınıfının bir örneğini oluşturun ve BmpOptions örneği için Kaynak olarak atayın
	#İkinci Boolean parametresi, oluşturulacak dosyanın Geçici olup olmadığını belirler
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Image bir örnek oluştur.
	with Image.create(bmpOptions, 500, 500) as image:
		# Graphics sınıfının bir örneğini oluştur ve başlat.
		graphics = Graphics(image)
		# Graphics yüzeyini temizle.
		graphics.clear(Color.wheat)
		# GraphicsPath sınıfının bir örneğini oluşturun
		graphicspath = GraphicsPath()
		#Figure sınıfının bir örneğini oluşturun
		figure1 = Figure()
		# Figure nesnesine Şekil ekleyin
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Figure sınıfının bir örneğini oluşturun
		figure2 = Figure()
		# Figure nesnesine Şekil ekleyin
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Figure nesnesini GraphicsPath'e ekleyin
		graphicspath.add_figures([figure1, figure2])
		# Siyah renkli Pen nesnesiyle yolu çizin
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# Tüm değişiklikleri kaydedin.
		image.save()


```

