---
title: "CompressionMethod"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Définit la méthode de compression utilisée pour les données d'image."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.psd/compressionmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionMethod extends System.Enum
```

Définit la méthode de compression utilisée pour les données d'image.
## Champs

| Champ | Description |
| --- | --- |
| [Raw](#Raw) | Pas de compression. |
| [RLE](#RLE) | Les données d'image compressées en RLE commencent par les comptes d'octets pour toutes les lignes de balayage (rows \* channels), chaque compte étant stocké sur deux octets. |
| [ZipWithoutPrediction](#ZipWithoutPrediction) | ZIP sans prédiction. |
| [ZipWithPrediction](#ZipWithPrediction) | ZIP avec prédiction. |
### Raw {#Raw}
```
public static final short Raw
```


Pas de compression. Les données d'image sont stockées sous forme d'octets bruts en ordre planaire RGBA. Cela signifie que d'abord toutes les données R sont écrites, puis toutes les données G, ensuite toutes les données B et enfin toutes les données A.

### RLE {#RLE}
```
public static final short RLE
```


Les données d'image compressées en RLE commencent par les comptes d'octets pour toutes les lignes de balayage (rows \* channels), chaque compte étant stocké sur deux octets. Les données compressées en RLE suivent, chaque ligne de balayage étant compressée séparément. La compression RLE est le même algorithme de compression utilisé par la routine PackBits du ROM Macintosh et la norme TIFF.

### ZipWithoutPrediction {#ZipWithoutPrediction}
```
public static final short ZipWithoutPrediction
```


ZIP sans prédiction.

### ZipWithPrediction {#ZipWithPrediction}
```
public static final short ZipWithPrediction
```


ZIP avec prédiction.

