---
title: "EmfPlusPixelOffsetMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération PixelOffsetMode définit comment les pixels sont décalés, ce qui spécifie le compromis entre la vitesse de rendu et la qualité."
type: docs
weight: 44
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelOffsetMode extends System.Enum
```

L'énumération PixelOffsetMode définit comment les pixels sont décalés, ce qui spécifie le compromis entre la vitesse de rendu et la qualité.
## Champs

| Champ | Description |
| --- | --- |
| [PixelOffsetModeDefault](#PixelOffsetModeDefault) | Les pixels sont centrés sur des coordonnées entières, privilégiant la vitesse sur la qualité. |
| [PixelOffsetModeHighSpeed](#PixelOffsetModeHighSpeed) | Les pixels sont centrés sur des coordonnées entières, comme avec PixelOffsetModeNone. |
| [PixelOffsetModeHighQuality](#PixelOffsetModeHighQuality) | Les pixels sont centrés sur des coordonnées demi-entières, comme avec PixelOffsetModeHalf. |
| [PixelOffsetModeNone](#PixelOffsetModeNone) | Les pixels sont centrés sur l'origine, ce qui signifie que le pixel couvre la zone de -0,5 à 0,5 sur les axes x et y et que son centre est à (0,0). |
| [PixelOffsetModeHalf](#PixelOffsetModeHalf) | Les pixels sont centrés sur des coordonnées demi-entières, ce qui signifie que le pixel couvre la zone de 0 à 1 sur les axes x et y et que son centre est à (0,5,0,5). |
### PixelOffsetModeDefault {#PixelOffsetModeDefault}
```
public static final byte PixelOffsetModeDefault
```


Les pixels sont centrés sur des coordonnées entières, privilégiant la vitesse sur la qualité.

### PixelOffsetModeHighSpeed {#PixelOffsetModeHighSpeed}
```
public static final byte PixelOffsetModeHighSpeed
```


Les pixels sont centrés sur des coordonnées entières, comme avec PixelOffsetModeNone. Une vitesse supérieure au détriment de la qualité est spécifiée.

### PixelOffsetModeHighQuality {#PixelOffsetModeHighQuality}
```
public static final byte PixelOffsetModeHighQuality
```


Les pixels sont centrés sur des coordonnées demi-entières, comme avec PixelOffsetModeHalf. Une qualité supérieure au détriment de la vitesse est spécifiée.

### PixelOffsetModeNone {#PixelOffsetModeNone}
```
public static final byte PixelOffsetModeNone
```


Les pixels sont centrés sur l'origine, ce qui signifie que le pixel couvre la zone de -0,5 à 0,5 sur les axes x et y et que son centre est à (0,0).

### PixelOffsetModeHalf {#PixelOffsetModeHalf}
```
public static final byte PixelOffsetModeHalf
```


Les pixels sont centrés sur des coordonnées demi-entières, ce qui signifie que le pixel couvre la zone de 0 à 1 sur les axes x et y et que son centre est à (0,5,0,5). En décalant les pixels pendant le rendu, la qualité du rendu peut être améliorée au coût de la vitesse de rendu.

