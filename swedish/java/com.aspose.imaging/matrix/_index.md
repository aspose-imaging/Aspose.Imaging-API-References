---
title: "Matrix"
second_title: "Aspose.Imaging för Java API-referens"
description: "Ersätter GDI-matrisen."
type: docs
weight: 72
url: /sv/java/com.aspose.imaging/matrix/
---
**Inheritance:**
java.lang.Object
```
public class Matrix
```

Ersätter GDI+ Matrix.

--------------------

De flesta algoritmer hämtade från Suns AffineTransform.java. Javas namn för matriselement som används internt. Karta över java-namn till .net-namn till beskrivning: m00 M11 Skala X m10 M12 Skjuv Y m01 M21 Skjuv X m11 M22 Skala Y m02 M31 Översätt X m12 M32 Översätt Y
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Matrix()](#Matrix--) | Initierar en ny instans av Matrix-klassen som identitetsmatris. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Initierar en ny instans av [Matrix](../../com.aspose.imaging/matrix)-klassen. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---) | Initierar en ny instans av [Matrix](../../com.aspose.imaging/matrix)-klassen till den geometriska transformationen som definieras av den angivna rektangeln och punktarrayen. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---) | Initierar en ny instans av [Matrix](../../com.aspose.imaging/matrix)-klassen till den geometriska transformationen som definieras av den angivna rektangeln och punktarrayen. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.imaging.Matrix-) | Skapar en kopia av [Matrix](../../com.aspose.imaging/matrix)-klassen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | En identitetstransform är en där utdata-koordinaterna alltid är samma som indata-koordinaterna. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | En translation flyttar koordinaterna med ett konstant värde i x och y utan att ändra vektorns längd eller vinkel. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | En enhetlig skala multiplicerar vektorns längd med samma värde i både x- och y-riktningarna utan att ändra vinkeln mellan vektorerna. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | En allmän skalning multiplicerar längden på vektorer med olika värden i x- och y-riktningarna utan att ändra vinkeln mellan vinkelräta vektorer. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Denna konstant är en bitmask för någon av skalningsflaggbitarna. |
| [TYPE_FLIP](#TYPE-FLIP) | Denna flaggbit indikerar att transformen som definieras av detta objekt utför en spegelvändning kring någon axel som ändrar det normalt högervriddna koordinatsystemet till ett vänstervridet system, utöver de konverteringar som anges av andra flaggbitar. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Denna flaggbit indikerar att transformen som definieras av detta objekt utför en kvadrantrotation med någon multipel av 90 grader, utöver de konverteringar som anges av andra flaggbitar. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Denna flaggbit indikerar att transformen som definieras av detta objekt utför en rotation med en godtycklig vinkel, utöver de konverteringar som anges av andra flaggbitar. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Denna konstant är en bitmask för någon av rotationsflaggbitarna. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Denna konstant indikerar att transformen som definieras av detta objekt utför en godtycklig konvertering av inmatningskoordinaterna. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-) | Bestämmer om två matriser är lika. |
| [getM11()](#getM11--) | Hämtar matriselementet i första raden första kolumnen. |
| [getM12()](#getM12--) | Hämtar matriselementet i första raden andra kolumnen. |
| [getM21()](#getM21--) | Hämtar matriselementet i andra raden första kolumnen. |
| [getM22()](#getM22--) | Hämtar matriselementet i andra raden andra kolumnen. |
| [getM31()](#getM31--) | Hämtar matriselementet i tredje raden första kolumnen. |
| [getM32()](#getM32--) | Hämtar matriselementet i tredje raden första kolumnen. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [getElements()](#getElements--) | Hämtar en kopia av matrisens element. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.imaging.PointF---) | Tillämpar den geometriska transformen som representeras av denna [Matrix](../../com.aspose.imaging/matrix) på en specificerad punktarray. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Tillämpar den specificerade skalvektorn (scaleX och scaleY) på denna [Matrix](../../com.aspose.imaging/matrix) med den angivna ordningen. |
| [scale(float sx, float sy)](#scale-float-float-) | Tillämpar den specificerade skalvektorn (scaleX och scaleY) på denna Matrix med (standard) Prepend‑ordning. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Tillämpar den specificerade translationsvektorn på denna Matrix i den angivna ordningen. |
| [translate(float tx, float ty)](#translate-float-float-) | Tillämpar den specificerade translationsvektorn på denna [Matrix](../../com.aspose.imaging/matrix) med (standard) Prepend‑ordning. |
| [multiply(Matrix tTx, int order)](#multiply-com.aspose.imaging.Matrix-int-) | Multiplicerar denna Matrix med den matris som anges i matris‑parametern, och i den ordning som anges i order‑parametern. |
| [multiply(Matrix tTx)](#multiply-com.aspose.imaging.Matrix-) | Multiplicerar denna Matrix med den matris som anges i matris‑parametern med (standard) Prepend‑ordning. |
| [rotate(float angle, int order)](#rotate-float-int-) | Tillämpar en medursrotation med en mängd som anges i vinkel‑parametern, kring origo (noll x‑ och y‑koordinater) för denna Matrix i den angivna ordningen. |
| [rotate(float angle)](#rotate-float-) | Tillämpar en medursrotation med en mängd som anges i vinkel‑parametern, kring origo (noll x‑ och y‑koordinater) för denna Matrix i standard (Prepend)‑ordning. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.imaging.PointF-int-) | Tillämpar en medursrotation kring den specificerade punkten på denna Matrix i den angivna ordningen. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.imaging.PointF-) | Tillämpar en medursrotation kring den specificerade punkten på denna Matrix i standard (Prepend)‑ordning. |
| [reset()](#reset--) | Återställer denna matris så att den har elementerna i identitetsmatrisen. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna `Object` är lika med detta objekt. |
| [isIdentity()](#isIdentity--) | Returnerar `true` om denna `AffineTransform` är en identitetstransform. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Initierar en ny instans av Matrix-klassen som identitetsmatris.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Initierar en ny instans av [Matrix](../../com.aspose.imaging/matrix)-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| m11 | float | m00 M11 Skala X |
| m12 | float | m10 M12 Skjuv Y |
| m21 | float | m01 M21 Skjuv X |
| m22 | float | m11 M22 Skala Y |
| m31 | float | m02 M31 Översätt X |
| m32 | float | m12 M32 Översätt Y |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Initierar en ny instans av [Matrix](../../com.aspose.imaging/matrix)-klassen till den geometriska transformationen som definieras av den angivna rektangeln och punktarrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | En [RectangleF](../../com.aspose.imaging/rectanglef)-struktur som representerar rektangeln som ska transformeras. |
| plgpts | [PointF\[\]](../../com.aspose.imaging/pointf) | En array med tre [PointF](../../com.aspose.imaging/pointf)-strukturer som representerar punkterna i ett parallellogram till vilket det övre vänstra, övre högra och nedre vänstra hörnet av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet antas av de första tre hörnen. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Initierar en ny instans av [Matrix](../../com.aspose.imaging/matrix)-klassen till den geometriska transformationen som definieras av den angivna rektangeln och punktarrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | En [Rectangle](../../com.aspose.imaging/rectangle)-struktur som representerar rektangeln som ska transformeras. |
| plgpts | [Point\[\]](../../com.aspose.imaging/point) | En array med tre [Point](../../com.aspose.imaging/point)-strukturer som representerar punkterna i ett parallellogram till vilket det övre vänstra, övre högra och nedre vänstra hörnet av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet antas av de första tre hörnen. |

### Matrix(Matrix origin) {#Matrix-com.aspose.imaging.Matrix-}
```
public Matrix(Matrix origin)
```


Skapar en kopia av [Matrix](../../com.aspose.imaging/matrix)-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.imaging/matrix) | En basmatris för kopiering |

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


En identitetstransform är en där utdata-koordinaterna alltid är samma som indata-koordinaterna. Om denna transform är något annat än en identitetstransform kommer typen antingen att vara konstanten GENERAL\_TRANSFORM eller en kombination av lämpliga flaggbitar för de olika koordinatkonverteringar som denna transform utför.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


En translation flyttar koordinaterna med ett konstant värde i x och y utan att ändra vektorns längd eller vinkel.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


En enhetlig skalning multiplicerar vektorlängden med samma mängd i både x- och y-riktningarna utan att ändra vinkeln mellan vektorerna. Denna flaggbit är ömsesidigt uteslutande med flaggan TypeGeneralScale.

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


En generell skalning multiplicerar vektorlängden med olika mängder i x- och y-riktningarna utan att ändra vinkeln mellan vinkelräta vektorer. Denna flaggbit är ömsesidigt uteslutande med flaggan TypeUniformScale.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Denna konstant är en bitmask för någon av skalningsflaggbitarna.

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Denna flaggbit indikerar att den transform som definieras av detta objekt utför en spegelvändning kring någon axel, vilket förändrar det normalt högerriktade koordinatsystemet till ett vänsterhänt system utöver de konverteringar som anges av andra flaggbitar. Ett högerriktat koordinatsystem är ett där den positiva X-axeln roterar moturs för att överlappa den positiva Y-axeln, liknande den riktning som fingrarna på din högra hand kröker sig när du tittar rakt på tummen. Ett vänsterhänt koordinatsystem är ett där den positiva X-axeln roterar medurs för att överlappa den positiva Y-axeln, liknande den riktning som fingrarna på din vänstra hand kröker sig. Det finns inget matematiskt sätt att bestämma vinkeln för den ursprungliga vändnings- eller speglingstransformen eftersom alla vändningsvinklar är identiska givet en lämplig justerande rotation. OBS: TypeFlip lades till efter att GENERAL\_TRANSFORM var i offentlig cirkulation och flaggbitarna kunde inte längre bekvämt omnumreras utan att introducera binär inkompatibilitet i extern kod.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Denna flaggbit indikerar att den transform som definieras av detta objekt utför en kvadrantrotation med någon multipel av 90 grader utöver de konverteringar som anges av andra flaggbitar. En rotation förändrar vektorernas vinklar med samma mängd oavsett vektorns ursprungliga riktning och utan att ändra vektorns längd. Denna flaggbit är ömsesidigt uteslutande med flaggan TypeGeneralRotation.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Denna flaggbits indikerar att transformen som definieras av detta objekt utför en rotation med en godtycklig vinkel utöver de konverteringar som anges av andra flaggbitar. En rotation ändrar vektorns vinklar med samma mängd oavsett vektorns ursprungliga riktning och utan att ändra vektorns längd. Denna flaggbits är ömsesidigt uteslutande med den

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Denna konstant är en bitmask för någon av rotationsflaggbitarna.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Denna konstant indikerar att transformen som definieras av detta objekt utför en godtycklig konvertering av inmatningskoordinaterna. Om denna transform kan klassificeras av någon av ovanstående konstanter kommer typen antingen att vara konstanten TypeIdentity eller en kombination av lämpliga flaggbitar för de olika koordinatkonverteringar som denna transform utför.

### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Bestämmer om två matriser är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.imaging/matrix) | Den första matrisen att jämföra. |
| b | [Matrix](../../com.aspose.imaging/matrix) | Den andra matrisen att jämföra. |

**Returns:**
boolean - Sant om matriserna är lika.
### getM11() {#getM11--}
```
public final float getM11()
```


Hämtar matriselementet i första raden första kolumnen. Representerar skalning längs X-axeln.

**Returns:**
float - matriselementet i första raden första kolumnen.
### getM12() {#getM12--}
```
public final float getM12()
```


Hämtar matriselementet i första raden andra kolumnen. Representerar skevning längs Y-axeln.

**Returns:**
float - matriselementet i första raden andra kolumnen.
### getM21() {#getM21--}
```
public final float getM21()
```


Hämtar matriselementet i andra raden första kolumnen. Representerar skevning längs X-axeln.

**Returns:**
float - matriselementet i andra raden första kolumnen.
### getM22() {#getM22--}
```
public final float getM22()
```


Hämtar matriselementet i andra raden andra kolumnen. Representerar skalning längs Y-axeln.

**Returns:**
float - matriselementet i andra raden andra kolumnen.
### getM31() {#getM31--}
```
public final float getM31()
```


Hämtar matriselementet i tredje raden första kolumnen. Representerar translation längs X-axeln.

**Returns:**
float - matriselementet i tredje raden första kolumnen.
### getM32() {#getM32--}
```
public final float getM32()
```


Hämtar matriselementet i tredje raden första kolumnen. Representerar translation längs Y-axeln.

**Returns:**
float - matriselementet i tredje raden första kolumnen.
### toString() {#toString--}
```
public String toString()
```


Returnerar en String som representerar detta objekt.

**Returns:**
java.lang.String - En sträng som representerar detta objekt.
### getElements() {#getElements--}
```
public final float[] getElements()
```


Hämtar en kopia av matrisens element.

**Returns:**
float[] - En kopia av matrisens element.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.imaging.PointF---}
```
public final void transformPoints(PointF[] points)
```


Tillämpar den geometriska transformen som representeras av denna [Matrix](../../com.aspose.imaging/matrix) på en specificerad punktarray.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Punkterna. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public final void scale(float scaleX, float scaleY, int order)
```


Tillämpar den specificerade skalvektorn (scaleX och scaleY) på denna [Matrix](../../com.aspose.imaging/matrix) med den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleX | float | Skalning X. |
| scaleY | float | Skalning Y. |
| order | int | Ordningen. |

### scale(float sx, float sy) {#scale-float-float-}
```
public final void scale(float sx, float sy)
```


Tillämpar den specificerade skalvektorn (scaleX och scaleY) på denna Matrix med (standard) Prepend‑ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | sx:et. sx:et. sx:et. |
| sy | float | sy:et. sy:et. sy:et. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public final void translate(float offsetX, float offsetY, int order)
```


Tillämpar den specificerade translationsvektorn på denna Matrix i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offsetX | float | offset X:et. |
| offsetY | float | offset Y:et. |
| order | int | Ordningen. |

### translate(float tx, float ty) {#translate-float-float-}
```
public final void translate(float tx, float ty)
```


Tillämpar den specificerade translationsvektorn på denna [Matrix](../../com.aspose.imaging/matrix) med (standard) Prepend‑ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tx | float | tx:et. tx:et. tx:et. |
| ty | float | ty:et. ty:et. ty:et. |

### multiply(Matrix tTx, int order) {#multiply-com.aspose.imaging.Matrix-int-}
```
public final void multiply(Matrix tTx, int order)
```


Multiplicerar denna Matrix med den matris som anges i matris‑parametern, och i den ordning som anges i order‑parametern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | tx:et. tx:et. tx:et. |
| order | int | ordningen. ordningen. ordningen. |

### multiply(Matrix tTx) {#multiply-com.aspose.imaging.Matrix-}
```
public final void multiply(Matrix tTx)
```


Multiplicerar denna Matrix med den matris som anges i matris‑parametern med (standard) Prepend‑ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | matrisen att multiplicera med. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public final void rotate(float angle, int order)
```


Tillämpar en medursrotation med en mängd som anges i vinkel‑parametern, kring origo (noll x‑ och y‑koordinater) för denna Matrix i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | rotationsvinkeln. |
| order | int | matrisordningen. |

### rotate(float angle) {#rotate-float-}
```
public final void rotate(float angle)
```


Tillämpar en medursrotation med en mängd som anges i vinkel‑parametern, kring origo (noll x‑ och y‑koordinater) för denna Matrix i standard (Prepend)‑ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | rotationsvinkeln. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.imaging.PointF-int-}
```
public final void rotateAt(float angle, PointF point, int order)
```


Tillämpar en medursrotation kring den specificerade punkten på denna Matrix i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | vinkeln. |
| point | [PointF](../../com.aspose.imaging/pointf) | punkten. |
| order | int | Ordningen. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.imaging.PointF-}
```
public final void rotateAt(float angle, PointF point)
```


Tillämpar en medursrotation kring den specificerade punkten på denna Matrix i standard (Prepend)‑ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | vinkeln. |
| point | [PointF](../../com.aspose.imaging/pointf) | punkten. |

### reset() {#reset--}
```
public final void reset()
```


Återställer denna matris så att den har elementerna i identitetsmatrisen.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna `Object` är lika med detta objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det `Object` att jämföra med den här instansen. |

**Returns:**
boolean - `true` om det angivna `Object` är lika med den här instansen; annars `false`.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Returnerar `true` om denna `AffineTransform` är en identitetstransform.

**Returns:**
boolean - `true` om detta `AffineTransform` är en identitetstransform; `false` annars.
