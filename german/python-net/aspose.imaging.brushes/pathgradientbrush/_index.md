---
title: "PathGradientBrush Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.imaging.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Initialisiert eine neue Instanz der PathGradientBrush-Klasse |
| [PathGradientBrush(path_points)](#PathGradientBrush_path_points_2) | Initialisiert eine neue Instanz der PathGradientBrush-Klasse |
| [PathGradientBrush(path_points)](#PathGradientBrush_path_points_3) | Initialisiert eine neue Instanz der PathGradientBrush-Klasse |
| [PathGradientBrush(path_points, wrap_mode)](#PathGradientBrush_path_points_wrap_mode_4) | Initialisiert eine neue Instanz der PathGradientBrush-Klasse |
| [PathGradientBrush(path_points, wrap_mode)](#PathGradientBrush_path_points_wrap_mode_5) | Initialisiert eine neue Instanz der PathGradientBrush-Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | Liest oder setzt ein [Blend](/imaging/python-net/aspose.imaging/blend/), das Positionen und Faktoren angibt, die einen benutzerdefinierten Verlauf für den Gradient definieren. |
| center_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt die Farbe im Zentrum des Pfadverlaufs. |
| center_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt den Mittelpunkt des Pfadverlaufs. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| focus_scales | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt den Fokuspunkt für den Verlaufabfall. |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r | Liest den Grafikpfad, auf dem dieser Pinsel aufgebaut ist. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Ruft ein [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) ab oder legt es fest, das einen mehrfarbigen linearen Verlauf definiert. |
| is_transform_changed | bool | r | Ruft einen Wert ab, der angibt, ob Transformationen auf irgendeine Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder<br/>            das Aufrufen einer der Methoden, die die Transformationsmatrix verändern. Die Eigenschaft wurde aus Gründen der Abwärtskompatibilität mit GDI+ eingeführt. |
| opacity | float | r/w | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r | Liest die Pfadpunkte, auf denen dieser Pinsel aufgebaut ist. |
| surround_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt ein Array von Farben, das den Punkten im Pfad entspricht, den dieser [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) füllt. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ruft eine Kopie des [Matrix](/imaging/python-net/aspose.imaging/matrix/) ab oder legt sie fest, die eine lokale geometrische Transformation für diesen [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) definiert. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Liest oder setzt eine [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) Aufzählung, die den Wrap-Modus für diesen [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) angibt. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_with_path(path)](#create_with_path_path_1) | Initialisiert eine neue Instanz der [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) Klasse mit dem angegebenen Pfad. |
| [create_with_points(path_points)](#create_with_points_path_points_2) | Initialisiert eine neue Instanz der [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten. |
| [create_with_points_f(path_points)](#create_with_points_f_path_points_3) | Initialisiert eine neue Instanz der [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten. |
| [create_with_points_f_wrap_mode(path_points, wrap_mode)](#create_with_points_f_wrap_mode_path_points_wrap_mode_4) | Initialisiert eine neue Instanz der [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten und Wrap-Modus. |
| [create_with_points_wrap_mode(path_points, wrap_mode)](#create_with_points_wrap_mode_path_points_wrap_mode_5) | Initialisiert eine neue Instanz der [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten und Wrap-Modus. |
| [deep_clone()](#deep_clone__6) | Erstellt einen neuen Deep-Clone des aktuellen [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_7) | Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/), indem die angegebene [Matrix](/imaging/python-net/aspose.imaging/matrix/) vorangestellt wird. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_8) | Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/) in der angegebenen Reihenfolge. |
| reset_transform() | Setzt die Eigenschaft [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) auf die Identität zurück. |
| [rotate_transform(angle)](#rotate_transform_angle_9) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_10) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_11) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungs-Matrix der Transformation voran. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_12) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_13) | Erstellt einen Verlauf mit einer Mittelwertfarbe und einem linearen Abfall zu einer umgebenden Farbe. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_14) | Erstellt einen Verlauf mit einer Mittelwertfarbe und einem linearen Abfall zu jeder umgebenden Farbe. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_15) | Erstellt einen Farbverlaufs-Pinsel, der die Farbe vom Zentrum des Pfades nach außen bis zur Pfadgrenze ändert. Der Übergang von einer Farbe zur nächsten basiert auf einer glockenförmigen Kurve. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_16) | Erstellt einen Farbverlaufs-Pinsel, der die Farbe vom Zentrum des Pfades nach außen bis zur Pfadgrenze ändert. Der Übergang von einer Farbe zur nächsten basiert auf einer glockenförmigen Kurve. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_17) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_18) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Initialisiert eine neue Instanz der PathGradientBrush-Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) |  |

### Constructor: PathGradientBrush(path_points) {#PathGradientBrush_path_points_2}


```
 PathGradientBrush(path_points) 
```

Initialisiert eine neue Instanz der PathGradientBrush-Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) |  |

### Constructor: PathGradientBrush(path_points) {#PathGradientBrush_path_points_3}


```
 PathGradientBrush(path_points) 
```

Initialisiert eine neue Instanz der PathGradientBrush-Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) |  |

### Constructor: PathGradientBrush(path_points, wrap_mode) {#PathGradientBrush_path_points_wrap_mode_4}


```
 PathGradientBrush(path_points, wrap_mode) 
```

Initialisiert eine neue Instanz der PathGradientBrush-Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) |  |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) |  |

### Constructor: PathGradientBrush(path_points, wrap_mode) {#PathGradientBrush_path_points_wrap_mode_5}


```
 PathGradientBrush(path_points, wrap_mode) 
```

Initialisiert eine neue Instanz der PathGradientBrush-Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) |  |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) |  |

### Method: create_with_path(path)  [static] {#create_with_path_path_1}


```
 create_with_path(path) 
```

Initialisiert eine neue Instanz der [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) Klasse mit dem angegebenen Pfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Der [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) definiert den von diesem [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) gefüllten Bereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points(path_points)  [static] {#create_with_points_path_points_2}


```
 create_with_points(path_points) 
```

Initialisiert eine neue Instanz der [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)-Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_f(path_points)  [static] {#create_with_points_f_path_points_3}


```
 create_with_points_f(path_points) 
```

Initialisiert eine neue Instanz der [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)-Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_f_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_f_wrap_mode_path_points_wrap_mode_4}


```
 create_with_points_f_wrap_mode(path_points, wrap_mode) 
```

Initialisiert eine neue Instanz der [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten und Wrap-Modus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)-Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Ein [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) der angibt, wie mit diesem [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) gezeichnete Füllungen gekachelt werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_wrap_mode_path_points_wrap_mode_5}


```
 create_with_points_wrap_mode(path_points, wrap_mode) 
```

Initialisiert eine neue Instanz der [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten und Wrap-Modus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Ein Array von [Point](/imaging/python-net/aspose.imaging/point/)-Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Ein [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) der angibt, wie mit diesem [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) gezeichnete Füllungen gekachelt werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__6}


```
 deep_clone() 
```

Erstellt einen neuen Deep-Clone des aktuellen [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Ein neuer [Brush](/imaging/python-net/aspose.imaging/brush/), der der Deep-Clone dieser [Brush](/imaging/python-net/aspose.imaging/brush/) Instanz ist. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_7}


```
 multiply_transform(matrix) 
```

Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/), indem die angegebene [Matrix](/imaging/python-net/aspose.imaging/matrix/) vorangestellt wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die [Matrix](/imaging/python-net/aspose.imaging/matrix/), mit der die geometrische Transformation multipliziert wird. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_8}


```
 multiply_transform(matrix, order) 
```

Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/) in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die [Matrix](/imaging/python-net/aspose.imaging/matrix/), mit der die geometrische Transformation multipliziert wird. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ein [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), der angibt, in welcher Reihenfolge die beiden Matrizen zu multiplizieren sind. |

### Method: rotate_transform(angle) {#rotate_transform_angle_9}


```
 rotate_transform(angle) 
```

Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_10}


