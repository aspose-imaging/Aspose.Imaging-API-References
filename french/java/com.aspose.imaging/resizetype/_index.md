---
title: "ResizeType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Spécifie le type de redimensionnement."
type: docs
weight: 97
url: /fr/java/com.aspose.imaging/resizetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResizeType extends System.Enum
```

Spécifie le type de redimensionnement.
## Champs

| Champ | Description |
| --- | --- |
| [None](#None) | Les pixels ne sont pas conservés pendant l'opération de redimensionnement. |
| [LeftTopToLeftTop](#LeftTopToLeftTop) | Le point supérieur gauche de la nouvelle image coïncidera avec le point supérieur gauche de l'image originale. |
| [RightTopToRightTop](#RightTopToRightTop) | Le point supérieur droit de la nouvelle image coïncidera avec le point supérieur droit de l'image originale. |
| [RightBottomToRightBottom](#RightBottomToRightBottom) | Le point inférieur droit de la nouvelle image coïncidera avec le point inférieur droit de l'image originale. |
| [LeftBottomToLeftBottom](#LeftBottomToLeftBottom) | Le point inférieur gauche de la nouvelle image coïncidera avec le point inférieur gauche de l'image originale. |
| [CenterToCenter](#CenterToCenter) | Le centre de la nouvelle image coïncidera avec le centre de l'image originale. |
| [LanczosResample](#LanczosResample) | Rééchantillonner en utilisant l'algorithme Lanczos avec a=3. |
| [NearestNeighbourResample](#NearestNeighbourResample) | Rééchantillonner en utilisant l'algorithme du plus proche voisin. |
| [AdaptiveResample](#AdaptiveResample) | Rééchantillonner en utilisant un algorithme adaptatif basé sur une fonction rationnelle pondérée et mélangée ainsi que les algorithmes d'interpolation Lanczos3. |
| [BilinearResample](#BilinearResample) | Rééchantillonner en utilisant l'interpolation bilinéaire. |
| [HighQualityResample](#HighQualityResample) | Le rééchantillonnage de haute qualité |
| [CatmullRom](#CatmullRom) | La méthode d'interpolation cubique Catmull-Rom. |
| [CubicConvolution](#CubicConvolution) | La méthode d'interpolation Cubic Convolution |
| [CubicBSpline](#CubicBSpline) | La méthode d'interpolation CubicBSpline cubique |
| [Mitchell](#Mitchell) | La méthode d'interpolation cubique Mitchell |
| [SinC](#SinC) | La méthode d'interpolation cubique Sinc (Lanczos3) |
| [Bell](#Bell) | La méthode d'interpolation Bell |

## Example: This example loads an image and resizes it using various resizing methods.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


## Example: Resize image using specific Resize Type.

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```

### None {#None}
```
public static final int None
```


Les pixels ne sont pas conservés pendant l'opération de redimensionnement.

### LeftTopToLeftTop {#LeftTopToLeftTop}
```
public static final int LeftTopToLeftTop
```


Le point supérieur gauche de la nouvelle image coïncidera avec le point supérieur gauche de l'image originale. Un recadrage sera effectué si nécessaire.

### RightTopToRightTop {#RightTopToRightTop}
```
public static final int RightTopToRightTop
```


Le point supérieur droit de la nouvelle image coïncidera avec le point supérieur droit de l'image originale. Un recadrage sera effectué si nécessaire.

### RightBottomToRightBottom {#RightBottomToRightBottom}
```
public static final int RightBottomToRightBottom
```


Le point inférieur droit de la nouvelle image coïncidera avec le point inférieur droit de l'image originale. Un recadrage sera effectué si nécessaire.

### LeftBottomToLeftBottom {#LeftBottomToLeftBottom}
```
public static final int LeftBottomToLeftBottom
```


Le point inférieur gauche de la nouvelle image coïncidera avec le point inférieur gauche de l'image originale. Un recadrage sera effectué si nécessaire.

### CenterToCenter {#CenterToCenter}
```
public static final int CenterToCenter
```


Le centre de la nouvelle image coïncidera avec le centre de l'image originale. Un recadrage sera effectué si nécessaire.

### LanczosResample {#LanczosResample}
```
public static final int LanczosResample
```


Rééchantillonner en utilisant l'algorithme Lanczos avec a=3.

### NearestNeighbourResample {#NearestNeighbourResample}
```
public static final int NearestNeighbourResample
```


Rééchantillonner en utilisant l'algorithme du plus proche voisin.

### AdaptiveResample {#AdaptiveResample}
```
public static final int AdaptiveResample
```


Rééchantillonner en utilisant un algorithme adaptatif basé sur une fonction rationnelle pondérée et mélangée ainsi que les algorithmes d'interpolation Lanczos3.

### BilinearResample {#BilinearResample}
```
public static final int BilinearResample
```


Rééchantillonner en utilisant l'interpolation bilinéaire. Le préfiltrage de l'image est autorisé pour supprimer le bruit avant le rééchantillonnage, si nécessaire.

### HighQualityResample {#HighQualityResample}
```
public static final int HighQualityResample
```


Le rééchantillonnage de haute qualité

### CatmullRom {#CatmullRom}
```
public static final int CatmullRom
```


La méthode d'interpolation cubique Catmull-Rom.

### CubicConvolution {#CubicConvolution}
```
public static final int CubicConvolution
```


La méthode d'interpolation Cubic Convolution

### CubicBSpline {#CubicBSpline}
```
public static final int CubicBSpline
```


La méthode d'interpolation CubicBSpline cubique

### Mitchell {#Mitchell}
```
public static final int Mitchell
```


La méthode d'interpolation cubique Mitchell

### SinC {#SinC}
```
public static final int SinC
```


La méthode d'interpolation cubique Sinc (Lanczos3)

### Bell {#Bell}
```
public static final int Bell
```


La méthode d'interpolation Bell

