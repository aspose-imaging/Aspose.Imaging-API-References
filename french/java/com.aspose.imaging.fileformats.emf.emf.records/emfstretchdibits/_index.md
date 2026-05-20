---
title: "EmfStretchDiBits"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_STRETCHDIBITS spécifie un transfert de blocs de pixels d'un bitmap source vers un rectangle de destination, éventuellement en combinaison avec un motif de brosse, selon une opération raster spécifiée, en étirant ou compressant la sortie pour l'adapter aux dimensions de la destination si nécessaire."
type: docs
weight: 150
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchDiBits extends EmfBitmapRecordType
```

L'enregistrement EMR\_STRETCHDIBITS spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée, en étirant ou compressant la sortie pour l'adapter aux dimensions de la destination, si nécessaire.

Cet enregistrement prend en charge les images sources aux formats JPEG et PNG. Le champ Compression dans l'en-tête du bitmap source indique le format de l'image. Si les signes des champs de hauteur et de largeur de la source et de la destination diffèrent, cet enregistrement spécifie une copie en miroir du bitmap source vers la destination. Ainsi, si cxSrc et cxDest ont des signes différents, une image miroir du bitmap source le long de l'axe x est spécifiée. Si cySrc et cyDest ont des signes différents, une image miroir du bitmap source le long de l'axe y est spécifiée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfStretchDiBits(EmfRecord source)](#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfStretchDiBits`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de dispositif. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de dispositif. |
| [getXDest()](#getXDest--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle de destination. |
| [setXDest(int value)](#setXDest-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle de destination. |
| [getYDest()](#getYDest--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle de destination. |
| [setYDest(int value)](#setYDest-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle de destination. |
| [getXSrc()](#getXSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x en pixels du coin supérieur gauche du rectangle source. |
| [setXSrc(int value)](#setXSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x en pixels du coin supérieur gauche du rectangle source. |
| [getYSrc()](#getYSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y en pixels du coin supérieur gauche du rectangle source. |
| [setYSrc(int value)](#setYSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y en pixels du coin supérieur gauche du rectangle source. |
| [getCxSrc()](#getCxSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur en pixels du rectangle source. |
| [setCxSrc(int value)](#setCxSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur en pixels du rectangle source. |
| [getCySrc()](#getCySrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur en pixels du rectangle source. |
| [setCySrc(int value)](#setCySrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur en pixels du rectangle source. |
| [getUsageSrc()](#getUsageSrc--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Obtient ou définit un entier non signé de 32 bits qui spécifie un code d'opération raster. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie un code d'opération raster. |
| [getCxDest()](#getCxDest--) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle de destination. |
| [setCxDest(int value)](#setCxDest-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle de destination. |
| [getCyDest()](#getCyDest--) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle de destination. |
| [setCyDest(int value)](#setCyDest-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle de destination. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtient ou définit un tampon contenant le bitmap source, qui n'est pas tenu d'être contigu avec la partie fixe de l'enregistrement EMR\_STRETCHDIBITS. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit un tampon contenant le bitmap source, qui n'est pas tenu d'être contigu avec la partie fixe de l'enregistrement EMR\_STRETCHDIBITS. |
### EmfStretchDiBits(EmfRecord source) {#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchDiBits(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfStretchDiBits`.

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

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x en pixels du coin supérieur gauche du rectangle source.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x en pixels du coin supérieur gauche du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y en pixels du coin supérieur gauche du rectangle source.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y en pixels du coin supérieur gauche du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la largeur en pixels du rectangle source.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la largeur en pixels du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur en pixels du rectangle source.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur en pixels du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. Cette valeur DOIT appartenir à l'énumération DIBColors (section 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. Cette valeur DOIT appartenir à l'énumération DIBColors (section 2.1.9).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie un code d'opération raster. Ces codes définissent comment les données de couleur du rectangle source doivent être combinées avec les données de couleur du rectangle de destination et éventuellement un motif de brosse, afin d'obtenir la couleur finale.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie un code d'opération raster. Ces codes définissent comment les données de couleur du rectangle source doivent être combinées avec les données de couleur du rectangle de destination et éventuellement un motif de brosse, afin d'obtenir la couleur finale.

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

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Obtient ou définit un tampon contenant le bitmap source, qui n'est pas tenu d'être contigu avec la partie fixe de l'enregistrement EMR\_STRETCHDIBITS. En conséquence, les champs de ce tampon étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtient ou définit un tampon contenant le bitmap source, qui n'est pas tenu d'être contigu avec la partie fixe de l'enregistrement EMR\_STRETCHDIBITS. En conséquence, les champs de ce tampon étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

