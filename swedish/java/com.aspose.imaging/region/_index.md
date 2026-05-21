---
title: "Region"
second_title: "Aspose.Imaging för Java API-referens"
description: "Beskriver insidan av en grafisk form bestående av rektanglar och banor."
type: docs
weight: 95
url: /sv/java/com.aspose.imaging/region/
---
**Inheritance:**
java.lang.Object
```
public final class Region
```

Beskriver insidan av en grafisk form bestående av rektanglar och banor. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Region()](#Region--) | Initierar en ny Region. |
| [Region(RectangleF rect)](#Region-com.aspose.imaging.RectangleF-) | Initierar en ny `T:Aspose.Imaging.Region` från den angivna `T:Aspose.Imaging.RectangleF`‑strukturen. |
| [Region(Rectangle rect)](#Region-com.aspose.imaging.Rectangle-) | Initierar en ny `T:Aspose.Imaging.Region` från den angivna `T:Aspose.Imaging.Rectangle`‑strukturen. |
| [Region(GraphicsPath path)](#Region-com.aspose.imaging.GraphicsPath-) | Initierar en ny `T:Aspose.Imaging.Region` med den angivna `T:Aspose.Imaging.GraphicsPath`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en exakt djup kopia av detta `com.aspose.imaging.region`. |
| [makeInfinite()](#makeInfinite--) | Initierar detta `com.aspose.imaging.Region`‑objekt till en oändlig insida. |
| [makeEmpty()](#makeEmpty--) | Initierar detta `com.aspose.imaging.Region` till en tom insida. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Uppdaterar detta `com.aspose.imaging.Region` till snittet av sig själv och den angivna `com.aspose.imaging.RectangleF`‑strukturen. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Uppdaterar detta `com.aspose.imaging.Region` till snittet av sig själv och den angivna `com.aspose.imaging.Rectangle`‑strukturen. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.imaging.GraphicsPath-) | Uppdaterar detta `com.aspose.imaging.Region` till snittet av sig själv och den angivna `com.aspose.imaging.graphicsPath`. |
| [intersect(Region region)](#intersect-com.aspose.imaging.Region-) | Uppdaterar detta `com.aspose.imaging.Region` till snittet av sig själv och den angivna `com.aspose.imaging.region`. |
| [union(RectangleF rect)](#union-com.aspose.imaging.RectangleF-) | Uppdaterar detta `com.aspose.imaging.Region` till unionen av sig själv och den angivna `com.aspose.imaging.RectangleF`‑strukturen. |
| [union(Rectangle rect)](#union-com.aspose.imaging.Rectangle-) | Uppdaterar detta `com.aspose.imaging.Region` till unionen av sig själv och den angivna `com.aspose.imaging.Rectangle`‑strukturen. |
| [union(GraphicsPath path)](#union-com.aspose.imaging.GraphicsPath-) | Uppdaterar detta `com.aspose.imaging.Region` till unionen av sig själv och den angivna `com.aspose.imaging.graphicsPath`. |
| [union(Region region)](#union-com.aspose.imaging.Region-) | Uppdaterar detta `com.aspose.imaging.Region` till unionen av sig själv och den angivna `com.aspose.imaging.region`. |
| [xor(RectangleF rect)](#xor-com.aspose.imaging.RectangleF-) | Uppdaterar detta `com.aspose.imaging.Region` till unionen minus snittet av sig själv och den angivna `com.aspose.imaging.RectangleF`‑strukturen. |
| [xor(Rectangle rect)](#xor-com.aspose.imaging.Rectangle-) | Uppdaterar detta `com.aspose.imaging.Region` till unionen minus skärningen av sig själv med den angivna `com.aspose.imaging.Rectangle`-strukturen. |
| [xor(GraphicsPath path)](#xor-com.aspose.imaging.GraphicsPath-) | Uppdaterar detta `com.aspose.imaging.Region` till unionen minus skärningen av sig själv med den angivna `com.aspose.imaging.graphicsPath`. |
| [xor(Region region)](#xor-com.aspose.imaging.Region-) | Uppdaterar detta `com.aspose.imaging.Region` till unionen minus skärningen av sig själv med den angivna `com.aspose.imaging.region`. |
| [exclude(RectangleF rect)](#exclude-com.aspose.imaging.RectangleF-) | Uppdaterar detta `com.aspose.imaging.Region` så att det endast innehåller den del av dess inre som inte skär med den angivna `com.aspose.imaging.RectangleF`-strukturen. |
| [exclude(Rectangle rect)](#exclude-com.aspose.imaging.Rectangle-) | Uppdaterar detta `com.aspose.imaging.Region` så att det endast innehåller den del av dess inre som inte skär med den angivna `com.aspose.imaging.Rectangle`-strukturen. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.imaging.GraphicsPath-) | Uppdaterar detta `com.aspose.imaging.Region` så att det endast innehåller den del av dess inre som inte skär med den angivna `com.aspose.imaging.graphicsPath`. |
| [exclude(Region region)](#exclude-com.aspose.imaging.Region-) | Uppdaterar detta `com.aspose.imaging.Region` så att det endast innehåller den del av dess inre som inte skär med den angivna `com.aspose.imaging.region`. |
| [complement(RectangleF rect)](#complement-com.aspose.imaging.RectangleF-) | Uppdaterar detta `com.aspose.imaging.Region` så att det innehåller den del av den angivna `com.aspose.imaging.RectangleF`-strukturen som inte skär med detta `com.aspose.imaging.region`. |
| [complement(Rectangle rect)](#complement-com.aspose.imaging.Rectangle-) | Uppdaterar detta `com.aspose.imaging.Region` så att det innehåller den del av den angivna `com.aspose.imaging.Rectangle`-strukturen som inte skär med detta `com.aspose.imaging.region`. |
| [complement(GraphicsPath path)](#complement-com.aspose.imaging.GraphicsPath-) | Uppdaterar detta `com.aspose.imaging.Region` så att det innehåller den del av den angivna `com.aspose.imaging.GraphicsPath` som inte skär med detta `com.aspose.imaging.region`. |
| [complement(Region region)](#complement-com.aspose.imaging.Region-) | Uppdaterar detta `com.aspose.imaging.Region` så att det innehåller den del av den angivna `com.aspose.imaging.Region` som inte skär med detta `com.aspose.imaging.region`. |
| [translate(float dx, float dy)](#translate-float-float-) | Förskjuter koordinaterna för detta `com.aspose.imaging.Region` med det angivna värdet. |
| [translate(int dx, int dy)](#translate-int-int-) | Förskjuter koordinaterna för detta `com.aspose.imaging.Region` med det angivna värdet. |
| [transform(Matrix matrix)](#transform-com.aspose.imaging.Matrix-) | Transformerar detta `com.aspose.imaging.Region` med den angivna `com.aspose.imaging.matrix`. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.imaging.Graphics-) | Testar om detta `com.aspose.imaging.Region` har ett tomt inre på den angivna ritytan. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.imaging.Graphics-) | Testar om detta `com.aspose.imaging.Region` har ett oändligt inre på den angivna ritytan. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-) | Testar om den angivna `com.aspose.imaging.Region` är identisk med detta `com.aspose.imaging.Region` på den angivna ritytan. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Testar om den angivna punkten finns inom detta `com.aspose.imaging.region`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Testar om den angivna `com.aspose.imaging.PointF`-strukturen finns inom detta `com.aspose.imaging.region`. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Testar om den angivna punkten finns inom detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Testar om den angivna `com.aspose.imaging.PointF`-strukturen finns inom detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Testar om någon del av den angivna rektangeln finns inom detta `com.aspose.imaging.region`. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.imaging.RectangleF-) | Testar om någon del av den angivna `com.aspose.imaging.RectangleF`-strukturen finns inom detta `com.aspose.imaging.region`. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.imaging.Graphics-) | Testar om någon del av den angivna rektangeln finns inom detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-) | Testar om någon del av den angivna `com.aspose.imaging.RectangleF`-strukturen finns inom detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Testar om den angivna punkten finns inom detta `com.aspose.imaging.Region`-objekt när den ritas med det angivna `com.aspose.imaging.Graphics`-objektet. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Testar om den angivna `com.aspose.imaging.Point`-strukturen finns i detta `com.aspose.imaging.region`. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Testar om den angivna `com.aspose.imaging.Point`-strukturen finns i detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Testar om någon del av den angivna rektangeln finns inom detta `com.aspose.imaging.region`. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.imaging.Rectangle-) | Testar om någon del av den angivna `com.aspose.imaging.Rectangle`-strukturen finns i detta `com.aspose.imaging.region`. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.imaging.Graphics-) | Testar om någon del av den angivna rektangeln finns inom detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-) | Testar om någon del av den angivna `com.aspose.imaging.Rectangle`-strukturen finns i detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) | Hämta hashkoden för det aktuella objektet. |
### Region() {#Region--}
```
public Region()
```


Initierar en ny Region.

### Region(RectangleF rect) {#Region-com.aspose.imaging.RectangleF-}
```
public Region(RectangleF rect)
```


Initierar en ny `T:Aspose.Imaging.Region` från den angivna `T:Aspose.Imaging.RectangleF`‑strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | En `T:Aspose.Imaging.RectangleF`-struktur som definierar insidan av den nya `T:Aspose.Imaging.Region`. |

### Region(Rectangle rect) {#Region-com.aspose.imaging.Rectangle-}
```
public Region(Rectangle rect)
```


Initierar en ny `T:Aspose.Imaging.Region` från den angivna `T:Aspose.Imaging.Rectangle`‑strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | En `T:Aspose.Imaging.Rectangle`-struktur som definierar insidan av den nya `T:Aspose.Imaging.Region`. |

### Region(GraphicsPath path) {#Region-com.aspose.imaging.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initierar en ny `T:Aspose.Imaging.Region` med den angivna `T:Aspose.Imaging.GraphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | En `T:Aspose.Imaging.GraphicsPath` som definierar den nya `T:Aspose.Imaging.Region`. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Skapar en exakt djup kopia av detta `com.aspose.imaging.region`.

**Returns:**
[Region](../../com.aspose.imaging/region) - The `com.aspose.imaging.Region` that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initierar detta `com.aspose.imaging.Region`‑objekt till en oändlig insida.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initierar detta `com.aspose.imaging.Region` till en tom insida.

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Uppdaterar detta `com.aspose.imaging.Region` till snittet av sig själv och den angivna `com.aspose.imaging.RectangleF`‑strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`-strukturen för att skära av detta `com.aspose.imaging.region`. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Uppdaterar detta `com.aspose.imaging.Region` till snittet av sig själv och den angivna `com.aspose.imaging.Rectangle`‑strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle`-strukturen för att skära av detta `com.aspose.imaging.region`. |

### intersect(GraphicsPath path) {#intersect-com.aspose.imaging.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Uppdaterar detta `com.aspose.imaging.Region` till snittet av sig själv och den angivna `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` för att skära av detta `com.aspose.imaging.region`. |

### intersect(Region region) {#intersect-com.aspose.imaging.Region-}
```
public void intersect(Region region)
```


Uppdaterar detta `com.aspose.imaging.Region` till snittet av sig själv och den angivna `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | `com.aspose.imaging.Region` för att skära av detta `com.aspose.imaging.region`. |

### union(RectangleF rect) {#union-com.aspose.imaging.RectangleF-}
```
public void union(RectangleF rect)
```


Uppdaterar detta `com.aspose.imaging.Region` till unionen av sig själv och den angivna `com.aspose.imaging.RectangleF`‑strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`-strukturen för att förena med detta `com.aspose.imaging.region`. |

### union(Rectangle rect) {#union-com.aspose.imaging.Rectangle-}
```
public void union(Rectangle rect)
```


Uppdaterar detta `com.aspose.imaging.Region` till unionen av sig själv och den angivna `com.aspose.imaging.Rectangle`‑strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle`-strukturen för att förena med detta `com.aspose.imaging.region`. |

### union(GraphicsPath path) {#union-com.aspose.imaging.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Uppdaterar detta `com.aspose.imaging.Region` till unionen av sig själv och den angivna `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` för att förena med detta `com.aspose.imaging.region`. |

### union(Region region) {#union-com.aspose.imaging.Region-}
```
public void union(Region region)
```


Uppdaterar detta `com.aspose.imaging.Region` till unionen av sig själv och den angivna `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | `com.aspose.imaging.Region` för att förena med detta `com.aspose.imaging.region`. |

### xor(RectangleF rect) {#xor-com.aspose.imaging.RectangleF-}
```
public void xor(RectangleF rect)
```


Uppdaterar detta `com.aspose.imaging.Region` till unionen minus snittet av sig själv och den angivna `com.aspose.imaging.RectangleF`‑strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`-strukturen för att xor:a med detta `com.aspose.imaging.region`. |

### xor(Rectangle rect) {#xor-com.aspose.imaging.Rectangle-}
```
public void xor(Rectangle rect)
```


Uppdaterar detta `com.aspose.imaging.Region` till unionen minus skärningen av sig själv med den angivna `com.aspose.imaging.Rectangle`-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle`-strukturen för att xor:a med detta `com.aspose.imaging.region`. |

### xor(GraphicsPath path) {#xor-com.aspose.imaging.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Uppdaterar detta `com.aspose.imaging.Region` till unionen minus skärningen av sig själv med den angivna `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` för att xor:a med detta `com.aspose.imaging.region`. |

### xor(Region region) {#xor-com.aspose.imaging.Region-}
```
public void xor(Region region)
```


Uppdaterar detta `com.aspose.imaging.Region` till unionen minus skärningen av sig själv med den angivna `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | `com.aspose.imaging.Region` för att xor:a med detta `com.aspose.imaging.region`. |

### exclude(RectangleF rect) {#exclude-com.aspose.imaging.RectangleF-}
```
public void exclude(RectangleF rect)
```


Uppdaterar detta `com.aspose.imaging.Region` så att det endast innehåller den del av dess inre som inte skär med den angivna `com.aspose.imaging.RectangleF`-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`-strukturen för att utesluta från detta `com.aspose.imaging.region`. |

### exclude(Rectangle rect) {#exclude-com.aspose.imaging.Rectangle-}
```
public void exclude(Rectangle rect)
```


Uppdaterar detta `com.aspose.imaging.Region` så att det endast innehåller den del av dess inre som inte skär med den angivna `com.aspose.imaging.Rectangle`-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle`-strukturen för att utesluta från detta `com.aspose.imaging.region`. |

### exclude(GraphicsPath path) {#exclude-com.aspose.imaging.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Uppdaterar detta `com.aspose.imaging.Region` så att det endast innehåller den del av dess inre som inte skär med den angivna `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` för att utesluta från detta `com.aspose.imaging.region`. |

### exclude(Region region) {#exclude-com.aspose.imaging.Region-}
```
public void exclude(Region region)
```


Uppdaterar detta `com.aspose.imaging.Region` så att det endast innehåller den del av dess inre som inte skär med den angivna `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | `com.aspose.imaging.Region` för att utesluta från detta `com.aspose.imaging.region`. |

### complement(RectangleF rect) {#complement-com.aspose.imaging.RectangleF-}
```
public void complement(RectangleF rect)
```


Uppdaterar detta `com.aspose.imaging.Region` så att det innehåller den del av den angivna `com.aspose.imaging.RectangleF`-strukturen som inte skär med detta `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`-strukturen för att komplettera detta `com.aspose.imaging.region`. |

### complement(Rectangle rect) {#complement-com.aspose.imaging.Rectangle-}
```
public void complement(Rectangle rect)
```


Uppdaterar detta `com.aspose.imaging.Region` så att det innehåller den del av den angivna `com.aspose.imaging.Rectangle`-strukturen som inte skär med detta `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle`-strukturen för att komplettera detta `com.aspose.imaging.region`. |

### complement(GraphicsPath path) {#complement-com.aspose.imaging.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Uppdaterar detta `com.aspose.imaging.Region` så att det innehåller den del av den angivna `com.aspose.imaging.GraphicsPath` som inte skär med detta `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Den `com.aspose.imaging.GraphicsPath` för att komplettera detta `com.aspose.imaging.region`. |

### complement(Region region) {#complement-com.aspose.imaging.Region-}
```
public void complement(Region region)
```


Uppdaterar detta `com.aspose.imaging.Region` så att det innehåller den del av den angivna `com.aspose.imaging.Region` som inte skär med detta `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Objektet `com.aspose.imaging.Region` för att komplettera detta `com.aspose.imaging.Region`-objekt. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Förskjuter koordinaterna för detta `com.aspose.imaging.Region` med det angivna värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Mängden för att förskjuta detta `com.aspose.imaging.Region` horisontellt. |
| dy | float | Mängden för att förskjuta detta `com.aspose.imaging.Region` vertikalt. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Förskjuter koordinaterna för detta `com.aspose.imaging.Region` med det angivna värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | int | Mängden för att förskjuta detta `com.aspose.imaging.Region` horisontellt. |
| dy | int | Mängden för att förskjuta detta `com.aspose.imaging.Region` vertikalt. |

### transform(Matrix matrix) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix matrix)
```


Transformerar detta `com.aspose.imaging.Region` med den angivna `com.aspose.imaging.matrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Den `com.aspose.imaging.Matrix` som ska användas för att transformera detta `com.aspose.imaging.region`. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.imaging.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Testar om detta `com.aspose.imaging.Region` har ett tomt inre på den angivna ritytan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ett `com.aspose.imaging.Graphics` som representerar en ritningsyta. |

**Returns:**
boolean - true om innanmätet av detta `com.aspose.imaging.Region` är tomt när transformationen som är associerad med `g` tillämpas; annars false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.imaging.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Testar om detta `com.aspose.imaging.Region` har ett oändligt inre på den angivna ritytan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ett `com.aspose.imaging.Graphics` som representerar en ritningsyta. |

**Returns:**
boolean - true om innanmätet av detta `com.aspose.imaging.Region` är oändligt när transformationen som är associerad med `g` tillämpas; annars false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Testar om den angivna `com.aspose.imaging.Region` är identisk med detta `com.aspose.imaging.Region` på den angivna ritytan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Den `com.aspose.imaging.Region` att testa. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ett `com.aspose.imaging.Graphics` som representerar en ritningsyta. |

**Returns:**
boolean - True om innanmätet av regionen är identiskt med innanmätet av detta region när transformationen som är associerad med `g`-parametern tillämpas; annars false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Testar om den angivna punkten finns inom detta `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |

**Returns:**
boolean - True när den angivna punkten finns inom detta `com.aspose.imaging.Region`; annars false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Testar om den angivna `com.aspose.imaging.PointF`-strukturen finns inom detta `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `com.aspose.imaging.PointF`-strukturen att testa. |

**Returns:**
boolean - true när `point` finns inom detta `com.aspose.imaging.Region`; annars false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Testar om den angivna punkten finns inom detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ett `com.aspose.imaging.Graphics` som representerar ett grafik-kontext. |

**Returns:**
boolean - True när den angivna punkten finns inom detta `com.aspose.imaging.Region`; annars false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Testar om den angivna `com.aspose.imaging.PointF`-strukturen finns inom detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `com.aspose.imaging.PointF`-strukturen att testa. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ett `com.aspose.imaging.Graphics` som representerar ett grafik-kontext. |

**Returns:**
boolean - true när `point` finns inom detta `com.aspose.imaging.Region`; annars false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Testar om någon del av den angivna rektangeln finns inom detta `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | x-koordinaten för det övre vänstra hörnet av rektangeln att testa. |
| y | float | y-koordinaten för det övre vänstra hörnet av rektangeln att testa. |
| bredd | float | Bredden på rektangeln att testa. |
| höjd | float | Höjden på rektangeln att testa. |

**Returns:**
boolean - true när någon del av den angivna rektangeln finns inom detta `com.aspose.imaging.Region`-objekt; annars false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.imaging.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Testar om någon del av den angivna `com.aspose.imaging.RectangleF`-strukturen finns inom detta `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Den `com.aspose.imaging.RectangleF`-strukturen att testa. |

**Returns:**
boolean - true när någon del av `rect` finns inom detta `com.aspose.imaging.Region`; annars false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Testar om någon del av den angivna rektangeln finns inom detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | x-koordinaten för det övre vänstra hörnet av rektangeln att testa. |
| y | float | y-koordinaten för det övre vänstra hörnet av rektangeln att testa. |
| bredd | float | Bredden på rektangeln att testa. |
| höjd | float | Höjden på rektangeln att testa. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ett `com.aspose.imaging.Graphics` som representerar ett grafik-kontext. |

**Returns:**
boolean - true när någon del av den angivna rektangeln finns inom detta `com.aspose.imaging.Region`; annars false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Testar om någon del av den angivna `com.aspose.imaging.RectangleF`-strukturen finns inom detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Den `com.aspose.imaging.RectangleF`-strukturen att testa. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ett `com.aspose.imaging.Graphics` som representerar ett grafik-kontext. |

**Returns:**
boolean - true när `rect` finns inom detta `com.aspose.imaging.Region`; annars false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Testar om den angivna punkten finns inom detta `com.aspose.imaging.Region`-objekt när den ritas med det angivna `com.aspose.imaging.Graphics`-objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten som ska testas. |
| y | int | Y-koordinaten för punkten som ska testas. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ett `com.aspose.imaging.Graphics` som representerar ett grafik-kontext. |

**Returns:**
boolean - sant när den angivna punkten finns inom detta `com.aspose.imaging.Region`; annars falskt.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Testar om den angivna `com.aspose.imaging.Point`-strukturen finns i detta `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Den `com.aspose.imaging.Point`-strukturen att testa. |

**Returns:**
boolean - true när `point` finns inom detta `com.aspose.imaging.Region`; annars false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Testar om den angivna `com.aspose.imaging.Point`-strukturen finns i detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Den `com.aspose.imaging.Point`-strukturen att testa. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ett `com.aspose.imaging.Graphics` som representerar ett grafik-kontext. |

**Returns:**
boolean - true när `point` finns inom detta `com.aspose.imaging.Region`; annars false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Testar om någon del av den angivna rektangeln finns inom detta `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | x-koordinaten för det övre vänstra hörnet av rektangeln att testa. |
| y | int | y-koordinaten för det övre vänstra hörnet av rektangeln att testa. |
| bredd | int | Bredden på rektangeln att testa. |
| höjd | int | Höjden på rektangeln att testa. |

**Returns:**
boolean - true när någon del av den angivna rektangeln finns inom detta `com.aspose.imaging.Region`; annars false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.imaging.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Testar om någon del av den angivna `com.aspose.imaging.Rectangle`-strukturen finns i detta `com.aspose.imaging.region`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Den `com.aspose.imaging.Rectangle`-strukturen att testa. |

**Returns:**
boolean - Denna metod returnerar sant när någon del av `rect` finns inom detta `com.aspose.imaging.Region`; annars falskt.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Testar om någon del av den angivna rektangeln finns inom detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | x-koordinaten för det övre vänstra hörnet av rektangeln att testa. |
| y | int | y-koordinaten för det övre vänstra hörnet av rektangeln att testa. |
| bredd | int | Bredden på rektangeln att testa. |
| höjd | int | Höjden på rektangeln att testa. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ett `com.aspose.imaging.Graphics` som representerar ett grafik-kontext. |

**Returns:**
boolean - true när någon del av den angivna rektangeln finns inom detta `com.aspose.imaging.Region`; annars false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Testar om någon del av den angivna `com.aspose.imaging.Rectangle`-strukturen finns i detta `com.aspose.imaging.Region` när den ritas med den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Den `com.aspose.imaging.Rectangle`-strukturen att testa. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Ett `com.aspose.imaging.Graphics` som representerar ett grafik-kontext. |

**Returns:**
boolean - sant när någon del av `rect` finns inom detta `com.aspose.imaging.Region`; annars falskt.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Det andra objektet. |

**Returns:**
boolean - Resultatet av likhetsjämförelsen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int - Hashkoden.
