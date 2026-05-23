---
title: "LinearGradientBrush Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse mit Standardparametern.<br/>            Die Startfarbe ist schwarz, die Endfarbe ist weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich bei (0,0) mit der Größe (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| angle | float | r/w | Ruft den Gradientwinkel ab oder legt ihn fest. |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | Liest oder setzt ein [Blend](/imaging/python-net/aspose.imaging/blend/), das Positionen und Faktoren angibt, die einen benutzerdefinierten Verlauf für den Gradient definieren. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| end_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt die Endfarbe des Gradienten. |
| gamma_correction | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Gammakorrektur für dieses [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) aktiviert ist. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Ruft ein [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) ab oder legt es fest, das einen mehrfarbigen linearen Verlauf definiert. |
| is_angle_scalable | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) während Transformationen mit diesem [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) geändert wird. |
| is_transform_changed | bool | r | Ruft einen Wert ab, der angibt, ob Transformationen auf irgendeine Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder<br/>            das Aufrufen einer der Methoden, die die Transformationsmatrix verändern. Die Eigenschaft wurde aus Gründen der Abwärtskompatibilität mit GDI+ eingeführt. |
| linear_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt die Start- und Endfarben des Gradienten. |
| opacity | float | r/w | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Ruft einen rechteckigen Bereich ab oder legt ihn fest, der die Start- und Endpunkte des Verlaufs definiert. |
| start_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt die Startfarbe des Gradienten. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ruft eine Kopie des [Matrix](/imaging/python-net/aspose.imaging/matrix/) ab oder legt sie fest, die eine lokale geometrische Transformation für diesen [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) definiert. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Liest oder setzt eine [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) Aufzählung, die den Wrap-Modus für diesen [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) angibt. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_with_points(point1, point2, color1, color2)](#create_with_points_point1_point2_color1_color2_1) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse mit den angegebenen Punkten und Farben. |
| [create_with_points_f(point1, point2, color1, color2)](#create_with_points_f_point1_point2_color1_color2_2) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse mit den angegebenen Punkten und Farben. |
| [create_with_rect_colors_angle(rect, color1, color2, angle)](#create_with_rect_colors_angle_rect_color1_color2_angle_3) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse basierend auf einem Rechteck, Start- und Endfarben sowie einem Orientierungwinkel. |
| [create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse basierend auf einem Rechteck, Start- und Endfarben sowie einem Orientierungwinkel. |
| [create_with_rect_f_colors_angle(rect, color1, color2, angle)](#create_with_rect_f_colors_angle_rect_color1_color2_angle_5) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse basierend auf einem Rechteck, Start- und Endfarben sowie einem Orientierungwinkel. |
| [create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6) | Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse basierend auf einem Rechteck, Start- und Endfarben sowie einem Orientierungwinkel. |
| [deep_clone()](#deep_clone__7) | Erstellt einen neuen Deep-Clone des aktuellen [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/), indem die angegebene [Matrix](/imaging/python-net/aspose.imaging/matrix/) vorangestellt wird. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/) in der angegebenen Reihenfolge. |
| reset_transform() | Setzt die Eigenschaft [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) auf die Identität zurück. |
| [rotate_transform(angle)](#rotate_transform_angle_10) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungs-Matrix der Transformation voran. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_14) | Erstellt einen linearen Gradient mit einer Mittelwertfarbe und einem linearen Verlauf zu einer einzelnen Farbe an beiden Enden. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_15) | Erstellt einen linearen Gradient mit einer Mittelwertfarbe und einem linearen Verlauf zu einer einzelnen Farbe an beiden Enden. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_16) | Erstellt einen Gradientenverlauf basierend auf einer glockenförmigen Kurve. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_17) | Erstellt einen Gradientenverlauf basierend auf einer glockenförmigen Kurve. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_18) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_19) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse mit Standardparametern.<br/>            Die Startfarbe ist schwarz, die Endfarbe ist weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich bei (0,0) mit der Größe (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der Punkt1. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der Punkt2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe2. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Der Punkt1. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Der Punkt2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe2. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Rechteck. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe2. |
| angle | float | Der Winkel. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe2. |
| angle | float | Der Winkel. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Rechteck. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe2. |
| angle | float | Der Winkel. |
| is_angle_scalable | bool | wenn auf <c>true</c> [ist Winkel skalierbar]. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe2. |
| angle | float | Der Winkel. |
| is_angle_scalable | bool | wenn auf <c>true</c> [ist Winkel skalierbar]. |

### Method: create_with_points(point1, point2, color1, color2)  [static] {#create_with_points_point1_point2_color1_color2_1}


```
 create_with_points(point1, point2, color1, color2) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse mit den angegebenen Punkten und Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Eine [Point](/imaging/python-net/aspose.imaging/point/) Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Eine [Point](/imaging/python-net/aspose.imaging/point/) Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Eine [Color](/imaging/python-net/aspose.imaging/color/) Struktur, die die Startfarbe des linearen Farbverlaufs darstellt. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Eine [Color](/imaging/python-net/aspose.imaging/color/) Struktur, die die Endfarbe des linearen Farbverlaufs darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_points_f(point1, point2, color1, color2)  [static] {#create_with_points_f_point1_point2_color1_color2_2}


```
 create_with_points_f(point1, point2, color1, color2) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse mit den angegebenen Punkten und Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Eine [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Eine [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Eine [Color](/imaging/python-net/aspose.imaging/color/) Struktur, die die Startfarbe des linearen Farbverlaufs darstellt. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Eine [Color](/imaging/python-net/aspose.imaging/color/) Struktur, die die Endfarbe des linearen Farbverlaufs darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_colors_angle_rect_color1_color2_angle_3}


```
 create_with_rect_colors_angle(rect, color1, color2, angle) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse basierend auf einem Rechteck, Start- und Endfarben sowie einem Orientierungwinkel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Eine [Color](/imaging/python-net/aspose.imaging/color/) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Eine [Color](/imaging/python-net/aspose.imaging/color/) Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4}


```
 create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse basierend auf einem Rechteck, Start- und Endfarben sowie einem Orientierungwinkel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Eine [Color](/imaging/python-net/aspose.imaging/color/) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Eine [Color](/imaging/python-net/aspose.imaging/color/) Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |
| is_angle_scalable | bool | wenn auf <c>true</c> gesetzt, wird der Winkel während Transformationen mit diesem [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) geändert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_f_colors_angle_rect_color1_color2_angle_5}


```
 create_with_rect_f_colors_angle(rect, color1, color2, angle) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse basierend auf einem Rechteck, Start- und Endfarben sowie einem Orientierungwinkel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Eine [Color](/imaging/python-net/aspose.imaging/color/) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Eine [Color](/imaging/python-net/aspose.imaging/color/) Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6}


```
 create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) Klasse basierend auf einem Rechteck, Start- und Endfarben sowie einem Orientierungwinkel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Eine [Color](/imaging/python-net/aspose.imaging/color/) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Eine [Color](/imaging/python-net/aspose.imaging/color/) Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |
| is_angle_scalable | bool | wenn auf <c>true</c> gesetzt, wird der Winkel während Transformationen mit diesem [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) geändert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: deep_clone() {#deep_clone__7}


```
 deep_clone() 
```

Erstellt einen neuen Deep-Clone des aktuellen [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Ein neuer [Brush](/imaging/python-net/aspose.imaging/brush/), der der Deep-Clone dieser [Brush](/imaging/python-net/aspose.imaging/brush/) Instanz ist. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_8}


```
 multiply_transform(matrix) 
```

Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/), indem die angegebene [Matrix](/imaging/python-net/aspose.imaging/matrix/) vorangestellt wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die [Matrix](/imaging/python-net/aspose.imaging/matrix/), mit der die geometrische Transformation multipliziert wird. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_9}


```
 multiply_transform(matrix, order) 
```

Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/) in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die [Matrix](/imaging/python-net/aspose.imaging/matrix/), mit der die geometrische Transformation multipliziert wird. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ein [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), der angibt, in welcher Reihenfolge die beiden Matrizen zu multiplizieren sind. |

### Method: rotate_transform(angle) {#rotate_transform_angle_10}


```
 rotate_transform(angle) 
```

Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_11}


```
 rotate_transform(angle, order) 
```

Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ein [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), der angibt, ob die Rotationsmatrix angehängt oder vorangestellt wird. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_12}


```
 scale_transform(sx, sy) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungs-Matrix der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_13}


```
 scale_transform(sx, sy, order) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ein [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) der angibt, ob die Skalierungsmatrix angehängt oder vorangestellt werden soll. |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_14}


```
 set_blend_triangular_shape(focus) 
```

Erstellt einen linearen Gradient mit einer Mittelwertfarbe und einem linearen Verlauf zu einer einzelnen Farbe an beiden Enden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Verlauf nur aus der Endfarbe besteht). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_15}


```
 set_blend_triangular_shape(focus, scale) 
```

Erstellt einen linearen Gradient mit einer Mittelwertfarbe und einem linearen Verlauf zu einer einzelnen Farbe an beiden Enden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Verlauf nur aus der Endfarbe besteht). |
| Skala | float | Ein Wert von 0 bis 1, der angibt, wie schnell die Farben von der Startfarbe zum _Fokus_ (Endfarbe) abfallen. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_16}


```
 set_sigma_bell_shape(focus) 
```

Erstellt einen Gradientenverlauf basierend auf einer glockenförmigen Kurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem die Start- und Endfarbe zu gleichen Teilen gemischt werden). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_17}


```
 set_sigma_bell_shape(focus, scale) 
```

Erstellt einen Gradientenverlauf basierend auf einer glockenförmigen Kurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Verlauf nur aus der Endfarbe besteht). |
| Skala | float | Ein Wert von 0 bis 1, der angibt, wie schnell die Farben vom _Fokus_ abfallen. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_18}


```
 translate_transform(dx, dy) 
```

Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_19}


```
 translate_transform(dx, dy, order) 
```

Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Die Reihenfolge (voranstellen oder anhängen), in der die Verschiebung angewendet wird. |

