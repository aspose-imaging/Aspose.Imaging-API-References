---
title: "SolidBrush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le pinceau plein est destiné au dessin continu avec une couleur spécifique."
type: docs
weight: 17
url: /fr/java/com.aspose.imaging.brushes/solidbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class SolidBrush extends Brush
```

Le pinceau plein est destiné au dessin continu avec une couleur spécifique. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | Initialise une nouvelle instance de la classe `SolidBrush`. |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.imaging.Color-) | Initialise une nouvelle instance de la classe `SolidBrush`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColor()](#getColor--) | Obtient ou définit la couleur du pinceau. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Obtient ou définit la couleur du pinceau. |
| [hashCode()](#hashCode--) |  |
| [equals(Object object)](#equals-java.lang.Object-) |  |

## Example: This example uses Graphics class to create primitive shapes on the Image surface.
Cet exemple utilise la classe Graphics pour créer des formes primitives sur la surface Image. Pour démontrer l'opération, l'exemple crée une nouvelle Image au format PNG et dessine des formes primitives sur la surface Image en utilisant les méthodes Draw exposées par la classe Graphics.
``` java
// Crée une instance de FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Créez une instance de PngOptions et définissez ses différentes propriétés
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Définissez la source pour PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Créer une instance de Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Créer et initialiser une instance de la classe Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Effacer la surface Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Dessinez un arc en spécifiant l'objet Pen ayant la couleur Black com.aspose.imaging.Color,
        // un Rectangle entourant l'arc, l'angle de départ et l'angle de balayage
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Dessinez un Bézier en spécifiant l'objet Pen ayant la couleur Blue com.aspose.imaging.Color et les points de coordonnées.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Dessinez une courbe en spécifiant l'objet Pen ayant la couleur Green com.aspose.imaging.Color et un tableau de points
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Dessinez une ellipse en utilisant l'objet Pen et un rectangle entourant
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Dessinez une ligne
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Dessinez un segment de tarte
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Dessinez un polygone en spécifiant l'objet Pen ayant la couleur Red com.aspose.imaging.Color et un tableau de points
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Dessinez un rectangle
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Créez un objet SolidBrush et définissez ses différentes propriétés
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Dessinez une chaîne en utilisant l'objet SolidBrush et la police Font, à un point spécifique
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Enregistrer toutes les modifications.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


Initialise une nouvelle instance de la classe `SolidBrush`.

### SolidBrush(Color color) {#SolidBrush-com.aspose.imaging.Color-}
```
public SolidBrush(Color color)
```


Initialise une nouvelle instance de la classe `SolidBrush`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | La couleur du pinceau plein. |

### getColor() {#getColor--}
```
public Color getColor()
```


Obtient ou définit la couleur du pinceau.

Valeur : la couleur du pinceau.

**Returns:**
[Color](../../com.aspose.imaging/color)

**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
Cet exemple utilise la classe Graphics pour créer des formes primitives sur la surface Image. Pour démontrer l'opération, l'exemple crée une nouvelle Image au format PNG et dessine des formes primitives sur la surface Image en utilisant les méthodes Draw exposées par la classe Graphics.
``` java
// Crée une instance de FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Créez une instance de PngOptions et définissez ses différentes propriétés
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Définissez la source pour PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Créer une instance de Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Créer et initialiser une instance de la classe Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Effacer la surface Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Dessinez un arc en spécifiant l'objet Pen ayant la couleur Black com.aspose.imaging.Color,
        // un Rectangle entourant l'arc, l'angle de départ et l'angle de balayage
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Dessinez un Bézier en spécifiant l'objet Pen ayant la couleur Blue com.aspose.imaging.Color et les points de coordonnées.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Dessinez une courbe en spécifiant l'objet Pen ayant la couleur Green com.aspose.imaging.Color et un tableau de points
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Dessinez une ellipse en utilisant l'objet Pen et un rectangle entourant
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Dessinez une ligne
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Dessinez un segment de tarte
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Dessinez un polygone en spécifiant l'objet Pen ayant la couleur Red com.aspose.imaging.Color et un tableau de points
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Dessinez un rectangle
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Créez un objet SolidBrush et définissez ses différentes propriétés
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Dessinez une chaîne en utilisant l'objet SolidBrush et la police Font, à un point spécifique
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Enregistrer toutes les modifications.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Obtient ou définit la couleur du pinceau.

Valeur : la couleur du pinceau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de l'objet actuel.

**Returns:**
int
### equals(Object object) {#equals-java.lang.Object-}
```
public boolean equals(Object object)
```


Vérifie si les objets sont égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| object | java.lang.Object |  |

**Returns:**
boolean
