---
title: "Region"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Décrit l'intérieur d'une forme graphique composée de rectangles et de chemins."
type: docs
weight: 95
url: /fr/java/com.aspose.imaging/region/
---
**Inheritance:**
java.lang.Object
```
public final class Region
```

Décrit l'intérieur d'une forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Region()](#Region--) | Initialise une nouvelle Region. |
| [Region(RectangleF rect)](#Region-com.aspose.imaging.RectangleF-) | Initialise une nouvelle `T:Aspose.Imaging.Region` à partir de la structure `T:Aspose.Imaging.RectangleF` spécifiée. |
| [Region(Rectangle rect)](#Region-com.aspose.imaging.Rectangle-) | Initialise une nouvelle `T:Aspose.Imaging.Region` à partir de la structure `T:Aspose.Imaging.Rectangle` spécifiée. |
| [Region(GraphicsPath path)](#Region-com.aspose.imaging.GraphicsPath-) | Initialise une nouvelle `T:Aspose.Imaging.Region` avec le `T:Aspose.Imaging.GraphicsPath` spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde exacte de ce `com.aspose.imaging.region`. |
| [makeInfinite()](#makeInfinite--) | Initialise cet objet `com.aspose.imaging.Region` à un intérieur infini. |
| [makeEmpty()](#makeEmpty--) | Initialise ce `com.aspose.imaging.Region` à un intérieur vide. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Met à jour ce `com.aspose.imaging.Region` avec l'intersection de lui-même et de la structure `com.aspose.imaging.RectangleF` spécifiée. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Met à jour ce `com.aspose.imaging.Region` avec l'intersection de lui-même et de la structure `com.aspose.imaging.Rectangle` spécifiée. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.imaging.GraphicsPath-) | Met à jour ce `com.aspose.imaging.Region` avec l'intersection de lui-même et du `com.aspose.imaging.graphicsPath` spécifié. |
| [intersect(Region region)](#intersect-com.aspose.imaging.Region-) | Met à jour ce `com.aspose.imaging.Region` avec l'intersection de lui-même et du `com.aspose.imaging.region` spécifié. |
| [union(RectangleF rect)](#union-com.aspose.imaging.RectangleF-) | Met à jour ce `com.aspose.imaging.Region` avec l'union de lui-même et de la structure `com.aspose.imaging.RectangleF` spécifiée. |
| [union(Rectangle rect)](#union-com.aspose.imaging.Rectangle-) | Met à jour ce `com.aspose.imaging.Region` avec l'union de lui-même et de la structure `com.aspose.imaging.Rectangle` spécifiée. |
| [union(GraphicsPath path)](#union-com.aspose.imaging.GraphicsPath-) | Met à jour ce `com.aspose.imaging.Region` avec l'union de lui-même et du `com.aspose.imaging.graphicsPath` spécifié. |
| [union(Region region)](#union-com.aspose.imaging.Region-) | Met à jour ce `com.aspose.imaging.Region` avec l'union de lui-même et du `com.aspose.imaging.region` spécifié. |
| [xor(RectangleF rect)](#xor-com.aspose.imaging.RectangleF-) | Met à jour ce `com.aspose.imaging.Region` avec l'union moins l'intersection de lui-même et de la structure `com.aspose.imaging.RectangleF` spécifiée. |
| [xor(Rectangle rect)](#xor-com.aspose.imaging.Rectangle-) | Met à jour ce `com.aspose.imaging.Region` en l'union moins l'intersection de lui-même avec la structure `com.aspose.imaging.Rectangle` spécifiée. |
| [xor(GraphicsPath path)](#xor-com.aspose.imaging.GraphicsPath-) | Met à jour ce `com.aspose.imaging.Region` en l'union moins l'intersection de lui-même avec le `com.aspose.imaging.graphicsPath` spécifié. |
| [xor(Region region)](#xor-com.aspose.imaging.Region-) | Met à jour ce `com.aspose.imaging.Region` en l'union moins l'intersection de lui-même avec le `com.aspose.imaging.region` spécifié. |
| [exclude(RectangleF rect)](#exclude-com.aspose.imaging.RectangleF-) | Met à jour ce `com.aspose.imaging.Region` pour ne contenir que la partie de son intérieur qui n'intersecte pas la structure `com.aspose.imaging.RectangleF` spécifiée. |
| [exclude(Rectangle rect)](#exclude-com.aspose.imaging.Rectangle-) | Met à jour ce `com.aspose.imaging.Region` pour ne contenir que la partie de son intérieur qui n'intersecte pas la structure `com.aspose.imaging.Rectangle` spécifiée. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.imaging.GraphicsPath-) | Met à jour ce `com.aspose.imaging.Region` pour ne contenir que la partie de son intérieur qui n'intersecte pas le `com.aspose.imaging.graphicsPath` spécifié. |
| [exclude(Region region)](#exclude-com.aspose.imaging.Region-) | Met à jour ce `com.aspose.imaging.Region` pour ne contenir que la partie de son intérieur qui n'intersecte pas le `com.aspose.imaging.region` spécifié. |
| [complement(RectangleF rect)](#complement-com.aspose.imaging.RectangleF-) | Met à jour ce `com.aspose.imaging.Region` pour contenir la partie de la structure `com.aspose.imaging.RectangleF` spécifiée qui n'intersecte pas ce `com.aspose.imaging.region`. |
| [complement(Rectangle rect)](#complement-com.aspose.imaging.Rectangle-) | Met à jour ce `com.aspose.imaging.Region` pour contenir la partie de la structure `com.aspose.imaging.Rectangle` spécifiée qui n'intersecte pas ce `com.aspose.imaging.region`. |
| [complement(GraphicsPath path)](#complement-com.aspose.imaging.GraphicsPath-) | Met à jour ce `com.aspose.imaging.Region` pour contenir la partie du `com.aspose.imaging.GraphicsPath` spécifié qui n'intersecte pas ce `com.aspose.imaging.region`. |
| [complement(Region region)](#complement-com.aspose.imaging.Region-) | Met à jour ce `com.aspose.imaging.Region` pour contenir la partie du `com.aspose.imaging.Region` spécifié qui n'intersecte pas ce `com.aspose.imaging.region`. |
| [translate(float dx, float dy)](#translate-float-float-) | Décale les coordonnées de ce `com.aspose.imaging.Region` du montant spécifié. |
| [translate(int dx, int dy)](#translate-int-int-) | Décale les coordonnées de ce `com.aspose.imaging.Region` du montant spécifié. |
| [transform(Matrix matrix)](#transform-com.aspose.imaging.Matrix-) | Transforme ce `com.aspose.imaging.Region` à l'aide du `com.aspose.imaging.matrix` spécifié. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.imaging.Graphics-) | Teste si ce `com.aspose.imaging.Region` possède un intérieur vide sur la surface de dessin spécifiée. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.imaging.Graphics-) | Teste si ce `com.aspose.imaging.Region` possède un intérieur infini sur la surface de dessin spécifiée. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-) | Teste si le `com.aspose.imaging.Region` spécifié est identique à ce `com.aspose.imaging.Region` sur la surface de dessin spécifiée. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Teste si le point spécifié est contenu dans ce `com.aspose.imaging.region`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Teste si la structure `com.aspose.imaging.PointF` spécifiée est contenue dans ce `com.aspose.imaging.region`. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Teste si le point spécifié est contenu dans ce `com.aspose.imaging.Region` lorsqu'il est dessiné avec le `com.aspose.imaging.graphics` spécifié. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Teste si la structure `com.aspose.imaging.PointF` spécifiée est contenue dans ce `com.aspose.imaging.Region` lorsqu'elle est dessinée avec le `com.aspose.imaging.graphics` spécifié. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Teste si une partie du rectangle spécifié est contenue dans ce `com.aspose.imaging.region`. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.imaging.RectangleF-) | Teste si une partie de la structure `com.aspose.imaging.RectangleF` spécifiée est contenue dans ce `com.aspose.imaging.region`. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.imaging.Graphics-) | Teste si une partie du rectangle spécifié est contenue dans ce `com.aspose.imaging.Region` lorsqu'il est dessiné avec le `com.aspose.imaging.graphics` spécifié. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-) | Teste si une partie de la structure `com.aspose.imaging.RectangleF` spécifiée est contenue dans ce `com.aspose.imaging.Region` lorsqu'elle est dessinée avec le `com.aspose.imaging.graphics` spécifié. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Teste si le point spécifié est contenu dans cet objet `com.aspose.imaging.Region` lorsqu'il est dessiné avec l'objet `com.aspose.imaging.Graphics` spécifié. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Teste si la structure `com.aspose.imaging.Point` spécifiée est contenue dans ce `com.aspose.imaging.region`. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Teste si la structure `com.aspose.imaging.Point` spécifiée est contenue dans ce `com.aspose.imaging.Region` lorsqu'elle est dessinée en utilisant le `com.aspose.imaging.graphics` spécifié. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Teste si une partie du rectangle spécifié est contenue dans ce `com.aspose.imaging.region`. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.imaging.Rectangle-) | Teste si une partie de la structure `com.aspose.imaging.Rectangle` spécifiée est contenue dans ce `com.aspose.imaging.region`. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.imaging.Graphics-) | Teste si une partie du rectangle spécifié est contenue dans ce `com.aspose.imaging.Region` lorsqu'il est dessiné avec le `com.aspose.imaging.graphics` spécifié. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-) | Teste si une partie de la structure `com.aspose.imaging.Rectangle` spécifiée est contenue dans ce `com.aspose.imaging.Region` lorsqu'elle est dessinée en utilisant le `com.aspose.imaging.graphics` spécifié. |
| [equals(Object o)](#equals-java.lang.Object-) | Vérifie si les objets sont égaux. |
| [hashCode()](#hashCode--) | Obtient le code de hachage de l'objet actuel. |
### Region() {#Region--}
```
public Region()
```


Initialise une nouvelle Region.

### Region(RectangleF rect) {#Region-com.aspose.imaging.RectangleF-}
```
public Region(RectangleF rect)
```


Initialise une nouvelle `T:Aspose.Imaging.Region` à partir de la structure `T:Aspose.Imaging.RectangleF` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Une structure `T:Aspose.Imaging.RectangleF` qui définit l'intérieur du nouveau `T:Aspose.Imaging.Region`. |

### Region(Rectangle rect) {#Region-com.aspose.imaging.Rectangle-}
```
public Region(Rectangle rect)
```


Initialise une nouvelle `T:Aspose.Imaging.Region` à partir de la structure `T:Aspose.Imaging.Rectangle` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Une structure `T:Aspose.Imaging.Rectangle` qui définit l'intérieur du nouveau `T:Aspose.Imaging.Region`. |

### Region(GraphicsPath path) {#Region-com.aspose.imaging.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initialise une nouvelle `T:Aspose.Imaging.Region` avec le `T:Aspose.Imaging.GraphicsPath` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un `T:Aspose.Imaging.GraphicsPath` qui définit le nouveau `T:Aspose.Imaging.Region`. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Crée une copie profonde exacte de ce `com.aspose.imaging.region`.

**Returns:**
[Region](../../com.aspose.imaging/region) - The `com.aspose.imaging.Region` that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initialise cet objet `com.aspose.imaging.Region` à un intérieur infini.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initialise ce `com.aspose.imaging.Region` à un intérieur vide.

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Met à jour ce `com.aspose.imaging.Region` avec l'intersection de lui-même et de la structure `com.aspose.imaging.RectangleF` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La structure `com.aspose.imaging.RectangleF` à intersecter avec ce `com.aspose.imaging.region`. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Met à jour ce `com.aspose.imaging.Region` avec l'intersection de lui-même et de la structure `com.aspose.imaging.Rectangle` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La structure `com.aspose.imaging.Rectangle` à intersecter avec ce `com.aspose.imaging.region`. |

### intersect(GraphicsPath path) {#intersect-com.aspose.imaging.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Met à jour ce `com.aspose.imaging.Region` avec l'intersection de lui-même et du `com.aspose.imaging.graphicsPath` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le `com.aspose.imaging.GraphicsPath` à intersecter avec ce `com.aspose.imaging.region`. |

### intersect(Region region) {#intersect-com.aspose.imaging.Region-}
```
public void intersect(Region region)
```


Met à jour ce `com.aspose.imaging.Region` avec l'intersection de lui-même et du `com.aspose.imaging.region` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Le `com.aspose.imaging.Region` à intersecter avec ce `com.aspose.imaging.region`. |

### union(RectangleF rect) {#union-com.aspose.imaging.RectangleF-}
```
public void union(RectangleF rect)
```


Met à jour ce `com.aspose.imaging.Region` avec l'union de lui-même et de la structure `com.aspose.imaging.RectangleF` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La structure `com.aspose.imaging.RectangleF` à unir avec ce `com.aspose.imaging.region`. |

### union(Rectangle rect) {#union-com.aspose.imaging.Rectangle-}
```
public void union(Rectangle rect)
```


Met à jour ce `com.aspose.imaging.Region` avec l'union de lui-même et de la structure `com.aspose.imaging.Rectangle` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La structure `com.aspose.imaging.Rectangle` à unir avec ce `com.aspose.imaging.region`. |

### union(GraphicsPath path) {#union-com.aspose.imaging.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Met à jour ce `com.aspose.imaging.Region` avec l'union de lui-même et du `com.aspose.imaging.graphicsPath` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le `com.aspose.imaging.GraphicsPath` à unir avec ce `com.aspose.imaging.region`. |

### union(Region region) {#union-com.aspose.imaging.Region-}
```
public void union(Region region)
```


Met à jour ce `com.aspose.imaging.Region` avec l'union de lui-même et du `com.aspose.imaging.region` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Le `com.aspose.imaging.Region` à unir avec ce `com.aspose.imaging.region`. |

### xor(RectangleF rect) {#xor-com.aspose.imaging.RectangleF-}
```
public void xor(RectangleF rect)
```


Met à jour ce `com.aspose.imaging.Region` avec l'union moins l'intersection de lui-même et de la structure `com.aspose.imaging.RectangleF` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La structure `com.aspose.imaging.RectangleF` à xor avec ce `com.aspose.imaging.region`. |

### xor(Rectangle rect) {#xor-com.aspose.imaging.Rectangle-}
```
public void xor(Rectangle rect)
```


Met à jour ce `com.aspose.imaging.Region` en l'union moins l'intersection de lui-même avec la structure `com.aspose.imaging.Rectangle` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La structure `com.aspose.imaging.Rectangle` à xor avec ce `com.aspose.imaging.region`. |

### xor(GraphicsPath path) {#xor-com.aspose.imaging.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Met à jour ce `com.aspose.imaging.Region` en l'union moins l'intersection de lui-même avec le `com.aspose.imaging.graphicsPath` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le `com.aspose.imaging.GraphicsPath` à xor avec ce `com.aspose.imaging.region`. |

### xor(Region region) {#xor-com.aspose.imaging.Region-}
```
public void xor(Region region)
```


Met à jour ce `com.aspose.imaging.Region` en l'union moins l'intersection de lui-même avec le `com.aspose.imaging.region` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Le `com.aspose.imaging.Region` à xor avec ce `com.aspose.imaging.region`. |

### exclude(RectangleF rect) {#exclude-com.aspose.imaging.RectangleF-}
```
public void exclude(RectangleF rect)
```


Met à jour ce `com.aspose.imaging.Region` pour ne contenir que la partie de son intérieur qui n'intersecte pas la structure `com.aspose.imaging.RectangleF` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La structure `com.aspose.imaging.RectangleF` à exclure de ce `com.aspose.imaging.region`. |

### exclude(Rectangle rect) {#exclude-com.aspose.imaging.Rectangle-}
```
public void exclude(Rectangle rect)
```


Met à jour ce `com.aspose.imaging.Region` pour ne contenir que la partie de son intérieur qui n'intersecte pas la structure `com.aspose.imaging.Rectangle` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La structure `com.aspose.imaging.Rectangle` à exclure de ce `com.aspose.imaging.region`. |

### exclude(GraphicsPath path) {#exclude-com.aspose.imaging.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Met à jour ce `com.aspose.imaging.Region` pour ne contenir que la partie de son intérieur qui n'intersecte pas le `com.aspose.imaging.graphicsPath` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le `com.aspose.imaging.GraphicsPath` à exclure de ce `com.aspose.imaging.region`. |

### exclude(Region region) {#exclude-com.aspose.imaging.Region-}
```
public void exclude(Region region)
```


Met à jour ce `com.aspose.imaging.Region` pour ne contenir que la partie de son intérieur qui n'intersecte pas le `com.aspose.imaging.region` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Le `com.aspose.imaging.Region` à exclure de ce `com.aspose.imaging.region`. |

### complement(RectangleF rect) {#complement-com.aspose.imaging.RectangleF-}
```
public void complement(RectangleF rect)
```


Met à jour ce `com.aspose.imaging.Region` pour contenir la partie de la structure `com.aspose.imaging.RectangleF` spécifiée qui n'intersecte pas ce `com.aspose.imaging.region`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La structure `com.aspose.imaging.RectangleF` pour compléter ce `com.aspose.imaging.region`. |

### complement(Rectangle rect) {#complement-com.aspose.imaging.Rectangle-}
```
public void complement(Rectangle rect)
```


Met à jour ce `com.aspose.imaging.Region` pour contenir la partie de la structure `com.aspose.imaging.Rectangle` spécifiée qui n'intersecte pas ce `com.aspose.imaging.region`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La structure `com.aspose.imaging.Rectangle` pour compléter ce `com.aspose.imaging.region`. |

### complement(GraphicsPath path) {#complement-com.aspose.imaging.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Met à jour ce `com.aspose.imaging.Region` pour contenir la partie du `com.aspose.imaging.GraphicsPath` spécifié qui n'intersecte pas ce `com.aspose.imaging.region`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le `com.aspose.imaging.GraphicsPath` pour compléter ce `com.aspose.imaging.region`. |

### complement(Region region) {#complement-com.aspose.imaging.Region-}
```
public void complement(Region region)
```


Met à jour ce `com.aspose.imaging.Region` pour contenir la partie du `com.aspose.imaging.Region` spécifié qui n'intersecte pas ce `com.aspose.imaging.region`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | L'objet `com.aspose.imaging.Region` pour compléter cet objet `com.aspose.imaging.Region`. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Décale les coordonnées de ce `com.aspose.imaging.Region` du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La quantité à décaler horizontalement ce `com.aspose.imaging.Region`. |
| dy | float | La quantité à décaler verticalement ce `com.aspose.imaging.Region`. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Décale les coordonnées de ce `com.aspose.imaging.Region` du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | int | La quantité à décaler horizontalement ce `com.aspose.imaging.Region`. |
| dy | int | La quantité à décaler verticalement ce `com.aspose.imaging.Region`. |

### transform(Matrix matrix) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix matrix)
```


Transforme ce `com.aspose.imaging.Region` à l'aide du `com.aspose.imaging.matrix` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La `com.aspose.imaging.Matrix` par laquelle transformer ce `com.aspose.imaging.region`. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.imaging.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Teste si ce `com.aspose.imaging.Region` possède un intérieur vide sur la surface de dessin spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` qui représente une surface de dessin. |

**Returns:**
boolean - true si l'intérieur de ce `com.aspose.imaging.Region` est vide lorsque la transformation associée à `g` est appliquée ; sinon, false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.imaging.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Teste si ce `com.aspose.imaging.Region` possède un intérieur infini sur la surface de dessin spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` qui représente une surface de dessin. |

**Returns:**
boolean - true si l'intérieur de ce `com.aspose.imaging.Region` est infini lorsque la transformation associée à `g` est appliquée ; sinon, false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Teste si le `com.aspose.imaging.Region` spécifié est identique à ce `com.aspose.imaging.Region` sur la surface de dessin spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Le `com.aspose.imaging.Region` à tester. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` qui représente une surface de dessin. |

**Returns:**
boolean - True si l'intérieur de la région est identique à l'intérieur de cette région lorsque la transformation associée au paramètre `g` est appliquée ; sinon, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Teste si le point spécifié est contenu dans ce `com.aspose.imaging.region`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns:**
boolean - True lorsque le point spécifié est contenu dans ce `com.aspose.imaging.Region` ; sinon, false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Teste si la structure `com.aspose.imaging.PointF` spécifiée est contenue dans ce `com.aspose.imaging.region`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | La structure `com.aspose.imaging.PointF` à tester. |

**Returns:**
boolean - true lorsque `point` est contenu dans ce `com.aspose.imaging.Region` ; sinon, false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Teste si le point spécifié est contenu dans ce `com.aspose.imaging.Region` lorsqu'il est dessiné avec le `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` qui représente un contexte graphique. |

**Returns:**
boolean - True lorsque le point spécifié est contenu dans ce `com.aspose.imaging.Region` ; sinon, false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Teste si la structure `com.aspose.imaging.PointF` spécifiée est contenue dans ce `com.aspose.imaging.Region` lorsqu'elle est dessinée avec le `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | La structure `com.aspose.imaging.PointF` à tester. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` qui représente un contexte graphique. |

**Returns:**
boolean - true lorsque `point` est contenu dans ce `com.aspose.imaging.Region` ; sinon, false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Teste si une partie du rectangle spécifié est contenue dans ce `com.aspose.imaging.region`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | float | La largeur du rectangle à tester. |
| height | float | La hauteur du rectangle à tester. |

**Returns:**
boolean - true lorsque une partie du rectangle spécifié est contenue dans cet objet `com.aspose.imaging.Region` ; sinon, false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.imaging.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Teste si une partie de la structure `com.aspose.imaging.RectangleF` spécifiée est contenue dans ce `com.aspose.imaging.region`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La structure `com.aspose.imaging.RectangleF` à tester. |

**Returns:**
boolean - true lorsque une partie de `rect` est contenue dans ce `com.aspose.imaging.Region` ; sinon, false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Teste si une partie du rectangle spécifié est contenue dans ce `com.aspose.imaging.Region` lorsqu'il est dessiné avec le `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | float | La largeur du rectangle à tester. |
| height | float | La hauteur du rectangle à tester. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` qui représente un contexte graphique. |

**Returns:**
boolean - true lorsque une partie du rectangle spécifié est contenue dans ce `com.aspose.imaging.Region` ; sinon, false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Teste si une partie de la structure `com.aspose.imaging.RectangleF` spécifiée est contenue dans ce `com.aspose.imaging.Region` lorsqu'elle est dessinée avec le `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La structure `com.aspose.imaging.RectangleF` à tester. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` qui représente un contexte graphique. |

**Returns:**
boolean - true lorsque `rect` est contenu dans ce `com.aspose.imaging.Region` ; sinon, false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Teste si le point spécifié est contenu dans cet objet `com.aspose.imaging.Region` lorsqu'il est dessiné avec l'objet `com.aspose.imaging.Graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` qui représente un contexte graphique. |

**Returns:**
booléen - vrai lorsque le point spécifié est contenu dans cette `com.aspose.imaging.Region` ; sinon, faux.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Teste si la structure `com.aspose.imaging.Point` spécifiée est contenue dans ce `com.aspose.imaging.region`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | La structure `com.aspose.imaging.Point` à tester. |

**Returns:**
boolean - true lorsque `point` est contenu dans ce `com.aspose.imaging.Region` ; sinon, false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Teste si la structure `com.aspose.imaging.Point` spécifiée est contenue dans ce `com.aspose.imaging.Region` lorsqu'elle est dessinée en utilisant le `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | La structure `com.aspose.imaging.Point` à tester. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` qui représente un contexte graphique. |

**Returns:**
boolean - true lorsque `point` est contenu dans ce `com.aspose.imaging.Region` ; sinon, false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Teste si une partie du rectangle spécifié est contenue dans ce `com.aspose.imaging.region`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | int | La largeur du rectangle à tester. |
| height | int | La hauteur du rectangle à tester. |

**Returns:**
boolean - true lorsque une partie du rectangle spécifié est contenue dans ce `com.aspose.imaging.Region` ; sinon, false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.imaging.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Teste si une partie de la structure `com.aspose.imaging.Rectangle` spécifiée est contenue dans ce `com.aspose.imaging.region`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La structure `com.aspose.imaging.Rectangle` à tester. |

**Returns:**
booléen - Cette méthode renvoie vrai lorsque n'importe quelle partie de `rect` est contenue dans cette `com.aspose.imaging.Region` ; sinon, faux.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Teste si une partie du rectangle spécifié est contenue dans ce `com.aspose.imaging.Region` lorsqu'il est dessiné avec le `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | int | La largeur du rectangle à tester. |
| height | int | La hauteur du rectangle à tester. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` qui représente un contexte graphique. |

**Returns:**
boolean - true lorsque une partie du rectangle spécifié est contenue dans ce `com.aspose.imaging.Region` ; sinon, false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Teste si une partie de la structure `com.aspose.imaging.Rectangle` spécifiée est contenue dans ce `com.aspose.imaging.Region` lorsqu'elle est dessinée en utilisant le `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La structure `com.aspose.imaging.Rectangle` à tester. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` qui représente un contexte graphique. |

**Returns:**
booléen - vrai lorsque n'importe quelle partie du `rect` est contenue dans cette `com.aspose.imaging.Region` ; sinon, faux.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Vérifie si les objets sont égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | L'autre objet. |

**Returns:**
boolean - Le résultat de la comparaison d'égalité.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de l'objet actuel.

**Returns:**
int - Le code de hachage.
