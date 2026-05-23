---
title: "CustomLineCap klass"
type: docs
weight: 1350
url: /sv/python-net/aspose.imaging/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CustomLineCap

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Initialiserar en ny instans av klassen [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) med den angivna konturen och fyllningen. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Initialiserar en ny instans av klassen [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) från den angivna befintliga [LineCap](/imaging/python-net/aspose.imaging/linecap/)-enumerationen med den angivna konturen och fyllningen. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Initialiserar en ny instans av klassen [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) från den angivna befintliga [LineCap](/imaging/python-net/aspose.imaging/linecap/)-enumerationen med den angivna konturen, fyllningen och inset. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Hämtar eller anger den [LineCap](/imaging/python-net/aspose.imaging/linecap/)-enumeration som detta [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) är baserat på. |
| base_inset | float | r/w | Hämtar eller anger avståndet mellan kappen och linjen. |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Hämtar eller anger objektet som definierar fyllningen för den anpassade toppen. |
| stroke_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Hämtar eller anger den [LineJoin](/imaging/python-net/aspose.imaging/linejoin/)-enumeration som bestämmer hur linjer som utgör detta [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/)-objekt sammanfogas. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Hämtar eller anger objektet som definierar konturen för den anpassade toppen. |
| width_scale | float | r/w | Hämtar eller anger mängden med vilken detta [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) klassobjekt skalas i förhållande till objektets bredd. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Hämtar de toppar som används för att starta och avsluta linjer som utgör denna anpassade topp. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Anger de toppar som används för att starta och avsluta linjer som utgör denna anpassade topp. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Initialiserar en ny instans av klassen [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) med den angivna konturen och fyllningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Ett [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)-objekt som definierar fyllningen för den anpassade toppen. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Ett [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)-objekt som definierar konturen för den anpassade toppen. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Initialiserar en ny instans av klassen [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) från den angivna befintliga [LineCap](/imaging/python-net/aspose.imaging/linecap/)-enumerationen med den angivna konturen och fyllningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Ett [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)-objekt som definierar fyllningen för den anpassade toppen. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Ett [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)-objekt som definierar konturen för den anpassade toppen. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Den linjetoppen som ska användas för att skapa den anpassade toppen. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Initialiserar en ny instans av klassen [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) från den angivna befintliga [LineCap](/imaging/python-net/aspose.imaging/linecap/)-enumerationen med den angivna konturen, fyllningen och inset.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Ett [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)-objekt som definierar fyllningen för den anpassade toppen. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Ett [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)-objekt som definierar konturen för den anpassade toppen. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Den linjetoppen som ska användas för att skapa den anpassade toppen. |
| base_inset | float | Avståndet mellan toppen och linjen. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Hämtar de toppar som används för att starta och avsluta linjer som utgör denna anpassade topp.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| start_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | Den [LineCap](/imaging/python-net/aspose.imaging/linecap/)-enumeration som används i början av en linje inom denna topp. |
| end_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | Den [LineCap](/imaging/python-net/aspose.imaging/linecap/)-enumeration som används i slutet av en linje inom denna topp. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Anger de toppar som används för att starta och avsluta linjer som utgör denna anpassade topp.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Den [LineCap](/imaging/python-net/aspose.imaging/linecap/)-enumeration som används i början av en linje inom denna topp. |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Den [LineCap](/imaging/python-net/aspose.imaging/linecap/)-enumeration som används i slutet av en linje inom denna topp. |