```
 rotate_transform(angle, order) 
```

Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ein [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), der angibt, ob die Rotationsmatrix angehängt oder vorangestellt wird. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_11}


```
 scale_transform(sx, sy) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungs-Matrix der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_12}


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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_13}


```
 set_blend_triangular_shape(focus) 
```

Erstellt einen Verlauf mit einer Mittelwertfarbe und einem linearen Abfall zu einer umgebenden Farbe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Mittelpunkt des Pfads zur Pfadgrenze die Mittelwertfarbe ihre höchste Intensität erreicht. Ein Wert von 1 (der Standard) legt die höchste Intensität in der Mitte des Pfads fest. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_14}


```
 set_blend_triangular_shape(focus, scale) 
```

Erstellt einen Verlauf mit einer Mittelwertfarbe und einem linearen Abfall zu jeder umgebenden Farbe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Mittelpunkt des Pfads zur Pfadgrenze die Mittelwertfarbe ihre höchste Intensität erreicht. Ein Wert von 1 (der Standard) legt die höchste Intensität in der Mitte des Pfads fest. |
| Skala | float | Ein Wert von 0 bis 1, der die maximale Intensität der Mittelwertfarbe angibt, die mit der Randfarbe gemischt wird. Ein Wert von 1 bewirkt die höchstmögliche Intensität der Mittelwertfarbe und ist der Standardwert. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_15}


```
 set_sigma_bell_shape(focus) 
```

Erstellt einen Farbverlaufs-Pinsel, der die Farbe vom Zentrum des Pfades nach außen bis zur Pfadgrenze ändert. Der Übergang von einer Farbe zur nächsten basiert auf einer glockenförmigen Kurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Mittelpunkt des Pfads zur Pfadgrenze die Mittelwertfarbe ihre höchste Intensität erreicht. Ein Wert von 1 (der Standard) legt die höchste Intensität in der Mitte des Pfads fest. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_16}


```
 set_sigma_bell_shape(focus, scale) 
```

Erstellt einen Farbverlaufs-Pinsel, der die Farbe vom Zentrum des Pfades nach außen bis zur Pfadgrenze ändert. Der Übergang von einer Farbe zur nächsten basiert auf einer glockenförmigen Kurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Mittelpunkt des Pfads zur Pfadgrenze die Mittelwertfarbe ihre höchste Intensität erreicht. Ein Wert von 1 (der Standard) legt die höchste Intensität in der Mitte des Pfads fest. |
| Skala | float | Ein Wert von 0 bis 1, der die maximale Intensität der Mittelwertfarbe angibt, die mit der Randfarbe gemischt wird. Ein Wert von 1 bewirkt die höchstmögliche Intensität der Mittelwertfarbe und ist der Standardwert. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_17}


```
 translate_transform(dx, dy) 
```

Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_18}


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

