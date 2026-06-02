---
title: "Police"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Définit un format particulier pour le texte incluant la police, la taille et les attributs de style."
type: docs
weight: 48
url: /fr/java/com.aspose.imaging/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Définit un format particulier pour le texte, incluant la police, la taille et les attributs de style. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.imaging.Font-int-) | Initialise une nouvelle `com.aspose.imaging.Font` qui utilise la `com.aspose.imaging.Font` existante spécifiée et l'énumération `com.aspose.imaging.FontStyle`. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Initialise une nouvelle `com.aspose.imaging.Font` en utilisant une taille spécifiée. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initialise une nouvelle `com.aspose.imaging.Font` en utilisant une taille et un style spécifiés. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Initialise une nouvelle `com.aspose.imaging.Font` en utilisant une taille, un style, une unité et un jeu de caractères spécifiés. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initialise une nouvelle `com.aspose.imaging.Font` en utilisant une taille, un style et une unité spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Initialise une nouvelle `com.aspose.imaging.Font` en utilisant une taille et une unité spécifiées. |
| [getBold()](#getBold--) | Obtient une valeur indiquant si cette `Font` est en gras. |
| [getCharacterSet()](#getCharacterSet--) | Obtient une valeur octet qui spécifie le jeu de caractères utilisé par cette `Font`. |
| [getItalic()](#getItalic--) | Obtient une valeur indiquant si cette `Font` est en italique. |
| [getName()](#getName--) | Obtient le nom de la police de cette `Font`. |
| [getStrikeout()](#getStrikeout--) | Obtient une valeur indiquant si cette `Font` spécifie une ligne horizontale traversant la police. |
| [getUnderline()](#getUnderline--) | Obtient une valeur indiquant si cette `Font` est soulignée. |
| [getStyle()](#getStyle--) | Obtient les informations de style pour cette `Font`. |
| [getSize()](#getSize--) | Obtient la taille en em de cette `Font` mesurée dans les unités spécifiées par la propriété `P:Aspose.Imaging.Font.Unit`. |
| [getUnit()](#getUnit--) | Obtient l'unité de mesure pour ce `Font`. |
| [deepClone()](#deepClone--) | Crée une copie profonde exacte de ce `Font`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Indique si l'objet spécifié est un `com.aspose.imaging.Font` et possède les mêmes valeurs de propriétés que ce `com.aspose.imaging.Font`. |
| [hashCode()](#hashCode--) | Obtient le code de hachage pour ce `com.aspose.imaging.Font`. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `com.aspose.imaging.Font`. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Cet exemple montre l'utilisation des classes Font et SolidBrush pour dessiner des chaînes sur la surface d'une Image. L'exemple crée une nouvelle Image et dessine des formes à l'aide de Figures et de GraphicsPath
``` java
//Crée une instance de BmpOptions et définit ses différentes propriétés
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Créez une instance de FileCreateSource et affectez‑la comme Source pour l'instance de BmpOptions
//Le deuxième paramètre booléen détermine si le fichier à créer est IsTemporal ou non
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Crée une instance de Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Crée et initialise une instance de la classe Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Efface la surface Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Crée une instance de Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Crée une instance de SolidBrush de couleur rouge
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Dessine une chaîne
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // enregistre toutes les modifications
    image.save();
} finally {
    image.dispose();
}
```

### Font(Font prototype, int newStyle) {#Font-com.aspose.imaging.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initialise une nouvelle `com.aspose.imaging.Font` qui utilise la `com.aspose.imaging.Font` existante spécifiée et l'énumération `com.aspose.imaging.FontStyle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.imaging/font) | Le `com.aspose.imaging.Font` existant à partir duquel créer le nouveau `com.aspose.imaging.Font`. |
| newStyle | int | Le `com.aspose.imaging.FontStyle` à appliquer au nouveau `com.aspose.imaging.Font`. Plusieurs valeurs de l'énumération `com.aspose.imaging.FontStyle` peuvent être combinées avec l'opérateur OR. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Initialise un nouveau `com.aspose.imaging.Font` en utilisant une taille spécifiée. Le jeu de caractères est défini sur `F:Aspose.Imaging.CharacterSet.Default`, l'unité graphique sur `F:Aspose.Imaging.GraphicsUnit.Point`, le style de police sur `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Une représentation sous forme de chaîne du nom `com.aspose.imaging.Font`. |
| emSize | float | La taille em, en points, de la nouvelle police. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Initialise un nouveau `com.aspose.imaging.Font` en utilisant une taille et un style spécifiés. Le jeu de caractères est défini sur `F:Aspose.Imaging.CharacterSet.Default`, l'unité graphique sur `F:Aspose.Imaging.GraphicsUnit.Point`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Une représentation sous forme de chaîne du nom `com.aspose.imaging.Font`. |
| emSize | float | La taille em, en points, de la nouvelle police. |
| style | int | Le `com.aspose.imaging.FontStyle` de la nouvelle police. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Initialise une nouvelle `com.aspose.imaging.Font` en utilisant une taille, un style, une unité et un jeu de caractères spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Une représentation sous forme de chaîne du nom `com.aspose.imaging.Font`. |
| emSize | float | La taille em de la nouvelle police dans les unités spécifiées par le paramètre `unit`. |
| style | int | Le `com.aspose.imaging.FontStyle` de la nouvelle police. |
| unit | int | Le `com.aspose.imaging.GraphicsUnit` de la nouvelle police. |
| characterSet | int | Un jeu de caractères à utiliser pour cette police. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Initialise une nouvelle `com.aspose.imaging.Font` en utilisant une taille, un style et une unité spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Une représentation sous forme de chaîne du nom `com.aspose.imaging.Font`. |
| emSize | float | La taille em de la nouvelle police dans les unités spécifiées par le paramètre `unit`. |
| style | int | Le `com.aspose.imaging.FontStyle` de la nouvelle police. |
| unit | int | Le `com.aspose.imaging.GraphicsUnit` de la nouvelle police. |

### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Initialise une nouvelle `com.aspose.imaging.Font` en utilisant une taille et une unité spécifiées. Le jeu de caractères est défini sur `F:Aspose.Imaging.CharacterSet.Default`, le style est défini sur `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Une représentation sous forme de chaîne du nom `com.aspose.imaging.Font`. |
| emSize | float | La taille em de la nouvelle police dans les unités spécifiées par le paramètre `unit`. |
| unit | int | Le `com.aspose.imaging.GraphicsUnit` de la nouvelle police. |

**Returns:**
[Font](../../com.aspose.imaging/font)
### getBold() {#getBold--}
```
public boolean getBold()
```


Obtient une valeur indiquant si cette `Font` est en gras.

**Returns:**
booléen - Vrai si cette `Font` est en gras ; sinon, faux.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Obtient une valeur octet qui spécifie le jeu de caractères utilisé par cette `Font`.

**Returns:**
int - Un jeu de caractères que cette `Font` utilise.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Obtient une valeur indiquant si cette `Font` est en italique.

**Returns:**
booléen - Vrai si cette `Font` est en italique ; sinon, faux.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom de la police de cette `Font`.

**Returns:**
java.lang.String - Une représentation sous forme de chaîne du nom de la police de cette `Font`.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Obtient une valeur indiquant si cette `Font` spécifie une ligne horizontale traversant la police.

**Returns:**
booléen - Vrai si cette `Font` possède une ligne horizontale traversante ; sinon, faux.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Obtient une valeur indiquant si cette `Font` est soulignée.

**Returns:**
booléen - Vrai si cette `Font` est soulignée ; sinon, faux.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Obtient les informations de style pour cette `Font`.

**Returns:**
int - Une énumération `FontStyle` qui contient les informations de style pour cette `Font`.
### getSize() {#getSize--}
```
public float getSize()
```


Obtient la taille en em de cette `Font` mesurée dans les unités spécifiées par la propriété `P:Aspose.Imaging.Font.Unit`.

**Returns:**
float - La taille en em de cette `Font`.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Obtient l'unité de mesure pour ce `Font`.

**Returns:**
int - Un `GraphicsUnit` qui représente l'unité de mesure de cette `Font`.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Crée une copie profonde exacte de ce `Font`.

**Returns:**
[Font](../../com.aspose.imaging/font) - The `Font` this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indique si l'objet spécifié est un `com.aspose.imaging.Font` et possède les mêmes valeurs de propriétés que ce `com.aspose.imaging.Font`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à tester. |

**Returns:**
booléen - Vrai si le paramètre `obj` est un `com.aspose.imaging.Font` et possède les mêmes valeurs de propriétés que ce `com.aspose.imaging.Font` ; sinon, faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage pour ce `com.aspose.imaging.Font`.

**Returns:**
int - Le code de hachage de ce `com.aspose.imaging.Font`.
### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `com.aspose.imaging.Font`.

**Returns:**
java.lang.String - Une chaîne qui représente ce `com.aspose.imaging.Font`.
