---
title: Region
second_title: Aspose.Imaging for Java API Reference
description: Describes the interior of a graphics shape composed of rectangles and paths.
type: docs
weight: 96
url: /java/com.aspose.imaging/region/
---
**Inheritance:**
java.lang.Object
```
public final class Region
```

Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [Region()](#Region--) | Initializes a new Region. |
| [Region(RectangleF rect)](#Region-com.aspose.imaging.RectangleF-) | Initializes a new `T:Aspose.Imaging.Region` from the specified `T:Aspose.Imaging.RectangleF` structure. |
| [Region(Rectangle rect)](#Region-com.aspose.imaging.Rectangle-) | Initializes a new `T:Aspose.Imaging.Region` from the specified `T:Aspose.Imaging.Rectangle` structure. |
| [Region(GraphicsPath path)](#Region-com.aspose.imaging.GraphicsPath-) | Initializes a new `T:Aspose.Imaging.Region` with the specified `T:Aspose.Imaging.GraphicsPath`. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates an exact deep copy of this `com.aspose.imaging.region`. |
| [makeInfinite()](#makeInfinite--) | Initializes this `com.aspose.imaging.Region` object to an infinite interior. |
| [makeEmpty()](#makeEmpty--) | Initializes this `com.aspose.imaging.Region` to an empty interior. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Updates this `com.aspose.imaging.Region` to the intersection of itself with the specified `com.aspose.imaging.RectangleF` structure. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Updates this `com.aspose.imaging.Region` to the intersection of itself with the specified `com.aspose.imaging.Rectangle` structure. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.imaging.GraphicsPath-) | Updates this `com.aspose.imaging.Region` to the intersection of itself with the specified `com.aspose.imaging.graphicsPath`. |
| [intersect(Region region)](#intersect-com.aspose.imaging.Region-) | Updates this `com.aspose.imaging.Region` to the intersection of itself with the specified `com.aspose.imaging.region`. |
| [union(RectangleF rect)](#union-com.aspose.imaging.RectangleF-) | Updates this `com.aspose.imaging.Region` to the union of itself and the specified `com.aspose.imaging.RectangleF` structure. |
| [union(Rectangle rect)](#union-com.aspose.imaging.Rectangle-) | Updates this `com.aspose.imaging.Region` to the union of itself and the specified `com.aspose.imaging.Rectangle` structure. |
| [union(GraphicsPath path)](#union-com.aspose.imaging.GraphicsPath-) | Updates this `com.aspose.imaging.Region` to the union of itself and the specified `com.aspose.imaging.graphicsPath`. |
| [union(Region region)](#union-com.aspose.imaging.Region-) | Updates this `com.aspose.imaging.Region` to the union of itself and the specified `com.aspose.imaging.region`. |
| [xor(RectangleF rect)](#xor-com.aspose.imaging.RectangleF-) | Updates this `com.aspose.imaging.Region` to the union minus the intersection of itself with the specified `com.aspose.imaging.RectangleF` structure. |
| [xor(Rectangle rect)](#xor-com.aspose.imaging.Rectangle-) | Updates this `com.aspose.imaging.Region` to the union minus the intersection of itself with the specified `com.aspose.imaging.Rectangle` structure. |
| [xor(GraphicsPath path)](#xor-com.aspose.imaging.GraphicsPath-) | Updates this `com.aspose.imaging.Region` to the union minus the intersection of itself with the specified `com.aspose.imaging.graphicsPath`. |
| [xor(Region region)](#xor-com.aspose.imaging.Region-) | Updates this `com.aspose.imaging.Region` to the union minus the intersection of itself with the specified `com.aspose.imaging.region`. |
| [exclude(RectangleF rect)](#exclude-com.aspose.imaging.RectangleF-) | Updates this `com.aspose.imaging.Region` to contain only the portion of its interior that does not intersect with the specified `com.aspose.imaging.RectangleF` structure. |
| [exclude(Rectangle rect)](#exclude-com.aspose.imaging.Rectangle-) | Updates this `com.aspose.imaging.Region` to contain only the portion of its interior that does not intersect with the specified `com.aspose.imaging.Rectangle` structure. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.imaging.GraphicsPath-) | Updates this `com.aspose.imaging.Region` to contain only the portion of its interior that does not intersect with the specified `com.aspose.imaging.graphicsPath`. |
| [exclude(Region region)](#exclude-com.aspose.imaging.Region-) | Updates this `com.aspose.imaging.Region` to contain only the portion of its interior that does not intersect with the specified `com.aspose.imaging.region`. |
| [complement(RectangleF rect)](#complement-com.aspose.imaging.RectangleF-) | Updates this `com.aspose.imaging.Region` to contain the portion of the specified `com.aspose.imaging.RectangleF` structure that does not intersect with this `com.aspose.imaging.region`. |
| [complement(Rectangle rect)](#complement-com.aspose.imaging.Rectangle-) | Updates this `com.aspose.imaging.Region` to contain the portion of the specified `com.aspose.imaging.Rectangle` structure that does not intersect with this `com.aspose.imaging.region`. |
| [complement(GraphicsPath path)](#complement-com.aspose.imaging.GraphicsPath-) | Updates this `com.aspose.imaging.Region` to contain the portion of the specified `com.aspose.imaging.GraphicsPath` that does not intersect with this `com.aspose.imaging.region`. |
| [complement(Region region)](#complement-com.aspose.imaging.Region-) | Updates this `com.aspose.imaging.Region` to contain the portion of the specified `com.aspose.imaging.Region` that does not intersect with this `com.aspose.imaging.region`. |
| [translate(float dx, float dy)](#translate-float-float-) | Offsets the coordinates of this `com.aspose.imaging.Region` by the specified amount. |
| [translate(int dx, int dy)](#translate-int-int-) | Offsets the coordinates of this `com.aspose.imaging.Region` by the specified amount. |
| [transform(Matrix matrix)](#transform-com.aspose.imaging.Matrix-) | Transforms this `com.aspose.imaging.Region` by the specified `com.aspose.imaging.matrix`. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.imaging.Graphics-) | Tests whether this `com.aspose.imaging.Region` has an empty interior on the specified drawing surface. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.imaging.Graphics-) | Tests whether this `com.aspose.imaging.Region` has an infinite interior on the specified drawing surface. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-) | Tests whether the specified `com.aspose.imaging.Region` is identical to this `com.aspose.imaging.Region` on the specified drawing surface. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Tests whether the specified point is contained within this `com.aspose.imaging.region`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Tests whether the specified `com.aspose.imaging.PointF` structure is contained within this `com.aspose.imaging.region`. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Tests whether the specified point is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Tests whether the specified `com.aspose.imaging.PointF` structure is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Tests whether any portion of the specified rectangle is contained within this `com.aspose.imaging.region`. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.imaging.RectangleF-) | Tests whether any portion of the specified `com.aspose.imaging.RectangleF` structure is contained within this `com.aspose.imaging.region`. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.imaging.Graphics-) | Tests whether any portion of the specified rectangle is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-) | Tests whether any portion of the specified `com.aspose.imaging.RectangleF` structure is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Tests whether the specified point is contained within this `com.aspose.imaging.Region` object when drawn using the specified `com.aspose.imaging.Graphics` object. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Tests whether the specified `com.aspose.imaging.Point` structure is contained within this `com.aspose.imaging.region`. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Tests whether the specified `com.aspose.imaging.Point` structure is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Tests whether any portion of the specified rectangle is contained within this `com.aspose.imaging.region`. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.imaging.Rectangle-) | Tests whether any portion of the specified `com.aspose.imaging.Rectangle` structure is contained within this `com.aspose.imaging.region`. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.imaging.Graphics-) | Tests whether any portion of the specified rectangle is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-) | Tests whether any portion of the specified `com.aspose.imaging.Rectangle` structure is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`. |
| [equals(Object o)](#equals-java.lang.Object-) | Check if objects are equal. |
| [hashCode()](#hashCode--) | Get hash code of the current object. |
### Region() {#Region--}
```
public Region()
```


Initializes a new Region.

### Region(RectangleF rect) {#Region-com.aspose.imaging.RectangleF-}
```
public Region(RectangleF rect)
```


Initializes a new `T:Aspose.Imaging.Region` from the specified `T:Aspose.Imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | A `T:Aspose.Imaging.RectangleF` structure that defines the interior of the new `T:Aspose.Imaging.Region`. |

### Region(Rectangle rect) {#Region-com.aspose.imaging.Rectangle-}
```
public Region(Rectangle rect)
```


Initializes a new `T:Aspose.Imaging.Region` from the specified `T:Aspose.Imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | A `T:Aspose.Imaging.Rectangle` structure that defines the interior of the new `T:Aspose.Imaging.Region`. |

### Region(GraphicsPath path) {#Region-com.aspose.imaging.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initializes a new `T:Aspose.Imaging.Region` with the specified `T:Aspose.Imaging.GraphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | A `T:Aspose.Imaging.GraphicsPath` that defines the new `T:Aspose.Imaging.Region`. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Creates an exact deep copy of this `com.aspose.imaging.region`.

**Returns:**
[Region](../../com.aspose.imaging/region) - The `com.aspose.imaging.Region` that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initializes this `com.aspose.imaging.Region` object to an infinite interior.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initializes this `com.aspose.imaging.Region` to an empty interior.

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Updates this `com.aspose.imaging.Region` to the intersection of itself with the specified `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` structure to intersect with this `com.aspose.imaging.region`. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Updates this `com.aspose.imaging.Region` to the intersection of itself with the specified `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` structure to intersect with this `com.aspose.imaging.region`. |

### intersect(GraphicsPath path) {#intersect-com.aspose.imaging.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Updates this `com.aspose.imaging.Region` to the intersection of itself with the specified `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The `com.aspose.imaging.GraphicsPath` to intersect with this `com.aspose.imaging.region`. |

### intersect(Region region) {#intersect-com.aspose.imaging.Region-}
```
public void intersect(Region region)
```


Updates this `com.aspose.imaging.Region` to the intersection of itself with the specified `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | The `com.aspose.imaging.Region` to intersect with this `com.aspose.imaging.region`. |

### union(RectangleF rect) {#union-com.aspose.imaging.RectangleF-}
```
public void union(RectangleF rect)
```


Updates this `com.aspose.imaging.Region` to the union of itself and the specified `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` structure to unite with this `com.aspose.imaging.region`. |

### union(Rectangle rect) {#union-com.aspose.imaging.Rectangle-}
```
public void union(Rectangle rect)
```


Updates this `com.aspose.imaging.Region` to the union of itself and the specified `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` structure to unite with this `com.aspose.imaging.region`. |

### union(GraphicsPath path) {#union-com.aspose.imaging.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Updates this `com.aspose.imaging.Region` to the union of itself and the specified `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The `com.aspose.imaging.GraphicsPath` to unite with this `com.aspose.imaging.region`. |

### union(Region region) {#union-com.aspose.imaging.Region-}
```
public void union(Region region)
```


Updates this `com.aspose.imaging.Region` to the union of itself and the specified `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | The `com.aspose.imaging.Region` to unite with this `com.aspose.imaging.region`. |

### xor(RectangleF rect) {#xor-com.aspose.imaging.RectangleF-}
```
public void xor(RectangleF rect)
```


Updates this `com.aspose.imaging.Region` to the union minus the intersection of itself with the specified `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` structure to xor with this `com.aspose.imaging.region`. |

### xor(Rectangle rect) {#xor-com.aspose.imaging.Rectangle-}
```
public void xor(Rectangle rect)
```


Updates this `com.aspose.imaging.Region` to the union minus the intersection of itself with the specified `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` structure to xor with this `com.aspose.imaging.region`. |

### xor(GraphicsPath path) {#xor-com.aspose.imaging.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Updates this `com.aspose.imaging.Region` to the union minus the intersection of itself with the specified `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The `com.aspose.imaging.GraphicsPath` to xor with this `com.aspose.imaging.region`. |

### xor(Region region) {#xor-com.aspose.imaging.Region-}
```
public void xor(Region region)
```


Updates this `com.aspose.imaging.Region` to the union minus the intersection of itself with the specified `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | The `com.aspose.imaging.Region` to xor with this `com.aspose.imaging.region`. |

### exclude(RectangleF rect) {#exclude-com.aspose.imaging.RectangleF-}
```
public void exclude(RectangleF rect)
```


Updates this `com.aspose.imaging.Region` to contain only the portion of its interior that does not intersect with the specified `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` structure to exclude from this `com.aspose.imaging.region`. |

### exclude(Rectangle rect) {#exclude-com.aspose.imaging.Rectangle-}
```
public void exclude(Rectangle rect)
```


Updates this `com.aspose.imaging.Region` to contain only the portion of its interior that does not intersect with the specified `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` structure to exclude from this `com.aspose.imaging.region`. |

### exclude(GraphicsPath path) {#exclude-com.aspose.imaging.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Updates this `com.aspose.imaging.Region` to contain only the portion of its interior that does not intersect with the specified `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The `com.aspose.imaging.GraphicsPath` to exclude from this `com.aspose.imaging.region`. |

### exclude(Region region) {#exclude-com.aspose.imaging.Region-}
```
public void exclude(Region region)
```


Updates this `com.aspose.imaging.Region` to contain only the portion of its interior that does not intersect with the specified `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | The `com.aspose.imaging.Region` to exclude from this `com.aspose.imaging.region`. |

### complement(RectangleF rect) {#complement-com.aspose.imaging.RectangleF-}
```
public void complement(RectangleF rect)
```


Updates this `com.aspose.imaging.Region` to contain the portion of the specified `com.aspose.imaging.RectangleF` structure that does not intersect with this `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` structure to complement this `com.aspose.imaging.region`. |

### complement(Rectangle rect) {#complement-com.aspose.imaging.Rectangle-}
```
public void complement(Rectangle rect)
```


Updates this `com.aspose.imaging.Region` to contain the portion of the specified `com.aspose.imaging.Rectangle` structure that does not intersect with this `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` structure to complement this `com.aspose.imaging.region`. |

### complement(GraphicsPath path) {#complement-com.aspose.imaging.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Updates this `com.aspose.imaging.Region` to contain the portion of the specified `com.aspose.imaging.GraphicsPath` that does not intersect with this `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The `com.aspose.imaging.GraphicsPath` to complement this `com.aspose.imaging.region`. |

### complement(Region region) {#complement-com.aspose.imaging.Region-}
```
public void complement(Region region)
```


Updates this `com.aspose.imaging.Region` to contain the portion of the specified `com.aspose.imaging.Region` that does not intersect with this `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | The `com.aspose.imaging.Region` object to complement this `com.aspose.imaging.Region` object. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Offsets the coordinates of this `com.aspose.imaging.Region` by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | float | The amount to offset this `com.aspose.imaging.Region` horizontally. |
| dy | float | The amount to offset this `com.aspose.imaging.Region` vertically. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Offsets the coordinates of this `com.aspose.imaging.Region` by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | int | The amount to offset this `com.aspose.imaging.Region` horizontally. |
| dy | int | The amount to offset this `com.aspose.imaging.Region` vertically. |

### transform(Matrix matrix) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix matrix)
```


Transforms this `com.aspose.imaging.Region` by the specified `com.aspose.imaging.matrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The `com.aspose.imaging.Matrix` by which to transform this `com.aspose.imaging.region`. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.imaging.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Tests whether this `com.aspose.imaging.Region` has an empty interior on the specified drawing surface.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | A `com.aspose.imaging.Graphics` that represents a drawing surface. |

**Returns:**
boolean - true if the interior of this `com.aspose.imaging.Region` is empty when the transformation associated with `g` is applied; otherwise, false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.imaging.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Tests whether this `com.aspose.imaging.Region` has an infinite interior on the specified drawing surface.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | A `com.aspose.imaging.Graphics` that represents a drawing surface. |

**Returns:**
boolean - true if the interior of this `com.aspose.imaging.Region` is infinite when the transformation associated with `g` is applied; otherwise, false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Tests whether the specified `com.aspose.imaging.Region` is identical to this `com.aspose.imaging.Region` on the specified drawing surface.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | The `com.aspose.imaging.Region` to test. |
| g | [Graphics](../../com.aspose.imaging/graphics) | A `com.aspose.imaging.Graphics` that represents a drawing surface. |

**Returns:**
boolean - True if the interior of region is identical to the interior of this region when the transformation associated with the `g` parameter is applied; otherwise, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Tests whether the specified point is contained within this `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns:**
boolean - True when the specified point is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Tests whether the specified `com.aspose.imaging.PointF` structure is contained within this `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `com.aspose.imaging.PointF` structure to test. |

**Returns:**
boolean - true when `point` is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Tests whether the specified point is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| g | [Graphics](../../com.aspose.imaging/graphics) | A `com.aspose.imaging.Graphics` that represents a graphics context. |

**Returns:**
boolean - True when the specified point is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Tests whether the specified `com.aspose.imaging.PointF` structure is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `com.aspose.imaging.PointF` structure to test. |
| g | [Graphics](../../com.aspose.imaging/graphics) | A `com.aspose.imaging.Graphics` that represents a graphics context. |

**Returns:**
boolean - true when `point` is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Tests whether any portion of the specified rectangle is contained within this `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | float | The width of the rectangle to test. |
| height | float | The height of the rectangle to test. |

**Returns:**
boolean - true when any portion of the specified rectangle is contained within this `com.aspose.imaging.Region` object; otherwise, false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.imaging.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Tests whether any portion of the specified `com.aspose.imaging.RectangleF` structure is contained within this `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` structure to test. |

**Returns:**
boolean - true when any portion of `rect` is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Tests whether any portion of the specified rectangle is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | float | The width of the rectangle to test. |
| height | float | The height of the rectangle to test. |
| g | [Graphics](../../com.aspose.imaging/graphics) | A `com.aspose.imaging.Graphics` that represents a graphics context. |

**Returns:**
boolean - true when any portion of the specified rectangle is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Tests whether any portion of the specified `com.aspose.imaging.RectangleF` structure is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` structure to test. |
| g | [Graphics](../../com.aspose.imaging/graphics) | A `com.aspose.imaging.Graphics` that represents a graphics context. |

**Returns:**
boolean - true when `rect` is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Tests whether the specified point is contained within this `com.aspose.imaging.Region` object when drawn using the specified `com.aspose.imaging.Graphics` object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| g | [Graphics](../../com.aspose.imaging/graphics) | A `com.aspose.imaging.Graphics` that represents a graphics context. |

**Returns:**
boolean - true when the specified point is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Tests whether the specified `com.aspose.imaging.Point` structure is contained within this `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | The `com.aspose.imaging.Point` structure to test. |

**Returns:**
boolean - true when `point` is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Tests whether the specified `com.aspose.imaging.Point` structure is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | The `com.aspose.imaging.Point` structure to test. |
| g | [Graphics](../../com.aspose.imaging/graphics) | A `com.aspose.imaging.Graphics` that represents a graphics context. |

**Returns:**
boolean - true when `point` is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Tests whether any portion of the specified rectangle is contained within this `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | int | The width of the rectangle to test. |
| height | int | The height of the rectangle to test. |

**Returns:**
boolean - true when any portion of the specified rectangle is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.imaging.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Tests whether any portion of the specified `com.aspose.imaging.Rectangle` structure is contained within this `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` structure to test. |

**Returns:**
boolean - This method returns true when any portion of `rect` is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Tests whether any portion of the specified rectangle is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | int | The width of the rectangle to test. |
| height | int | The height of the rectangle to test. |
| g | [Graphics](../../com.aspose.imaging/graphics) | A `com.aspose.imaging.Graphics` that represents a graphics context. |

**Returns:**
boolean - true when any portion of the specified rectangle is contained within this `com.aspose.imaging.Region`; otherwise, false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Tests whether any portion of the specified `com.aspose.imaging.Rectangle` structure is contained within this `com.aspose.imaging.Region` when drawn using the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` structure to test. |
| g | [Graphics](../../com.aspose.imaging/graphics) | A `com.aspose.imaging.Graphics` that represents a graphics context. |

**Returns:**
boolean - true when any portion of the `rect` is contained within this `com.aspose.imaging.Region`; otherwise, false.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Check if objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | The other object. |

**Returns:**
boolean - The equality comparison result.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Get hash code of the current object.

**Returns:**
int - The hash code.
