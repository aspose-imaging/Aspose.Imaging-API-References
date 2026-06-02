---
title: "OdGradientStyle"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le style de dégradé"
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.opendocument.enums/odgradientstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdGradientStyle extends System.Enum
```

Le style de dégradé
## Champs

| Champ | Description |
| --- | --- |
| [Axial](#Axial) | L'axial définit un dégradé bi‑linéaire également connu sous le nom de dégradé reflété ou dégradé linéaire miroir. |
| [Ellipsoid](#Ellipsoid) | L'ellipsoïde définit un dégradé où les couleurs sont mélangées le long du rayon depuis le centre d'un ellipsoïde tel que défini avec les attributs draw:cx et draw:cy. |
| [Linear](#Linear) | Le linéaire définit un dégradé où les couleurs se mélangent le long de l'axe linéaire du dégradé. |
| [Radial](#Radial) | Le radial définit un dégradé où les couleurs sont mélangées le long du rayon depuis le centre d'un cercle tel que défini avec les attributs draw:cx et draw:cy. |
| [Rectangle](#Rectangle) | Le rectangle définit un dégradé qui produit un mélange rectangulaire depuis le centre du rectangle jusqu'au bord le plus court des 4. |
| [Square](#Square) | Le carré définit un dégradé qui produit un mélange carré, imitant la perspective visuelle dans un couloir ou la vue aérienne d'une pyramide. |
| [None](#None) | Le style de dégradé est aucun |
### Axial {#Axial}
```
public static final int Axial
```


L'axial définit un dégradé bi‑linéaire également connu sous le nom de dégradé reflété ou dégradé linéaire miroir. Il est créé comme un dégradé linéaire qui est miroir (ou reflété) le long de son axe.

### Ellipsoid {#Ellipsoid}
```
public static final int Ellipsoid
```


L'ellipsoïde définit un dégradé où les couleurs sont mélangées le long du rayon depuis le centre d'un ellipsoïde tel que défini avec les attributs draw:cx et draw:cy. La longueur du demi‑axe majeur est la largeur de la zone remplie et la longueur du demi‑axe mineur

### Linear {#Linear}
```
public static final int Linear
```


Le linéaire définit un dégradé où les couleurs se mélangent le long de l'axe linéaire du dégradé. L'axe du dégradé est spécifié avec l'attribut draw:angle dans le sens horaire par rapport à l'axe vertical.

### Radial {#Radial}
```
public static final int Radial
```


Le radial définit un dégradé où les couleurs sont mélangées le long du rayon depuis le centre d'un cercle tel que défini avec les attributs draw:cx et draw:cy. L'extérieur du cercle est rempli avec la couleur finale.

### Rectangle {#Rectangle}
```
public static final int Rectangle
```


Le rectangle définit un dégradé qui produit un mélange rectangulaire depuis le centre du rectangle jusqu'au bord le plus court des 4. Le centre du rectangle est défini avec les attributs draw:cx et draw:cy. La largeur du rectangle est la largeur de la zone remplie, la hauteur du rectangle est la hauteur de la zone remplie. L'extérieur du carré est rempli avec la couleur finale.

### Square {#Square}
```
public static final int Square
```


Le carré définit un dégradé qui produit un mélange carré, imitant la perspective visuelle dans un couloir ou la vue aérienne d'une pyramide. Aussi connu sous le nom de "box gradient" et "pyramidal gradient". Le centre du carré est défini avec les attributs draw:cx et draw:cy. La largeur et la hauteur du carré sont la valeur minimale entre la largeur ou la hauteur de la zone remplie. L'extérieur du carré est rempli avec la couleur finale.

### None {#None}
```
public static final int None
```


Le style de dégradé est aucun

