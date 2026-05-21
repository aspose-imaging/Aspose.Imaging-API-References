---
title: "InterpolationMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération com.aspose.imaging.InterpolationMode spécifie l'algorithme utilisé lorsque les images sont mises à l'échelle ou pivotées."
type: docs
weight: 65
url: /fr/java/com.aspose.imaging/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

L'énumération `com.aspose.imaging.InterpolationMode` spécifie l'algorithme utilisé lorsque les images sont agrandies ou tournées.
## Champs

| Champ | Description |
| --- | --- |
| [Invalid](#Invalid) | Mode d'interpolation invalide. |
| [Default](#Default) | Spécifie le mode par défaut. |
| [Low](#Low) | Spécifie une interpolation de basse qualité. |
| [High](#High) | Spécifie une interpolation de haute qualité. |
| [Bilinear](#Bilinear) | Spécifie une interpolation bilinéaire. |
| [Bicubic](#Bicubic) | Spécifie une interpolation bicubique. |
| [NearestNeighbor](#NearestNeighbor) | Spécifie l'interpolation au plus proche voisin. |
| [HighQualityBilinear](#HighQualityBilinear) | Spécifie une interpolation bilinéaire de haute qualité. |
| [HighQualityBicubic](#HighQualityBicubic) | Spécifie une interpolation bicubique de haute qualité. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Mode d'interpolation invalide.

### Default {#Default}
```
public static final int Default
```


Spécifie le mode par défaut.

### Low {#Low}
```
public static final int Low
```


Spécifie une interpolation de basse qualité.

### High {#High}
```
public static final int High
```


Spécifie une interpolation de haute qualité.

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


Spécifie une interpolation bilinéaire. Aucun préfiltrage n'est effectué. Ce mode n'est pas adapté à la réduction d'une image en dessous de 50 % de sa taille d'origine.

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


Spécifie une interpolation bicubique. Aucun préfiltrage n'est effectué. Ce mode n'est pas adapté à la réduction d'une image en dessous de 25 % de sa taille d'origine.

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


Spécifie l'interpolation au plus proche voisin.

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


Spécifie une interpolation bilinéaire de haute qualité. Un préfiltrage est effectué pour garantir une réduction de haute qualité.

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


Spécifie une interpolation bicubique de haute qualité. Un préfiltrage est effectué pour garantir une réduction de haute qualité. Ce mode produit les images transformées de la plus haute qualité.

