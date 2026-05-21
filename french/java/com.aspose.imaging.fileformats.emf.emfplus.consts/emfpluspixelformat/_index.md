---
title: "EmfPlusPixelFormat"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération PixelFormat définit les formats de pixel pris en charge dans les images bitmap EMF."
type: docs
weight: 43
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelFormat extends System.Enum
```

L'énumération PixelFormat définit les formats de pixels pris en charge dans les images bitmap EMF+.
## Champs

| Champ | Description |
| --- | --- |
| [PixelFormatUndefined](#PixelFormatUndefined) | Le format n'est pas spécifié. |
| [PixelFormat1bppIndexed](#PixelFormat1bppIndexed) | Le format est monochrome, et une table de recherche de palette de couleurs est utilisée. |
| [PixelFormat4bppIndexed](#PixelFormat4bppIndexed) | Le format est en 16 couleurs, et une table de recherche de palette de couleurs est utilisée. |
| [PixelFormat8bppIndexed](#PixelFormat8bppIndexed) | Le format est en 256 couleurs, et une table de recherche de palette de couleurs est utilisée. |
| [PixelFormat16bppGrayScale](#PixelFormat16bppGrayScale) | Le format est de 16 bits par pixel, en niveaux de gris. |
| [PixelFormat16bppRGB555](#PixelFormat16bppRGB555) | Le format est de 16 bits par pixel ; 5 bits chacun sont utilisés pour les composantes rouge, verte et bleue. |
| [PixelFormat16bppRGB565](#PixelFormat16bppRGB565) | Le format est de 16 bits par pixel ; 5 bits sont utilisés pour la composante rouge, 6 bits pour la composante verte, et 5 bits pour la composante bleue. |
| [PixelFormat16bppARGB1555](#PixelFormat16bppARGB1555) | Le format est de 16 bits par pixel ; 1 bit est utilisé pour la composante alpha, et 5 bits chacun sont utilisés pour les composantes rouge, verte et bleue. |
| [PixelFormat24bppRGB](#PixelFormat24bppRGB) | Le format est de 24 bits par pixel ; 8 bits chacun sont utilisés pour les composantes rouge, verte et bleue. |
| [PixelFormat32bppRGB](#PixelFormat32bppRGB) | Le format est de 32 bits par pixel ; 8 bits chacun sont utilisés pour les composantes rouge, verte et bleue. |
| [PixelFormat32bppARGB](#PixelFormat32bppARGB) | Le format est de 32 bits par pixel ; 8 bits chacun sont utilisés pour les composantes alpha, rouge, verte et bleue. |
| [PixelFormat32bppPARGB](#PixelFormat32bppPARGB) | Le format est de 32 bits par pixel ; 8 bits chacun sont utilisés pour les composantes alpha, rouge, verte et bleue. |
| [PixelFormat48bppRGB](#PixelFormat48bppRGB) | Le format est de 48 bits par pixel ; 16 bits chacun sont utilisés pour les composantes rouge, verte et bleue. |
| [PixelFormat64bppARGB](#PixelFormat64bppARGB) | Le format est de 64 bits par pixel ; 16 bits chacun sont utilisés pour les composantes alpha, rouge, verte et bleue. |
| [PixelFormat64bppPARGB](#PixelFormat64bppPARGB) | Le format est de 64 bits par pixel ; 16 bits chacun sont utilisés pour les composantes alpha, rouge, verte et bleue. |
### PixelFormatUndefined {#PixelFormatUndefined}
```
public static final int PixelFormatUndefined
```


Le format n'est pas spécifié.

--------------------

Les formats de pixel sont spécifiés par les objets [EmfPlusBitmap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap). Ils sont codés comme suit : - Bits 0-7 : Énumération des constantes de format de pixel, à partir de zéro. - Bits 8-15 : Nombre total de bits par pixel. - Bit 16 : Si défini, la valeur de couleur est indexée dans une palette. - Bit 17 : Si défini, la valeur de couleur est dans un format pris en charge par GDI. - Bit 18 : Si défini, la valeur de couleur possède une composante alpha. - Bit 19 : Si défini, la valeur de couleur possède une composante alpha prémultipliée. - Bit 20 : Si défini, les couleurs étendues, 16 bits par canal, sont prises en charge. - Bits 21-31 : Réservés.

### PixelFormat1bppIndexed {#PixelFormat1bppIndexed}
```
public static final int PixelFormat1bppIndexed
```


Le format est monochrome, et une table de recherche de palette de couleurs est utilisée.

### PixelFormat4bppIndexed {#PixelFormat4bppIndexed}
```
public static final int PixelFormat4bppIndexed
```


Le format est en 16 couleurs, et une table de recherche de palette de couleurs est utilisée.

### PixelFormat8bppIndexed {#PixelFormat8bppIndexed}
```
public static final int PixelFormat8bppIndexed
```


Le format est en 256 couleurs, et une table de recherche de palette de couleurs est utilisée.

### PixelFormat16bppGrayScale {#PixelFormat16bppGrayScale}
```
public static final int PixelFormat16bppGrayScale
```


Le format est de 16 bits par pixel, en niveaux de gris.

### PixelFormat16bppRGB555 {#PixelFormat16bppRGB555}
```
public static final int PixelFormat16bppRGB555
```


Le format est de 16 bits par pixel ; 5 bits chacun sont utilisés pour les composantes rouge, verte et bleue. Le bit restant n'est pas utilisé.

### PixelFormat16bppRGB565 {#PixelFormat16bppRGB565}
```
public static final int PixelFormat16bppRGB565
```


Le format est de 16 bits par pixel ; 5 bits sont utilisés pour la composante rouge, 6 bits pour la composante verte, et 5 bits pour la composante bleue.

### PixelFormat16bppARGB1555 {#PixelFormat16bppARGB1555}
```
public static final int PixelFormat16bppARGB1555
```


Le format est de 16 bits par pixel ; 1 bit est utilisé pour la composante alpha, et 5 bits chacun sont utilisés pour les composantes rouge, verte et bleue.

### PixelFormat24bppRGB {#PixelFormat24bppRGB}
```
public static final int PixelFormat24bppRGB
```


Le format est de 24 bits par pixel ; 8 bits chacun sont utilisés pour les composantes rouge, verte et bleue.

### PixelFormat32bppRGB {#PixelFormat32bppRGB}
```
public static final int PixelFormat32bppRGB
```


Le format est de 32 bits par pixel ; 8 bits chacun sont utilisés pour les composantes rouge, verte et bleue. Les 8 bits restants ne sont pas utilisés.

### PixelFormat32bppARGB {#PixelFormat32bppARGB}
```
public static final int PixelFormat32bppARGB
```


Le format est de 32 bits par pixel ; 8 bits chacun sont utilisés pour les composantes alpha, rouge, verte et bleue.

### PixelFormat32bppPARGB {#PixelFormat32bppPARGB}
```
public static final int PixelFormat32bppPARGB
```


Le format est de 32 bits par pixel ; 8 bits chacun sont utilisés pour les composantes alpha, rouge, verte et bleue. Les composantes rouge, verte et bleue sont prémultipliées selon la composante alpha.

### PixelFormat48bppRGB {#PixelFormat48bppRGB}
```
public static final int PixelFormat48bppRGB
```


Le format est de 48 bits par pixel ; 16 bits chacun sont utilisés pour les composantes rouge, verte et bleue.

### PixelFormat64bppARGB {#PixelFormat64bppARGB}
```
public static final int PixelFormat64bppARGB
```


Le format est de 64 bits par pixel ; 16 bits chacun sont utilisés pour les composantes alpha, rouge, verte et bleue.

### PixelFormat64bppPARGB {#PixelFormat64bppPARGB}
```
public static final int PixelFormat64bppPARGB
```


Le format est de 64 bits par pixel ; 16 bits chacun sont utilisés pour les composantes alpha, rouge, verte et bleue. Les composantes rouge, verte et bleue sont prémultipliées selon la composante alpha.

