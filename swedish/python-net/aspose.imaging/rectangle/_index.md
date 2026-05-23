---
title: "Rectangle-klass"
type: docs
weight: 7120
url: /sv/python-net/aspose.imaging/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Rectangle

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Initierar en ny instans av Rectangle-klassen |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Initierar en ny instans av [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen med den angivna platsen och storleken. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Initierar en ny instans av [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen med den angivna platsen och storleken. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | int | r/w | Hämtar eller anger y-koordinaten som är summan av [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/) och [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) egenskapsvärdena för denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| empty [static] | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Hämtar en ny instans av [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen som har [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) och [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) värden satta till noll. |
| height | int | r/w | Hämtar eller anger höjden på denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| is_empty | bool | r | Hämtar ett värde som indikerar om alla numeriska egenskaper för denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) har värden på noll. |
| left | int | r/w | Hämtar eller anger x‑koordinaten för den vänstra kanten av denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| right | int | r/w | Hämtar eller anger x‑koordinaten som är summan av egenskapsvärdena [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/) och [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) för denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Hämtar eller anger storleken på denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| top | int | r/w | Hämtar eller anger y‑koordinaten för den övre kanten av denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| width | int | r/w | Hämtar eller anger bredden på denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| x | int | r/w | Hämtar eller anger x‑koordinaten för det övre vänstra hörnet av denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| y | int | r/w | Hämtar eller anger y‑koordinaten för det övre vänstra hörnet av denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Konverterar den angivna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen till en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur genom att avrunda [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)-värdena till nästa högre heltal. |
| [contains(point)](#contains_point_2) | Avgör om den angivna punkten finns inom denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| [contains(rect)](#contains_rect_3) | Avgör om det rektangulära området som representeras av _rect_ är helt innehållet i denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| [contains(x, y)](#contains_x_y_4) | Avgör om den angivna punkten finns inom denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| [contains_point(point)](#contains_point_point_5) | Avgör om den angivna punkten finns inom denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| [contains_rect(rect)](#contains_rect_rect_6) | Avgör om det rektangulära området som representeras av _rect_ är helt innehållet i denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_7) | Skapar en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur med de angivna kantpositionerna. |
| [from_points(point1, point2)](#from_points_point1_point2_8) | Skapar en ny [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) från två angivna punkter. De två vertikala kanterna på den skapade [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) kommer att vara lika med de angivna _point1_ och _point2_. Dessa är vanligtvis de motsatta hörnen. |
| [inflate(rect, x, y)](#inflate_rect_x_y_9) | Skapar och returnerar en uppblåst kopia av den angivna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen. Kopian uppblåses med det angivna beloppet. Den ursprungliga [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen förblir oförändrad. |
| [inflate(size)](#inflate_size_10) | Uppblåser denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) med det angivna beloppet. |
| [inflate(width, height)](#inflate_width_height_11) | Uppblåser denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) med det angivna beloppet. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_12) | Skapar och returnerar en uppblåst kopia av den angivna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen. Kopian uppblåses med det angivna beloppet. Den ursprungliga [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen förblir oförändrad. |
| [intersect(a, b)](#intersect_a_b_13) | Returnerar en tredje [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar skärningspunkten mellan två andra [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer. Om det inte finns någon skärning returneras en tom [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [intersect(rect)](#intersect_rect_14) | Ersätter denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) med skärningspunkten mellan den själv och den angivna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [intersect_rects(a, b)](#intersect_rects_a_b_15) | Returnerar en tredje [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar skärningspunkten mellan två andra [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer. Om det inte finns någon skärning returneras en tom [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [intersects_with(rect)](#intersects_with_rect_16) | Avgör om denna rektangel skär med _rect_. |
| normalize() | Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten. |
| [offset(pos)](#offset_pos_17) | Justera placeringen av denna rektangel med det angivna värdet. |
| [offset(x, y)](#offset_x_y_18) | Justera placeringen av denna rektangel med det angivna värdet. |
| [round(value)](#round_value_19) | Konverterar den angivna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) till en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) genom att avrunda [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)-värdena till närmaste heltal. |
| [truncate(value)](#truncate_value_20) | Konverterar den angivna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) till en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) genom att trunkera [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)-värdena. |
| [union(a, b)](#union_a_b_21) | Hämtar en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som innehåller föreningen av två [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer. |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Initierar en ny instans av Rectangle-klassen

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Initierar en ny instans av [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen med den angivna platsen och storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | En [Point](/imaging/python-net/aspose.imaging/point/) som representerar det övre vänstra hörnet av det rektangulära området. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | En [Size](/imaging/python-net/aspose.imaging/size/) som representerar bredden och höjden på det rektangulära området. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Initierar en ny instans av [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen med den angivna platsen och storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | x-koordinaten för det övre vänstra hörnet av rektangeln. |
| y | int | y-koordinaten för det övre vänstra hörnet av rektangeln. |
| width | int | Rektangelns bredd. |
| height | int | Rektangelns höjd. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Konverterar den angivna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen till en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur genom att avrunda [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)-värdena till nästa högre heltal.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Den [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen som ska konverteras. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Returnerar en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Avgör om den angivna punkten finns inom denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Den [Point](/imaging/python-net/aspose.imaging/point/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om punkten som representeras av _point_ finns inom denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur; annars false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Avgör om det rektangulära området som representeras av _rect_ är helt innehållet i denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om det rektangulära området som representeras av _rect_ är helt innehållet i denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur; annars false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Avgör om den angivna punkten finns inom denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för den punkt som ska testas. |
| y | int | Y-koordinaten för den punkt som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om punkten definierad av _x_ och _y_ finns inom denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur; annars false. |


### Method: contains_point(point) {#contains_point_point_5}


```
 contains_point(point) 
```

Avgör om den angivna punkten finns inom denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Den [Point](/imaging/python-net/aspose.imaging/point/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om punkten som representeras av _point_ finns inom denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur; annars false. |


### Method: contains_rect(rect) {#contains_rect_rect_6}


```
 contains_rect(rect) 
```

Avgör om det rektangulära området som representeras av _rect_ är helt innehållet i denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om det rektangulära området som representeras av _rect_ är helt innehållet i denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur; annars false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_7}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Skapar en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur med de angivna kantpositionerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| left | int | X-koordinaten för det övre vänstra hörnet av denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| top | int | Y-koordinaten för det övre vänstra hörnet av denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| right | int | X-koordinaten för det nedre högra hörnet av denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| bottom | int | Y-koordinaten för det nedre högra hörnet av denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den nya [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) som denna metod skapar. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_8}


```
 from_points(point1, point2) 
```

Skapar en ny [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) från två angivna punkter. De två vertikala kanterna på den skapade [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) kommer att vara lika med de angivna _point1_ och _point2_. Dessa är vanligtvis de motsatta hörnen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Den första [Point](/imaging/python-net/aspose.imaging/point/) för den nya rektangeln. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Den andra [Point](/imaging/python-net/aspose.imaging/point/) för den nya rektangeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En nyss skapad [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_9}


```
 inflate(rect, x, y) 
```

Skapar och returnerar en uppblåst kopia av den angivna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen. Kopian uppblåses med det angivna beloppet. Den ursprungliga [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen förblir oförändrad.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) att börja med. Denna rektangel modifieras inte. |
| x | int | Mängden att expandera denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horisontellt. |
| y | int | Mängden att expandera denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vertikalt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den expanderade [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(size) {#inflate_size_10}


```
 inflate(size) 
```

Uppblåser denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) med det angivna beloppet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Mängden att expandera denna rektangel. |

### Method: inflate(width, height) {#inflate_width_height_11}


```
 inflate(width, height) 
```

Uppblåser denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) med det angivna beloppet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Mängden att expandera denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horisontellt. |
| height | int | Mängden att expandera denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vertikalt. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_12}


```
 inflate_rect(rect, x, y) 
```

Skapar och returnerar en uppblåst kopia av den angivna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen. Kopian uppblåses med det angivna beloppet. Den ursprungliga [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturen förblir oförändrad.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) att börja med. Denna rektangel modifieras inte. |
| x | int | Mängden att expandera denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horisontellt. |
| y | int | Mängden att expandera denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vertikalt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den expanderade [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: intersect(a, b)  [static] {#intersect_a_b_13}


```
 intersect(a, b) 
```

Returnerar en tredje [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar skärningspunkten mellan två andra [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer. Om det inte finns någon skärning returneras en tom [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En första rektangel att skära av. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En andra rektangel att skära av. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) som representerar skärningspunkten mellan _a_ och _b_. |


### Method: intersect(rect) {#intersect_rect_14}


```
 intersect(rect) 
```

Ersätter denna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) med skärningspunkten mellan den själv och den angivna [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) att skära med. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_15}


```
 intersect_rects(a, b) 
```

Returnerar en tredje [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar skärningspunkten mellan två andra [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer. Om det inte finns någon skärning returneras en tom [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En första rektangel att skära av. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En andra rektangel att skära av. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) som representerar skärningspunkten mellan _a_ och _b_. |


### Method: intersects_with(rect) {#intersects_with_rect_16}


```
 intersects_with(rect) 
```

Avgör om denna rektangel skär med _rect_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om det finns någon skärning, annars false. |


### Method: offset(pos) {#offset_pos_17}


```
 offset(pos) 
```

Justera placeringen av denna rektangel med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pos | [Point](/imaging/python-net/aspose.imaging/point/) | Mängd för att förskjuta platsen. |

### Method: offset(x, y) {#offset_x_y_18}


```
 offset(x, y) 
```

Justera placeringen av denna rektangel med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | Den horisontella förskjutningen. |
| y | int | Den vertikala förskjutningen. |

### Method: round(value)  [static] {#round_value_19}


```
 round(value) 
```

Konverterar den angivna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) till en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) genom att avrunda [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)-värdena till närmaste heltal.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Den [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) som ska konverteras. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En ny [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_20}


```
 truncate(value) 
```

Konverterar den angivna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) till en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) genom att trunkera [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)-värdena.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Den [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) som ska konverteras. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En ny [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_21}


```
 union(a, b) 
```

Hämtar en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som innehåller föreningen av två [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En första rektangel att förena. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En andra rektangel att förena. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som omger föreningen av de två [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturerna. |


