---
title: "Clase CmxRasterizationOptions"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.imageoptions/cmxrasterizationoptions/
---

**Summary:** the CMX exporter options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.CmxRasterizationOptions

**Inheritance:** VectorRasterizationOptions

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [CmxRasterizationOptions()](#CmxRasterizationOptions__1) | Inicializa una nueva instancia de la clase [CmxRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/cmxrasterizationoptions/). |
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
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtiene o establece la configuración de resolución. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Obtiene o establece el modo de suavizado. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Obtiene o establece la sugerencia de renderizado de texto. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Crea un nuevo objeto que es una copia superficial de la instancia actual. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copia a. |


### Constructor: CmxRasterizationOptions() {#CmxRasterizationOptions__1}


```
 CmxRasterizationOptions() 
```

Inicializa una nueva instancia de la clase [CmxRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/cmxrasterizationoptions/).

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

Copia a.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | Las opciones de rasterización vectorial. |

