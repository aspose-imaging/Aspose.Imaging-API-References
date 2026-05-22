---
title: "EmfRasterizationOptions Classe"
type: docs
weight: 100
url: /fr/python-net/aspose.imaging.imageoptions/emfrasterizationoptions/
---

**Summary:** The Emf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.EmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions__1) | Initialise une nouvelle instance de la classe EmfRasterizationOptions |
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
| render_mode | [EmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.emf/emfrendermode/) | r/w | Obtient ou définit le mode de rendu. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Obtient ou définit le mode d'anticrénelage. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Obtient ou définit l'indice de rendu du texte. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un nouvel objet qui est une copie superficielle de l'instance actuelle. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copie ceci dans _vectorRasterizationOptions_. |


### Constructor: EmfRasterizationOptions() {#EmfRasterizationOptions__1}


```
 EmfRasterizationOptions() 
```

Initialise une nouvelle instance de la classe EmfRasterizationOptions

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

