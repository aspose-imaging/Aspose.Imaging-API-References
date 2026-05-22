---
title: "Classe IcoOptions"
type: docs
weight: 140
url: /fr/python-net/aspose.imaging.imageoptions/icooptions/
---

**Summary:** Create custom ICO image files for application icons effortlessly with our API,<br/>            empowering you to represent your software seamlessly. Our API supports PNG and<br/>            BMP image frames with various bits per pixel values, ensuring versatility and<br/>            compatibility for your icon creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.IcoOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [IcoOptions()](#IcoOptions__1) | Initialise une nouvelle instance de la classe [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) avec le format de trame ICO égal à Png et<br/>            bitsPerPixel égal à 32. |
| [IcoOptions(format, bits_per_pixel)](#IcoOptions_format_bits_per_pixel_2) | Initialise une nouvelle instance de la classe [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r/w | Obtient ou définit la valeur bits-per-pixel. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit les données Exif. |
| format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r/w | Obtient ou définit le format de trame ICO. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| keep_metadata | bool | r/w | Obtient une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Les options multipages |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtient ou définit les paramètres de résolution. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un clone membre à membre de cette instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: IcoOptions() {#IcoOptions__1}


```
 IcoOptions() 
```

Initialise une nouvelle instance de la classe [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) avec le format de trame ICO égal à Png et<br/>            bitsPerPixel égal à 32.

### Constructor: IcoOptions(format, bits_per_pixel) {#IcoOptions_format_bits_per_pixel_2}


```
 IcoOptions(format, bits_per_pixel) 
```

Initialise une nouvelle instance de la classe [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Le format de trame ICO.<br/>            Notez que l'image ICO ne prend en charge que les images [FileFormat.PNG](/imaging/python-net/aspose.imaging/fileformat/) et [FileFormat.BMP](/imaging/python-net/aspose.imaging/fileformat/) comme entrées. |
| bits_per_pixel | int | La valeur bits-per-pixel. |

### Method: clone() {#clone__1}


```
 clone() 
```

Crée un clone membre à membre de cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Un clone membre à membre de cette instance. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Les métadonnées. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai, si l'instance [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) prend en charge et/ou implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) ; sinon, faux. |


