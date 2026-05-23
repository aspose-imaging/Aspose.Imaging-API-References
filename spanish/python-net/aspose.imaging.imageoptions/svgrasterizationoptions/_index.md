---
title: "SvgRasterizationOptions Clase"
type: docs
weight: 310
url: /es/python-net/aspose.imaging.imageoptions/svgrasterizationoptions/
---

**Summary:** The SVG rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.SvgRasterizationOptions

**Inheritance:** VectorRasterizationOptions

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions__1) | Inicializa una nueva instancia de la clase [SvgRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/svgrasterizationoptions/) . |
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
| scale_x | float | r/w | Obtiene o establece la escala x. |
| scale_y | float | r/w | Obtiene o establece la escala y. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Obtiene o establece el modo de suavizado. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Obtiene o establece la sugerencia de renderizado de texto. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Crea un nuevo objeto que es una copia superficial de la instancia actual. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copia esta instancia a _vectorRasterizationOptions_. |


### Constructor: SvgRasterizationOptions() {#SvgRasterizationOptions__1}


```
 SvgRasterizationOptions() 
```

Inicializa una nueva instancia de la clase [SvgRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/svgrasterizationoptions/) .

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

Copia esta instancia a _vectorRasterizationOptions_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | Las opciones de rasterización vectorial. |

