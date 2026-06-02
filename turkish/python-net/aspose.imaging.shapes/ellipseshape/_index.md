---
title: "EllipseShape Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.imaging.shapes/ellipseshape/
---

**Summary:** Represents an ellipse shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.EllipseShape

**Inheritance:** RectangleShape

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EllipseShape()](#EllipseShape__1) | [EllipseShape](/imaging/python-net/aspose.imaging.shapes/ellipseshape/) sınıfının yeni bir örneğini başlatır. |
| [EllipseShape(rectangle)](#EllipseShape_rectangle_2) | [EllipseShape](/imaging/python-net/aspose.imaging.shapes/ellipseshape/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Nesnenin sınırlarını alır. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Şeklin merkezini alır. |
| has_segments | bool | r | Şeklin segmentlere sahip olup olmadığını gösteren bir değer alır. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Sol alt dikdörtgen noktasını alır. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Sol üst dikdörtgen noktasını alır. |
| rectangle_height | float | r | Dikdörtgen yüksekliğini alır. |
| rectangle_width | float | r | Dikdörtgen genişliğini alır. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Sağ alt dikdörtgen noktasını alır. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Sağ üst dikdörtgen noktasını alır. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Şeklin segmentlerini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Nesnenin sınırlarını alır. |
| [transform(transform)](#transform_transform_3) | Belirtilen dönüşümü şekle uygular. |


### Constructor: EllipseShape() {#EllipseShape__1}


```
 EllipseShape() 
```

[EllipseShape](/imaging/python-net/aspose.imaging.shapes/ellipseshape/) sınıfının yeni bir örneğini başlatır.

### Constructor: EllipseShape(rectangle) {#EllipseShape_rectangle_2}


```
 EllipseShape(rectangle) 
```

[EllipseShape](/imaging/python-net/aspose.imaging.shapes/ellipseshape/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Dikdörtgen. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


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

