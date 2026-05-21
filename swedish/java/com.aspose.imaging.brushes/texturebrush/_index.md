---
title: "TextureBrush"
second_title: "Aspose.Imaging för Java API-referens"
description: "Varje egenskap i klassen Aspose.Imaging.Brushes.TextureBrush är ett Aspose.Imaging.Brush-objekt som använder en bild för att fylla insidan av en form."
type: docs
weight: 18
url: /sv/java/com.aspose.imaging.brushes/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

Varje egenskap i klassen `Aspose.Imaging.Brushes.TextureBrush` är ett `Aspose.Imaging.Brush`-objekt som använder en bild för att fylla insidan av en form. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.imaging.Image-) | Initierar en ny instans av klassen `Aspose.Imaging.Brushes.TextureBrush` som använder den angivna bilden. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.imaging.Image-int-) | Initierar en ny instans av klassen `Aspose.Imaging.Brushes.TextureBrush` som använder den angivna bilden och wrap‑läget. |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-) | Initierar en ny instans av klassen [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) som använder den angivna bilden, begränsningsrektangeln och bildattributen. |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Initierar en ny instans av klassen [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) som använder den angivna bilden och begränsningsrektangeln. |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-) | Initierar en ny instans av klassen [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) som använder den angivna bilden och begränsningsrektangeln. |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-) | Initierar en ny instans av klassen [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) som använder den angivna bilden, wrap‑läget och begränsningsrektangeln. |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-) | Initierar en ny instans av klassen `Aspose.Imaging.Brushes.TextureBrush` som använder den angivna bilden, wrap‑läget och begränsningsrektangeln. |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-) | Initierar en ny instans av klassen `Aspose.Imaging.Brushes.TextureBrush` som använder den angivna bilden, begränsningsrektangeln och bildattributen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getImage()](#getImage--) | Hämtar `com.aspose.imaging.Image`-objektet som är associerat med detta `com.aspose.imaging.brushes.TextureBrush`-objekt. |
| [getImageAttributes()](#getImageAttributes--) | Hämtar `ImageAttributes` som är associerade med detta `TextureBrush`. |
| [getImageRectangle()](#getImageRectangle--) | Hämtar `Rectangle` som är associerad med detta `TextureBrush`. |
### TextureBrush(Image image) {#TextureBrush-com.aspose.imaging.Image-}
```
public TextureBrush(Image image)
```


Initierar en ny instans av klassen `Aspose.Imaging.Brushes.TextureBrush` som använder den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Det `Aspose.Imaging.Image`-objektet som detta `Aspose.Imaging.Brushes.TextureBrush`-objekt fyller interiörer med. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.imaging.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Initierar en ny instans av klassen `Aspose.Imaging.Brushes.TextureBrush` som använder den angivna bilden och wrap‑läget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Det `Aspose.Imaging.Image`-objektet som detta `Aspose.Imaging.Brushes.TextureBrush`-objekt fyller interiörer med. |
| wrapMode | int | En `Aspose.Imaging.WrapMode`-enumeration som specificerar hur detta `Aspose.Imaging.Brushes.TextureBrush`-objekt är kaklad. |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


Initierar en ny instans av klassen [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) som använder den angivna bilden, begränsningsrektangeln och bildattributen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Det [Image](../../com.aspose.imaging/image)-objektet som detta [TextureBrush](../../com.aspose.imaging.brushes/texturebrush)-objekt fyller interiörer med. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | En [Rectangle](../../com.aspose.imaging/rectangle)-struktur som representerar den omgivande rektangeln för detta [TextureBrush](../../com.aspose.imaging.brushes/texturebrush)-objekt. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | Ett [ImageAttributes](../../com.aspose.imaging/imageattributes)-objekt som innehåller ytterligare information om bilden som används av detta [TextureBrush](../../com.aspose.imaging.brushes/texturebrush)-objekt. |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


Initierar en ny instans av klassen [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) som använder den angivna bilden och begränsningsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Det [Image](../../com.aspose.imaging/image)-objektet som detta [TextureBrush](../../com.aspose.imaging.brushes/texturebrush)-objekt fyller interiörer med. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | En [Rectangle](../../com.aspose.imaging/rectangle)-struktur som representerar den omgivande rektangeln för detta [TextureBrush](../../com.aspose.imaging.brushes/texturebrush)-objekt. |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


Initierar en ny instans av klassen [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) som använder den angivna bilden och begränsningsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Det [Image](../../com.aspose.imaging/image)-objektet som detta [TextureBrush](../../com.aspose.imaging.brushes/texturebrush)-objekt fyller interiörer med. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | En [RectangleF](../../com.aspose.imaging/rectanglef)-struktur som representerar den omgivande rektangeln för detta [TextureBrush](../../com.aspose.imaging.brushes/texturebrush)-objekt. |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


Initierar en ny instans av klassen [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) som använder den angivna bilden, wrap‑läget och begränsningsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Det [Image](../../com.aspose.imaging/image)-objektet som detta [TextureBrush](../../com.aspose.imaging.brushes/texturebrush)-objekt fyller interiörer med. |
| wrapMode | int | En [WrapMode](../../com.aspose.imaging/wrapmode)-enumeration som specificerar hur detta [TextureBrush](../../com.aspose.imaging.brushes/texturebrush)-objekt är kaklat. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | En [Rectangle](../../com.aspose.imaging/rectangle)-struktur som representerar den omgivande rektangeln för detta [TextureBrush](../../com.aspose.imaging.brushes/texturebrush)-objekt. |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


Initierar en ny instans av klassen `Aspose.Imaging.Brushes.TextureBrush` som använder den angivna bilden, wrap‑läget och begränsningsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Det `Aspose.Imaging.Image`-objektet som detta `Aspose.Imaging.Brushes.TextureBrush`-objekt fyller interiörer med. |
| wrapMode | int | En `Aspose.Imaging.WrapMode`-enumeration som specificerar hur detta `Aspose.Imaging.Brushes.TextureBrush`-objekt är kaklad. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | En `Aspose.Imaging.RectangleF`-struktur som representerar den omgivande rektangeln för detta `Aspose.Imaging.Brushes.TextureBrush`-objekt. |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


Initierar en ny instans av klassen `Aspose.Imaging.Brushes.TextureBrush` som använder den angivna bilden, begränsningsrektangeln och bildattributen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Det `Aspose.Imaging.Image`-objektet som detta `Aspose.Imaging.Brushes.TextureBrush`-objekt fyller interiörer med. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | En `Aspose.Imaging.RectangleF`-struktur som representerar den omgivande rektangeln för detta `Aspose.Imaging.Brushes.TextureBrush`-objekt. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | Ett `com.aspose.imaging.ImageAttributes`-objekt som innehåller ytterligare information om bilden som används av detta `Aspose.Imaging.Brushes.TextureBrush`-objekt. |

### getImage() {#getImage--}
```
public Image getImage()
```


Hämtar `com.aspose.imaging.Image`-objektet som är associerat med detta `com.aspose.imaging.brushes.TextureBrush`-objekt.

Värde: Ett `com.aspose.imaging.Image`-objekt som representerar bilden som detta `com.aspose.imaging.brushes.TextureBrush`-objekt fyller former med.

**Returns:**
[Image](../../com.aspose.imaging/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


Hämtar `ImageAttributes` som är associerade med detta `TextureBrush`.

Värde: `ImageAttributes`-objektet.

**Returns:**
[ImageAttributes](../../com.aspose.imaging/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


Hämtar `Rectangle` som är associerad med detta `TextureBrush`.

Värde: `Rectangle`-objektet.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
