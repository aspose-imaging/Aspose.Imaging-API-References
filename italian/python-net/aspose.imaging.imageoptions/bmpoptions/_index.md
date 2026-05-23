---
title: "Classe BmpOptions"
type: docs
weight: 30
url: /it/python-net/aspose.imaging.imageoptions/bmpoptions/
---

**Summary:** The API for BMP and DIB raster image format creation options provides developers<br/>            with a versatile toolset for generating custom Bitmap (BMP) and Device<br/>            Independent Bitmap (DIB) images. With this API, you can precisely define<br/>            image characteristics such as bits per pixel, compression level and compression<br/>            type, tailoring the output to meet specific requirements. This feature-rich<br/>            API empowers developers to create high-quality, customized raster images<br/>            with ease and flexibility for diverse applications.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BmpOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Inizializza una nuova istanza della classe [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/). |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Inizializza una nuova istanza della classe [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| [bits_per_pixel](#bits_per_pixel1) | int | r/w | Ottiene o imposta il conteggio dei bit per pixel dell'immagine. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| [compression](#compression2) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r/w | Ottiene o imposta il tipo di compressione. Il tipo di compressione predefinito è [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), che consente di salvare un [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) con trasparenza. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta i dati Exif. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| keep_metadata | bool | r/w | Ottiene un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Le opzioni multipagina |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonazione membro per membro di questa istanza. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Inizializza una nuova istanza della classe [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/).


**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Inizializza una nuova istanza della classe [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| bmp_options | [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) | Le opzioni BMP. |

### Property: bits_per_pixel {#bits_per_pixel1}

Ottiene o imposta il conteggio dei bit per pixel dell'immagine.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 3](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Property: compression {#compression2}

Ottiene o imposta il tipo di compressione. Il tipo di compressione predefinito è [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), che consente di salvare un [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) con trasparenza.

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...

**[Example # 3](#example_208)**: Decompress BMP image which was previously compressed using DXT1 compression a...

**[Example # 4](#example_225)**: The example shows how to export a BMP from a PNG file while keeping the alpha...

**[Example # 5](#example_226)**: The example shows how to export a BMP with the RGB compression type.


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
### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Crea un'istanza di `BmpOptions` e imposta le sue varie proprietà
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Crea un'istanza di `FileCreateSource` e assegnala come `source` per l'istanza di `BmpOptions`
	#Il secondo parametro `Boolean` determina se il file da creare è_temporal o meno
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Crea un'istanza di Image e inizializzala con l'istanza di BmpOptions chiamando il metodo Create
	with Image.create(bmp_options, 500, 500) as image:
		#esegui qualche elaborazione dell'immagine
		# salva tutte le modifiche
		image.save()


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

### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Crea un'immagine BMP 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# Il gradiente lineare dall'angolo in alto a sinistra a quello in basso a destra dell'immagine.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Riempie l'intera immagine con il pennello a gradiente lineare.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Ottieni la tavolozza di colori a 8 bit più vicina che copre il maggior numero possibile di pixel, in modo che un'immagine con palette
	# sia quasi indistinguibile visivamente da un BMP senza palette
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# La palette a 8 bit contiene al massimo 256 colori.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# L'output appare così:
# La dimensione dell'immagine con palette è 11078 byte.
# La dimensione dell'immagine senza palette è 40054 byte.

```

### The following example loads a BMP image and saves it back to BMP using various save options. {#example_91}
``` python
from aspose.imaging import Image, RasterImage, ColorPaletteHelper, ResolutionSetting
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
import os
import aspose.pycore as aspycore

directory = "c:\\temp\\"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	
	rasterImage = aspycore.as_of(image, RasterImage)

	# Crea BmpOptions
	saveOptions = BmpOptions()

	# Usa 8 bit per pixel per ridurre la dimensione dell'immagine di output.
	saveOptions.bits_per_pixel = 8

	# Imposta la tavolozza di colori a 8 bit più vicina che copre il numero massimo di pixel dell'immagine, in modo che un'immagine con palette
	# è quasi visivamente indistinguibile da una versione non palettizzata.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Salva senza compressione.
	# Puoi anche usare la compressione RLE-8 per ridurre le dimensioni dell'immagine di output.
	saveOptions.compression = BitmapCompression.RGB

	# Imposta la risoluzione orizzontale e verticale a 96 dpi.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

### The following example creates a palettized grayscale BMP image and then saves it to a file. {#example_92}
``` python

from os.path import join as path_join
from aspose.imaging import Image, ColorPaletteHelper, ResolutionSetting, Graphics, Point, Color
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.brushes import LinearGradientBrush

directory = "c:\\temp\\"
createOptions = BmpOptions()

# Salva su un file
createOptions.source = FileCreateSource(path_join(directory, "output.palette8bit.bmp"), False)
	
# Usa 8 bit per pixel per ridurre la dimensione dell'immagine di output.
createOptions.bits_per_pixel = 8

# Imposta la tavolozza di colore in scala di grigi a 8 bit standard che copre tutti i colori in scala di grigi.
# Se l'immagine elaborata contiene solo colori in scala di grigi, allora la sua versione palettizzata
# è visivamente indistinguibile da una versione non palettizzata.
createOptions.palette = ColorPaletteHelper.create_8_bit_grayscale(False)

# Salva senza compressione.
# Puoi anche usare la compressione RLE-8 per ridurre le dimensioni dell'immagine di output.
createOptions.compression = BitmapCompression.RGB

# Imposta la risoluzione orizzontale e verticale a 96 dpi.
createOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

# Crea un'immagine BMP di 100 x 100 px e salvala su un file.
with Image.create(createOptions, 100, 100) as image:
	graphics = Graphics(image)
	gradientBrush = LinearGradientBrush(Point(0, 0), Point(image.width, image.height), Color.black, Color.white)
	# Riempie l'immagine con una sfumatura in scala di grigi
	graphics.fill_rectangle(gradientBrush, image.bounds)
	image.save()


```

### Decompress BMP image which was previously compressed using DXT1 compression algorithm. {#example_208}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions

with Image.load("CompressedTiger.bmp") as image:
	image.save("DecompressedTiger.bmp", BmpOptions())


```

### The example shows how to export a BMP from a PNG file while keeping the alpha channel, save a BMP file with transparency. {#example_225}
``` python
from aspose.imaging import Image
from aspose.imaging.fileformats.png import BmpOptions

source_path = "input.png"
output_path_def = "result_def.bmp"
output_path_def_2 = "result_def-2.bmp"
output_path_bitfields = "result_bitfields.bmp"
# Carica un'immagine PNG da un file.
with Image.load(source_path) as pngImage:
	# L'immagine BMP viene salvata con supporto alla trasparenza per impostazione predefinita.
	# Se desideri specificare esplicitamente tale modalità, la proprietà `compression` di BmpOptions dovrebbe essere impostata su BitmapCompression.BITFIELDS.
	# Il metodo di compressione BitmapCompression.BITFIELDS è il metodo di compressione predefinito in BmpOptions.
	# Quindi lo stesso risultato dell'esportazione di un'immagine Bmp con trasparenza può essere ottenuto in uno dei seguenti modi.
	# Con opzioni predefinite implicite:
	pngImage.save(output_path_def)
	# Con opzioni predefinite esplicite:
	pngImage.save(output_path_def_2, BmpOptions())
	# Specificando il metodo di compressione BitmapCompression.BITFIELDS:
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.BITFIELDS
	pngImage.save(output_path_bitfields, bmp_options)


```

### The example shows how to export a BMP with the RGB compression type. {#example_226}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.imageoptions import BmpOptions

source_path = "input.png"
output_path = "output.png"
# Carica un'immagine PNG da un file.
with Image.load(source_path) as pngImage:
	# L'immagine BMP viene salvata con supporto alla trasparenza per impostazione predefinita, ciò è ottenuto utilizzando il metodo di compressione BitmapCompression.BITFIELDS.
	# Per salvare un'immagine BMP con il metodo di compressione RGB, è necessario specificare BmpOptions con la proprietà `compression` impostata su BitmapCompression.RGB.
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.RGB
	pngImage.save(output_path, bmp_options)


```

