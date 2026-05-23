---
title: "RectangleF-klass"
type: docs
weight: 7130
url: /sv/python-net/aspose.imaging/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RectangleF

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Initierar en ny instans av RectangleF-klassen |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Initierar en ny instans av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen med den angivna platsen och storleken. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Initierar en ny instans av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen med den angivna platsen och storleken. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | float | r/w | Hämtar eller anger y-koordinaten som är summan av [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/) och [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) för denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| empty [static] | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Hämtar en ny instans av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen som har värdena [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) och [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) satta till noll. |
| height | float | r/w | Hämtar eller anger höjden på denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| is_empty | bool | r | Hämtar ett värde som indikerar om egenskapen [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) eller [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) för denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) har värdet noll. |
| left | float | r/w | Hämtar eller anger x-koordinaten för den vänstra kanten av denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| right | float | r/w | Hämtar eller anger x-koordinaten som är summan av [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/) och [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) för denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Hämtar eller anger storleken på denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| top | float | r/w | Hämtar eller anger y-koordinaten för den övre kanten av denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| width | float | r/w | Hämtar eller anger bredden på denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| x | float | r/w | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| y | float | r/w | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [contains(point)](#contains_point_1) | Avgör om den angivna punkten finns inom denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [contains(rect)](#contains_rect_2) | Avgör om det rektangulära området som representeras av _rect_ är helt innehållet i denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [contains(x, y)](#contains_x_y_3) | Avgör om den angivna punkten finns inom denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [contains_point_f(point)](#contains_point_f_point_4) | Avgör om den angivna punkten finns inom denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [contains_rect_f(rect)](#contains_rect_f_rect_5) | Avgör om det rektangulära området som representeras av _rect_ är helt innehållet i denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_6) | Skapar en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur med övre vänstra hörnet och nedre högra hörnet på de angivna positionerna. |
| [from_points(point1, point2)](#from_points_point1_point2_7) | Skapar en ny [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) från två angivna punkter. De två hörnen i den skapade [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) kommer att motsvara de överförda _point1_ och _point2_. Dessa är vanligtvis de motsatta hörnen. |
| [inflate(rect, x, y)](#inflate_rect_x_y_8) | Skapar och returnerar en uppblåst kopia av den angivna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen. Kopian uppblåses med det angivna värdet. Den ursprungliga rektangeln förblir oförändrad. |
| [inflate(size)](#inflate_size_9) | Uppblåser denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) med det angivna värdet. |
| [inflate(x, y)](#inflate_x_y_10) | Uppblåser denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur med det angivna värdet. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_11) | Skapar och returnerar en uppblåst kopia av den angivna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen. Kopian uppblåses med det angivna värdet. Den ursprungliga rektangeln förblir oförändrad. |
| [intersect(a, b)](#intersect_a_b_12) | Returnerar en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar skärningspunkten mellan två rektanglar. Om det inte finns någon skärning returneras en tom [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [intersect(rect)](#intersect_rect_13) | Ersätter denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur med skärningspunkten mellan sig själv och den angivna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen. |
| [intersect_rects(a, b)](#intersect_rects_a_b_14) | Returnerar en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar skärningspunkten mellan två rektanglar. Om det inte finns någon skärning returneras en tom [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [intersects_with(rect)](#intersects_with_rect_15) | Avgör om denna rektangel skär med _rect_. |
| normalize() | Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten. |
| [offset(pos)](#offset_pos_16) | Justera placeringen av denna rektangel med det angivna värdet. |
| [offset(x, y)](#offset_x_y_17) | Justera placeringen av denna rektangel med det angivna värdet. |
| [union(a, b)](#union_a_b_18) | Skapar den minsta möjliga tredje rektangeln som kan innehålla båda två rektanglar som bildar en union. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Initierar en ny instans av RectangleF-klassen

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Initierar en ny instans av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen med den angivna platsen och storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som representerar det övre vänstra hörnet av det rektangulära området. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | En [SizeF](/imaging/python-net/aspose.imaging/sizef/) som representerar bredden och höjden av det rektangulära området. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Initierar en ny instans av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen med den angivna platsen och storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | x-koordinaten för det övre vänstra hörnet av rektangeln. |
| y | float | y-koordinaten för det övre vänstra hörnet av rektangeln. |
| width | float | Rektangelns bredd. |
| height | float | Rektangelns höjd. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Avgör om den angivna punkten finns inom denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Den [PointF](/imaging/python-net/aspose.imaging/pointf/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om punkten som representeras av parametern _point_ finns inom denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur; annars false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Avgör om det rektangulära området som representeras av _rect_ är helt innehållet i denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Den [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om det rektangulära området som representeras av _rect_ är helt innehållet inom det rektangulära området som representeras av denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); annars false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Avgör om den angivna punkten finns inom denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för den punkt som ska testas. |
| y | float | Y-koordinaten för den punkt som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om punkten som definieras av _x_ och _y_ är innehållen inom denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur; annars false. |


### Method: contains_point_f(point) {#contains_point_f_point_4}


```
 contains_point_f(point) 
```

Avgör om den angivna punkten finns inom denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Den [PointF](/imaging/python-net/aspose.imaging/pointf/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om punkten som representeras av parametern _point_ finns inom denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur; annars false. |


### Method: contains_rect_f(rect) {#contains_rect_f_rect_5}


```
 contains_rect_f(rect) 
```

Avgör om det rektangulära området som representeras av _rect_ är helt innehållet i denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Den [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om det rektangulära området som representeras av _rect_ är helt innehållet inom det rektangulära området som representeras av denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); annars false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_6}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Skapar en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur med övre vänstra hörnet och nedre högra hörnet på de angivna positionerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vänster | float | X-koordinaten för det övre vänstra hörnet av det rektangulära området. |
| överkant | float | Y-koordinaten för det övre vänstra hörnet av det rektangulära området. |
| höger | float | X-koordinaten för det nedre högra hörnet av det rektangulära området. |
| nedre | float | Y-koordinaten för det nedre högra hörnet av det rektangulära området. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Den nya [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) som denna metod skapar. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_7}


```
 from_points(point1, point2) 
```

Skapar en ny [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) från två angivna punkter. De två hörnen i den skapade [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) kommer att motsvara de överförda _point1_ och _point2_. Dessa är vanligtvis de motsatta hörnen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Den första [Point](/imaging/python-net/aspose.imaging/point/) för den nya rektangeln. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Den andra [Point](/imaging/python-net/aspose.imaging/point/) för den nya rektangeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En nyss skapad [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_8}


```
 inflate(rect, x, y) 
```

Skapar och returnerar en uppblåst kopia av den angivna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen. Kopian uppblåses med det angivna värdet. Den ursprungliga rektangeln förblir oförändrad.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) som ska kopieras. Denna rektangel ändras inte. |
| x | float | Mängden att expandera kopian av rektangeln horisontellt. |
| y | float | Mängden att expandera kopian av rektangeln vertikalt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Den expanderade [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |


### Method: inflate(size) {#inflate_size_9}


```
 inflate(size) 
```

Uppblåser denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Mängden att expandera denna rektangel. |

### Method: inflate(x, y) {#inflate_x_y_10}


```
 inflate(x, y) 
```

Uppblåser denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | Mängden att expandera denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur horisontellt. |
| y | float | Mängden att expandera denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur vertikalt. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_11}


```
 inflate_rect(rect, x, y) 
```

Skapar och returnerar en uppblåst kopia av den angivna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen. Kopian uppblåses med det angivna värdet. Den ursprungliga rektangeln förblir oförändrad.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) som ska kopieras. Denna rektangel ändras inte. |
| x | float | Mängden att expandera kopian av rektangeln horisontellt. |
| y | float | Mängden att expandera kopian av rektangeln vertikalt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Den expanderade [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |


### Method: intersect(a, b)  [static] {#intersect_a_b_12}


```
 intersect(a, b) 
```

Returnerar en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar skärningspunkten mellan två rektanglar. Om det inte finns någon skärning returneras en tom [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En första rektangel att skära av. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En andra rektangel att skära av. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En tredje [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur vars storlek representerar det överlappande området av de två angivna rektanglarna. |


### Method: intersect(rect) {#intersect_rect_13}


```
 intersect(rect) 
```

Ersätter denna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur med skärningspunkten mellan sig själv och den angivna [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rektangeln att skära av. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_14}


```
 intersect_rects(a, b) 
```

Returnerar en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar skärningspunkten mellan två rektanglar. Om det inte finns någon skärning returneras en tom [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En första rektangel att skära av. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En andra rektangel att skära av. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En tredje [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur vars storlek representerar det överlappande området av de två angivna rektanglarna. |


### Method: intersects_with(rect) {#intersects_with_rect_15}


```
 intersects_with(rect) 
```

Avgör om denna rektangel skär med _rect_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rektangeln att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om det finns någon skärning. |


### Method: offset(pos) {#offset_pos_16}


```
 offset(pos) 
```

Justera placeringen av denna rektangel med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pos | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Mängden att förskjuta platsen. |

### Method: offset(x, y) {#offset_x_y_17}


```
 offset(x, y) 
```

Justera placeringen av denna rektangel med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | Mängden att förskjuta platsen horisontellt. |
| y | float | Mängden att förskjuta platsen vertikalt. |

### Method: union(a, b)  [static] {#union_a_b_18}


```
 union(a, b) 
```

Skapar den minsta möjliga tredje rektangeln som kan innehålla båda två rektanglar som bildar en union.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En första rektangel att förena. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En andra rektangel att förena. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En tredje [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som innehåller båda de två rektanglarna som bildar föreningen. |


