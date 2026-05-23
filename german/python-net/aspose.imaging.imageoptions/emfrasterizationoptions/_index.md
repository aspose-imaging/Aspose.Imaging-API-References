---
title: "EmfRasterizationOptions Klasse"
type: docs
weight: 100
url: /de/python-net/aspose.imaging.imageoptions/emfrasterizationoptions/
---

**Summary:** The Emf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.EmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions__1) | Initialisiert eine neue Instanz der EmfRasterizationOptions Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Legt eine Hintergrundfarbe fest oder ruft sie ab. |
| border_x | float | r/w | Liest oder setzt den Rand X. |
| border_y | float | r/w | Liest oder setzt den Rand Y. |
| center_drawing | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Zeichnen zentriert ist. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt eine Vordergrundfarbe. |
| page_height | float | r/w | Liest oder setzt die Seitenhöhe.<br/>            Wenn der Wert 0 ist, wird das Seitenverhältnis des Quellbildes beibehalten. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Liest oder setzt die Seitengröße.<br/>            Wenn eine der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Dimensionen 0 ist, wird das Seitenverhältnis des Quellbildes beibehalten. |
| page_width | float | r/w | Liest oder setzt die Seitenbreite.<br/>            Wenn der Wert 0 ist, wird das Seitenverhältnis des Quellbildes beibehalten. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Liest oder setzt die Positionierung. |
| render_mode | [EmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.emf/emfrendermode/) | r/w | Liest oder setzt den Rendermodus. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Liest oder setzt den Glättungsmodus. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Liest oder setzt den Hinweis zur Textdarstellung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Erstellt ein neues Objekt, das eine flache Kopie der aktuellen Instanz ist. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Kopiert dies nach _vectorRasterizationOptions_. |


### Constructor: EmfRasterizationOptions() {#EmfRasterizationOptions__1}


```
 EmfRasterizationOptions() 
```

Initialisiert eine neue Instanz der EmfRasterizationOptions Klasse.

### Method: clone() {#clone__1}


```
 clone() 
```

Erstellt ein neues Objekt, das eine flache Kopie der aktuellen Instanz ist.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Object | Ein neues Objekt, das eine flache Kopie dieser Instanz ist. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Kopiert dies nach _vectorRasterizationOptions_.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | vectorRasterizationOptions |

