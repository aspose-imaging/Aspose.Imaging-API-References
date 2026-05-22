---
title: "OdgRasterizationOptions Classe"
type: docs
weight: 220
url: /fr/python-net/aspose.imaging.imageoptions/odgrasterizationoptions/
---

**Summary:** The Odg rasterization options

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.OdgRasterizationOptions

**Inheritance:** OdRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [OdgRasterizationOptions()](#OdgRasterizationOptions__1) | Initialise une nouvelle instance de la classe OdgRasterizationOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit une couleur d'arrière-plan. |
| border_x | float | r/w | Obtient ou définit la bordure X. |
| border_y | float | r/w | Obtient ou définit la bordure Y. |
| center_drawing | bool | r/w | Obtient ou définit une valeur indiquant si le dessin est centré. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit une couleur de premier plan. |
| page_height | float | r/w | Obtient ou définit la hauteur de la page.<br/>            Si la valeur est 0, le rapport d'aspect de l'image source sera conservé. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Obtient ou définit la taille de la page.<br/>            Si l'une des dimensions de [SizeF](/imaging/python-net/aspose.imaging/sizef/) est 0, le rapport d'aspect de l'image source sera conservé. |
| page_width | float | r/w | Obtient ou définit la largeur de la page.<br/>            Si la valeur est 0, le rapport d'aspect de l'image source sera conservé. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Obtient ou définit le positionnement. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Obtient ou définit le mode d'anticrénelage. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Obtient ou définit l'indice de rendu du texte. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un nouvel objet qui est une copie superficielle de l'instance actuelle. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copie vers. |


### Constructor: OdgRasterizationOptions() {#OdgRasterizationOptions__1}


```
 OdgRasterizationOptions() 
```

Initialise une nouvelle instance de la classe OdgRasterizationOptions

### Method: clone() {#clone__1}


```
 clone() 
```

Crée un nouvel objet qui est une copie superficielle de l'instance actuelle.

**Returns**

| Type | Description |
| :- | :- |
| System.Object | Un nouvel objet qui est une copie superficielle de cette instance. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copie vers.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | Les options de rastérisation vectorielle. |

## **Examples**
### The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format. {#example_189}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import OdgRasterizationOptions, PdfOptions

dir_: str = "c:\\aspose.imaging\\issues\\net\\3635"
input_file_name: str = join(dir_, "VariousObjectsMultiPage.fodg")
output_file_name: str = input_file_name + ".pdf"
with Image.load(input_file_name) as image:
	rasterization_options = OdgRasterizationOptions()
	rasterization_options.background_color = Color.white
	rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	save_options = PdfOptions()
	save_options.vector_rasterization_options = rasterization_options
	image.save(output_file_name, save_options)


```

