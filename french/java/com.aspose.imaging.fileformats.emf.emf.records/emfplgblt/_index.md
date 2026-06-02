---
title: "EmfPlgBlt"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_PLGBLT spécifie un transfert de bloc de pixels d'un bitmap source vers un parallélogramme de destination avec l'application d'un bitmap de masque de couleur."
type: docs
weight: 84
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfPlgBlt extends EmfBitmapRecordType
```

L'enregistrement EMR\_PLGBLT spécifie un transfert de bloc de pixels d'une image source vers un parallélogramme de destination, avec l'application d'une image masque de couleur.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlgBlt(EmfRecord source)](#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfPlgBlt`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle englobant, en unités de dispositif, pour la sortie vers la destination. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle englobant, en unités de dispositif, pour la sortie vers la destination. |
| [getAptlDest()](#getAptlDest--) | Obtient ou définit un tableau de trois objets WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie les trois coins d’une zone de destination en parallélogramme pour le transfert de bloc. |
| [setAptlDest(Point[] value)](#setAptlDest-com.aspose.imaging.Point---) | Obtient ou définit un tableau de trois objets WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie les trois coins d’une zone de destination en parallélogramme pour le transfert de bloc. |
| [getXSrc()](#getXSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle source. |
| [setXSrc(int value)](#setXSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle source. |
| [getYSrc()](#getYSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle source. |
| [setYSrc(int value)](#setYSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle source. |
| [getCxSrc()](#getCxSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle source. |
| [setCxSrc(int value)](#setCxSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle source. |
| [getCySrc()](#getCySrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle source. |
| [setCySrc(int value)](#setCySrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle source. |
| [getXFormSrc()](#getXFormSrc--) | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source. |
| [setXFormSrc(Matrix value)](#setXFormSrc-com.aspose.imaging.Matrix-) | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la couleur d’arrière-plan du bitmap source. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la couleur d’arrière-plan du bitmap source. |
| [getUsageSrc()](#getUsageSrc--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. |
| [getXMask()](#getXMask--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du bitmap de masque. |
| [setXMask(int value)](#setXMask-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du bitmap de masque. |
| [getYMask()](#getYMask--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du bitmap de masque. |
| [setYMask(int value)](#setYMask-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du bitmap de masque. |
| [getUsageMask()](#getUsageMask--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du bitmap de masque. |
| [setUsageMask(int value)](#setUsageMask-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du bitmap de masque. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtient ou définit un tampon contenant le bitmap source, qui n’est pas obligé d’être contigu avec la partie fixe de l’enregistrement EMR\_PLGBLT ou entre eux. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit un tampon contenant le bitmap source, qui n’est pas obligé d’être contigu avec la partie fixe de l’enregistrement EMR\_PLGBLT ou entre eux. |
| [getMaskBitmap()](#getMaskBitmap--) | Obtient ou définit un tampon contenant le bitmap de masque, qui n’est pas obligé d’être contigu avec la partie fixe de l’enregistrement EMR\_PLGBLT ou entre eux. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit un tampon contenant le bitmap de masque, qui n’est pas obligé d’être contigu avec la partie fixe de l’enregistrement EMR\_PLGBLT ou entre eux. |
### EmfPlgBlt(EmfRecord source) {#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPlgBlt(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlgBlt`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle englobant, en unités de dispositif, pour la sortie vers la destination.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle englobant, en unités de dispositif, pour la sortie vers la destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAptlDest() {#getAptlDest--}
```
public Point[] getAptlDest()
```


Obtient ou définit un tableau de trois objets WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie les trois coins d’une zone de destination en parallélogramme pour le transfert de bloc. Le coin supérieur gauche du rectangle source est associé au premier point de ce tableau, le coin supérieur droit au deuxième point, et le coin inférieur gauche au troisième point. Le coin inférieur droit du rectangle source est associé au quatrième point implicite du parallélogramme, qui est calculé à partir des trois premiers points (A, B et C) en les traitant comme des vecteurs. D = B + C A

**Returns:**
com.aspose.imaging.Point[]
### setAptlDest(Point[] value) {#setAptlDest-com.aspose.imaging.Point---}
```
public void setAptlDest(Point[] value)
```


Obtient ou définit un tableau de trois objets WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie les trois coins d’une zone de destination en parallélogramme pour le transfert de bloc. Le coin supérieur gauche du rectangle source est associé au premier point de ce tableau, le coin supérieur droit au deuxième point, et le coin inférieur gauche au troisième point. Le coin inférieur droit du rectangle source est associé au quatrième point implicite du parallélogramme, qui est calculé à partir des trois premiers points (A, B et C) en les traitant comme des vecteurs. D = B + C A

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle source.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle source.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle source.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle source.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getXFormSrc() {#getXFormSrc--}
```
public Matrix getXFormSrc()
```


Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXFormSrc(Matrix value) {#setXFormSrc-com.aspose.imaging.Matrix-}
```
public void setXFormSrc(Matrix value)
```


Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBkSrcArgb32Color() {#getBkSrcArgb32Color--}
```
public int getBkSrcArgb32Color()
```


Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la couleur d’arrière-plan du bitmap source.

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la couleur d’arrière-plan du bitmap source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l’en-tête du bitmap source. Cette valeur DOIT appartenir à l’enumération DIBColors.

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l’en-tête du bitmap source. Cette valeur DOIT appartenir à l’enumération DIBColors.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getXMask() {#getXMask--}
```
public int getXMask()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du bitmap de masque.

**Returns:**
int
### setXMask(int value) {#setXMask-int-}
```
public void setXMask(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du bitmap de masque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getYMask() {#getYMask--}
```
public int getYMask()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du bitmap de masque.

**Returns:**
int
### setYMask(int value) {#setYMask-int-}
```
public void setYMask(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du bitmap de masque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getUsageMask() {#getUsageMask--}
```
public int getUsageMask()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du bitmap de masque. Cette valeur DOIT appartenir à l'énumération DIBColors.

**Returns:**
int
### setUsageMask(int value) {#setUsageMask-int-}
```
public void setUsageMask(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du bitmap de masque. Cette valeur DOIT appartenir à l'énumération DIBColors.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Obtient ou définit un tampon contenant le bitmap source, qui n’est pas obligé d’être contigu avec la partie fixe de l’enregistrement EMR\_PLGBLT ou entre eux. En conséquence, les champs de ce tampon portant le libellé "UndefinedSpace" sont facultatifs et DOIVENT être ignorés.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtient ou définit un tampon contenant le bitmap source, qui n’est pas obligé d’être contigu avec la partie fixe de l’enregistrement EMR\_PLGBLT ou entre eux. En conséquence, les champs de ce tampon portant le libellé "UndefinedSpace" sont facultatifs et DOIVENT être ignorés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Obtient ou définit un tampon contenant le bitmap de masque, qui n’est pas obligé d’être contigu avec la partie fixe de l’enregistrement EMR\_PLGBLT ou entre eux. En conséquence, les champs de ce tampon portant le libellé "UndefinedSpace" sont facultatifs et DOIVENT être ignorés.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Obtient ou définit un tampon contenant le bitmap de masque, qui n’est pas obligé d’être contigu avec la partie fixe de l’enregistrement EMR\_PLGBLT ou entre eux. En conséquence, les champs de ce tampon portant le libellé "UndefinedSpace" sont facultatifs et DOIVENT être ignorés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

