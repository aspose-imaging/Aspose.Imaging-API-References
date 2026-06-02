---
title: "WmfBitmapInfoHeader"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet BitmapInfoHeader contient des informations sur les dimensions et le format couleur d'un bitmap indépendant du dispositif DIB."
type: docs
weight: 16
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
```
public class WmfBitmapInfoHeader extends WmfBitmapBaseHeader
```

L'objet BitmapInfoHeader contient des informations sur les dimensions et le format couleur d'un bitmap indépendant du dispositif (DIB).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [STRUCTURE_SIZE](#STRUCTURE-SIZE) | La taille de la structure |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Obtient ou définit un entier signé de 32 bits qui définit la largeur du DIB, en pixels. |
| [setWidth(int value)](#setWidth-int-) | Obtient ou définit un entier signé de 32 bits qui définit la largeur du DIB, en pixels. |
| [getHeight()](#getHeight--) | Obtient ou définit un entier signé de 32 bits qui définit la hauteur du DIB, en pixels. |
| [setHeight(int value)](#setHeight-int-) | Obtient ou définit un entier signé de 32 bits qui définit la hauteur du DIB, en pixels. |
| [getCompression()](#getCompression--) | Obtient ou définit un entier non signé de 32 bits qui définit le mode de compression du DIB. |
| [setCompression(int value)](#setCompression-int-) | Obtient ou définit un entier non signé de 32 bits qui définit le mode de compression du DIB. |
| [getImageSize()](#getImageSize--) | Obtient ou définit un entier non signé de 32 bits qui définit la taille, en octets, de l'image. |
| [setImageSize(int value)](#setImageSize-int-) | Obtient ou définit un entier non signé de 32 bits qui définit la taille, en octets, de l'image. |
| [getXPelsPerMeter()](#getXPelsPerMeter--) | Obtient ou définit un entier signé de 32 bits qui définit la résolution horizontale, en pixels par mètre, du dispositif cible pour le DIB |
| [setXPelsPerMeter(int value)](#setXPelsPerMeter-int-) | Obtient ou définit un entier signé de 32 bits qui définit la résolution horizontale, en pixels par mètre, du dispositif cible pour le DIB |
| [getYPelsPerMeter()](#getYPelsPerMeter--) | Obtient ou définit un entier signé de 32 bits qui définit la résolution verticale, en pixels par mètre, du dispositif cible pour le DIB |
| [setYPelsPerMeter(int value)](#setYPelsPerMeter-int-) | Obtient ou définit un entier signé de 32 bits qui définit la résolution verticale, en pixels par mètre, du dispositif cible pour le DIB |
| [getColorUsed()](#getColorUsed--) | Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'index dans la table de couleurs utilisée par le DIB, comme suit : si cette valeur est zéro, le DIB utilise le nombre maximal de couleurs correspondant à la valeur BitCount. |
| [setColorUsed(int value)](#setColorUsed-int-) | Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'index dans la table de couleurs utilisée par le DIB, comme suit : si cette valeur est zéro, le DIB utilise le nombre maximal de couleurs correspondant à la valeur BitCount. |
| [getColorImportant()](#getColorImportant--) | Obtient ou définit un entier non signé de 32 bits qui définit le nombre d'index de couleur requis pour afficher le DIB. |
| [setColorImportant(int value)](#setColorImportant-int-) | Obtient ou définit un entier non signé de 32 bits qui définit le nombre d'index de couleur requis pour afficher le DIB. |
### WmfBitmapInfoHeader() {#WmfBitmapInfoHeader--}
```
public WmfBitmapInfoHeader()
```


### STRUCTURE_SIZE {#STRUCTURE-SIZE}
```
public static final int STRUCTURE_SIZE
```


La taille de la structure

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient ou définit un entier signé de 32 bits qui définit la largeur du DIB, en pixels. Cette valeur DOIT être positive. Ce champ DEVRA spécifier la largeur du fichier image décompressé, si la valeur Compression spécifie le format JPEG ou PNG.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtient ou définit un entier signé de 32 bits qui définit la largeur du DIB, en pixels. Cette valeur DOIT être positive. Ce champ DEVRA spécifier la largeur du fichier image décompressé, si la valeur Compression spécifie le format JPEG ou PNG.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient ou définit un entier signé de 32 bits qui définit la hauteur du DIB, en pixels. Cette valeur NE DOIT PAS être zéro. Si cette valeur est positive, le DIB est un bitmap bottom‑up, et son origine est le coin inférieur gauche. Si cette valeur est négative, le DIB est un bitmap top‑down, et son origine est le coin supérieur gauche. Les bitmaps top‑down ne prennent pas en charge la compression. Ce champ DEVRA spécifier la hauteur du fichier image décompressé, si la valeur Compression spécifie le format JPEG ou PNG.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtient ou définit un entier signé de 32 bits qui définit la hauteur du DIB, en pixels. Cette valeur NE DOIT PAS être zéro. Si cette valeur est positive, le DIB est un bitmap bottom‑up, et son origine est le coin inférieur gauche. Si cette valeur est négative, le DIB est un bitmap top‑down, et son origine est le coin supérieur gauche. Les bitmaps top‑down ne prennent pas en charge la compression. Ce champ DEVRA spécifier la hauteur du fichier image décompressé, si la valeur Compression spécifie le format JPEG ou PNG.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Obtient ou définit un entier non signé de 32 bits qui définit le mode de compression du DIB. Cette valeur DOIT appartenir à l'énumération Compression (section 2.1.1.7). Cette valeur NE DOIT PAS spécifier un format compressé si le DIB est un bitmap top‑down, comme indiqué par la valeur Height.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Obtient ou définit un entier non signé de 32 bits qui définit le mode de compression du DIB. Cette valeur DOIT appartenir à l'énumération Compression (section 2.1.1.7). Cette valeur NE DOIT PAS spécifier un format compressé si le DIB est un bitmap top‑down, comme indiqué par la valeur Height.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getImageSize() {#getImageSize--}
```
public int getImageSize()
```


Obtient ou définit un entier non signé de 32 bits qui définit la taille, en octets, de l'image. Si la valeur Compression est BI\_RGB, cette valeur DEVRA être zéro et DOIT être ignorée. Si la valeur Compression est BI\_JPEG ou BI\_PNG, cette valeur DOIT spécifier la taille du tampon d'image JPEG ou PNG, respectivement.

**Returns:**
int
### setImageSize(int value) {#setImageSize-int-}
```
public void setImageSize(int value)
```


Obtient ou définit un entier non signé de 32 bits qui définit la taille, en octets, de l'image. Si la valeur Compression est BI\_RGB, cette valeur DEVRA être zéro et DOIT être ignorée. Si la valeur Compression est BI\_JPEG ou BI\_PNG, cette valeur DOIT spécifier la taille du tampon d'image JPEG ou PNG, respectivement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getXPelsPerMeter() {#getXPelsPerMeter--}
```
public int getXPelsPerMeter()
```


Obtient ou définit un entier signé de 32 bits qui définit la résolution horizontale, en pixels par mètre, du dispositif cible pour le DIB

**Returns:**
int
### setXPelsPerMeter(int value) {#setXPelsPerMeter-int-}
```
public void setXPelsPerMeter(int value)
```


Obtient ou définit un entier signé de 32 bits qui définit la résolution horizontale, en pixels par mètre, du dispositif cible pour le DIB

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getYPelsPerMeter() {#getYPelsPerMeter--}
```
public int getYPelsPerMeter()
```


Obtient ou définit un entier signé de 32 bits qui définit la résolution verticale, en pixels par mètre, du dispositif cible pour le DIB

**Returns:**
int
### setYPelsPerMeter(int value) {#setYPelsPerMeter-int-}
```
public void setYPelsPerMeter(int value)
```


Obtient ou définit un entier signé de 32 bits qui définit la résolution verticale, en pixels par mètre, du dispositif cible pour le DIB

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getColorUsed() {#getColorUsed--}
```
public int getColorUsed()
```


Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'index dans la table de couleurs utilisée par le DIB, comme suit : si cette valeur est zéro, le DIB utilise le nombre maximal de couleurs correspondant à la valeur BitCount. Si cette valeur est non nulle et que la valeur BitCount est inférieure à 16, cette valeur indique le nombre de couleurs utilisées par le DIB. Si cette valeur est non nulle et que la valeur BitCount est de 16 ou plus, cette valeur indique la taille de la table de couleurs utilisée pour optimiser les performances de la palette système. Remarque : si cette valeur est non nulle et supérieure à la taille maximale possible de la table de couleurs basée sur la valeur BitCount, la taille maximale de la table de couleurs DOIT être supposée.

**Returns:**
int
### setColorUsed(int value) {#setColorUsed-int-}
```
public void setColorUsed(int value)
```


Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'index dans la table de couleurs utilisée par le DIB, comme suit : si cette valeur est zéro, le DIB utilise le nombre maximal de couleurs correspondant à la valeur BitCount. Si cette valeur est non nulle et que la valeur BitCount est inférieure à 16, cette valeur indique le nombre de couleurs utilisées par le DIB. Si cette valeur est non nulle et que la valeur BitCount est de 16 ou plus, cette valeur indique la taille de la table de couleurs utilisée pour optimiser les performances de la palette système. Remarque : si cette valeur est non nulle et supérieure à la taille maximale possible de la table de couleurs basée sur la valeur BitCount, la taille maximale de la table de couleurs DOIT être supposée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getColorImportant() {#getColorImportant--}
```
public int getColorImportant()
```


Obtient ou définit un entier non signé de 32 bits qui définit le nombre d'index de couleur requis pour afficher le DIB. Si cette valeur est zéro, tous les index de couleur sont requis.

**Returns:**
int
### setColorImportant(int value) {#setColorImportant-int-}
```
public void setColorImportant(int value)
```


Obtient ou définit un entier non signé de 32 bits qui définit le nombre d'index de couleur requis pour afficher le DIB. Si cette valeur est zéro, tous les index de couleur sont requis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

