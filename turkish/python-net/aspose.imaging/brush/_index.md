---
title: "Brush Sınıfı"
type: docs
weight: 340
url: /tr/python-net/aspose.imaging/brush/
---

**Summary:** The base brush class.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Brush

**Inheritance:** DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| [opacity](#opacity1) | float | r/w | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Mevcut [Brush](/imaging/python-net/aspose.imaging/brush/) nesnesinin yeni bir derin kopyasını oluşturur. |


### Property: opacity {#opacity1}

Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir.

**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Mevcut [Brush](/imaging/python-net/aspose.imaging/brush/) nesnesinin yeni bir derin kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Bu [Brush](/imaging/python-net/aspose.imaging/brush/) örneğinin derin kopyası olan yeni bir [Brush](/imaging/python-net/aspose.imaging/brush/). |


## **Examples**
### This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class {#example_12}
``` python

from aspose.imaging import Image, RotateFlipType, Graphics, Color, Pen, Rectangle, Point, Size,\
	Font, PointF
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from aspose.imaging.sources import StreamSource

from os.path import join as path_join

#Bir dosya akışı örneği oluşturur.
with open(r"C:\temp\output.png", "w+b") as stream:
	#PngOptions bir örnek oluştur ve çeşitli özelliklerini ayarla.
	pngOptions = PngOptions()
	#PngOptions için Kaynak ayarla.
	pngOptions.source = StreamSource(stream)
	#Image bir örnek oluştur.
	with Image.create(pngOptions, 500, 500) as image:
		#Graphics sınıfının bir örneğini oluştur ve başlat.
		graphics = Graphics(image)
		#Graphics yüzeyini temizle.
		graphics.clear(Color.wheat);
		#Siyah renkli Pen nesnesini belirterek bir Yay çizin, 
		#Yayı çevreleyen bir Rectangle, Başlangıç Açısı ve Tarama Açısı
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Mavi renkli Pen nesnesini ve koordinat noktalarını belirterek bir Bezier çizin.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Pen nesnesini Yeşil renkli olarak belirterek ve bir dizi Nokta ile bir Eğri çizin
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Pen nesnesini ve çevresindeki Rectangle kullanarak bir Elips çizin
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Bir Çizgi çizin
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Bir Pasta dilimi çizin
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Pen nesnesini Kırmızı renkli olarak belirterek ve bir dizi Nokta ile bir Çokgen çizin
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Bir Dikdörtgen çizin
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#SolidBrush nesnesi oluşturun ve çeşitli özelliklerini ayarlayın
		brush = SolidBrush()
		brush.color = Color.purple
		#SolidBrush nesnesi ve Font kullanarak, belirli bir Point'ta bir Dize çizin
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# Tüm değişiklikleri kaydedin.
		image.save();

```

