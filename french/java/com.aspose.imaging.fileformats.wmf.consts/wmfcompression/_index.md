---
title: "WmfCompression"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération Compression spécifie le type de compression pour une image bitmap."
type: docs
weight: 16
url: /fr/java/com.aspose.imaging.fileformats.wmf.consts/wmfcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfCompression extends System.Enum
```

L'énumération Compression spécifie le type de compression pour une image bitmap.
## Champs

| Champ | Description |
| --- | --- |
| [BI_RGB](#BI-RGB) | Le bitmap est au format rouge vert bleu (RGB) non compressé, qui n'est pas compressé et n'utilise pas de masques de couleur. |
| [BI_RLE8](#BI-RLE8) | Un format RGB qui utilise la compression par codage run-length (RLE) pour les bitmaps de 8 bits par pixel. |
| [BI_RLE4](#BI-RLE4) | Un format RGB qui utilise la compression RLE pour les bitmaps de 4 bits par pixel. |
| [BI_BITFIELDS](#BI-BITFIELDS) | Le bitmap n'est pas compressé et la table de couleurs se compose de trois masques de couleur DWORD qui spécifient respectivement les composantes rouge, verte et bleue de chaque pixel. |
| [BI_JPEG](#BI-JPEG) | L'image est une image JPEG, comme spécifié dans [JFIF]. |
| [BI_PNG](#BI-PNG) | L'image est une image PNG, comme spécifié dans [RFC2083]. |
| [BI_CMYK](#BI-CMYK) | L'image est au format CMYK non compressé. |
| [BI_CMYKRLE8](#BI-CMYKRLE8) | Un format CMYK qui utilise la compression RLE pour les bitmaps avec 8 bits par pixel. |
| [BI_CMYKRLE4](#BI-CMYKRLE4) | Un format CMYK qui utilise la compression RLE pour les bitmaps avec 4 bits par pixel. |
### BI_RGB {#BI-RGB}
```
public static final int BI_RGB
```


Le bitmap est au format rouge vert bleu (RGB) non compressé, qui n'est pas compressé et n'utilise pas de masques de couleur.

### BI_RLE8 {#BI-RLE8}
```
public static final int BI_RLE8
```


Un format RGB qui utilise la compression par codage de longueur d'exécution (RLE) pour les bitmaps avec 8 bits par pixel. La compression utilise un format de 2 octets composé d'un octet de compteur suivi d'un octet contenant un index de couleur.

### BI_RLE4 {#BI-RLE4}
```
public static final int BI_RLE4
```


Un format RGB qui utilise la compression RLE pour les bitmaps avec 4 bits par pixel. La compression utilise un format de 2 octets composé d'un octet de compteur suivi de deux index de couleur de longueur mot.

### BI_BITFIELDS {#BI-BITFIELDS}
```
public static final int BI_BITFIELDS
```


Le bitmap n'est pas compressé et la table de couleurs se compose de trois masques de couleur DWORD qui spécifient respectivement les composantes rouge, verte et bleue de chaque pixel. Cela est valable lorsqu'il est utilisé avec des bitmaps de 16 et 32 bits par pixel.

### BI_JPEG {#BI-JPEG}
```
public static final int BI_JPEG
```


L'image est une image JPEG, comme spécifié dans [JFIF]. Cette valeur DOIT uniquement être utilisée dans certaines opérations de bitmap, telles que le passage JPEG. L'application DOIT interroger la prise en charge du passage, car tous les appareils ne supportent pas le passage JPEG. L'utilisation de bitmaps non RGB PEUT limiter la portabilité du métafichier vers d'autres appareils. Par exemple, les contextes de périphérique d'affichage ne supportent généralement pas ce passage.

### BI_PNG {#BI-PNG}
```
public static final int BI_PNG
```


L'image est une image PNG, comme spécifié dans [RFC2083]. Cette valeur DOIT uniquement être utilisée dans certaines opérations de bitmap, telles que le passage JPEG/PNG. L'application DOIT interroger la prise en charge du passage, car tous les appareils ne supportent pas le passage JPEG/PNG. L'utilisation de bitmaps non RGB PEUT limiter la portabilité du métafichier vers d'autres appareils. Par exemple, les contextes de périphérique d'affichage ne supportent généralement pas ce passage.

### BI_CMYK {#BI-CMYK}
```
public static final int BI_CMYK
```


L'image est au format CMYK non compressé.

### BI_CMYKRLE8 {#BI-CMYKRLE8}
```
public static final int BI_CMYKRLE8
```


Un format CMYK qui utilise la compression RLE pour les bitmaps avec 8 bits par pixel. La compression utilise un format de 2 octets composé d'un octet de compteur suivi d'un octet contenant un index de couleur.

### BI_CMYKRLE4 {#BI-CMYKRLE4}
```
public static final int BI_CMYKRLE4
```


Un format CMYK qui utilise la compression RLE pour les bitmaps avec 4 bits par pixel. La compression utilise un format de 2 octets composé d'un octet de compteur suivi de deux index de couleur de longueur mot.

