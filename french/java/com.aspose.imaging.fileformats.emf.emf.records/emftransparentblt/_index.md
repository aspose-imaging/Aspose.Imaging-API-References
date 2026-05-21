---
title: "EmfTransparentBlt"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_TRANSPARENTBLT spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination en traitant une couleur spécifiée comme transparente, en étirant ou compressant la sortie pour l'adapter aux dimensions de la destination si nécessaire."
type: docs
weight: 154
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfTransparentBlt extends EmfBitmapRecordType
```

L'enregistrement EMR\_TRANSPARENTBLT spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, en traitant une couleur spécifiée comme transparente, en étirant ou compressant la sortie pour l'adapter aux dimensions de la destination, si nécessaire.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfTransparentBlt(EmfRecord source)](#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfTransparentBlt`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de dispositif. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de dispositif. |
| [getXDest()](#getXDest--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle de destination. |
| [setXDest(int value)](#setXDest-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle de destination. |
| [getYDest()](#getYDest--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle de destination. |
| [setYDest(int value)](#setYDest-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle de destination. |
| [getCxDest()](#getCxDest--) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle de destination. |
| [setCxDest(int value)](#setCxDest-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle de destination. |
| [getCyDest()](#getCyDest--) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle de destination. |
| [setCyDest(int value)](#setCyDest-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle de destination. |
| [getTransparentArgb32Color()](#getTransparentArgb32Color--) | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la couleur dans le bitmap source à traiter comme transparente. |
| [setTransparentArgb32Color(int value)](#setTransparentArgb32Color-int-) | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la couleur dans le bitmap source à traiter comme transparente. |
| [getXSrc()](#getXSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle source. |
| [setXSrc(int value)](#setXSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle source. |
| [getYSrc()](#getYSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle source. |
| [setYSrc(int value)](#setYSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle source. |
| [getXformSrc()](#getXformSrc--) | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source. |
| [getSrcBkArgb32Color()](#getSrcBkArgb32Color--) | Obtient ou définit un objet WMF ColorRef qui spécifie la couleur d'arrière-plan du bitmap source. |
| [setSrcBkArgb32Color(int value)](#setSrcBkArgb32Color-int-) | Obtient ou définit un objet WMF ColorRef qui spécifie la couleur d'arrière-plan du bitmap source. |
| [getUsageSrc()](#getUsageSrc--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. |
| [getCxSrc()](#getCxSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle source. |
| [setCxSrc(int value)](#setCxSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle source. |
| [getCySrc()](#getCySrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle source. |
| [setCySrc(int value)](#setCySrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle source. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtient ou définit un tampon contenant le bitmap source, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EMR\_TRANSPARENTBLT. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit un tampon contenant le bitmap source, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EMR\_TRANSPARENTBLT. |
### EmfTransparentBlt(EmfRecord source) {#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfTransparentBlt(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfTransparentBlt`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de dispositif.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de dispositif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle de destination.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle de destination.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle de destination.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle de destination.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTransparentArgb32Color() {#getTransparentArgb32Color--}
```
public int getTransparentArgb32Color()
```


Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la couleur dans le bitmap source à traiter comme transparente.

**Returns:**
int
### setTransparentArgb32Color(int value) {#setTransparentArgb32Color-int-}
```
public void setTransparentArgb32Color(int value)
```


Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la couleur dans le bitmap source à traiter comme transparente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

### getXformSrc() {#getXformSrc--}
```
public Matrix getXformSrc()
```


Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSrc(Matrix value) {#setXformSrc-com.aspose.imaging.Matrix-}
```
public void setXformSrc(Matrix value)
```


Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getSrcBkArgb32Color() {#getSrcBkArgb32Color--}
```
public int getSrcBkArgb32Color()
```


Obtient ou définit un objet WMF ColorRef qui spécifie la couleur d'arrière-plan du bitmap source.

**Returns:**
int
### setSrcBkArgb32Color(int value) {#setSrcBkArgb32Color-int-}
```
public void setSrcBkArgb32Color(int value)
```


Obtient ou définit un objet WMF ColorRef qui spécifie la couleur d'arrière-plan du bitmap source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. Cette valeur DOIT être dans l'énumération DIBColors (section 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. Cette valeur DOIT être dans l'énumération DIBColors (section 2.1.9).

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

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Obtient ou définit un tampon contenant le bitmap source, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EMR\_TRANSPARENTBLT. En conséquence, les champs de ce tampon étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtient ou définit un tampon contenant le bitmap source, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EMR\_TRANSPARENTBLT. En conséquence, les champs de ce tampon étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

