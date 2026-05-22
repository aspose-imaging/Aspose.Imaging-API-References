---
title: "Classe CustomLineCap"
type: docs
weight: 1350
url: /fr/python-net/aspose.imaging/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CustomLineCap

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Initialise une nouvelle instance de la classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) avec le contour et le remplissage spécifiés. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Initialise une nouvelle instance de la classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) à partir de l'énumération [LineCap](/imaging/python-net/aspose.imaging/linecap/) existante spécifiée, avec le contour et le remplissage spécifiés. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Initialise une nouvelle instance de la classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) à partir de l'énumération [LineCap](/imaging/python-net/aspose.imaging/linecap/) existante spécifiée, avec le contour, le remplissage et l'encoche spécifiés. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Obtient ou définit l'énumération [LineCap](/imaging/python-net/aspose.imaging/linecap/) sur laquelle cette [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) est basée. |
| base_inset | float | r/w | Obtient ou définit la distance entre le cap et la ligne. |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Obtient ou définit l'objet qui définit le remplissage du cap personnalisé. |
| stroke_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Obtient ou définit l'énumération [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) qui détermine comment les lignes qui composent cet objet [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) sont jointes. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Obtient ou définit l'objet qui définit le contour du cap personnalisé. |
| width_scale | float | r/w | Obtient ou définit la quantité par laquelle mettre à l'échelle cet objet de classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) par rapport à la largeur de l'objet. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Obtient les caps utilisés pour démarrer et terminer les lignes qui composent ce cap personnalisé. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Définit les caps utilisés pour démarrer et terminer les lignes qui composent ce cap personnalisé. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Initialise une nouvelle instance de la classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) avec le contour et le remplissage spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un objet [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) qui définit le remplissage du cap personnalisé. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un objet [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) qui définit le contour du cap personnalisé. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Initialise une nouvelle instance de la classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) à partir de l'énumération [LineCap](/imaging/python-net/aspose.imaging/linecap/) existante spécifiée, avec le contour et le remplissage spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un objet [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) qui définit le remplissage du cap personnalisé. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un objet [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) qui définit le contour du cap personnalisé. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Le cap de ligne à partir duquel créer le cap personnalisé. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Initialise une nouvelle instance de la classe [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) à partir de l'énumération [LineCap](/imaging/python-net/aspose.imaging/linecap/) existante spécifiée, avec le contour, le remplissage et l'encoche spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un objet [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) qui définit le remplissage du cap personnalisé. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un objet [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) qui définit le contour du cap personnalisé. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Le cap de ligne à partir duquel créer le cap personnalisé. |
| base_inset | float | La distance entre le cap et la ligne. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Obtient les caps utilisés pour démarrer et terminer les lignes qui composent ce cap personnalisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | L'énumération [LineCap](/imaging/python-net/aspose.imaging/linecap/) utilisée au début d'une ligne dans ce cap. |
| end_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | L'énumération [LineCap](/imaging/python-net/aspose.imaging/linecap/) utilisée à la fin d'une ligne dans ce cap. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Définit les caps utilisés pour démarrer et terminer les lignes qui composent ce cap personnalisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | L'énumération [LineCap](/imaging/python-net/aspose.imaging/linecap/) utilisée au début d'une ligne dans ce cap. |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | L'énumération [LineCap](/imaging/python-net/aspose.imaging/linecap/) utilisée à la fin d'une ligne dans ce cap. |

