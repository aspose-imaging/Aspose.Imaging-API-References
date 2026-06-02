---
title: "EmfSetDiBitsToDevice"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETDIBITSTODEVICE spécifie un transfert de bloc de pixels depuis les lignes de numérisation spécifiées d'un bitmap source vers un rectangle de destination."
type: docs
weight: 124
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfSetDiBitsToDevice extends EmfBitmapRecordType
```

L'enregistrement EMR\_SETDIBITSTODEVICE spécifie un transfert de bloc de pixels depuis les lignes de balayage spécifiées d'un bitmap source vers un rectangle de destination.

Cet enregistrement prend en charge les images source au format JPEG et PNG. Le champ Compression dans l'en-tête du bitmap source spécifie le format de l'image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetDiBitsToDevice(EmfRecord source)](#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetDiBitsToDevice`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de dispositif. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de dispositif. |
| [getXDest()](#getXDest--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle de destination. |
| [setXDest(int value)](#setXDest-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle de destination. |
| [getYDest()](#getYDest--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle de destination. |
| [setYDest(int value)](#setYDest-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle de destination. |
| [getXSrc()](#getXSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x en pixels du coin inférieur gauche du rectangle source. |
| [setXSrc(int value)](#setXSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x en pixels du coin inférieur gauche du rectangle source. |
| [getYSrc()](#getYSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y en pixels du coin inférieur gauche du rectangle source. |
| [setYSrc(int value)](#setYSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y en pixels du coin inférieur gauche du rectangle source. |
| [getCxSrc()](#getCxSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur en pixels du rectangle source. |
| [setCxSrc(int value)](#setCxSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur en pixels du rectangle source. |
| [getCySrc()](#getCySrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur en pixels du rectangle source |
| [setCySrc(int value)](#setCySrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur en pixels du rectangle source |
| [getUsageSrc()](#getUsageSrc--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. |
| [getIStartScan()](#getIStartScan--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la première ligne de numérisation dans le tableau. |
| [setIStartScan(int value)](#setIStartScan-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la première ligne de numérisation dans le tableau. |
| [getCScans()](#getCScans--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de lignes de numérisation. |
| [setCScans(int value)](#setCScans-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de lignes de numérisation. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtient ou définit un tampon contenant le bitmap source, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EMR\_SETDIBITSTODEVICE. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit un tampon contenant le bitmap source, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EMR\_SETDIBITSTODEVICE. |
### EmfSetDiBitsToDevice(EmfRecord source) {#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetDiBitsToDevice(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetDiBitsToDevice`.

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


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x en pixels du coin inférieur gauche du rectangle source.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x en pixels du coin inférieur gauche du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y en pixels du coin inférieur gauche du rectangle source.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y en pixels du coin inférieur gauche du rectangle source.

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


Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur en pixels du rectangle source

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur en pixels du rectangle source

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

### getIStartScan() {#getIStartScan--}
```
public int getIStartScan()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la première ligne de numérisation dans le tableau.

**Returns:**
int
### setIStartScan(int value) {#setIStartScan-int-}
```
public void setIStartScan(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la première ligne de numérisation dans le tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCScans() {#getCScans--}
```
public int getCScans()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de lignes de numérisation.

**Returns:**
int
### setCScans(int value) {#setCScans-int-}
```
public void setCScans(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de lignes de numérisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Obtient ou définit un tampon contenant le bitmap source, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EMR\_SETDIBITSTODEVICE. En conséquence, les champs de ce tampon qui sont étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtient ou définit un tampon contenant le bitmap source, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EMR\_SETDIBITSTODEVICE. En conséquence, les champs de ce tampon qui sont étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

