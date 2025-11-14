---
title: StreamSource Class
type: docs
weight: 40
url: /python-net/aspose.imaging.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.StreamSource

**Inheritance:** Source

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StreamSource()](#StreamSource__1) | Initializes a new instance of the [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) class. |
| [StreamSource(stream)](#StreamSource_stream_2) | Initializes a new instance of the [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) class. |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_3) | Initializes a new instance of the [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Gets a value indicating whether stream should be disposed whenever container gets disposed. |
| stream | _io.BufferedRandom | r | Gets the stream. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Gets the stream container. |


### Constructor: StreamSource() {#StreamSource__1}


```
 StreamSource() 
```

Initializes a new instance of the [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) class.

### Constructor: StreamSource(stream) {#StreamSource_stream_2}


```
 StreamSource(stream) 
```

Initializes a new instance of the [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to open. |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...


### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_3}


```
 StreamSource(stream, dispose_stream) 
```

Initializes a new instance of the [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to open. |
| dispose_stream | bool | if set to <c>true</c> the stream will be disposed. |


**See also:**

**[Example # 1](#example_5)**: This example demonstrates the use of file stream to Create a new Image file (...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Gets the stream container.

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | the stream container. |


## **Examples**
### This example demonstrates the use of file stream to Create a new Image file (a JPEG type) {#example_5}
``` python

from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.sources import StreamSource

# Creates an instance of JpegOptions and set its various properties
with JpegOptions() as jpegOptions:
	# Create an instance of stream
	with open(r"C:\temp\sample.jpeg", "w+b") as stream:
		#Define the source property for the instance of JpegOptions
		#Second boolean parameter determines if the Stream is disposed once get out of scope
		jpegOptions.source = StreamSource(stream, True)
		#Creates an instance of Image and call Create method with JpegOptions as parameter to initialize the Image object   
		with Image.create(jpegOptions, 500, 500) as image:
			#do some image processing
			pass

```

### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Create an instance of MemoryStream
with strm_ext.create_memory_stream() as stream:
	#Create an instance of GifOptions and set its various properties including the Source property
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Create an instance of Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Get the pixels of image by specifying the area as image boundary
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Loop over the Array and sets color of alternative indexed pixel
			for index in range(pixel.length):
				if index % 2 == 0:
					#Set the indexed pixel color to yellow
					pixels[index] = yellow_color
				else:
					#Set the indexed pixel color to blue
					pixels[index] = blue_color

			#Apply the pixel changes to the image
			image.save_pixels(image.bounds, pixels)

			# save all changes.
			image.save()

	# Write MemoryStream to File
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

#Creates an instance of file stream
with open(r"C:\temp\output.png", "w+b") as stream:
	#Create an instance of PngOptions and set its various properties
	pngOptions = PngOptions()
	#Set the Source for PngOptions
	pngOptions.source = StreamSource(stream)
	#Create an instance of Image 
	with Image.create(pngOptions, 500, 500) as image:
		#Create and initialize an instance of Graphics class
		graphics = Graphics(image)
		#Clear Graphics surface
		graphics.clear(Color.wheat);
		#Draw an Arc by specifying the Pen object having Black color, 
		#a Rectangle surrounding the Arc, Start Angle and Sweep Angle
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Draw a Bezier by specifying the Pen object having Blue color and co-ordinate Points.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Draw a Curve by specifying the Pen object having Green color and an array of Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Draw an Ellipse using the Pen object and a surrounding Rectangle
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Draw a Line 
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Draw a Pie segment
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Draw a Polygon by specifying the Pen object having Red color and an array of Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Draw a Rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Create a SolidBrush object and set its various properties
		brush = SolidBrush()
		brush.color = Color.purple
		#Draw a String using the SolidBrush object and Font, at specific Point
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# save all changes.
		image.save();

```

