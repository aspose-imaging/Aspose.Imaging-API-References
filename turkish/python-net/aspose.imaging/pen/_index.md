---
title: "Pen Sınıfı"
type: docs
weight: 6890
url: /tr/python-net/aspose.imaging/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Pen

**Inheritance:** TransparencySupporter

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Belirtilen [Pen.brush](/imaging/python-net/aspose.imaging/pen/) ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır. |
| [Pen(brush, width)](#Pen_brush_width_2) | Belirtilen [Pen.brush](/imaging/python-net/aspose.imaging/pen/) ve [Pen.width](/imaging/python-net/aspose.imaging/pen/) ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır. |
| [Pen(color)](#Pen_color_3) | Belirtilen renk ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır. |
| [Pen(color, width)](#Pen_color_width_4) | Belirtilen [Pen.color](/imaging/python-net/aspose.imaging/pen/) ve [Pen.width](/imaging/python-net/aspose.imaging/pen/) özellikleri ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | r/w | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) için hizalamayı alır veya ayarlar. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | r/w | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) özelliklerini belirleyen [Pen.brush](/imaging/python-net/aspose.imaging/pen/) alır veya ayarlar. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) rengini alır veya ayarlar. |
| compound_array | float[] | r/w | Bir bileşik kalemi belirten değerler dizisini alır veya ayarlar. Bileşik kalem, paralel çizgiler ve boşluklardan oluşan bir bileşik çizgi çizer. |
| custom_end_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen satırların sonunda kullanılacak özel bir kapak alır veya ayarlar. |
| custom_start_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen satırların başlangıcında kullanılacak özel bir kapak alır veya ayarlar. |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | r/w | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen kesikli satırları oluşturan tirelerin sonunda kullanılan kapak stilini alır veya ayarlar. |
| dash_offset | float | r/w | Bir satırın başlangıcından tire deseninin başlangıcına olan mesafeyi alır veya ayarlar. |
| dash_pattern | float[] | r/w | Özel tire ve boşluklardan oluşan bir dizi alır veya ayarlar. |
| dash_style | [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | r/w | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen kesikli çizgiler için kullanılan stili alır veya ayarlar. |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen çizgilerin sonunda kullanılan kapak stilini alır veya ayarlar. |
| line_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen iki ardışık çizginin uçları için birleştirme stilini alır veya ayarlar. |
| miter_limit | float | r/w | Miter köşesindeki birleşim kalınlığının sınırını alır veya ayarlar. |
| opacity | float | r/w | Nesnenin opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri nesnenin tamamen görünür olduğu, 1 değeri ise nesnenin tamamen opak olduğu anlamına gelir. |
| pen_type | [PenType](/imaging/python-net/aspose.imaging/pentype/) | r | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen çizgilerin stilini alır. |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen çizgilerin başlangıcında kullanılan kapak stilini alır veya ayarlar. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) için geometrik dönüşümün bir kopyasını alır veya ayarlar. |
| width | float | r/w | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) genişliğini, çizim için kullanılan Graphics nesnesinin birimlerinde alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_with_brush(brush)](#create_with_brush_brush_1) | Belirtilen [Pen.brush](/imaging/python-net/aspose.imaging/pen/) ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır. |
| [create_with_brush_width(brush, width)](#create_with_brush_width_brush_width_2) | Belirtilen [Pen.brush](/imaging/python-net/aspose.imaging/pen/) ve [Pen.width](/imaging/python-net/aspose.imaging/pen/) ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır. |
| [create_with_color(color)](#create_with_color_color_3) | Belirtilen renk ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır. |
| [create_with_color_width(color, width)](#create_with_color_width_color_width_4) | Belirtilen [Pen.color](/imaging/python-net/aspose.imaging/pen/) ve [Pen.width](/imaging/python-net/aspose.imaging/pen/) özellikleri ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır. |
| [multiply_transform(matrix)](#multiply_transform_matrix_5) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) için dönüşüm matrisini belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile çarpar. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_6) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) için dönüşüm matrisini belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile belirtilen sırada çarpar. |
| reset_transform() | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) için geometrik dönüşüm matrisini birim matrise sıfırlar. |
| [rotate_transform(angle)](#rotate_transform_angle_7) | Yerel geometrik dönüşümü belirtilen açıyla döndürür. Bu yöntem dönüşüme rotasyonu ön ekler. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_8) | Yerel geometrik dönüşümü belirtilen açıyla belirtilen sırada döndürür. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_9) | Yerel geometrik dönüşümü belirtilen faktörlerle ölçeklendirir. Bu yöntem dönüşüme ölçekleme matrisini ön ekler. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_10) | Yerel geometrik dönüşümü belirtilen faktörlerle belirtilen sırada ölçeklendirir. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_11) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen çizgileri sonlandırmak için kullanılan kapak stilini belirleyen değerleri ayarlar. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem dönüşüme çeviriyi ön ekler. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Yerel geometrik dönüşümü belirtilen boyutlarla belirtilen sırada çevirir. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Belirtilen [Pen.brush](/imaging/python-net/aspose.imaging/pen/) ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) doldurma özelliklerini belirleyen bir [Pen.brush](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Belirtilen [Pen.brush](/imaging/python-net/aspose.imaging/pen/) ve [Pen.width](/imaging/python-net/aspose.imaging/pen/) ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) özelliklerini belirleyen bir [Pen.brush](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Yeni [Pen](/imaging/python-net/aspose.imaging/pen/) genişliği. |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Belirtilen renk ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) rengini gösteren bir [Pen.color](/imaging/python-net/aspose.imaging/pen/) yapısı. |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Belirtilen [Pen.color](/imaging/python-net/aspose.imaging/pen/) ve [Pen.width](/imaging/python-net/aspose.imaging/pen/) özellikleri ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) rengini gösteren bir [Pen.color](/imaging/python-net/aspose.imaging/pen/) yapısı. |
| width | float | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) nesnesinin genişliğini belirten bir değer. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: create_with_brush(brush)  [static] {#create_with_brush_brush_1}


```
 create_with_brush(brush) 
```

Belirtilen [Pen.brush](/imaging/python-net/aspose.imaging/pen/) ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) doldurma özelliklerini belirleyen bir [Pen.brush](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_brush_width(brush, width)  [static] {#create_with_brush_width_brush_width_2}


```
 create_with_brush_width(brush, width) 
```

Belirtilen [Pen.brush](/imaging/python-net/aspose.imaging/pen/) ve [Pen.width](/imaging/python-net/aspose.imaging/pen/) ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) özelliklerini belirleyen bir [Pen.brush](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Yeni [Pen](/imaging/python-net/aspose.imaging/pen/) genişliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color(color)  [static] {#create_with_color_color_3}


```
 create_with_color(color) 
```

Belirtilen renk ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) rengini gösteren bir [Pen.color](/imaging/python-net/aspose.imaging/pen/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color_width(color, width)  [static] {#create_with_color_width_color_width_4}


```
 create_with_color_width(color, width) 
```

Belirtilen [Pen.color](/imaging/python-net/aspose.imaging/pen/) ve [Pen.width](/imaging/python-net/aspose.imaging/pen/) özellikleri ile yeni bir [Pen](/imaging/python-net/aspose.imaging/pen/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) rengini gösteren bir [Pen.color](/imaging/python-net/aspose.imaging/pen/) yapısı. |
| width | float | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) nesnesinin genişliğini belirten bir değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_5}


```
 multiply_transform(matrix) 
```

Bu [Pen](/imaging/python-net/aspose.imaging/pen/) için dönüşüm matrisini belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Dönüşüm matrisini çarpmak için kullanılacak [Matrix](/imaging/python-net/aspose.imaging/matrix/) nesnesi. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_6}


```
 multiply_transform(matrix, order) 
```

Bu [Pen](/imaging/python-net/aspose.imaging/pen/) için dönüşüm matrisini belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile belirtilen sırada çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Dönüşüm matrisini çarpmak için kullanılacak [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Çarpma işleminin gerçekleştirileceği sıra. |

### Method: rotate_transform(angle) {#rotate_transform_angle_7}


```
 rotate_transform(angle) 
```

Yerel geometrik dönüşümü belirtilen açıyla döndürür. Bu yöntem dönüşüme rotasyonu ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_8}


```
 rotate_transform(angle, order) 
```

Yerel geometrik dönüşümü belirtilen açıyla belirtilen sırada döndürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Dönüşüm matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_9}


```
 scale_transform(sx, sy) 
```

Yerel geometrik dönüşümü belirtilen faktörlerle ölçeklendirir. Bu yöntem dönüşüme ölçekleme matrisini ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseninde ölçekleneceği faktör. |
| sy | float | Dönüşümün y ekseninde ölçekleneceği faktör. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_10}


```
 scale_transform(sx, sy, order) 
```

Yerel geometrik dönüşümü belirtilen faktörlerle belirtilen sırada ölçeklendirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseninde ölçekleneceği faktör. |
| sy | float | Dönüşümün y ekseninde ölçekleneceği faktör. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ölçekleme matrisini ekleme ya da başına ekleme belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_11}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen çizgileri sonlandırmak için kullanılan kapak stilini belirleyen değerleri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen çizgilerin başlangıcında kullanılacak kap stilini temsil eden bir [LineCap](/imaging/python-net/aspose.imaging/linecap/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen çizgilerin sonunda kullanılacak kap stilini temsil eden bir [LineCap](/imaging/python-net/aspose.imaging/linecap/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | Bu [Pen](/imaging/python-net/aspose.imaging/pen/) ile çizilen kesikli çizgilerin başlangıç veya sonunda kullanılacak kap stilini temsil eden bir [LineCap](/imaging/python-net/aspose.imaging/linecap/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem dönüşüme çeviriyi ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x eksenindeki çevirmenin değeri. |
| dy | float | y eksenindeki çevirmenin değeri. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Yerel geometrik dönüşümü belirtilen boyutlarla belirtilen sırada çevirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x eksenindeki çevirmenin değeri. |
| dy | float | y eksenindeki çevirmenin değeri. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Çevirmenin uygulanacağı sıra (başına ekleme ya da ekleme). |

## **Examples**
### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# BmpOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# FileCreateSource sınıfının bir örneğini oluşturun ve BmpOptions örneği için Kaynak olarak atayın
# İkinci Boolean parametresi, oluşturulacak dosyanın Geçici olup olmadığını belirler
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Belirtilen Yolda bir Image örneği oluşturun
with Image.create(bmpOptions, 500, 500) as image:
	# Graphics bir örneği oluşturun ve Image nesnesiyle başlatın
	graphics = Graphics(image)
	# Graphics yüzeyini Beyaz Renk ile temizleyin
	graphics.clear(Color.white)
	#Renk Kırmızı ve genişlik 5 olan bir Pen örneği oluşturun
	pen = Pen(Color.red, 5.0);
	# HatchBrush bir örneği oluşturun ve özelliklerini ayarlayın
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Pen bir örneği oluşturun
	# HatchBrush nesnesi ve genişlikle başlatın
	brusedpen = Pen(brush, 5.0)
	# Pen nesnesini belirterek Dikdörtgenler çizin
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Pen nesnesini belirterek Dikdörtgenler çizin
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# Tüm değişiklikleri kaydedin.
	image.save()


```

