---
title: "PolygonShape Sınıfı"
type: docs
weight: 60
url: /tr/python-net/aspose.imaging.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Yeni bir [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) sınıfı örneği başlatır. |
| [PolygonShape(points)](#PolygonShape_points_2) | Yeni bir [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) sınıfı örneği başlatır. |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Yeni bir [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Nesnenin sınırlarını alır. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Şeklin merkezini alır. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Şeklin son noktasını alır. |
| has_segments | bool | r | Şeklin segmentlere sahip olup olmadığını gösteren bir değer alır. |
| is_closed | bool | r/w | Şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Eğri noktalarını alır veya ayarlar. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Şeklin segmentlerini alır. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Şeklin başlangıç noktasını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Nesnenin sınırlarını alır. |
| reverse() | Bu şekil için nokta sırasını tersine çevirir. |
| [transform(transform)](#transform_transform_3) | Belirtilen dönüşümü şekle uygular. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Yeni bir [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) sınıfı örneği başlatır.

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Yeni bir [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Nokta dizisi. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Yeni bir [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Nokta dizisi. |
| is_closed | bool | Eğer <c>true</c> olarak ayarlanırsa çokgen kapalıdır. |

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

