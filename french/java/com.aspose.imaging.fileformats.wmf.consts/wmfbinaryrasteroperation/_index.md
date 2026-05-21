---
title: "WmfBinaryRasterOperation"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La section de l'énumération BinaryRasterOperation répertorie les codes d'opération raster binaire."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfBinaryRasterOperation extends System.Enum
```

La section d'énumération BinaryRasterOperation répertorie les codes d'opération raster binaire. Les codes d'opération raster définissent comment le traitement du métafichier combine les bits du stylo sélectionné avec les bits du bitmap de destination.

--------------------

Chaque code d'opération raster représente une opération booléenne dans laquelle les valeurs des pixels du stylo sélectionné et du bitmap de destination sont combinées. Voici les deux opérandes utilisés dans ces opérations. Opérande Signification P Stylo sélectionné D Bitmap de destination a ET binaire n NON binaire (inverse) o OU binaire x OU exclusif binaire (XOR)
## Champs

| Champ | Description |
| --- | --- |
| [Black](#Black) | 0, le pixel est toujours 0. |
| [Notmergepen](#Notmergepen) | DPon, le pixel est l'inverse de la couleur MERGEPEN |
| [Masknotpen](#Masknotpen) | DPna, le pixel est une combinaison de la couleur de l'écran et de l'inverse de la couleur du stylo. |
| [Notcopypen](#Notcopypen) | Pn, le pixel est l'inverse de la couleur du stylo. |
| [Maskpennot](#Maskpennot) | PDna, le pixel est une combinaison des couleurs communes au stylo et à l'inverse de l'écran. |
| [Not](#Not) | Dn, le pixel est l'inverse de la couleur de l'écran. |
| [Xorpen](#Xorpen) | DPx, le pixel est une combinaison des couleurs du stylo ou de l'écran, mais pas des deux. |
| [Notmaskpen](#Notmaskpen) | DPan, le pixel est l'inverse de la couleur MASKPEN. |
| [Maskpen](#Maskpen) | DPa, le pixel est une combinaison des couleurs communes au stylo et à l'écran. |
| [Notxorpen](#Notxorpen) | DPxn, le pixel est l'inverse de la couleur XORPEN. |
| [Nop](#Nop) | D, le pixel reste inchangé. |
| [Mergenotpen](#Mergenotpen) | DPno, le pixel est une combinaison des couleurs communes à l'écran et à l'inverse du stylo. |
| [Copypen](#Copypen) | P, le Pixel est la couleur du stylo. |
| [Mergepennot](#Mergepennot) | PDno, le Pixel est une combinaison de la couleur du stylo et de l'inverse de la couleur de l'écran. |
| [Mergepen](#Mergepen) | DPo, le Pixel est une combinaison de la couleur du stylo et de la couleur de l'écran. |
| [White](#White) | 1, le Pixel est toujours 1 |
### Black {#Black}
```
public static final int Black
```


0, le pixel est toujours 0.

### Notmergepen {#Notmergepen}
```
public static final int Notmergepen
```


DPon, le pixel est l'inverse de la couleur MERGEPEN

### Masknotpen {#Masknotpen}
```
public static final int Masknotpen
```


DPna, le pixel est une combinaison de la couleur de l'écran et de l'inverse de la couleur du stylo.

### Notcopypen {#Notcopypen}
```
public static final int Notcopypen
```


Pn, le pixel est l'inverse de la couleur du stylo.

### Maskpennot {#Maskpennot}
```
public static final int Maskpennot
```


PDna, le pixel est une combinaison des couleurs communes au stylo et à l'inverse de l'écran.

### Not {#Not}
```
public static final int Not
```


Dn, le pixel est l'inverse de la couleur de l'écran.

### Xorpen {#Xorpen}
```
public static final int Xorpen
```


DPx, le pixel est une combinaison des couleurs du stylo ou de l'écran, mais pas des deux.

### Notmaskpen {#Notmaskpen}
```
public static final int Notmaskpen
```


DPan, le pixel est l'inverse de la couleur MASKPEN.

### Maskpen {#Maskpen}
```
public static final int Maskpen
```


DPa, le pixel est une combinaison des couleurs communes au stylo et à l'écran.

### Notxorpen {#Notxorpen}
```
public static final int Notxorpen
```


DPxn, le pixel est l'inverse de la couleur XORPEN.

### Nop {#Nop}
```
public static final int Nop
```


D, le pixel reste inchangé.

### Mergenotpen {#Mergenotpen}
```
public static final int Mergenotpen
```


DPno, le pixel est une combinaison des couleurs communes à l'écran et à l'inverse du stylo.

### Copypen {#Copypen}
```
public static final int Copypen
```


P, le Pixel est la couleur du stylo.

### Mergepennot {#Mergepennot}
```
public static final int Mergepennot
```


PDno, le Pixel est une combinaison de la couleur du stylo et de l'inverse de la couleur de l'écran.

### Mergepen {#Mergepen}
```
public static final int Mergepen
```


DPo, le Pixel est une combinaison de la couleur du stylo et de la couleur de l'écran.

### White {#White}
```
public static final int White
```


1, le Pixel est toujours 1

