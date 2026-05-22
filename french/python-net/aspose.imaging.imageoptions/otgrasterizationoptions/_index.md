---
title: "OtgRasterizationOptions Classe"
type: docs
weight: 230
url: /fr/python-net/aspose.imaging.imageoptions/otgrasterizationoptions/
---

**Summary:** The Otg rasterization options

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.OtgRasterizationOptions

**Inheritance:** OdRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [OtgRasterizationOptions()](#OtgRasterizationOptions__1) | Initialise une nouvelle instance de la classe OtgRasterizationOptions |
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


### Constructor: OtgRasterizationOptions() {#OtgRasterizationOptions__1}


```
 OtgRasterizationOptions() 
```

Initialise une nouvelle instance de la classe OtgRasterizationOptions

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
### The following code snippet demonstrates how to convert an OTG image to PDF and other image formats. {#example_183}
``` python

from aspose.pycore import cast
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import PngOptions, PdfOptions, OtgRasterizationOptions

dir_: str = "c:\\3567\\"
input_file_path: str = dir_ + "VariousObjectsMultiPage.otg"
options = [PngOptions(), PdfOptions()]
for save_options in options:
	extension: str = ".png" if aspycore.is_assignable(save_options, PngOptions) else ".pdf"
	with Image.load(input_file_path) as image:
		otg_rasterization_options = OtgRasterizationOptions()
		otg_rasterization_options.page_size = cast(SizeF, image.size)
		save_options.vector_rasterization_options = otg_rasterization_options
		image.save(input_file_path + extension, save_options)


```

