---
title: "EmfRasterizationOptions Classe"
type: docs
weight: 100
url: /it/python-net/aspose.imaging.imageoptions/emfrasterizationoptions/
---

**Summary:** The Emf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.EmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions__1) | Inizializza una nuova istanza della classe EmfRasterizationOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta un colore di sfondo. |
| border_x | float | r/w | Ottiene o imposta il bordo X. |
| border_y | float | r/w | Ottiene o imposta il bordo Y. |
| center_drawing | bool | r/w | Ottiene o imposta un valore che indica se il disegno è centrato. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta un colore di primo piano. |
| page_height | float | r/w | Ottiene o imposta l'altezza della pagina.<br/>            Se il valore è 0, il rapporto d'aspetto dell'immagine di origine verrà mantenuto. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Ottiene o imposta la dimensione della pagina.<br/>            Se una delle dimensioni di [SizeF](/imaging/python-net/aspose.imaging/sizef/) è 0, il rapporto d'aspetto dell'immagine di origine verrà mantenuto. |
| page_width | float | r/w | Ottiene o imposta la larghezza della pagina.<br/>            Se il valore è 0, il rapporto d'aspetto dell'immagine di origine verrà mantenuto. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Ottiene o imposta il posizionamento. |
| render_mode | [EmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.emf/emfrendermode/) | r/w | Ottiene o imposta la modalità di rendering. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Ottiene o imposta la modalità di smussatura. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Ottiene o imposta il suggerimento di rendering del testo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea un nuovo oggetto che è una copia superficiale dell'istanza corrente. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copia questo in _vectorRasterizationOptions_. |


### Constructor: EmfRasterizationOptions() {#EmfRasterizationOptions__1}


```
 EmfRasterizationOptions() 
```

Inizializza una nuova istanza della classe EmfRasterizationOptions

### Method: clone() {#clone__1}


```
 clone() 
```

Crea un nuovo oggetto che è una copia superficiale dell'istanza corrente.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Object | Un nuovo oggetto che è una copia superficiale di questa istanza. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copia questo in _vectorRasterizationOptions_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | vectorRasterizationOptions |

