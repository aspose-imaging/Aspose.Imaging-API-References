---
title: "TiffExifIfd"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe de répertoire de fichiers image Exif TIFF."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.tiff/tiffexififd/
---
**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

Classe de répertoire de fichiers image Exif TIFF.

Encapsule un pointeur vers l'Exif IFD. Interoperability, Exif IFD a la même structure que celle de l'IFD spécifié dans le TIFF. Ordinairement, cependant, il ne contient pas de données d'image comme dans le cas du TIFF. Voir http://www.exiv2.org/tags.html et http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html pour plus de détails.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Initialise une nouvelle instance de la classe `TiffExifIfd`. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Initialise une nouvelle instance de la classe `TiffExifIfd`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [hasValue()](#hasValue--) | Obtient une valeur indiquant si cette instance possède une valeur. |
| [getOffset()](#getOffset--) | Obtient ou définit le pointeur vers l'EXIF IFD. |
| [setOffset(long value)](#setOffset-long-) | Obtient ou définit le pointeur vers l'EXIF IFD. |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Initialise une nouvelle instance de la classe `TiffExifIfd`.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Initialise une nouvelle instance de la classe `TiffExifIfd`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | ifdOffset | long | Un pointeur vers l'Exif IFD. |

Interoperability, Exif IFD a la même structure que celle de l'IFD spécifié dans le TIFF. Ordinairement, cependant, il ne contient pas de données d'image comme dans le cas du TIFF. |

### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Obtient une valeur indiquant si cette instance possède une valeur.

**Returns:**
booléen - `true` si cette instance possède une valeur ; sinon, `false`.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Obtient ou définit le pointeur vers l'EXIF IFD.

**Returns:**
long - Le pointeur vers l'EXIF IFD.
### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


Obtient ou définit le pointeur vers l'EXIF IFD.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | Le pointeur vers l'EXIF IFD. |

