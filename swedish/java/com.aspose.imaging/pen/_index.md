---
title: "Pen"
second_title: "Aspose.Imaging för Java API-referens"
description: "Definierar ett objekt som används för att rita linjer, kurvor och figurer."
type: docs
weight: 81
url: /sv/java/com.aspose.imaging/pen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.TransparencySupporter](../../com.aspose.imaging/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Definierar ett objekt som används för att rita linjer, kurvor och figurer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.imaging.Color-) | Initierar en ny instans av `Pen`-klassen med den angivna färgen. |
| [Pen(Color color, float width)](#Pen-com.aspose.imaging.Color-float-) | Initierar en ny instans av `Pen`-klassen med de angivna egenskaperna `Color` och `Pen.Width`. |
| [Pen(Brush brush)](#Pen-com.aspose.imaging.Brush-) | Initierar en ny instans av `Pen`-klassen med den angivna `Brush`. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.imaging.Brush-float-) | Initierar en ny instans av `Pen`-klassen med den angivna `Brush` och `Pen.Width`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | Hämtar bredden på denna `Pen`, i enheter av Graphics-objektet som används för ritning. |
| [setWidth(float value)](#setWidth-float-) | Ställer in bredden på denna `Pen`, i enheter av Graphics-objektet som används för ritning. |
| [getStartCap()](#getStartCap--) | Hämtar kapslingsstilen som används i början av linjer som ritas med denna `Pen`. |
| [setStartCap(int value)](#setStartCap-int-) | Ställer in kapslingsstilen som används i början av linjer som ritas med denna `Pen`. |
| [getEndCap()](#getEndCap--) | Hämtar kapslingsstilen som används i slutet av linjer som ritas med denna `Pen`. |
| [setEndCap(int value)](#setEndCap-int-) | Ställer in kapslingsstilen som används i slutet av linjer som ritas med denna `Pen`. |
| [getDashCap()](#getDashCap--) | Hämtar kapslingsstilen som används i slutet av strecken som utgör streckade linjer ritat med denna `Pen`. |
| [setDashCap(int value)](#setDashCap-int-) | Ställer in kapslingsstilen som används i slutet av strecken som utgör streckade linjer ritat med denna `Pen`. |
| [getLineJoin()](#getLineJoin--) | Hämtar sammanfogningsstilen för ändarna på två på varandra följande linjer som ritas med denna `Pen`. |
| [setLineJoin(int value)](#setLineJoin-int-) | Ställer in sammanfogningsstilen för ändarna på två på varandra följande linjer som ritas med denna `Pen`. |
| [getCustomStartCap()](#getCustomStartCap--) | Hämtar en anpassad kapsling att använda i början av linjer som ritas med denna `Pen`. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.imaging.CustomLineCap-) | Ställer in en anpassad kapsling att använda i början av linjer som ritas med denna `Pen`. |
| [getCustomEndCap()](#getCustomEndCap--) | Hämtar en anpassad kapsling att använda i slutet av linjer som ritas med denna `Pen`. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.imaging.CustomLineCap-) | Ställer in en anpassad kapsling att använda i slutet av linjer som ritas med denna `Pen`. |
| [getMiterLimit()](#getMiterLimit--) | Hämtar gränsen för tjockleken på sammanfogningen i ett snedställd hörn. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Ställer in gränsen för tjockleken på fogen på ett fasat hörn. |
| [getAlignment()](#getAlignment--) | Hämtar justeringen för denna `Pen`. |
| [setAlignment(int value)](#setAlignment-int-) | Ställer in justeringen för denna `Pen`. |
| [getTransform()](#getTransform--) | Hämtar en kopia av den geometriska transformationen för denna `Pen`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Ställer in en kopia av den geometriska transformationen för denna `Pen`. |
| [getPenType()](#getPenType--) | Hämtar stilen för linjer som ritas med denna `Pen`. |
| [getColor()](#getColor--) | Hämtar färgen på denna `Pen`. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Ställer in färgen på denna `Pen`. |
| [getBrush()](#getBrush--) | Hämtar `Brush` som bestämmer attribut för denna `Pen`. |
| [setBrush(Brush value)](#setBrush-com.aspose.imaging.Brush-) | Ställer in `Brush` som bestämmer attribut för denna `Pen`. |
| [getDashStyle()](#getDashStyle--) | Hämtar stilen som används för streckade linjer som ritas med denna `Pen`. |
| [setDashStyle(int value)](#setDashStyle-int-) | Ställer in stilen som används för streckade linjer som ritas med denna `Pen`. |
| [getDashOffset()](#getDashOffset--) | Hämtar avståndet från början av en linje till början av ett streckmönster. |
| [setDashOffset(float value)](#setDashOffset-float-) | Ställer in avståndet från början av en linje till början av ett streckmönster. |
| [getDashPattern()](#getDashPattern--) | Hämtar en array av anpassade streck och mellanslag. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Ställer in en array av anpassade streck och mellanslag. |
| [getCompoundArray()](#getCompoundArray--) | Hämtar en array av värden som specificerar en sammansatt penna. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Ställer in en array av värden som specificerar en sammansatt penna. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Ställer in värdena som bestämmer stil för ändkappa som används för att avsluta linjer ritade med denna `Pen`. |
| [resetTransform()](#resetTransform--) | Återställer den geometriska transformationsmatrisen för denna `Pen` till identitet. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multiplicerar transformationsmatrisen för denna `Pen` med den angivna `Matrix`. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multiplicerar transformationsmatrisen för denna `Pen` med den angivna `Matrix` i den angivna ordningen. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skalar den lokala geometriska transformationen med de angivna faktorerna. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rotera den lokala geometriska transformationen med den angivna vinkeln. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rotera den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) |  |

## Example: This example shows the creation and usage Pen objects.
Detta exempel visar skapandet och användningen av Pen-objekt. Exemplet skapar en ny Image och ritar rektanglar på Image-ytan.
``` java

// Skapa en instans av BmpOptions och sätt dess olika egenskaper.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Skapa en instans av FileCreateSource och tilldela den som Source för BmpOptions‑instansen.
// Den andra booleska parametern avgör om filen som ska skapas är temporär eller inte.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Skapa en instans av Image på angiven sökväg
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Skapa en instans av Graphics och initiera den med Image-objektet
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Rensa Graphics-ytan med vit färg
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Skapa en instans av Pen med färgen Röd och bredd 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Skapa en instans av HatchBrush och ställ in dess egenskaper
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Skapa en instans av Pen och initiera den med HatchBrush-objektet och bredd
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Rita rektanglar genom att ange Pen-objektet
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Rita rektanglar genom att ange Pen-objektet
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Spara alla ändringar.
    image.save();
} finally {
    image.dispose();
}
```

### Pen(Color color) {#Pen-com.aspose.imaging.Color-}
```
public Pen(Color color)
```


Initierar en ny instans av `Pen`-klassen med den angivna färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | En `Color`-struktur som anger färgen på detta `Pen`. |

### Pen(Color color, float width) {#Pen-com.aspose.imaging.Color-float-}
```
public Pen(Color color, float width)
```


Initierar en ny instans av `Pen`-klassen med de angivna egenskaperna `Color` och `Pen.Width`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | En `Color`-struktur som anger färgen på detta `Pen`. |
| bredd | float | Ett värde som anger bredden på detta `Pen`. |

### Pen(Brush brush) {#Pen-com.aspose.imaging.Brush-}
```
public Pen(Brush brush)
```


Initierar en ny instans av `Pen`-klassen med den angivna `Brush`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | En `Brush` som bestämmer fyllningsegenskaperna för detta `Pen`. |

### Pen(Brush brush, float width) {#Pen-com.aspose.imaging.Brush-float-}
```
public Pen(Brush brush, float width)
```


Initierar en ny instans av `Pen`-klassen med den angivna `Brush` och `Pen.Width`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | En `Brush` som bestämmer egenskaperna för detta `Pen`. |
| bredd | float | Bredden på den nya `Pen`. |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Hämtar bredden på denna `Pen`, i enheter av Graphics-objektet som används för ritning.

**Returns:**
float - Bredden på detta `Pen`.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Ställer in bredden på denna `Pen`, i enheter av Graphics-objektet som används för ritning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Bredden på detta `Pen`. |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Hämtar kapslingsstilen som används i början av linjer som ritas med denna `Pen`.

**Returns:**
int - Ett av `LineCap`-värdena som representerar kapstil som används i början av linjer som ritas med detta `Pen`.
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Ställer in kapslingsstilen som används i början av linjer som ritas med denna `Pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Ett av `LineCap`-värdena som representerar kapstil som används i början av linjer som ritas med detta `Pen`. |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Hämtar kapslingsstilen som används i slutet av linjer som ritas med denna `Pen`.

**Returns:**
int - Ett av `LineCap`-värdena som representerar kapstil som används i slutet av linjer som ritas med detta `Pen`.
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Ställer in kapslingsstilen som används i slutet av linjer som ritas med denna `Pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Ett av `LineCap`-värdena som representerar kapstil som används i slutet av linjer som ritas med detta `Pen`. |

### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Hämtar kapslingsstilen som används i slutet av strecken som utgör streckade linjer ritat med denna `Pen`.

**Returns:**
int - Ett av `DashCap`-värdena som representerar kapstil som används i början och slutet av strecken som utgör streckade linjer ritat med detta `Pen`.
### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Ställer in kapslingsstilen som används i slutet av strecken som utgör streckade linjer ritat med denna `Pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Ett av `DashCap`-värdena som representerar kapstil som används i början och slutet av strecken som utgör streckade linjer ritat med detta `Pen`. |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Hämtar sammanfogningsstilen för ändarna på två på varandra följande linjer som ritas med denna `Pen`.

**Returns:**
int - En `LineJoin` som representerar sammanfogningsstilen för ändarna på två på varandra följande linjer ritat med detta `Pen`.
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Ställer in sammanfogningsstilen för ändarna på två på varandra följande linjer som ritas med denna `Pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En `LineJoin` som representerar sammanfogningsstilen för ändarna på två på varandra följande linjer som ritas med denna `Pen`. |

### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Hämtar en anpassad kapsling att använda i början av linjer som ritas med denna `Pen`.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the beginning of lines drawn with this `Pen`.
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Ställer in en anpassad kapsling att använda i början av linjer som ritas med denna `Pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | En `CustomLineCap` som representerar kappen som används i början av linjer som ritas med denna `Pen`. |

### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Hämtar en anpassad kapsling att använda i slutet av linjer som ritas med denna `Pen`.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the end of lines drawn with this `Pen`.
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Ställer in en anpassad kapsling att använda i slutet av linjer som ritas med denna `Pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | En `CustomLineCap` som representerar kappen som används i slutet av linjer som ritas med denna `Pen`. |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Hämtar gränsen för tjockleken på sammanfogningen i ett snedställd hörn.

**Returns:**
float - Gränsen för tjockleken på sammanfogningen på ett snedställt hörn.
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Ställer in gränsen för tjockleken på fogen på ett fasat hörn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Gränsen för tjockleken på sammanfogningen på ett snedställt hörn. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Hämtar justeringen för denna `Pen`.

**Returns:**
int - En `PenAlignment` som representerar justeringen för denna `Pen`.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Ställer in justeringen för denna `Pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En `PenAlignment` som representerar justeringen för denna `Pen`. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Hämtar en kopia av den geometriska transformationen för denna `Pen`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Matrix` that represents the geometric transformation for this `Pen`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Ställer in en kopia av den geometriska transformationen för denna `Pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | En kopia av `Matrix` som representerar den geometriska transformationen för denna `Pen`. |

### getPenType() {#getPenType--}
```
public int getPenType()
```


Hämtar stilen för linjer som ritas med denna `Pen`.

**Returns:**
int - En `PenType`-enumeration som specificerar stilen på linjer som ritas med denna `Pen`.
### getColor() {#getColor--}
```
public Color getColor()
```


Hämtar färgen på denna `Pen`.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `Color` structure that represents the color of this `Pen`.
### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Ställer in färgen på denna `Pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | En `Color`-struktur som representerar färgen på denna `Pen`. |

### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Hämtar `Brush` som bestämmer attribut för denna `Pen`.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A `Brush` that determines attributes of this `Pen`.
### setBrush(Brush value) {#setBrush-com.aspose.imaging.Brush-}
```
public void setBrush(Brush value)
```


Ställer in `Brush` som bestämmer attribut för denna `Pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Brush](../../com.aspose.imaging/brush) | En `Brush` som bestämmer attributen för denna `Pen`. |

### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Hämtar stilen som används för streckade linjer som ritas med denna `Pen`.

**Returns:**
int - En `DashStyle` som representerar stilen som används för streckade linjer som ritas med denna `Pen`.
### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Ställer in stilen som används för streckade linjer som ritas med denna `Pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En `DashStyle` som representerar stilen som används för streckade linjer som ritas med denna `Pen`. |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Hämtar avståndet från början av en linje till början av ett streckmönster.

**Returns:**
float - Avståndet från början av en linje till början av ett streckmönster.
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Ställer in avståndet från början av en linje till början av ett streckmönster.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Avståndet från början av en linje till början av ett streckmönster. |

### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Hämtar en array av anpassade streck och mellanslag.

**Returns:**
float[] - En array av reella tal som specificerar längderna på alternerande streck och mellanslag i streckade linjer.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Ställer in en array av anpassade streck och mellanslag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float[] | En array av reella tal som specificerar längderna på alternerande streck och mellanslag i streckade linjer. |

### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Hämtar en array av värden som specificerar en compound pen. En compound pen ritar en compound line bestående av parallella linjer och mellanrum.

**Returns:**
float[] - En array av reella tal som specificerar compound-arrayen. Elementen i arrayen måste vara i stigande ordning, inte mindre än 0 och inte större än 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Ställer in en array av värden som specificerar en compound pen. En compound pen ritar en compound line bestående av parallella linjer och mellanrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float[] | En array av reella tal som specificerar compound-arrayen. Elementen i arrayen måste vara i stigande ordning, inte mindre än 0 och inte större än 1. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Ställer in värdena som bestämmer stil för ändkappa som används för att avsluta linjer ritade med denna `Pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startCap | int | En `LineCap` som representerar kapslingsstilen att använda i början av linjer som ritas med denna `Pen`. |
| endCap | int | En `LineCap` som representerar kapslingsstilen att använda i slutet av linjer som ritas med denna `Pen`. |
| dashCap | int | En `LineCap` som representerar kapslingsstilen att använda i början eller slutet av streckade linjer som ritas med denna `Pen`. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Återställer den geometriska transformationsmatrisen för denna `Pen` till identitet.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplicerar transformationsmatrisen för denna `Pen` med den angivna `Matrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Det `Matrix`-objektet som ska multipliceras med transformationsmatrisen. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplicerar transformationsmatrisen för denna `Pen` med den angivna `Matrix` i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Den `Matrix` som ska multipliceras med transformationsmatrisen. |
| order | int | Den ordning i vilken multiplikationsoperationen ska utföras. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger till förflyttningen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Värdet för förflyttningen i x. |
| dy | float | Värdet för förflyttningen i y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Värdet för förflyttningen i x. |
| dy | float | Värdet för förflyttningen i y. |
| order | int | Den ordning (före eller efter) i vilken förflyttningen ska tillämpas. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skalar den lokala geometriska transformationen med de angivna faktorerna. Denna metod lägger till skalningsmatrisen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Faktorn som ska skala transformationen i x‑axelns riktning. |
| sy | float | Faktorn som ska skala transformationen i y‑axelns riktning. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Faktorn som ska skala transformationen i x‑axelns riktning. |
| sy | float | Faktorn som ska skala transformationen i y‑axelns riktning. |
| order | int | En `MatrixOrder` som anger om skalningsmatrisen ska läggas till i slutet eller i början. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roterar den lokala geometriska transformationen med den angivna vinkeln. Denna metod lägger till rotationen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rotera den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln. |
| order | int | En `MatrixOrder` som anger om rotationsmatrisen ska läggas till i slutet eller i början. |

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
int
