---
title: "Storleksklass"
type: docs
weight: 7280
url: /sv/python-net/aspose.imaging/size/
---

**Summary:** Represents size.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Size

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Size()](#Size__1) | Initierar en ny instans av Size-klassen |
| [Size(point)](#Size_point_2) | Initierar en ny instans av strukturen [Size](/imaging/python-net/aspose.imaging/size/) från den angivna [Point](/imaging/python-net/aspose.imaging/point/). |
| [Size(width, height)](#Size_width_height_3) | Initierar en ny instans av strukturen [Size](/imaging/python-net/aspose.imaging/size/) från de angivna dimensionerna. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Size](/imaging/python-net/aspose.imaging/size/) | r | Hämtar en ny instans av strukturen [Size](/imaging/python-net/aspose.imaging/size/) som har värdena [Size.width](/imaging/python-net/aspose.imaging/size/) och [Size.height](/imaging/python-net/aspose.imaging/size/) satta till noll. |
| height | int | r/w | Hämtar eller anger den vertikala komponenten i detta [Size](/imaging/python-net/aspose.imaging/size/). |
| is_empty | bool | r | Hämtar ett värde som indikerar om detta [Size](/imaging/python-net/aspose.imaging/size/) har bredd och höjd på 0. |
| width | int | r/w | Hämtar eller anger den horisontella komponenten i detta [Size](/imaging/python-net/aspose.imaging/size/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Lägger till bredden och höjden av en [Size](/imaging/python-net/aspose.imaging/size/) struktur till bredden och höjden av en annan [Size](/imaging/python-net/aspose.imaging/size/) struktur. |
| [ceiling(size)](#ceiling_size_2) | Konverterar den angivna [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen till en [Size](/imaging/python-net/aspose.imaging/size/) struktur genom att avrunda värdena i [Size](/imaging/python-net/aspose.imaging/size/) strukturen till nästa högre heltalsvärden. |
| [round(size)](#round_size_3) | Konverterar den angivna [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen till en [Size](/imaging/python-net/aspose.imaging/size/) struktur genom att avrunda värdena i [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen till närmaste heltalsvärden. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Subtraherar bredden och höjden av en [Size](/imaging/python-net/aspose.imaging/size/) struktur från bredden och höjden av en annan [Size](/imaging/python-net/aspose.imaging/size/) struktur. |
| [truncate(size)](#truncate_size_5) | Konverterar den angivna [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen till en [Size](/imaging/python-net/aspose.imaging/size/) struktur genom att trunkera värdena i [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen till nästa lägre heltalsvärden. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Initierar en ny instans av Size-klassen

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Initierar en ny instans av strukturen [Size](/imaging/python-net/aspose.imaging/size/) från den angivna [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) som ska användas för att initiera detta [Size](/imaging/python-net/aspose.imaging/size/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Initierar en ny instans av strukturen [Size](/imaging/python-net/aspose.imaging/size/) från de angivna dimensionerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Breddkomponenten i den nya [Size](/imaging/python-net/aspose.imaging/size/). |
| height | int | Höjdkomponenten i den nya [Size](/imaging/python-net/aspose.imaging/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Lägger till bredden och höjden av en [Size](/imaging/python-net/aspose.imaging/size/) struktur till bredden och höjden av en annan [Size](/imaging/python-net/aspose.imaging/size/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | Den första [Size](/imaging/python-net/aspose.imaging/size/) att lägga till. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | Den andra [Size](/imaging/python-net/aspose.imaging/size/) att lägga till. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | En [Size](/imaging/python-net/aspose.imaging/size/) struktur som är resultatet av additionsoperationen. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Konverterar den angivna [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen till en [Size](/imaging/python-net/aspose.imaging/size/) struktur genom att avrunda värdena i [Size](/imaging/python-net/aspose.imaging/size/) strukturen till nästa högre heltalsvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | [Size](/imaging/python-net/aspose.imaging/size/) strukturen som den här metoden konverterar till. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Konverterar den angivna [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen till en [Size](/imaging/python-net/aspose.imaging/size/) struktur genom att avrunda värdena i [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen till närmaste heltalsvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | [Size](/imaging/python-net/aspose.imaging/size/) strukturen som den här metoden konverterar till. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Subtraherar bredden och höjden av en [Size](/imaging/python-net/aspose.imaging/size/) struktur från bredden och höjden av en annan [Size](/imaging/python-net/aspose.imaging/size/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | Strukturen [Size](/imaging/python-net/aspose.imaging/size/) på vänster sida av subtraktionsoperatorn. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | Strukturen [Size](/imaging/python-net/aspose.imaging/size/) på högra sidan av subtraktionsoperatorn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Den [Size](/imaging/python-net/aspose.imaging/size/) som är resultatet av subtraktionsoperationen. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Konverterar den angivna [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen till en [Size](/imaging/python-net/aspose.imaging/size/) struktur genom att trunkera värdena i [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen till nästa lägre heltalsvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | [Size](/imaging/python-net/aspose.imaging/size/) strukturen som den här metoden konverterar till. |


