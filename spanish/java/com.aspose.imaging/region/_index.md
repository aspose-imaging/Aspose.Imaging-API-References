---
title: "Region"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Describe el interior de una forma gráfica compuesta de rectángulos y rutas."
type: docs
weight: 95
url: /es/java/com.aspose.imaging/region/
---
**Inheritance:**
java.lang.Object
```
public final class Region
```

Describe el interior de una forma gráfica compuesta por rectángulos y rutas. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Region()](#Region--) | Inicializa una nueva Region. |
| [Region(RectangleF rect)](#Region-com.aspose.imaging.RectangleF-) | Inicializa una nueva `T:Aspose.Imaging.Region` a partir de la estructura `T:Aspose.Imaging.RectangleF` especificada. |
| [Region(Rectangle rect)](#Region-com.aspose.imaging.Rectangle-) | Inicializa una nueva `T:Aspose.Imaging.Region` a partir de la estructura `T:Aspose.Imaging.Rectangle` especificada. |
| [Region(GraphicsPath path)](#Region-com.aspose.imaging.GraphicsPath-) | Inicializa una nueva `T:Aspose.Imaging.Region` con el `T:Aspose.Imaging.GraphicsPath` especificado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profunda exacta de este `com.aspose.imaging.region`. |
| [makeInfinite()](#makeInfinite--) | Inicializa este objeto `com.aspose.imaging.Region` a un interior infinito. |
| [makeEmpty()](#makeEmpty--) | Inicializa este `com.aspose.imaging.Region` a un interior vacío. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Actualiza este `com.aspose.imaging.Region` a la intersección de sí mismo con la estructura `com.aspose.imaging.RectangleF` especificada. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Actualiza este `com.aspose.imaging.Region` a la intersección de sí mismo con la estructura `com.aspose.imaging.Rectangle` especificada. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.imaging.GraphicsPath-) | Actualiza este `com.aspose.imaging.Region` a la intersección de sí mismo con el `com.aspose.imaging.graphicsPath` especificado. |
| [intersect(Region region)](#intersect-com.aspose.imaging.Region-) | Actualiza este `com.aspose.imaging.Region` a la intersección de sí mismo con el `com.aspose.imaging.region` especificado. |
| [union(RectangleF rect)](#union-com.aspose.imaging.RectangleF-) | Actualiza este `com.aspose.imaging.Region` a la unión de sí mismo y la estructura `com.aspose.imaging.RectangleF` especificada. |
| [union(Rectangle rect)](#union-com.aspose.imaging.Rectangle-) | Actualiza este `com.aspose.imaging.Region` a la unión de sí mismo y la estructura `com.aspose.imaging.Rectangle` especificada. |
| [union(GraphicsPath path)](#union-com.aspose.imaging.GraphicsPath-) | Actualiza este `com.aspose.imaging.Region` a la unión de sí mismo y el `com.aspose.imaging.graphicsPath` especificado. |
| [union(Region region)](#union-com.aspose.imaging.Region-) | Actualiza este `com.aspose.imaging.Region` a la unión de sí mismo y el `com.aspose.imaging.region` especificado. |
| [xor(RectangleF rect)](#xor-com.aspose.imaging.RectangleF-) | Actualiza este `com.aspose.imaging.Region` a la unión menos la intersección de sí mismo con la estructura `com.aspose.imaging.RectangleF` especificada. |
| [xor(Rectangle rect)](#xor-com.aspose.imaging.Rectangle-) | Actualiza este `com.aspose.imaging.Region` a la unión menos la intersección de sí mismo con la estructura `com.aspose.imaging.Rectangle` especificada. |
| [xor(GraphicsPath path)](#xor-com.aspose.imaging.GraphicsPath-) | Actualiza este `com.aspose.imaging.Region` a la unión menos la intersección de sí mismo con el `com.aspose.imaging.graphicsPath` especificado. |
| [xor(Region region)](#xor-com.aspose.imaging.Region-) | Actualiza este `com.aspose.imaging.Region` a la unión menos la intersección de sí mismo con el `com.aspose.imaging.region` especificado. |
| [exclude(RectangleF rect)](#exclude-com.aspose.imaging.RectangleF-) | Actualiza este `com.aspose.imaging.Region` para que contenga solo la parte de su interior que no intersecta con la estructura `com.aspose.imaging.RectangleF` especificada. |
| [exclude(Rectangle rect)](#exclude-com.aspose.imaging.Rectangle-) | Actualiza este `com.aspose.imaging.Region` para que contenga solo la parte de su interior que no intersecta con la estructura `com.aspose.imaging.Rectangle` especificada. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.imaging.GraphicsPath-) | Actualiza este `com.aspose.imaging.Region` para que contenga solo la parte de su interior que no intersecta con el `com.aspose.imaging.graphicsPath` especificado. |
| [exclude(Region region)](#exclude-com.aspose.imaging.Region-) | Actualiza este `com.aspose.imaging.Region` para que contenga solo la parte de su interior que no intersecta con el `com.aspose.imaging.region` especificado. |
| [complement(RectangleF rect)](#complement-com.aspose.imaging.RectangleF-) | Actualiza este `com.aspose.imaging.Region` para que contenga la parte de la estructura `com.aspose.imaging.RectangleF` especificada que no intersecta con este `com.aspose.imaging.region`. |
| [complement(Rectangle rect)](#complement-com.aspose.imaging.Rectangle-) | Actualiza este `com.aspose.imaging.Region` para que contenga la parte de la estructura `com.aspose.imaging.Rectangle` especificada que no intersecta con este `com.aspose.imaging.region`. |
| [complement(GraphicsPath path)](#complement-com.aspose.imaging.GraphicsPath-) | Actualiza este `com.aspose.imaging.Region` para que contenga la parte del `com.aspose.imaging.GraphicsPath` especificado que no intersecta con este `com.aspose.imaging.region`. |
| [complement(Region region)](#complement-com.aspose.imaging.Region-) | Actualiza este `com.aspose.imaging.Region` para que contenga la parte del `com.aspose.imaging.Region` especificado que no intersecta con este `com.aspose.imaging.region`. |
| [translate(float dx, float dy)](#translate-float-float-) | Desplaza las coordenadas de este `com.aspose.imaging.Region` por la cantidad especificada. |
| [translate(int dx, int dy)](#translate-int-int-) | Desplaza las coordenadas de este `com.aspose.imaging.Region` por la cantidad especificada. |
| [transform(Matrix matrix)](#transform-com.aspose.imaging.Matrix-) | Transforma este `com.aspose.imaging.Region` mediante la `com.aspose.imaging.matrix` especificada. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.imaging.Graphics-) | Comprueba si este `com.aspose.imaging.Region` tiene un interior vacío en la superficie de dibujo especificada. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.imaging.Graphics-) | Comprueba si este `com.aspose.imaging.Region` tiene un interior infinito en la superficie de dibujo especificada. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-) | Comprueba si el `com.aspose.imaging.Region` especificado es idéntico a este `com.aspose.imaging.Region` en la superficie de dibujo especificada. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Comprueba si el punto especificado está contenido dentro de este `com.aspose.imaging.region`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Comprueba si la estructura `com.aspose.imaging.PointF` especificada está contenida dentro de este `com.aspose.imaging.region`. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Comprueba si el punto especificado está contenido dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Comprueba si la estructura `com.aspose.imaging.PointF` especificada está contenida dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este `com.aspose.imaging.region`. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.imaging.RectangleF-) | Comprueba si alguna parte de la estructura `com.aspose.imaging.RectangleF` especificada está contenida dentro de este `com.aspose.imaging.region`. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.imaging.Graphics-) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-) | Comprueba si alguna parte de la estructura `com.aspose.imaging.RectangleF` especificada está contenida dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Comprueba si el punto especificado está contenido dentro de este objeto `com.aspose.imaging.Region` cuando se dibuja usando el objeto `com.aspose.imaging.Graphics` especificado. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Comprueba si la estructura `com.aspose.imaging.Point` especificada está contenida dentro de este `com.aspose.imaging.region`. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Comprueba si la estructura `com.aspose.imaging.Point` especificada está contenida dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este `com.aspose.imaging.region`. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.imaging.Rectangle-) | Comprueba si alguna parte de la estructura `com.aspose.imaging.Rectangle` especificada está contenida dentro de este `com.aspose.imaging.region`. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.imaging.Graphics-) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-) | Comprueba si alguna parte de la estructura `com.aspose.imaging.Rectangle` especificada está contenida dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado. |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si los objetos son iguales. |
| [hashCode()](#hashCode--) | Obtiene el código hash del objeto actual. |
### Region() {#Region--}
```
public Region()
```


Inicializa una nueva Region.

### Region(RectangleF rect) {#Region-com.aspose.imaging.RectangleF-}
```
public Region(RectangleF rect)
```


Inicializa una nueva `T:Aspose.Imaging.Region` a partir de la estructura `T:Aspose.Imaging.RectangleF` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Una estructura `T:Aspose.Imaging.RectangleF` que define el interior del nuevo `T:Aspose.Imaging.Region`. |

### Region(Rectangle rect) {#Region-com.aspose.imaging.Rectangle-}
```
public Region(Rectangle rect)
```


Inicializa una nueva `T:Aspose.Imaging.Region` a partir de la estructura `T:Aspose.Imaging.Rectangle` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Una estructura `T:Aspose.Imaging.Rectangle` que define el interior del nuevo `T:Aspose.Imaging.Region`. |

### Region(GraphicsPath path) {#Region-com.aspose.imaging.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Inicializa una nueva `T:Aspose.Imaging.Region` con el `T:Aspose.Imaging.GraphicsPath` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un `T:Aspose.Imaging.GraphicsPath` que define el nuevo `T:Aspose.Imaging.Region`. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Crea una copia profunda exacta de este `com.aspose.imaging.region`.

**Returns:**
[Region](../../com.aspose.imaging/region) - The `com.aspose.imaging.Region` that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Inicializa este objeto `com.aspose.imaging.Region` a un interior infinito.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Inicializa este `com.aspose.imaging.Region` a un interior vacío.

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Actualiza este `com.aspose.imaging.Region` a la intersección de sí mismo con la estructura `com.aspose.imaging.RectangleF` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La estructura `com.aspose.imaging.RectangleF` para intersectar con este `com.aspose.imaging.region`. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Actualiza este `com.aspose.imaging.Region` a la intersección de sí mismo con la estructura `com.aspose.imaging.Rectangle` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La estructura `com.aspose.imaging.Rectangle` para intersectar con este `com.aspose.imaging.region`. |

### intersect(GraphicsPath path) {#intersect-com.aspose.imaging.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Actualiza este `com.aspose.imaging.Region` a la intersección de sí mismo con el `com.aspose.imaging.graphicsPath` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | El `com.aspose.imaging.GraphicsPath` para intersectar con este `com.aspose.imaging.region`. |

### intersect(Region region) {#intersect-com.aspose.imaging.Region-}
```
public void intersect(Region region)
```


Actualiza este `com.aspose.imaging.Region` a la intersección de sí mismo con el `com.aspose.imaging.region` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | El `com.aspose.imaging.Region` para intersectar con este `com.aspose.imaging.region`. |

### union(RectangleF rect) {#union-com.aspose.imaging.RectangleF-}
```
public void union(RectangleF rect)
```


Actualiza este `com.aspose.imaging.Region` a la unión de sí mismo y la estructura `com.aspose.imaging.RectangleF` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La estructura `com.aspose.imaging.RectangleF` para unir con este `com.aspose.imaging.region`. |

### union(Rectangle rect) {#union-com.aspose.imaging.Rectangle-}
```
public void union(Rectangle rect)
```


Actualiza este `com.aspose.imaging.Region` a la unión de sí mismo y la estructura `com.aspose.imaging.Rectangle` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La estructura `com.aspose.imaging.Rectangle` para unir con este `com.aspose.imaging.region`. |

### union(GraphicsPath path) {#union-com.aspose.imaging.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Actualiza este `com.aspose.imaging.Region` a la unión de sí mismo y el `com.aspose.imaging.graphicsPath` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | El `com.aspose.imaging.GraphicsPath` para unir con este `com.aspose.imaging.region`. |

### union(Region region) {#union-com.aspose.imaging.Region-}
```
public void union(Region region)
```


Actualiza este `com.aspose.imaging.Region` a la unión de sí mismo y el `com.aspose.imaging.region` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | El `com.aspose.imaging.Region` para unir con este `com.aspose.imaging.region`. |

### xor(RectangleF rect) {#xor-com.aspose.imaging.RectangleF-}
```
public void xor(RectangleF rect)
```


Actualiza este `com.aspose.imaging.Region` a la unión menos la intersección de sí mismo con la estructura `com.aspose.imaging.RectangleF` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La estructura `com.aspose.imaging.RectangleF` para xor con este `com.aspose.imaging.region`. |

### xor(Rectangle rect) {#xor-com.aspose.imaging.Rectangle-}
```
public void xor(Rectangle rect)
```


Actualiza este `com.aspose.imaging.Region` a la unión menos la intersección de sí mismo con la estructura `com.aspose.imaging.Rectangle` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La estructura `com.aspose.imaging.Rectangle` para xor con este `com.aspose.imaging.region`. |

### xor(GraphicsPath path) {#xor-com.aspose.imaging.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Actualiza este `com.aspose.imaging.Region` a la unión menos la intersección de sí mismo con el `com.aspose.imaging.graphicsPath` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | El `com.aspose.imaging.GraphicsPath` para xor con este `com.aspose.imaging.region`. |

### xor(Region region) {#xor-com.aspose.imaging.Region-}
```
public void xor(Region region)
```


Actualiza este `com.aspose.imaging.Region` a la unión menos la intersección de sí mismo con el `com.aspose.imaging.region` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | El `com.aspose.imaging.Region` para xor con este `com.aspose.imaging.region`. |

### exclude(RectangleF rect) {#exclude-com.aspose.imaging.RectangleF-}
```
public void exclude(RectangleF rect)
```


Actualiza este `com.aspose.imaging.Region` para que contenga solo la parte de su interior que no intersecta con la estructura `com.aspose.imaging.RectangleF` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La estructura `com.aspose.imaging.RectangleF` para excluir de este `com.aspose.imaging.region`. |

### exclude(Rectangle rect) {#exclude-com.aspose.imaging.Rectangle-}
```
public void exclude(Rectangle rect)
```


Actualiza este `com.aspose.imaging.Region` para que contenga solo la parte de su interior que no intersecta con la estructura `com.aspose.imaging.Rectangle` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La estructura `com.aspose.imaging.Rectangle` para excluir de este `com.aspose.imaging.region`. |

### exclude(GraphicsPath path) {#exclude-com.aspose.imaging.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Actualiza este `com.aspose.imaging.Region` para que contenga solo la parte de su interior que no intersecta con el `com.aspose.imaging.graphicsPath` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | El `com.aspose.imaging.GraphicsPath` para excluir de este `com.aspose.imaging.region`. |

### exclude(Region region) {#exclude-com.aspose.imaging.Region-}
```
public void exclude(Region region)
```


Actualiza este `com.aspose.imaging.Region` para que contenga solo la parte de su interior que no intersecta con el `com.aspose.imaging.region` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | El `com.aspose.imaging.Region` para excluir de este `com.aspose.imaging.region`. |

### complement(RectangleF rect) {#complement-com.aspose.imaging.RectangleF-}
```
public void complement(RectangleF rect)
```


Actualiza este `com.aspose.imaging.Region` para que contenga la parte de la estructura `com.aspose.imaging.RectangleF` especificada que no intersecta con este `com.aspose.imaging.region`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La estructura `com.aspose.imaging.RectangleF` para complementar este `com.aspose.imaging.region`. |

### complement(Rectangle rect) {#complement-com.aspose.imaging.Rectangle-}
```
public void complement(Rectangle rect)
```


Actualiza este `com.aspose.imaging.Region` para que contenga la parte de la estructura `com.aspose.imaging.Rectangle` especificada que no intersecta con este `com.aspose.imaging.region`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La estructura `com.aspose.imaging.Rectangle` para complementar este `com.aspose.imaging.region`. |

### complement(GraphicsPath path) {#complement-com.aspose.imaging.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Actualiza este `com.aspose.imaging.Region` para que contenga la parte del `com.aspose.imaging.GraphicsPath` especificado que no intersecta con este `com.aspose.imaging.region`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | El `com.aspose.imaging.GraphicsPath` para complementar este `com.aspose.imaging.region`. |

### complement(Region region) {#complement-com.aspose.imaging.Region-}
```
public void complement(Region region)
```


Actualiza este `com.aspose.imaging.Region` para que contenga la parte del `com.aspose.imaging.Region` especificado que no intersecta con este `com.aspose.imaging.region`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | El objeto `com.aspose.imaging.Region` para complementar este objeto `com.aspose.imaging.Region`. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Desplaza las coordenadas de este `com.aspose.imaging.Region` por la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | La cantidad para desplazar horizontalmente este `com.aspose.imaging.Region`. |
| dy | float | La cantidad para desplazar verticalmente este `com.aspose.imaging.Region`. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Desplaza las coordenadas de este `com.aspose.imaging.Region` por la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | int | La cantidad para desplazar horizontalmente este `com.aspose.imaging.Region`. |
| dy | int | La cantidad para desplazar verticalmente este `com.aspose.imaging.Region`. |

### transform(Matrix matrix) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix matrix)
```


Transforma este `com.aspose.imaging.Region` mediante la `com.aspose.imaging.matrix` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La `com.aspose.imaging.Matrix` por la cual transformar este `com.aspose.imaging.region`. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.imaging.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Comprueba si este `com.aspose.imaging.Region` tiene un interior vacío en la superficie de dibujo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` que representa una superficie de dibujo. |

**Returns:**
boolean - verdadero si el interior de este `com.aspose.imaging.Region` está vacío cuando se aplica la transformación asociada con `g`; de lo contrario, falso.
### isInfinite(Graphics g) {#isInfinite-com.aspose.imaging.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Comprueba si este `com.aspose.imaging.Region` tiene un interior infinito en la superficie de dibujo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` que representa una superficie de dibujo. |

**Returns:**
boolean - verdadero si el interior de este `com.aspose.imaging.Region` es infinito cuando se aplica la transformación asociada con `g`; de lo contrario, falso.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Comprueba si el `com.aspose.imaging.Region` especificado es idéntico a este `com.aspose.imaging.Region` en la superficie de dibujo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | El `com.aspose.imaging.Region` a probar. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` que representa una superficie de dibujo. |

**Returns:**
boolean - Verdadero si el interior de la región es idéntico al interior de esta región cuando se aplica la transformación asociada con el parámetro `g`; de lo contrario, falso.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Comprueba si el punto especificado está contenido dentro de este `com.aspose.imaging.region`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns:**
boolean - Verdadero cuando el punto especificado está contenido dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Comprueba si la estructura `com.aspose.imaging.PointF` especificada está contenida dentro de este `com.aspose.imaging.region`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | La estructura `com.aspose.imaging.PointF` a probar. |

**Returns:**
boolean - verdadero cuando `point` está contenido dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Comprueba si el punto especificado está contenido dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` que representa un contexto gráfico. |

**Returns:**
boolean - Verdadero cuando el punto especificado está contenido dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Comprueba si la estructura `com.aspose.imaging.PointF` especificada está contenida dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | La estructura `com.aspose.imaging.PointF` a probar. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando `point` está contenido dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Comprueba si alguna parte del rectángulo especificado está contenida dentro de este `com.aspose.imaging.region`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | float | El ancho del rectángulo a probar. |
| height | float | La altura del rectángulo a probar. |

**Returns:**
boolean - verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este objeto `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(RectangleF rect) {#isVisible-com.aspose.imaging.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Comprueba si alguna parte de la estructura `com.aspose.imaging.RectangleF` especificada está contenida dentro de este `com.aspose.imaging.region`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La estructura `com.aspose.imaging.RectangleF` a probar. |

**Returns:**
boolean - verdadero cuando cualquier parte de `rect` está contenida dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Comprueba si alguna parte del rectángulo especificado está contenida dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | float | El ancho del rectángulo a probar. |
| height | float | La altura del rectángulo a probar. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Comprueba si alguna parte de la estructura `com.aspose.imaging.RectangleF` especificada está contenida dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | La estructura `com.aspose.imaging.RectangleF` a probar. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando `rect` está contenido dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Comprueba si el punto especificado está contenido dentro de este objeto `com.aspose.imaging.Region` cuando se dibuja usando el objeto `com.aspose.imaging.Graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando el punto especificado está contenido dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Comprueba si la estructura `com.aspose.imaging.Point` especificada está contenida dentro de este `com.aspose.imaging.region`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | La estructura `com.aspose.imaging.Point` a probar. |

**Returns:**
boolean - verdadero cuando `point` está contenido dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Comprueba si la estructura `com.aspose.imaging.Point` especificada está contenida dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | La estructura `com.aspose.imaging.Point` a probar. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando `point` está contenido dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Comprueba si alguna parte del rectángulo especificado está contenida dentro de este `com.aspose.imaging.region`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | int | El ancho del rectángulo a probar. |
| height | int | La altura del rectángulo a probar. |

**Returns:**
boolean - verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(Rectangle rect) {#isVisible-com.aspose.imaging.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Comprueba si alguna parte de la estructura `com.aspose.imaging.Rectangle` especificada está contenida dentro de este `com.aspose.imaging.region`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La estructura `com.aspose.imaging.Rectangle` a probar. |

**Returns:**
boolean - Este método devuelve verdadero cuando cualquier parte de `rect` está contenida dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Comprueba si alguna parte del rectángulo especificado está contenida dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | int | El ancho del rectángulo a probar. |
| height | int | La altura del rectángulo a probar. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Comprueba si alguna parte de la estructura `com.aspose.imaging.Rectangle` especificada está contenida dentro de este `com.aspose.imaging.Region` cuando se dibuja usando el `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La estructura `com.aspose.imaging.Rectangle` a probar. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Un `com.aspose.imaging.Graphics` que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando cualquier parte del `rect` está contenida dentro de este `com.aspose.imaging.Region`; de lo contrario, falso.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Comprueba si los objetos son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | java.lang.Object | El otro objeto. |

**Returns:**
boolean - El resultado de la comparación de igualdad.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash del objeto actual.

**Returns:**
int - El código hash.
