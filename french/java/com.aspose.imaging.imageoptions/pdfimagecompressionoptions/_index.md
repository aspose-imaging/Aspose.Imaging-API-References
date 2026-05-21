---
title: "PdfImageCompressionOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Options de compression d'image PDF"
type: docs
weight: 35
url: /fr/java/com.aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfImageCompressionOptions extends System.Enum
```

Options de compression d'image PDF
## Champs

| Champ | Description |
| --- | --- |
| [Auto](#Auto) | Sélectionne automatiquement la compression la plus appropriée pour chaque image. |
| [None](#None) | Enregistre les octets d'image bruts, ce qui entraîne des tailles de fichiers PDF plus importantes. |
| [Rle](#Rle) | Compression Run Length. |
| [Flate](#Flate) | Compression Flate. |
| [LzwBaselinePredictor](#LzwBaselinePredictor) | La sélection du prédicteur est limitée au prédicteur PNG Paeth pour accélérer le processus. |
| [LzwOptimizedPredictor](#LzwOptimizedPredictor) | La sélection du prédicteur est plus compliquée et devrait donner des tailles d'image plus petites, mais prend plus de temps. |
| [Jpeg](#Jpeg) | Compression JPEG. |
| [Ccitt3](#Ccitt3) | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 ne prend pas en charge la transparence. |
| [Ccitt4](#Ccitt4) | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 ne prend pas en charge la transparence. |
### Auto {#Auto}
```
public static final int Auto
```


Sélectionne automatiquement la compression la plus appropriée pour chaque image.

### None {#None}
```
public static final int None
```


Enregistre les octets d'image bruts, ce qui entraîne des tailles de fichiers PDF plus importantes.

### Rle {#Rle}
```
public static final int Rle
```


Compression Run Length.

### Flate {#Flate}
```
public static final int Flate
```


Compression Flate.

### LzwBaselinePredictor {#LzwBaselinePredictor}
```
public static final int LzwBaselinePredictor
```


La sélection du prédicteur est limitée au prédicteur PNG Paeth pour accélérer le processus. En pratique, il fonctionne étonnamment bien. Meilleur que [LzwOptimizedPredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwOptimizedPredictor).

### LzwOptimizedPredictor {#LzwOptimizedPredictor}
```
public static final int LzwOptimizedPredictor
```


La sélection du prédicteur est plus compliquée et devrait donner des tailles d'image plus petites, mais prend plus de temps. Le RFC 2083 indique que c'est la meilleure approche. Cependant, sur les données de test, le prédicteur de référence [LzwBaselinePredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwBaselinePredictor) surpasse le prédicteur optimisé avec un gain de taux de compression de 25 à 40 %.

### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Compression JPEG. Ne prend pas en charge la transparence.

### Ccitt3 {#Ccitt3}
```
public static final int Ccitt3
```


/CCITTFaxDecode/DecodeParms/K 0/Columns 173 ne prend pas en charge la transparence.

### Ccitt4 {#Ccitt4}
```
public static final int Ccitt4
```


/CCITTFaxDecode/DecodeParms/K -1/Columns 173 ne prend pas en charge la transparence.

