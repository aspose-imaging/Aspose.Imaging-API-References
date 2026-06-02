---
title: "HatchBrush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Définit un pinceau rectangulaire avec un style de hachure, une couleur de premier plan et une couleur d'arrière-plan."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.brushes/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class HatchBrush extends Brush
```

Définit un pinceau rectangulaire avec un style de hachure, une couleur de premier plan et une couleur d'arrière-plan. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getForegroundColor()](#getForegroundColor--) | Obtient la couleur des lignes de hachure. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.imaging.Color-) | Définit la couleur des lignes de hachure. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient la couleur des espaces entre les lignes de hachure. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Définit la couleur des espaces entre les lignes de hachure. |
| [getHatchStyle()](#getHatchStyle--) | Obtient le style de hachure de ce pinceau. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Définit le style de hachures de ce pinceau. |

## Example: This example shows the creation and usage Pen objects.
Cet exemple montre la création et l'utilisation d'objets Pen. L'exemple crée une nouvelle Image et dessine des rectangles sur la surface de l'Image.
``` java

// Créez une instance de BmpOptions et définissez ses différentes propriétés
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Créez une instance de FileCreateSource et affectez‑la comme Source pour l'instance de BmpOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est IsTemporal ou non
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Créer une instance de Image au chemin spécifié.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Créer une instance de Graphics et l'initialiser avec l'objet Image.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Effacer la surface Graphics avec la couleur blanche.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Créer une instance de Pen avec la couleur rouge et une largeur de 5.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Créer une instance de HatchBrush et définir ses propriétés.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Créer une instance de Pen et l'initialiser avec l'objet HatchBrush et la largeur.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Dessiner des rectangles en spécifiant l'objet Pen.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Dessiner des rectangles en spécifiant l'objet Pen.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Enregistrer toutes les modifications.
    image.save();
} finally {
    image.dispose();
}
```

### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Obtient la couleur des lignes de hachure.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of hatch lines.
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.imaging.Color-}
```
public void setForegroundColor(Color value)
```


Définit la couleur des lignes de hachure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | La couleur des lignes de hachures. |


**Example: This example shows the creation and usage Pen objects.**
Cet exemple montre la création et l'utilisation d'objets Pen. L'exemple crée une nouvelle Image et dessine des rectangles sur la surface de l'Image.
``` java

// Créez une instance de BmpOptions et définissez ses différentes propriétés
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Créez une instance de FileCreateSource et affectez‑la comme Source pour l'instance de BmpOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est IsTemporal ou non
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Créer une instance de Image au chemin spécifié.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Créer une instance de Graphics et l'initialiser avec l'objet Image.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Effacer la surface Graphics avec la couleur blanche.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Créer une instance de Pen avec la couleur rouge et une largeur de 5.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Créer une instance de HatchBrush et définir ses propriétés.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Créer une instance de Pen et l'initialiser avec l'objet HatchBrush et la largeur.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Dessiner des rectangles en spécifiant l'objet Pen.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Dessiner des rectangles en spécifiant l'objet Pen.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Enregistrer toutes les modifications.
    image.save();
} finally {
    image.dispose();
}
```

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient la couleur des espaces entre les lignes de hachure.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of spaces between the hatch lines.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Définit la couleur des espaces entre les lignes de hachure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | La couleur des espaces entre les lignes de hachures. |


**Example: This example shows the creation and usage Pen objects.**
Cet exemple montre la création et l'utilisation d'objets Pen. L'exemple crée une nouvelle Image et dessine des rectangles sur la surface de l'Image.
``` java

// Créez une instance de BmpOptions et définissez ses différentes propriétés
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Créez une instance de FileCreateSource et affectez‑la comme Source pour l'instance de BmpOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est IsTemporal ou non
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Créer une instance de Image au chemin spécifié.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Créer une instance de Graphics et l'initialiser avec l'objet Image.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Effacer la surface Graphics avec la couleur blanche.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Créer une instance de Pen avec la couleur rouge et une largeur de 5.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Créer une instance de HatchBrush et définir ses propriétés.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Créer une instance de Pen et l'initialiser avec l'objet HatchBrush et la largeur.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Dessiner des rectangles en spécifiant l'objet Pen.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Dessiner des rectangles en spécifiant l'objet Pen.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Enregistrer toutes les modifications.
    image.save();
} finally {
    image.dispose();
}
```

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Obtient le style de hachure de ce pinceau.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Définit le style de hachures de ce pinceau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

