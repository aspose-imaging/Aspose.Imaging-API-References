---
title: "Classe GifOptions"
type: docs
weight: 120
url: /it/python-net/aspose.imaging.imageoptions/gifoptions/
---

**Summary:** The API for Graphical Interchange Format (GIF) raster image file creation offers<br/>            developers comprehensive options for generating GIF images with precise<br/>            control. With features to set background color, color palette, resolution,<br/>            interlaced type, transparent color, XMP metadata container, and image<br/>            compression, this API ensures flexibility and efficiency in creating optimized<br/>            and visually appealing GIFs tailored to specific application requirements.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.GifOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Inizializza una nuova istanza della classe [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Inizializza una nuova istanza della classe [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta il colore di sfondo. |
| background_color_index | System.Byte | r/w | Ottiene o imposta l'indice del colore di sfondo GIF. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| color_resolution | System.Byte | r/w | Ottiene o imposta la risoluzione colore GIF. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| do_palette_correction | bool | r/w | Ottiene o imposta un valore che indica se la correzione della palette è applicata. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta i dati Exif. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| has_trailer | bool | r/w | Ottiene o imposta un valore che indica se il GIF ha un trailer. |
| has_transparent_color | System.Nullable`1[[System.Boolean]] | r/w | Ottiene o imposta un valore che indica se un'immagine GIF ha un colore trasparente. <br/>            Se il valore restituito è **None**, questa proprietà è sovrascritta dal contesto dell'immagine di origine. |
| interlaced | bool | r/w | True se l'immagine deve essere interlacciata. |
| is_palette_sorted | bool | r/w | Ottiene o imposta un valore che indica se le voci della palette sono ordinate. |
| keep_metadata | bool | r/w | Ottiene un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |
| loops_count | int | r/w | Ottiene o imposta il conteggio dei cicli (Predefinito 1 ciclo) |
| max_diff | int | r/w | Ottiene o imposta la differenza massima consentita tra i pixel. Se maggiore di zero, verrà utilizzata la compressione con perdita.<br/>            Il valore consigliato per una compressione con perdita ottimale è 80. 30 corrisponde a una compressione molto leggera, 200 è pesante.<br/>            Funziona al meglio quando viene introdotta solo una piccola perdita, e a causa delle limitazioni dell'algoritmo di compressione livelli di perdita molto alti non forniscono tanto guadagno.<br/>            L'intervallo dei valori consentiti è [0, 1000]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Le opzioni multipagina |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. |
| pixel_aspect_ratio | System.Byte | r/w | Ottiene o imposta il rapporto di aspetto dei pixel GIF. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonazione membro per membro di questa istanza. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Inizializza una nuova istanza della classe [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Inizializza una nuova istanza della classe [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| gif_options | [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) | Le Opzioni GIF. |

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
### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Crea un'istanza di MemoryStream
with strm_ext.create_memory_stream() as stream:
	#Crea un'istanza di GifOptions e imposta le sue varie proprietà, inclusa la proprietà Source
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Crea un'istanza di Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Ottieni i pixel dell'immagine specificando l'area come confine dell'immagine
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Itera sull'Array e imposta il colore dei pixel indicizzati alternativi
			for index in range(pixel.length):
				if index % 2 == 0:
					#Imposta il colore del pixel indicizzato a giallo
					pixels[index] = yellow_color
				else:
					#Imposta il colore del pixel indicizzato a blu
					pixels[index] = blue_color

			#Applica le modifiche dei pixel all'immagine
			image.save_pixels(image.bounds, pixels)

			# salva tutte le modifiche.
			image.save()

	# Scrivi MemoryStream su File
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

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

