---
title: "Classe ImageOptionsBase"
type: docs
weight: 5760
url: /it/python-net/aspose.imaging/imageoptionsbase/
---

**Summary:** The image base options.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageOptionsBase

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| [buffer_size_hint](#buffer_size_hint1) | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta i dati Exif. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| keep_metadata | bool | r/w | Ottiene un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Le opzioni multipagina |
| [palette](#palette2) | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. |
| [resolution_settings](#resolution_settings3) | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonazione membro per membro di questa istanza. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Property: buffer_size_hint {#buffer_size_hint1}

Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni.

**See also:**

**[Example # 1](#example_180)**: The following example shows how to set a memory limit when creating a new JPE...


### Property: palette {#palette2}

Ottiene o imposta la tavolozza dei colori.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...

**[Example # 3](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Property: resolution_settings {#resolution_settings3}

Ottiene o imposta le impostazioni di risoluzione.

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


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

### The following example shows how to set a memory limit when creating a new JPEG image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers. {#example_180}
``` python
from os.path import join
from aspose.imaging import Image
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.fileformats.jpeg import JpegCompressionMode

dir_: str = "c:\\aspose.imaging\\issues\\net\\3404\\"
# Impostazione di un limite di memoria di 50 megabyte per l'immagine creata di destinazione
create_options = JpegOptions()
create_options.compression_type = JpegCompressionMode.PROGRESSIVE
create_options.buffer_size_hint = 50
create_options.source = FileCreateSource(join(dir_, "createdFile.jpg"), False)
with Aspose.Imaging.Image.create(create_options, 1000, 1000) as image:
	# salva nella stessa posizione
	image.save()


```

