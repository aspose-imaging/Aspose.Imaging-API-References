---
title: "EmfMaskBlt"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_MASKBLT spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, éventuellement en combinaison avec un motif de brosse et avec l'application d'un bitmap de masque de couleur selon les opérations raster de premier plan et d'arrière-plan spécifiées."
type: docs
weight: 69
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfMaskBlt extends EmfBitmapRecordType
```

L'enregistrement EMR\_MASKBLT spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, éventuellement en combinaison avec un motif de brosse et avec l'application d'un bitmap de masque de couleur, selon les opérations raster de premier plan et d'arrière-plan spécifiées.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfMaskBlt(EmfRecord source)](#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfMaskBlt`. |
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
| [getRop4()](#getRop4--) | Obtient ou définit une opération raster quaternaire, qui spécifie des opérations raster ternaires pour les couleurs de premier plan et d'arrière-plan d'un bitmap. |
| [setRop4(EmfRop4 value)](#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-) | Obtient ou définit une opération raster quaternaire, qui spécifie des opérations raster ternaires pour les couleurs de premier plan et d'arrière-plan d'un bitmap. |
| [getXSrc()](#getXSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle source. |
| [setXSrc(int value)](#setXSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique x du coin supérieur gauche du rectangle source. |
| [getYSrc()](#getYSrc--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle source. |
| [setYSrc(int value)](#setYSrc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée logique y du coin supérieur gauche du rectangle source. |
| [getXformSrc()](#getXformSrc--) | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source. |
| [getArgb32BkColorSrc()](#getArgb32BkColorSrc--) | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8 qui spécifie la couleur d'arrière-plan du bitmap source. |
| [setArgb32BkColorSrc(int value)](#setArgb32BkColorSrc-int-) | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8 qui spécifie la couleur d'arrière-plan du bitmap source. |
| [getUsageSrc()](#getUsageSrc--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleurs de l'en-tête du bitmap source. |
| [getXMask()](#getXMask--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du bitmap de masque. |
| [setXMask(int value)](#setXMask-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du bitmap de masque. |
| [getYMask()](#getYMask--) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du bitmap de masque. |
| [setYMask(int value)](#setYMask-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du bitmap de masque. |
| [getUsageMask()](#getUsageMask--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du bitmap de masque. |
| [setUsageMask(int value)](#setUsageMask-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du bitmap de masque. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtient ou définit un tampon contenant les bitmaps source, qui ne sont pas obligés d'être contigus avec la partie fixe de l'enregistrement EMR\_MASKBLT ou entre eux. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit un tampon contenant les bitmaps source, qui ne sont pas obligés d'être contigus avec la partie fixe de l'enregistrement EMR\_MASKBLT ou entre eux. |
| [getMaskBitmap()](#getMaskBitmap--) | Obtient ou définit un tampon contenant les bitmaps de masque, qui ne sont pas obligés d'être contigus avec la partie fixe de l'enregistrement EMR\_MASKBLT ou entre eux. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit un tampon contenant les bitmaps de masque, qui ne sont pas obligés d'être contigus avec la partie fixe de l'enregistrement EMR\_MASKBLT ou entre eux. |
### EmfMaskBlt(EmfRecord source) {#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMaskBlt(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfMaskBlt`.

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

### getRop4() {#getRop4--}
```
public EmfRop4 getRop4()
```


Obtient ou définit une opération raster quaternaire, qui spécifie des opérations raster ternaires pour les couleurs de premier plan et d'arrière-plan d'un bitmap. Ces valeurs définissent comment les données de couleur du rectangle source doivent être combinées avec les données de couleur du rectangle de destination.

**Returns:**
[EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4)
### setRop4(EmfRop4 value) {#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-}
```
public void setRop4(EmfRop4 value)
```


Obtient ou définit une opération raster quaternaire, qui spécifie des opérations raster ternaires pour les couleurs de premier plan et d'arrière-plan d'un bitmap. Ces valeurs définissent comment les données de couleur du rectangle source doivent être combinées avec les données de couleur du rectangle de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4) |  |

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

### getArgb32BkColorSrc() {#getArgb32BkColorSrc--}
```
public int getArgb32BkColorSrc()
```


Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8 qui spécifie la couleur d'arrière-plan du bitmap source.

**Returns:**
int
### setArgb32BkColorSrc(int value) {#setArgb32BkColorSrc-int-}
```
public void setArgb32BkColorSrc(int value)
```


Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8 qui spécifie la couleur d'arrière-plan du bitmap source.

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


Obtient ou définit un tampon contenant les bitmaps source, qui ne sont pas obligés d'être contigus avec la partie fixe de l'enregistrement EMR\_MASKBLT ou entre eux. En conséquence, les champs de ce tampon étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtient ou définit un tampon contenant les bitmaps source, qui ne sont pas obligés d'être contigus avec la partie fixe de l'enregistrement EMR\_MASKBLT ou entre eux. En conséquence, les champs de ce tampon étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Obtient ou définit un tampon contenant les bitmaps de masque, qui ne sont pas obligés d'être contigus avec la partie fixe de l'enregistrement EMR\_MASKBLT ou entre eux. En conséquence, les champs de ce tampon étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Obtient ou définit un tampon contenant les bitmaps de masque, qui ne sont pas obligés d'être contigus avec la partie fixe de l'enregistrement EMR\_MASKBLT ou entre eux. En conséquence, les champs de ce tampon étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

