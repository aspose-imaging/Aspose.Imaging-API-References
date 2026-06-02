---
title: "PngOptions Classe"
type: docs
weight: 250
url: /it/python-net/aspose.imaging.imageoptions/pngoptions/
---

**Summary:** Create high-quality Portable Network Graphics (PNG) raster images effortlessly<br/>            with our API, offering customizable options for compression levels,<br/>            bits per pixel depths, and alpha bits. Seamlessly process XMP metadata containers,<br/>            ensuring comprehensive image metadata management, and empowering you to tailor<br/>            PNG images to your exact specifications with ease.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Inizializza una nuova istanza della classe [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/). |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Inizializza una nuova istanza della classe [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | Il livello di compressione predefinito. |
| bit_depth | System.Byte | r/w | Ottiene o imposta i valori di profondità di bit nell'intervallo 1, 2, 4, 8, 16.<br/>            <br/><br/>            Tenere presente i seguenti limiti:<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) supporta una profondità di bit di 1, 2, 4, 8.<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) supportano una profondità di bit di 8.<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) supportano una profondità di bit di 8, 16.<br/>            <br/> |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| [color_type](#color_type1) | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | Ottiene o imposta il tipo di colore. |
| [compression_level](#compression_level2) | int | r/w | Ottiene o imposta il livello di compressione del [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta i dati Exif. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | Ottiene o imposta il tipo di filtro utilizzato durante il processo di salvataggio del file png. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| keep_metadata | bool | r/w | Ottiene un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Le opzioni multipagina |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | Ottiene o imposta il livello di compressione del [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [progressive](#progressive3) | bool | r/w | Ottiene o imposta un valore che indica se un [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) è progressivo. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonazione membro per membro di questa istanza. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Inizializza una nuova istanza della classe [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/).

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Inizializza una nuova istanza della classe [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) | Le opzioni PNG. |

### Property: color_type {#color_type1}

Ottiene o imposta il tipo di colore.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: compression_level {#compression_level2}

Ottiene o imposta il livello di compressione del [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: progressive {#progressive3}

Ottiene o imposta un valore che indica se un [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) è progressivo.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Method: clone() {#clone__1}


```
 clone() 
```

Crea una clonazione membro per membro di questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Una clonazione membro per membro di questa istanza. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | I metadati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | True, se l'istanza [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) supporta e/o implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); altrimenti, false. |


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

#Crea un'istanza di flusso file
with open(r"C:\temp\output.png", "w+b") as stream:
	#Crea un'istanza di PngOptions e imposta le sue varie proprietà
	pngOptions = PngOptions()
	#Imposta la sorgente per PngOptions
	pngOptions.source = StreamSource(stream)
	#Crea un'istanza di Image 
	with Image.create(pngOptions, 500, 500) as image:
		#Crea e inizializza un'istanza della classe Graphics
		graphics = Graphics(image)
		#Cancella la superficie Graphics
		graphics.clear(Color.wheat);
		#Disegna un arco specificando l'oggetto Pen con colore Nero, 
		#un rettangolo che circonda l'arco, angolo di partenza e angolo di sweep
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Disegna un Bezier specificando l'oggetto Pen con colore Blu e i punti di coordinate.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Disegna una curva specificando l'oggetto Pen con colore Verde e un array di Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Disegna un'ellisse usando l'oggetto Pen e un Rectangle circostante
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Disegna una linea
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Disegna un segmento di torta
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Disegna un poligono specificando l'oggetto Pen con colore Rosso e un array di Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Disegna un Rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Crea un oggetto SolidBrush e imposta le sue varie proprietà
		brush = SolidBrush()
		brush.color = Color.purple
		#Disegna una String usando l'oggetto SolidBrush e Font, in un Point specifico
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# salva tutte le modifiche.
		image.save();

```

### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Carica un'immagine gif esistente come istanza della classe Image
with Image.load(path_join(directory, "sample.gif")) as image:
	# Esporta nel formato file BMP utilizzando le opzioni predefinite
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Esporta nel formato file JPEG utilizzando le opzioni predefinite
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Esporta nel formato file PNG utilizzando le opzioni predefinite
	image.save(path_join(directory, "output.png"), PngOptions())
	# Esporta nel formato file TIFF utilizzando le opzioni predefinite
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Carica immagine PNG        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Usa il tipo di colore indicizzato
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Usa compressione massima
	png_options.compression_level = 9
	# Ottieni la tavolozza di colori a 8 bit più vicina, coprendo il maggior numero possibile di pixel, in modo che un'immagine
	# con palette sia quasi indistinguibile visivamente da un'immagine senza palette.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# La dimensione del file di output dovrebbe essere notevolmente ridotta

```

