---
title: "Classe WmfRasterizationOptions"
type: docs
weight: 380
url: /fr/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/
---

**Summary:** The Wmf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions__1) | Initialise une nouvelle instance de la classe [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/) |
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
| [render_mode](#render_mode1) | [WmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfrendermode/) | r/w | Obtient ou définit le mode de rendu WMF |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Obtient ou définit le mode d'anticrénelage. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Obtient ou définit l'indice de rendu du texte. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un nouvel objet qui est une copie superficielle de l'instance actuelle. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copie ceci dans _vectorRasterizationOptions_. |


### Constructor: WmfRasterizationOptions() {#WmfRasterizationOptions__1}


```
 WmfRasterizationOptions() 
```

Initialise une nouvelle instance de la classe [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/)

### Property: render_mode {#render_mode1}

Obtient ou définit le mode de rendu WMF

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


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

Copie ceci dans _vectorRasterizationOptions_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | vectorRasterizationOptions |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger tous les types d'images, y compris WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Le texte sera converti en formes.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# La couleur d'arrière-plan de la surface de dessin.
	rasterizationOptions.background_color = Color.white_smoke
	# La taille de la page.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Si un emf intégré existe, alors rendre l'emf ; sinon rendre le wmf.
	rasterizationOptions.render_mode = WmfRenderMode.AUTO
	saveOptions.vector_rasterization_options = rasterizationOptions
	wmfImage.save("test.output.svg", saveOptions)


```

