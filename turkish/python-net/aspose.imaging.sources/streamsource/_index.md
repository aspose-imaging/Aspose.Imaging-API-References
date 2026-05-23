---
title: "StreamSource Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.imaging.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.StreamSource

**Inheritance:** Source

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [StreamSource()](#StreamSource__1) | Yeni bir [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) sınıfı örneği başlatır. |
| [StreamSource(stream)](#StreamSource_stream_2) | Yeni bir [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) sınıfı örneği başlatır. |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_3) | Yeni bir [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Konteyner atıldığında akışın da atılıp atılmayacağını gösteren bir değer alır. |
| akış | _io.BufferedRandom | r | Akışı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Akış kapsayıcısını alır. |


### Constructor: StreamSource() {#StreamSource__1}


```
 StreamSource() 
```

Yeni bir [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) sınıfı örneği başlatır.

### Constructor: StreamSource(stream) {#StreamSource_stream_2}


```
 StreamSource(stream) 
```

Yeni bir [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Açılacak akış. |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...


### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_3}


```
 StreamSource(stream, dispose_stream) 
```

Yeni bir [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Açılacak akış. |
| dispose_stream | bool | eğer <c>true</c> olarak ayarlanırsa akış atılacaktır. |


**See also:**

**[Example # 1](#example_5)**: This example demonstrates the use of file stream to Create a new Image file (...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Akış kapsayıcısını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | akış kapsayıcısı. |


## **Examples**
### This example demonstrates the use of file stream to Create a new Image file (a JPEG type) {#example_5}
``` python

from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.sources import StreamSource

# JpegOptions sınıfının bir örneğini oluşturur ve çeşitli özelliklerini ayarlar
with JpegOptions() as jpegOptions:
	# Bir akış örneği oluştur
	with open(r"C:\temp\sample.jpeg", "w+b") as stream:
		#JpegOptions örneği için source özelliğini tanımla
		#İkinci boolean parametre, Stream'in kapsam dışına çıktığında atılıp atılmayacağını belirler
		jpegOptions.source = StreamSource(stream, True)
		#Image sınıfının bir örneğini oluşturur ve Image nesnesini başlatmak için JpegOptions parametresiyle Create metodunu çağırır
		with Image.create(jpegOptions, 500, 500) as image:
			#bazı görüntü işleme yap
			pass

```

### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# MemoryStream'in bir örneğini oluşturun
with strm_ext.create_memory_stream() as stream:
	#GifOptions bir örneği oluşturun ve Source özelliği dahil çeşitli özelliklerini ayarlayın
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Image sınıfının bir örneğini oluşturun
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Görüntünün pikselini, alanı görüntü sınırı olarak belirterek alın
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Diziyi döngüye al ve alternatif indeksli pikselin rengini ayarla
			for index in range(pixel.length):
				if index % 2 == 0:
					#İndeksli piksel rengini sarıya ayarla
					pixels[index] = yellow_color
				else:
					#İndeksli piksel rengini maviye ayarla
					pixels[index] = blue_color

			#Piksel değişikliklerini görüntüye uygula
			image.save_pixels(image.bounds, pixels)

			# Tüm değişiklikleri kaydedin.
			image.save()

	# MemoryStream'i dosyaya yaz
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

```

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

