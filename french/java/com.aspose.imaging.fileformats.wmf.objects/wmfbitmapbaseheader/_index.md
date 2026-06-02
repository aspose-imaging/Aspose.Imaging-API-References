---
title: "WmfBitmapBaseHeader"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La classe d'en-tête de bitmap de base."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public abstract class WmfBitmapBaseHeader extends MetaObject
```

La classe d'en-tête de bitmap de base.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfBitmapBaseHeader()](#WmfBitmapBaseHeader--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Obtient ou définit un entier non signé de 32 bits qui définit la taille de cet objet, en octets. |
| [setHeaderSize(int value)](#setHeaderSize-int-) | Obtient ou définit un entier non signé de 32 bits qui définit la taille de cet objet, en octets. |
| [getPlanes()](#getPlanes--) | Obtient ou définit un entier non signé de 16 bits qui définit le nombre de `planes` pour le dispositif cible. |
| [setPlanes(short value)](#setPlanes-short-) | Obtient ou définit un entier non signé de 16 bits qui définit le nombre de `planes` pour le dispositif cible. |
| [getBitCount()](#getBitCount--) | Obtient ou définit un entier non signé de 16 bits qui définit le format de chaque pixel, et le nombre maximal de couleurs dans le DIB. |
| [setBitCount(short value)](#setBitCount-short-) | Obtient ou définit un entier non signé de 16 bits qui définit le format de chaque pixel, et le nombre maximal de couleurs dans le DIB. |
### WmfBitmapBaseHeader() {#WmfBitmapBaseHeader--}
```
public WmfBitmapBaseHeader()
```


### getHeaderSize() {#getHeaderSize--}
```
public int getHeaderSize()
```


Obtient ou définit un entier non signé de 32 bits qui définit la taille de cet objet, en octets.

**Returns:**
int
### setHeaderSize(int value) {#setHeaderSize-int-}
```
public void setHeaderSize(int value)
```


Obtient ou définit un entier non signé de 32 bits qui définit la taille de cet objet, en octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | un entier non signé de 16 bits qui définit le nombre de `planes` pour le dispositif cible. Cette valeur DOIT être 0x0001. |

### getPlanes() {#getPlanes--}
```
public short getPlanes()
```


Obtient ou définit un entier non signé de 16 bits qui définit le nombre de `planes` pour le dispositif cible. Cette valeur DOIT être 0x0001.

**Returns:**
short - un entier non signé de 16 bits qui définit le nombre de `planes` pour le dispositif cible.
### setPlanes(short value) {#setPlanes-short-}
```
public void setPlanes(short value)
```


Obtient ou définit un entier non signé de 16 bits qui définit le nombre de `planes` pour le dispositif cible. Cette valeur DOIT être 0x0001.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short | un entier non signé de 16 bits qui définit le nombre de `planes` pour le dispositif cible. Cette valeur DOIT être \* 0x0001. |

### getBitCount() {#getBitCount--}
```
public short getBitCount()
```


Obtient ou définit un entier non signé de 16 bits qui définit le format de chaque pixel et le nombre maximal de couleurs dans le DIB. Cette valeur DOIT être dans l'énumération `BitCount` (section 2.1.1.3).

**Returns:**
short - un entier non signé de 16 bits qui définit le format de chaque pixel et le nombre maximal de couleurs dans le DIB.
### setBitCount(short value) {#setBitCount-short-}
```
public void setBitCount(short value)
```


Obtient ou définit un entier non signé de 16 bits qui définit le format de chaque pixel et le nombre maximal de couleurs dans le DIB. Cette valeur DOIT être dans l'énumération `BitCount` (section 2.1.1.3).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short | un entier non signé de 16 bits qui définit le format de chaque pixel et le nombre maximal de couleurs dans le DIB. |

