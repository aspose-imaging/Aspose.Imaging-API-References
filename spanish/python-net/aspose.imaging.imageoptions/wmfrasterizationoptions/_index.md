---
title: "Clase WmfRasterizationOptions"
type: docs
weight: 380
url: /es/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/
---

**Summary:** The Wmf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions__1) | Inicializa una nueva instancia de la clase [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/) |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece un color de fondo. |
| border_x | float | r/w | Obtiene o establece el border X. |
| border_y | float | r/w | Obtiene o establece el border Y. |
| center_drawing | bool | r/w | Obtiene o establece un valor que indica si center drawing. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece un color de primer plano. |
| page_height | float | r/w | Obtiene o establece la altura de la página.<br/>            Si el valor es 0, se preservará la relación de aspecto de la imagen de origen. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Obtiene o establece el tamaño de la página.<br/>            Si una de las dimensiones de [SizeF](/imaging/python-net/aspose.imaging/sizef/) es 0, se preservará la relación de aspecto de la imagen de origen. |
| page_width | float | r/w | Obtiene o establece el ancho de la página.<br/>            Si el valor es 0, se preservará la relación de aspecto de la imagen de origen. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Obtiene o establece la posición. |
| [render_mode](#render_mode1) | [WmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfrendermode/) | r/w | Obtiene o establece el modo de renderizado WMF |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Obtiene o establece el modo de suavizado. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Obtiene o establece la sugerencia de renderizado de texto. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Crea un nuevo objeto que es una copia superficial de la instancia actual. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copia esto a _vectorRasterizationOptions_. |


### Constructor: WmfRasterizationOptions() {#WmfRasterizationOptions__1}


```
 WmfRasterizationOptions() 
```

Inicializa una nueva instancia de la clase [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/)

### Property: render_mode {#render_mode1}

Obtiene o establece el modo de renderizado WMF

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Method: clone() {#clone__1}


```
 clone() 
```

Crea un nuevo objeto que es una copia superficial de la instancia actual.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Object | Un nuevo objeto que es una copia superficial de esta instancia. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copia esto a _vectorRasterizationOptions_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | vectorRasterizationOptions |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Usar Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# El texto se convertirá en formas.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# El color de fondo de la superficie de dibujo.
	rasterizationOptions.background_color = Color.white_smoke
	# El tamaño de página.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Si existe un emf incrustado, renderiza emf; de lo contrario renderiza wmf.
	rasterizationOptions.render_mode = WmfRenderMode.AUTO
	saveOptions.vector_rasterization_options = rasterizationOptions
	wmfImage.save("test.output.svg", saveOptions)


```

