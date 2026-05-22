---
title: "Region"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Dikdörtgenler ve yollarla oluşturulmuş bir grafik şeklinin iç kısmını tanımlar."
type: docs
weight: 95
url: /tr/java/com.aspose.imaging/region/
---
**Inheritance:**
java.lang.Object
```
public final class Region
```

Dikdörtgenler ve yollarla oluşturulmuş bir grafik şeklinin iç kısmını tanımlar. Bu sınıf miras alınamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Region()](#Region--) | Yeni bir Region başlatır. |
| [Region(RectangleF rect)](#Region-com.aspose.imaging.RectangleF-) | Belirtilen `T:Aspose.Imaging.RectangleF` yapısından yeni bir `T:Aspose.Imaging.Region` başlatır. |
| [Region(Rectangle rect)](#Region-com.aspose.imaging.Rectangle-) | Belirtilen `T:Aspose.Imaging.Rectangle` yapısından yeni bir `T:Aspose.Imaging.Region` başlatır. |
| [Region(GraphicsPath path)](#Region-com.aspose.imaging.GraphicsPath-) | Belirtilen `T:Aspose.Imaging.GraphicsPath` ile yeni bir `T:Aspose.Imaging.Region` başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone()](#deepClone--) | Bu `com.aspose.imaging.region` nesnesinin tam bir derin kopyasını oluşturur. |
| [makeInfinite()](#makeInfinite--) | Bu `com.aspose.imaging.Region` nesnesini sonsuz bir iç bölgeye başlatır. |
| [makeEmpty()](#makeEmpty--) | Bu `com.aspose.imaging.Region` nesnesini boş bir iç bölgeye başlatır. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.RectangleF` yapısının kesişimine günceller. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.Rectangle` yapısının kesişimine günceller. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.imaging.GraphicsPath-) | Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.graphicsPath` öğesinin kesişimine günceller. |
| [intersect(Region region)](#intersect-com.aspose.imaging.Region-) | Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.region` nesnesinin kesişimine günceller. |
| [union(RectangleF rect)](#union-com.aspose.imaging.RectangleF-) | Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.RectangleF` yapısının birleşimine günceller. |
| [union(Rectangle rect)](#union-com.aspose.imaging.Rectangle-) | Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.Rectangle` yapısının birleşimine günceller. |
| [union(GraphicsPath path)](#union-com.aspose.imaging.GraphicsPath-) | Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.graphicsPath` öğesinin birleşimine günceller. |
| [union(Region region)](#union-com.aspose.imaging.Region-) | Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.region` nesnesinin birleşimine günceller. |
| [xor(RectangleF rect)](#xor-com.aspose.imaging.RectangleF-) | Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.RectangleF` yapısının kesişimini çıkararak birleşime günceller. |
| [xor(Rectangle rect)](#xor-com.aspose.imaging.Rectangle-) | Bu `com.aspose.imaging.Region` öğesini, kendisi ile belirtilen `com.aspose.imaging.Rectangle` yapısının kesişiminin çıkarıldığı birleşime günceller. |
| [xor(GraphicsPath path)](#xor-com.aspose.imaging.GraphicsPath-) | Bu `com.aspose.imaging.Region` öğesini, kendisi ile belirtilen `com.aspose.imaging.graphicsPath` öğesinin kesişiminin çıkarıldığı birleşime günceller. |
| [xor(Region region)](#xor-com.aspose.imaging.Region-) | Bu `com.aspose.imaging.Region` öğesini, kendisi ile belirtilen `com.aspose.imaging.region` öğesinin kesişiminin çıkarıldığı birleşime günceller. |
| [exclude(RectangleF rect)](#exclude-com.aspose.imaging.RectangleF-) | Bu `com.aspose.imaging.Region` öğesini, iç kısmının yalnızca belirtilen `com.aspose.imaging.RectangleF` yapısı ile kesişmeyen bölümünü içerecek şekilde günceller. |
| [exclude(Rectangle rect)](#exclude-com.aspose.imaging.Rectangle-) | Bu `com.aspose.imaging.Region` öğesini, iç kısmının yalnızca belirtilen `com.aspose.imaging.Rectangle` yapısı ile kesişmeyen bölümünü içerecek şekilde günceller. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.imaging.GraphicsPath-) | Bu `com.aspose.imaging.Region` öğesini, iç kısmının yalnızca belirtilen `com.aspose.imaging.graphicsPath` öğesi ile kesişmeyen bölümünü içerecek şekilde günceller. |
| [exclude(Region region)](#exclude-com.aspose.imaging.Region-) | Bu `com.aspose.imaging.Region` öğesini, iç kısmının yalnızca belirtilen `com.aspose.imaging.region` öğesi ile kesişmeyen bölümünü içerecek şekilde günceller. |
| [complement(RectangleF rect)](#complement-com.aspose.imaging.RectangleF-) | Bu `com.aspose.imaging.Region` öğesini, belirtilen `com.aspose.imaging.RectangleF` yapısının bu `com.aspose.imaging.region` ile kesişmeyen bölümünü içerecek şekilde günceller. |
| [complement(Rectangle rect)](#complement-com.aspose.imaging.Rectangle-) | Bu `com.aspose.imaging.Region` öğesini, belirtilen `com.aspose.imaging.Rectangle` yapısının bu `com.aspose.imaging.region` ile kesişmeyen bölümünü içerecek şekilde günceller. |
| [complement(GraphicsPath path)](#complement-com.aspose.imaging.GraphicsPath-) | Bu `com.aspose.imaging.Region` öğesini, belirtilen `com.aspose.imaging.GraphicsPath` öğesinin bu `com.aspose.imaging.region` ile kesişmeyen bölümünü içerecek şekilde günceller. |
| [complement(Region region)](#complement-com.aspose.imaging.Region-) | Bu `com.aspose.imaging.Region` öğesini, belirtilen `com.aspose.imaging.Region` öğesinin bu `com.aspose.imaging.region` ile kesişmeyen bölümünü içerecek şekilde günceller. |
| [translate(float dx, float dy)](#translate-float-float-) | Bu `com.aspose.imaging.Region` öğesinin koordinatlarını belirtilen miktarda kaydırır. |
| [translate(int dx, int dy)](#translate-int-int-) | Bu `com.aspose.imaging.Region` öğesinin koordinatlarını belirtilen miktarda kaydırır. |
| [transform(Matrix matrix)](#transform-com.aspose.imaging.Matrix-) | Bu `com.aspose.imaging.Region` öğesini belirtilen `com.aspose.imaging.matrix` ile dönüştürür. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.imaging.Graphics-) | Bu `com.aspose.imaging.Region` öğesinin belirtilen çizim yüzeyinde boş bir iç kısmı olup olmadığını test eder. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.imaging.Graphics-) | Bu `com.aspose.imaging.Region` öğesinin belirtilen çizim yüzeyinde sonsuz bir iç kısmı olup olmadığını test eder. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-) | Belirtilen `com.aspose.imaging.Region` öğesinin, bu `com.aspose.imaging.Region` öğesiyle belirtilen çizim yüzeyinde aynı olup olmadığını test eder. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Belirtilen noktanın bu `com.aspose.imaging.region` içinde bulunup bulunmadığını test eder. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Belirtilen `com.aspose.imaging.PointF` yapısının bu `com.aspose.imaging.region` içinde bulunup bulunmadığını test eder. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Belirtilen noktanın, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde bulunup bulunmadığını test eder. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Belirtilen `com.aspose.imaging.PointF` yapısının, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde bulunup bulunmadığını test eder. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Belirtilen dikdörtgenin herhangi bir bölümünün bu `com.aspose.imaging.region` içinde bulunup bulunmadığını test eder. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.imaging.RectangleF-) | Belirtilen `com.aspose.imaging.RectangleF` yapısının herhangi bir bölümünün bu `com.aspose.imaging.region` içinde bulunup bulunmadığını test eder. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.imaging.Graphics-) | Belirtilen dikdörtgenin herhangi bir bölümünün, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde bulunup bulunmadığını test eder. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-) | Belirtilen `com.aspose.imaging.RectangleF` yapısının herhangi bir bölümünün, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde bulunup bulunmadığını test eder. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Belirtilen noktanın, belirtilen `com.aspose.imaging.Graphics` nesnesi kullanılarak çizildiğinde bu `com.aspose.imaging.Region` nesnesi içinde bulunup bulunmadığını test eder. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Belirtilen `com.aspose.imaging.Point` yapısının bu `com.aspose.imaging.region` içinde olup olmadığını test eder. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Belirtilen `com.aspose.imaging.Point` yapısının, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde olup olmadığını test eder. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Belirtilen dikdörtgenin herhangi bir bölümünün bu `com.aspose.imaging.region` içinde bulunup bulunmadığını test eder. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.imaging.Rectangle-) | Belirtilen `com.aspose.imaging.Rectangle` yapısının herhangi bir bölümünün bu `com.aspose.imaging.region` içinde olup olmadığını test eder. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.imaging.Graphics-) | Belirtilen dikdörtgenin herhangi bir bölümünün, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde bulunup bulunmadığını test eder. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-) | Belirtilen `com.aspose.imaging.Rectangle` yapısının, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde olup olmadığını test eder. |
| [equals(Object o)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | Geçerli nesnenin karma kodunu al. |
### Region() {#Region--}
```
public Region()
```


Yeni bir Region başlatır.

### Region(RectangleF rect) {#Region-com.aspose.imaging.RectangleF-}
```
public Region(RectangleF rect)
```


Belirtilen `T:Aspose.Imaging.RectangleF` yapısından yeni bir `T:Aspose.Imaging.Region` başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Yeni `T:Aspose.Imaging.Region`'in içini tanımlayan bir `T:Aspose.Imaging.RectangleF` yapısı. |

### Region(Rectangle rect) {#Region-com.aspose.imaging.Rectangle-}
```
public Region(Rectangle rect)
```


Belirtilen `T:Aspose.Imaging.Rectangle` yapısından yeni bir `T:Aspose.Imaging.Region` başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Yeni `T:Aspose.Imaging.Region`'in içini tanımlayan bir `T:Aspose.Imaging.Rectangle` yapısı. |

### Region(GraphicsPath path) {#Region-com.aspose.imaging.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Belirtilen `T:Aspose.Imaging.GraphicsPath` ile yeni bir `T:Aspose.Imaging.Region` başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Yeni `T:Aspose.Imaging.Region`'i tanımlayan bir `T:Aspose.Imaging.GraphicsPath`. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Bu `com.aspose.imaging.region` nesnesinin tam bir derin kopyasını oluşturur.

**Returns:**
[Region](../../com.aspose.imaging/region) - The `com.aspose.imaging.Region` that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Bu `com.aspose.imaging.Region` nesnesini sonsuz bir iç bölgeye başlatır.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Bu `com.aspose.imaging.Region` nesnesini boş bir iç bölgeye başlatır.

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.RectangleF` yapısının kesişimine günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Bu `com.aspose.imaging.region` ile kesişecek `com.aspose.imaging.RectangleF` yapısı. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.Rectangle` yapısının kesişimine günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Bu `com.aspose.imaging.region` ile kesişecek `com.aspose.imaging.Rectangle` yapısı. |

### intersect(GraphicsPath path) {#intersect-com.aspose.imaging.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.graphicsPath` öğesinin kesişimine günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Bu `com.aspose.imaging.region` ile kesişecek `com.aspose.imaging.GraphicsPath`. |

### intersect(Region region) {#intersect-com.aspose.imaging.Region-}
```
public void intersect(Region region)
```


Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.region` nesnesinin kesişimine günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Bu `com.aspose.imaging.region` ile kesişecek `com.aspose.imaging.Region`. |

### union(RectangleF rect) {#union-com.aspose.imaging.RectangleF-}
```
public void union(RectangleF rect)
```


Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.RectangleF` yapısının birleşimine günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Bu `com.aspose.imaging.region` ile birleştirilecek `com.aspose.imaging.RectangleF` yapısı. |

### union(Rectangle rect) {#union-com.aspose.imaging.Rectangle-}
```
public void union(Rectangle rect)
```


Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.Rectangle` yapısının birleşimine günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Bu `com.aspose.imaging.region` ile birleştirilecek `com.aspose.imaging.Rectangle` yapısı. |

### union(GraphicsPath path) {#union-com.aspose.imaging.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.graphicsPath` öğesinin birleşimine günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Bu `com.aspose.imaging.region` ile birleştirilecek `com.aspose.imaging.GraphicsPath`. |

### union(Region region) {#union-com.aspose.imaging.Region-}
```
public void union(Region region)
```


Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.region` nesnesinin birleşimine günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Bu `com.aspose.imaging.region` ile birleştirilecek `com.aspose.imaging.Region`. |

### xor(RectangleF rect) {#xor-com.aspose.imaging.RectangleF-}
```
public void xor(RectangleF rect)
```


Bu `com.aspose.imaging.Region` nesnesini, kendisi ile belirtilen `com.aspose.imaging.RectangleF` yapısının kesişimini çıkararak birleşime günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Bu `com.aspose.imaging.region` ile xor yapılacak `com.aspose.imaging.RectangleF` yapısı. |

### xor(Rectangle rect) {#xor-com.aspose.imaging.Rectangle-}
```
public void xor(Rectangle rect)
```


Bu `com.aspose.imaging.Region` öğesini, kendisi ile belirtilen `com.aspose.imaging.Rectangle` yapısının kesişiminin çıkarıldığı birleşime günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Bu `com.aspose.imaging.region` ile xor yapılacak `com.aspose.imaging.Rectangle` yapısı. |

### xor(GraphicsPath path) {#xor-com.aspose.imaging.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Bu `com.aspose.imaging.Region` öğesini, kendisi ile belirtilen `com.aspose.imaging.graphicsPath` öğesinin kesişiminin çıkarıldığı birleşime günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Bu `com.aspose.imaging.region` ile xor yapılacak `com.aspose.imaging.GraphicsPath`. |

### xor(Region region) {#xor-com.aspose.imaging.Region-}
```
public void xor(Region region)
```


Bu `com.aspose.imaging.Region` öğesini, kendisi ile belirtilen `com.aspose.imaging.region` öğesinin kesişiminin çıkarıldığı birleşime günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Bu `com.aspose.imaging.region` ile xor yapılacak `com.aspose.imaging.Region`. |

### exclude(RectangleF rect) {#exclude-com.aspose.imaging.RectangleF-}
```
public void exclude(RectangleF rect)
```


Bu `com.aspose.imaging.Region` öğesini, iç kısmının yalnızca belirtilen `com.aspose.imaging.RectangleF` yapısı ile kesişmeyen bölümünü içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Bu `com.aspose.imaging.region`'den hariç tutulacak `com.aspose.imaging.RectangleF` yapısı. |

### exclude(Rectangle rect) {#exclude-com.aspose.imaging.Rectangle-}
```
public void exclude(Rectangle rect)
```


Bu `com.aspose.imaging.Region` öğesini, iç kısmının yalnızca belirtilen `com.aspose.imaging.Rectangle` yapısı ile kesişmeyen bölümünü içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Bu `com.aspose.imaging.region`'den hariç tutulacak `com.aspose.imaging.Rectangle` yapısı. |

### exclude(GraphicsPath path) {#exclude-com.aspose.imaging.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Bu `com.aspose.imaging.Region` öğesini, iç kısmının yalnızca belirtilen `com.aspose.imaging.graphicsPath` öğesi ile kesişmeyen bölümünü içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Bu `com.aspose.imaging.region`'den hariç tutulacak `com.aspose.imaging.GraphicsPath`. |

### exclude(Region region) {#exclude-com.aspose.imaging.Region-}
```
public void exclude(Region region)
```


Bu `com.aspose.imaging.Region` öğesini, iç kısmının yalnızca belirtilen `com.aspose.imaging.region` öğesi ile kesişmeyen bölümünü içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Bu `com.aspose.imaging.region`'den hariç tutulacak `com.aspose.imaging.Region`. |

### complement(RectangleF rect) {#complement-com.aspose.imaging.RectangleF-}
```
public void complement(RectangleF rect)
```


Bu `com.aspose.imaging.Region` öğesini, belirtilen `com.aspose.imaging.RectangleF` yapısının bu `com.aspose.imaging.region` ile kesişmeyen bölümünü içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Bu `com.aspose.imaging.region`'i tamamlayacak `com.aspose.imaging.RectangleF` yapısı. |

### complement(Rectangle rect) {#complement-com.aspose.imaging.Rectangle-}
```
public void complement(Rectangle rect)
```


Bu `com.aspose.imaging.Region` öğesini, belirtilen `com.aspose.imaging.Rectangle` yapısının bu `com.aspose.imaging.region` ile kesişmeyen bölümünü içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Bu `com.aspose.imaging.region`'i tamamlayacak `com.aspose.imaging.Rectangle` yapısı. |

### complement(GraphicsPath path) {#complement-com.aspose.imaging.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Bu `com.aspose.imaging.Region` öğesini, belirtilen `com.aspose.imaging.GraphicsPath` öğesinin bu `com.aspose.imaging.region` ile kesişmeyen bölümünü içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Bu `com.aspose.imaging.region` öğesini tamamlamak için `com.aspose.imaging.GraphicsPath`. |

### complement(Region region) {#complement-com.aspose.imaging.Region-}
```
public void complement(Region region)
```


Bu `com.aspose.imaging.Region` öğesini, belirtilen `com.aspose.imaging.Region` öğesinin bu `com.aspose.imaging.region` ile kesişmeyen bölümünü içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Bu `com.aspose.imaging.Region` nesnesini tamamlamak için `com.aspose.imaging.Region` nesnesi. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Bu `com.aspose.imaging.Region` öğesinin koordinatlarını belirtilen miktarda kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | float | Bu `com.aspose.imaging.Region` öğesini yatay olarak kaydırma miktarı. |
| dy | float | Bu `com.aspose.imaging.Region` öğesini dikey olarak kaydırma miktarı. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Bu `com.aspose.imaging.Region` öğesinin koordinatlarını belirtilen miktarda kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | int | Bu `com.aspose.imaging.Region` öğesini yatay olarak kaydırma miktarı. |
| dy | int | Bu `com.aspose.imaging.Region` öğesini dikey olarak kaydırma miktarı. |

### transform(Matrix matrix) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix matrix)
```


Bu `com.aspose.imaging.Region` öğesini belirtilen `com.aspose.imaging.matrix` ile dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Bu `com.aspose.imaging.region` öğesini dönüştürmek için kullanılacak `com.aspose.imaging.Matrix`. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.imaging.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Bu `com.aspose.imaging.Region` öğesinin belirtilen çizim yüzeyinde boş bir iç kısmı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | Bir `com.aspose.imaging.Graphics`, bir çizim yüzeyini temsil eder. |

**Returns:**
boolean - `g` ile ilişkili dönüşüm uygulandığında bu `com.aspose.imaging.Region` öğesinin içi boş ise doğru; aksi takdirde yanlış.
### isInfinite(Graphics g) {#isInfinite-com.aspose.imaging.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Bu `com.aspose.imaging.Region` öğesinin belirtilen çizim yüzeyinde sonsuz bir iç kısmı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | Bir `com.aspose.imaging.Graphics`, bir çizim yüzeyini temsil eder. |

**Returns:**
boolean - `g` ile ilişkili dönüşüm uygulandığında bu `com.aspose.imaging.Region` öğesinin içi sonsuz ise doğru; aksi takdirde yanlış.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Belirtilen `com.aspose.imaging.Region` öğesinin, bu `com.aspose.imaging.Region` öğesiyle belirtilen çizim yüzeyinde aynı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Test edilecek `com.aspose.imaging.Region`. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Bir `com.aspose.imaging.Graphics`, bir çizim yüzeyini temsil eder. |

**Returns:**
boolean - `g` parametresiyle ilişkili dönüşüm uygulandığında bölgenin içi bu bölgenin içiyle aynıysa doğru; aksi takdirde yanlış.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Belirtilen noktanın bu `com.aspose.imaging.region` içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |

**Returns:**
boolean - Belirtilen nokta bu `com.aspose.imaging.Region` içinde yer alıyorsa doğru; aksi takdirde yanlış.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Belirtilen `com.aspose.imaging.PointF` yapısının bu `com.aspose.imaging.region` içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Test edilecek `com.aspose.imaging.PointF` yapısı. |

**Returns:**
boolean - `point` bu `com.aspose.imaging.Region` içinde yer alıyorsa doğru; aksi takdirde yanlış.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Belirtilen noktanın, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Bir `com.aspose.imaging.Graphics`, bir grafik bağlamını temsil eder. |

**Returns:**
boolean - Belirtilen nokta bu `com.aspose.imaging.Region` içinde yer alıyorsa doğru; aksi takdirde yanlış.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Belirtilen `com.aspose.imaging.PointF` yapısının, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Test edilecek `com.aspose.imaging.PointF` yapısı. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Bir `com.aspose.imaging.Graphics`, bir grafik bağlamını temsil eder. |

**Returns:**
boolean - `point` bu `com.aspose.imaging.Region` içinde yer alıyorsa doğru; aksi takdirde yanlış.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Belirtilen dikdörtgenin herhangi bir bölümünün bu `com.aspose.imaging.region` içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Test edilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| genişlik | float | Test edilecek dikdörtgenin genişliği. |
| yükseklik | float | Test edilecek dikdörtgenin yüksekliği. |

**Returns:**
boolean - Belirtilen dikdörtgenin herhangi bir bölümü bu `com.aspose.imaging.Region` nesnesi içinde yer alıyorsa doğru; aksi takdirde yanlış.
### isVisible(RectangleF rect) {#isVisible-com.aspose.imaging.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Belirtilen `com.aspose.imaging.RectangleF` yapısının herhangi bir bölümünün bu `com.aspose.imaging.region` içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Test edilecek `com.aspose.imaging.RectangleF` yapısı. |

**Returns:**
boolean - `rect`'in herhangi bir bölümü bu `com.aspose.imaging.Region` içinde yer alıyorsa doğru; aksi takdirde yanlış.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Belirtilen dikdörtgenin herhangi bir bölümünün, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Test edilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| genişlik | float | Test edilecek dikdörtgenin genişliği. |
| yükseklik | float | Test edilecek dikdörtgenin yüksekliği. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Bir `com.aspose.imaging.Graphics`, bir grafik bağlamını temsil eder. |

**Returns:**
boolean - Belirtilen dikdörtgenin herhangi bir bölümü bu `com.aspose.imaging.Region` içinde yer alıyorsa doğru; aksi takdirde yanlış.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Belirtilen `com.aspose.imaging.RectangleF` yapısının herhangi bir bölümünün, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Test edilecek `com.aspose.imaging.RectangleF` yapısı. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Bir `com.aspose.imaging.Graphics`, bir grafik bağlamını temsil eder. |

**Returns:**
boolean - `rect` bu `com.aspose.imaging.Region` içinde yer alıyorsa doğru; aksi takdirde yanlış.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Belirtilen noktanın, belirtilen `com.aspose.imaging.Graphics` nesnesi kullanılarak çizildiğinde bu `com.aspose.imaging.Region` nesnesi içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Bir `com.aspose.imaging.Graphics`, bir grafik bağlamını temsil eder. |

**Returns:**
boolean - belirtilen nokta bu `com.aspose.imaging.Region` içinde bulunduğunda doğru; aksi takdirde yanlış.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Belirtilen `com.aspose.imaging.Point` yapısının bu `com.aspose.imaging.region` içinde olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Test edilecek `com.aspose.imaging.Point` yapısı. |

**Returns:**
boolean - `point` bu `com.aspose.imaging.Region` içinde yer alıyorsa doğru; aksi takdirde yanlış.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Belirtilen `com.aspose.imaging.Point` yapısının, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Test edilecek `com.aspose.imaging.Point` yapısı. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Bir `com.aspose.imaging.Graphics`, bir grafik bağlamını temsil eder. |

**Returns:**
boolean - `point` bu `com.aspose.imaging.Region` içinde yer alıyorsa doğru; aksi takdirde yanlış.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Belirtilen dikdörtgenin herhangi bir bölümünün bu `com.aspose.imaging.region` içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Test edilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| genişlik | int | Test edilecek dikdörtgenin genişliği. |
| yükseklik | int | Test edilecek dikdörtgenin yüksekliği. |

**Returns:**
boolean - Belirtilen dikdörtgenin herhangi bir bölümü bu `com.aspose.imaging.Region` içinde yer alıyorsa doğru; aksi takdirde yanlış.
### isVisible(Rectangle rect) {#isVisible-com.aspose.imaging.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Belirtilen `com.aspose.imaging.Rectangle` yapısının herhangi bir bölümünün bu `com.aspose.imaging.region` içinde olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Test edilecek `com.aspose.imaging.Rectangle` yapısı. |

**Returns:**
boolean - Bu yöntem, `rect`'in herhangi bir kısmı bu `com.aspose.imaging.Region` içinde bulunduğunda doğru; aksi takdirde yanlış.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Belirtilen dikdörtgenin herhangi bir bölümünün, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Test edilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| genişlik | int | Test edilecek dikdörtgenin genişliği. |
| yükseklik | int | Test edilecek dikdörtgenin yüksekliği. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Bir `com.aspose.imaging.Graphics`, bir grafik bağlamını temsil eder. |

**Returns:**
boolean - Belirtilen dikdörtgenin herhangi bir bölümü bu `com.aspose.imaging.Region` içinde yer alıyorsa doğru; aksi takdirde yanlış.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Belirtilen `com.aspose.imaging.Rectangle` yapısının, belirtilen `com.aspose.imaging.graphics` kullanılarak çizildiğinde bu `com.aspose.imaging.Region` içinde olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Test edilecek `com.aspose.imaging.Rectangle` yapısı. |
| g | [Graphics](../../com.aspose.imaging/graphics) | Bir `com.aspose.imaging.Graphics`, bir grafik bağlamını temsil eder. |

**Returns:**
boolean - `rect`'in herhangi bir kısmı bu `com.aspose.imaging.Region` içinde bulunduğunda doğru; aksi takdirde yanlış.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Nesnelerin eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object | Diğer nesne. |

**Returns:**
boolean - Eşitlik karşılaştırma sonucu.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesnenin karma kodunu al.

**Returns:**
int - Hash kodu.
