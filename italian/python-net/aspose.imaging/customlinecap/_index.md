---
title: "Classe CustomLineCap"
type: docs
weight: 1350
url: /it/python-net/aspose.imaging/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CustomLineCap

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Inizializza una nuova istanza della classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) con il contorno e il riempimento specificati. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Inizializza una nuova istanza della classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) a partire dall'enumerazione [LineCap](/imaging/python-net/aspose.imaging/linecap/) esistente specificata, con il contorno e il riempimento specificati. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Inizializza una nuova istanza della classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) a partire dall'enumerazione [LineCap](/imaging/python-net/aspose.imaging/linecap/) esistente specificata, con il contorno, il riempimento e l'inserimento specificati. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Ottiene o imposta l'enumerazione [LineCap](/imaging/python-net/aspose.imaging/linecap/) su cui si basa questo [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/). |
| base_inset | float | r/w | Ottiene o imposta la distanza tra il cap e la linea. |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Ottiene o imposta l'oggetto che definisce il riempimento per il cap personalizzato. |
| stroke_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Ottiene o imposta l'enumerazione [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) che determina come le linee che compongono questo oggetto [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) sono unite. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Ottiene o imposta l'oggetto che definisce il contorno del cap personalizzato. |
| width_scale | float | r/w | Ottiene o imposta la quantità di scala di questo oggetto classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) rispetto alla larghezza dell'oggetto. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Ottiene i cap utilizzati per avviare e terminare le linee che compongono questo cap personalizzato. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Imposta i cap utilizzati per avviare e terminare le linee che compongono questo cap personalizzato. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Inizializza una nuova istanza della classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) con il contorno e il riempimento specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un oggetto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) che definisce il riempimento per il cap personalizzato. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un oggetto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) che definisce il contorno del cap personalizzato. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Inizializza una nuova istanza della classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) a partire dall'enumerazione [LineCap](/imaging/python-net/aspose.imaging/linecap/) esistente specificata, con il contorno e il riempimento specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un oggetto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) che definisce il riempimento per il cap personalizzato. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un oggetto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) che definisce il contorno del cap personalizzato. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Il cap di linea da cui creare il cap personalizzato. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Inizializza una nuova istanza della classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) a partire dall'enumerazione [LineCap](/imaging/python-net/aspose.imaging/linecap/) esistente specificata, con il contorno, il riempimento e l'inserimento specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un oggetto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) che definisce il riempimento per il cap personalizzato. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un oggetto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) che definisce il contorno del cap personalizzato. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Il cap di linea da cui creare il cap personalizzato. |
| base_inset | float | La distanza tra il cap e la linea. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Ottiene i cap utilizzati per avviare e terminare le linee che compongono questo cap personalizzato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| start_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | L'enumerazione [LineCap](/imaging/python-net/aspose.imaging/linecap/) utilizzata all'inizio di una linea all'interno di questo cap. |
| end_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | L'enumerazione [LineCap](/imaging/python-net/aspose.imaging/linecap/) utilizzata alla fine di una linea all'interno di questo cap. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Imposta i cap utilizzati per avviare e terminare le linee che compongono questo cap personalizzato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | L'enumerazione [LineCap](/imaging/python-net/aspose.imaging/linecap/) utilizzata all'inizio di una linea all'interno di questo cap. |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | L'enumerazione [LineCap](/imaging/python-net/aspose.imaging/linecap/) utilizzata alla fine di una linea all'interno di questo cap. |

