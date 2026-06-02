---
title: "Matrix"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Ersetzt die GDI‑Matrix."
type: docs
weight: 72
url: /de/java/com.aspose.imaging/matrix/
---
**Inheritance:**
java.lang.Object
```
public class Matrix
```

Ersetzt die GDI+‑Matrix.

--------------------

Die meisten Algorithmen stammen aus Sun's AffineTransform.java. Java‑Namen für Matrix‑Elemente werden intern verwendet. Zuordnung von Java‑Namen zu .net‑Namen mit Beschreibung: m00 M11 Skalierung X m10 M12 Scherung Y m01 M21 Scherung X m11 M22 Skalierung Y m02 M31 Translation X m12 M32 Translation Y
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Matrix()](#Matrix--) | Initialisiert eine neue Instanz der Matrix‑Klasse als Einheitsmatrix. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Initialisiert eine neue Instanz der [Matrix](../../com.aspose.imaging/matrix)-Klasse. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---) | Initialisiert eine neue Instanz der [Matrix](../../com.aspose.imaging/matrix)-Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---) | Initialisiert eine neue Instanz der [Matrix](../../com.aspose.imaging/matrix)-Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.imaging.Matrix-) | Erstellt eine Kopie der [Matrix](../../com.aspose.imaging/matrix)-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Eine Identitätstransformation ist eine, bei der die Ausgabekoordinaten immer den Eingabekoordinaten entsprechen. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Eine Translation verschiebt die Koordinaten um einen konstanten Betrag in x und y, ohne die Länge oder den Winkel von Vektoren zu ändern. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Eine einheitliche Skalierung multipliziert die Länge von Vektoren in sowohl x‑ als auch y‑Richtung um denselben Betrag, ohne den Winkel zwischen den Vektoren zu ändern. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Eine allgemeine Skalierung multipliziert die Länge von Vektoren um unterschiedliche Beträge in den x‑ und y‑Richtungen, ohne den Winkel zwischen senkrechten Vektoren zu ändern. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Diese Konstante ist eine Bitmaske für beliebige der Skalierungs‑Flag‑Bits. |
| [TYPE_FLIP](#TYPE-FLIP) | Dieses Flag‑Bit zeigt an, dass die durch dieses Objekt definierte Transformation eine Spiegelung um eine Achse durchführt, die das normalerweise rechtshändige Koordinatensystem in ein linkshändiges System ändert, zusätzlich zu den durch andere Flag‑Bits angegebenen Umwandlungen. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Dieses Flag‑Bit zeigt an, dass die durch dieses Objekt definierte Transformation eine Quadrant‑Drehung um ein Vielfaches von 90 Grad ausführt, zusätzlich zu den durch andere Flag‑Bits angegebenen Umwandlungen. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Dieses Flag‑Bit zeigt an, dass die durch dieses Objekt definierte Transformation eine Drehung um einen beliebigen Winkel ausführt, zusätzlich zu den durch andere Flag‑Bits angegebenen Umwandlungen. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Diese Konstante ist eine Bitmaske für beliebige der Rotations‑Flag‑Bits. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Diese Konstante zeigt an, dass die durch dieses Objekt definierte Transformation eine beliebige Umwandlung der Eingabekoordinaten vornimmt. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-) | Bestimmt, ob zwei Matrizen gleich sind. |
| [getM11()](#getM11--) | Liefert das Matrix‑Element in der ersten Zeile, ersten Spalte. |
| [getM12()](#getM12--) | Liefert das Matrix‑Element in der ersten Zeile, zweiten Spalte. |
| [getM21()](#getM21--) | Liefert das Matrix‑Element in der zweiten Zeile, ersten Spalte. |
| [getM22()](#getM22--) | Liefert das Matrix‑Element in der zweiten Zeile, zweiten Spalte. |
| [getM31()](#getM31--) | Liefert das Matrix‑Element in der dritten Zeile, ersten Spalte. |
| [getM32()](#getM32--) | Liefert das Matrix‑Element in der dritten Zeile, ersten Spalte. |
| [toString()](#toString--) | Gibt einen String zurück, der diese Instanz darstellt. |
| [getElements()](#getElements--) | Liefert eine Kopie der Matrix‑Elemente. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.imaging.PointF---) | Wendet die geometrische Transformation, die durch diese [Matrix](../../com.aspose.imaging/matrix) dargestellt wird, auf ein angegebenes Array von Punkten an. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese [Matrix](../../com.aspose.imaging/matrix) unter Verwendung der angegebenen Reihenfolge an. |
| [scale(float sx, float sy)](#scale-float-float-) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese Matrix unter Verwendung der (Standard‑)Prepend‑Reihenfolge an. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Wendet den angegebenen Translationsvektor auf diese Matrix in der angegebenen Reihenfolge an. |
| [translate(float tx, float ty)](#translate-float-float-) | Wendet den angegebenen Translationsvektor auf diese [Matrix](../../com.aspose.imaging/matrix) unter Verwendung der (Standard‑)Prepend‑Reihenfolge an. |
| [multiply(Matrix tTx, int order)](#multiply-com.aspose.imaging.Matrix-int-) | Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix und in der im Parameter order angegebenen Reihenfolge. |
| [multiply(Matrix tTx)](#multiply-com.aspose.imaging.Matrix-) | Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix unter Verwendung der (Standard‑)Prepend‑Reihenfolge. |
| [rotate(float angle, int order)](#rotate-float-int-) | Wendet eine im Parameter angle angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der angegebenen Reihenfolge an. |
| [rotate(float angle)](#rotate-float-) | Wendet eine im Parameter angle angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der Standard‑(Prepend‑)Reihenfolge an. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.imaging.PointF-int-) | Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der angegebenen Reihenfolge an. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.imaging.PointF-) | Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der Standard‑(Prepend‑)Reihenfolge an. |
| [reset()](#reset--) | Setzt diese Matrix zurück, sodass sie die Elemente der Einheitsmatrix enthält. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene `Object` gleich dieser Instanz ist. |
| [isIdentity()](#isIdentity--) | Gibt `true` zurück, wenn dieses `AffineTransform` eine Identitätstransformation ist. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Initialisiert eine neue Instanz der Matrix‑Klasse als Einheitsmatrix.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Initialisiert eine neue Instanz der [Matrix](../../com.aspose.imaging/matrix)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| m11 | float | m00 M11 Skalierung X |
| m12 | float | m10 M12 Scheren Y |
| m21 | float | m01 M21 Scheren X |
| m22 | float | m11 M22 Skalierung Y |
| m31 | float | m02 M31 Translation X |
| m32 | float | m12 M32 Translation Y |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Initialisiert eine neue Instanz der [Matrix](../../com.aspose.imaging/matrix)-Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Eine [RectangleF](../../com.aspose.imaging/rectanglef)-Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | [PointF\[\]](../../com.aspose.imaging/pointf) | Ein Array aus drei [PointF](../../com.aspose.imaging/pointf)-Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die oberen linken, oberen rechten und unteren linken Ecken des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Initialisiert eine neue Instanz der [Matrix](../../com.aspose.imaging/matrix)-Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Eine [Rectangle](../../com.aspose.imaging/rectangle)-Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | [Point\[\]](../../com.aspose.imaging/point) | Ein Array aus drei [Point](../../com.aspose.imaging/point)-Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die oberen linken, oberen rechten und unteren linken Ecken des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### Matrix(Matrix origin) {#Matrix-com.aspose.imaging.Matrix-}
```
public Matrix(Matrix origin)
```


Erstellt eine Kopie der [Matrix](../../com.aspose.imaging/matrix)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.imaging/matrix) | Eine Basis-Matrix zum Kopieren. |

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Eine Identitätstransformation ist eine, bei der die Ausgabekoordinaten stets mit den Eingabekoordinaten übereinstimmen. Wenn diese Transformation etwas anderes als die Identitätstransformation ist, wird der Typ entweder die Konstante GENERAL\_TRANSFORM sein oder eine Kombination der entsprechenden Flag‑Bits für die verschiedenen Koordinatenkonvertierungen, die diese Transformation durchführt.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Eine Translation verschiebt die Koordinaten um einen konstanten Betrag in x und y, ohne die Länge oder den Winkel von Vektoren zu ändern.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Eine einheitliche Skalierung multipliziert die Länge von Vektoren in sowohl x‑ als auch y‑Richtung um denselben Betrag, ohne den Winkel zwischen den Vektoren zu ändern. Dieses Flag‑Bit ist wechselseitig exklusiv zum Flag TypeGeneralScale.

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Eine allgemeine Skalierung multipliziert die Länge von Vektoren in x‑ und y‑Richtung um unterschiedliche Beträge, ohne den Winkel zwischen senkrechten Vektoren zu ändern. Dieses Flag‑Bit ist wechselseitig exklusiv zum Flag TypeUniformScale.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Diese Konstante ist eine Bitmaske für beliebige der Skalierungs‑Flag‑Bits.

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Dieses Flag‑Bit zeigt an, dass die von diesem Objekt definierte Transformation eine Spiegelbild‑Umkehr um eine Achse durchführt, die das normalerweise rechtshändige Koordinatensystem in ein linkshändiges System umwandelt, zusätzlich zu den von anderen Flag‑Bits angegebenen Konvertierungen. Ein rechtshändiges Koordinatensystem ist eines, bei dem die positive X‑Achse sich gegen den Uhrzeigersinn dreht, um die positive Y‑Achse zu überlagern, ähnlich der Richtung, in die sich die Finger Ihrer rechten Hand krümmen, wenn Sie Ihren Daumen frontal betrachten. Ein linkshändiges Koordinatensystem ist eines, bei dem die positive X‑Achse sich im Uhrzeigersinn dreht, um die positive Y‑Achse zu überlagern, ähnlich der Richtung, in die sich die Finger Ihrer linken Hand krümmen. Es gibt keinen mathematischen Weg, den Winkel der ursprünglichen Umkehr‑ oder Spiegelungs­transformation zu bestimmen, da alle Umkehrwinkel bei einer geeigneten nachfolgenden Rotation identisch sind. HINWEIS: TypeFlip wurde hinzugefügt, nachdem GENERAL\_TRANSFORM bereits öffentlich verbreitet war, und die Flag‑Bits konnten nicht mehr bequem neu nummeriert werden, ohne eine binäre Inkompatibilität im externen Code zu verursachen.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Dieses Flag‑Bit zeigt an, dass die von diesem Objekt definierte Transformation eine Quadrant‑Drehung um ein Vielfaches von 90 Grad durchführt, zusätzlich zu den von anderen Flag‑Bits angegebenen Konvertierungen. Eine Drehung ändert die Winkel von Vektoren um denselben Betrag, unabhängig von der ursprünglichen Richtung des Vektors, und ohne die Länge des Vektors zu verändern. Dieses Flag‑Bit ist wechselseitig exklusiv zum Flag TypeGeneralRotation.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Dieses Flag‑Bit zeigt an, dass die durch dieses Objekt definierte Transformation eine Drehung um einen beliebigen Winkel zusätzlich zu den durch andere Flag‑Bits angegebenen Umwandlungen durchführt. Eine Drehung ändert die Winkel von Vektoren um denselben Betrag, unabhängig von der ursprünglichen Richtung des Vektors und ohne die Länge des Vektors zu verändern. Dieses Flag‑Bit ist wechselseitig ausschließend mit dem

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Diese Konstante ist eine Bitmaske für beliebige der Rotations‑Flag‑Bits.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Diese Konstante gibt an, dass die durch dieses Objekt definierte Transformation eine beliebige Umwandlung der Eingabekoordinaten durchführt. Wenn diese Transformation durch eine der oben genannten Konstanten klassifiziert werden kann, ist der Typ entweder die Konstante TypeIdentity oder eine Kombination der entsprechenden Flag‑Bits für die verschiedenen Koordinatenumwandlungen, die diese Transformation ausführt.

### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Bestimmt, ob zwei Matrizen gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.imaging/matrix) | Die erste Matrix zum Vergleich. |
| b | [Matrix](../../com.aspose.imaging/matrix) | Die zweite Matrix zum Vergleich. |

**Returns:**
boolean - Wahr, wenn Matrizen gleich sind.
### getM11() {#getM11--}
```
public final float getM11()
```


Liefert das Matrixelement in der ersten Zeile, ersten Spalte. Stellt die Skalierung entlang der X‑Achse dar.

**Returns:**
float - das Matrixelement in der ersten Zeile, ersten Spalte.
### getM12() {#getM12--}
```
public final float getM12()
```


Liefert das Matrixelement in der ersten Zeile, zweiten Spalte. Stellt die Scherung entlang der Y‑Achse dar.

**Returns:**
float - das Matrixelement in der ersten Zeile, zweiten Spalte.
### getM21() {#getM21--}
```
public final float getM21()
```


Liefert das Matrixelement in der zweiten Zeile, ersten Spalte. Stellt die Scherung entlang der X‑Achse dar.

**Returns:**
float - das Matrixelement in der zweiten Zeile, ersten Spalte.
### getM22() {#getM22--}
```
public final float getM22()
```


Liefert das Matrixelement in der zweiten Zeile, zweiten Spalte. Stellt die Skalierung entlang der Y‑Achse dar.

**Returns:**
float - das Matrixelement in der zweiten Zeile, zweiten Spalte.
### getM31() {#getM31--}
```
public final float getM31()
```


Liefert das Matrixelement in der dritten Zeile, ersten Spalte. Stellt die Translation entlang der X‑Achse dar.

**Returns:**
float - das Matrixelement in der dritten Zeile, ersten Spalte.
### getM32() {#getM32--}
```
public final float getM32()
```


Liefert das Matrixelement in der dritten Zeile, ersten Spalte. Stellt die Translation entlang der Y‑Achse dar.

**Returns:**
float - das Matrixelement in der dritten Zeile, ersten Spalte.
### toString() {#toString--}
```
public String toString()
```


Gibt einen String zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein String, der diese Instanz darstellt.
### getElements() {#getElements--}
```
public final float[] getElements()
```


Liefert eine Kopie der Matrix‑Elemente.

**Returns:**
float[] - Eine Kopie der Matrixelemente.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.imaging.PointF---}
```
public final void transformPoints(PointF[] points)
```


Wendet die geometrische Transformation, die durch diese [Matrix](../../com.aspose.imaging/matrix) dargestellt wird, auf ein angegebenes Array von Punkten an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Die Punkte. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public final void scale(float scaleX, float scaleY, int order)
```


Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese [Matrix](../../com.aspose.imaging/matrix) unter Verwendung der angegebenen Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleX | float | Die Skalierung X. |
| scaleY | float | Die Skalierung Y. |
| order | int | Die Reihenfolge. |

### scale(float sx, float sy) {#scale-float-float-}
```
public final void scale(float sx, float sy)
```


Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese Matrix unter Verwendung der (Standard‑)Prepend‑Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der sx. Der sx. Der sx. |
| sy | float | Der sy. Der sy. Der sy. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public final void translate(float offsetX, float offsetY, int order)
```


Wendet den angegebenen Translationsvektor auf diese Matrix in der angegebenen Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offsetX | float | Der offset X. |
| offsetY | float | Der offset Y. |
| order | int | Die Reihenfolge. |

### translate(float tx, float ty) {#translate-float-float-}
```
public final void translate(float tx, float ty)
```


Wendet den angegebenen Translationsvektor auf diese [Matrix](../../com.aspose.imaging/matrix) unter Verwendung der (Standard‑)Prepend‑Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tx | float | Der tx. Der tx. Der tx. |
| ty | float | Der ty. Der ty. Der ty. |

### multiply(Matrix tTx, int order) {#multiply-com.aspose.imaging.Matrix-int-}
```
public final void multiply(Matrix tTx, int order)
```


Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix und in der im Parameter order angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | Der tx. Der tx. Der tx. |
| order | int | Die Reihenfolge. Die Reihenfolge. Die Reihenfolge. |

### multiply(Matrix tTx) {#multiply-com.aspose.imaging.Matrix-}
```
public final void multiply(Matrix tTx)
```


Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix unter Verwendung der (Standard‑)Prepend‑Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | Die Matrix, mit der multipliziert wird. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public final void rotate(float angle, int order)
```


Wendet eine im Parameter angle angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der angegebenen Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel. |
| order | int | Die Matrixreihenfolge. |

### rotate(float angle) {#rotate-float-}
```
public final void rotate(float angle)
```


Wendet eine im Parameter angle angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der Standard‑(Prepend‑)Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.imaging.PointF-int-}
```
public final void rotateAt(float angle, PointF point, int order)
```


Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der angegebenen Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Winkel. |
| point | [PointF](../../com.aspose.imaging/pointf) | Der Punkt. |
| order | int | Die Reihenfolge. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.imaging.PointF-}
```
public final void rotateAt(float angle, PointF point)
```


Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der Standard‑(Prepend‑)Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Winkel. |
| point | [PointF](../../com.aspose.imaging/pointf) | Der Punkt. |

### reset() {#reset--}
```
public final void reset()
```


Setzt diese Matrix zurück, sodass sie die Elemente der Einheitsmatrix enthält.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int – Ein Hashcode für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene `Object` gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das `Object` zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - `true` wenn das angegebene `Object` dieser Instanz gleich ist; andernfalls `false`.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Gibt `true` zurück, wenn dieses `AffineTransform` eine Identitätstransformation ist.

**Returns:**
boolean - `true` wenn dieses `AffineTransform` eine Identitätstransformation ist; `false` andernfalls.
