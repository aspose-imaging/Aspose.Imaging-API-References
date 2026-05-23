---
title: "ArcShape Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Yeni bir [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) sınıfı örneği başlatır. |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Yeni bir [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) sınıfı örneği başlatır. |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Yeni bir [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Nesnenin sınırlarını alır. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Şeklin merkezini alır. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Şeklin son noktasını alır. |
| has_segments | bool | r | Şeklin segmentlere sahip olup olmadığını gösteren bir değer alır. |
| is_closed | bool | r/w | Kapalı sıralı şeklin olup olmadığını gösteren bir değeri alır veya ayarlar. Kapalı sıralı şekil işlenirken başlangıç ve bitiş noktaları bir anlam taşımaz. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Sol alt dikdörtgen noktasını alır. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Sol üst dikdörtgen noktasını alır. |
| rectangle_height | float | r | Dikdörtgen yüksekliğini alır. |
| rectangle_width | float | r | Dikdörtgen genişliğini alır. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Sağ alt dikdörtgen noktasını alır. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Sağ üst dikdörtgen noktasını alır. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Şeklin segmentlerini alır. |
| start_angle | float | r/w | Başlangıç açısını alır veya ayarlar. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Şeklin başlangıç noktasını alır. |
| sweep_angle | float | r/w | Tarama açısını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Nesnenin sınırlarını alır. |
| reverse() | Bu şekil için nokta sırasını tersine çevirir. |
| [transform(transform)](#transform_transform_3) | Belirtilen dönüşümü şekle uygular. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Yeni bir [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) sınıfı örneği başlatır.

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Yeni bir [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Dikdörtgen. |
| start_angle | float | Başlangıç açısı. |
| sweep_angle | float | Tarama açısı. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Yeni bir [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Dikdörtgen. |
| start_angle | float | Başlangıç açısı. |
| sweep_angle | float | Tarama açısı. |
| is_closed | bool | Eğer <c>true</c> olarak ayarlanırsa yay kapatılır. Kapalı yay aslında bir elipse dönüşür. |

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

