---
title: "WmfRegion"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet Region définit une forme potentiellement non rectiligne définie par un tableau de lignes de balayage."
type: docs
weight: 62
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfRegion extends MetaObject
```

L'objet Region définit une forme potentiellement non rectiligne définie par un tableau de lignes de balayage.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfRegion()](#WmfRegion--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getNextInChain()](#getNextInChain--) | Obtient ou définit le suivant dans la chaîne. |
| [setNextInChain(short value)](#setNextInChain-short-) | Obtient ou définit le suivant dans la chaîne. |
| [getObjectType()](#getObjectType--) | Obtient ou définit le type de l'objet. |
| [setObjectType(short value)](#setObjectType-short-) | Obtient ou définit le type de l'objet. |
| [getObjectCount()](#getObjectCount--) | Obtient ou définit le nombre d'objets. |
| [setObjectCount(int value)](#setObjectCount-int-) | Obtient ou définit le nombre d'objets. |
| [getRegionSize()](#getRegionSize--) | Obtient ou définit la taille de la région. |
| [setRegionSize(short value)](#setRegionSize-short-) | Obtient ou définit la taille de la région. |
| [getScanCount()](#getScanCount--) | Obtient ou définit le nombre de balayages. |
| [setScanCount(short value)](#setScanCount-short-) | Obtient ou définit le nombre de balayages. |
| [getMaxScan()](#getMaxScan--) | Obtient ou définit le balayage maximum. |
| [setMaxScan(short value)](#setMaxScan-short-) | Obtient ou définit le balayage maximum. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Obtient ou définit le rectangle englobant. |
| [setBoundingRectangle(Rectangle value)](#setBoundingRectangle-com.aspose.imaging.Rectangle-) | Obtient ou définit le rectangle englobant. |
| [getAScans()](#getAScans--) | Obtient ou définit les scans. |
| [setAScans(WmfScanObject[] value)](#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---) | Obtient ou définit les scans. |
### WmfRegion() {#WmfRegion--}
```
public WmfRegion()
```


### getNextInChain() {#getNextInChain--}
```
public short getNextInChain()
```


Obtient ou définit le suivant dans la chaîne.

Valeur : Une valeur qui DOIT être ignorée.

**Returns:**
short
### setNextInChain(short value) {#setNextInChain-short-}
```
public void setNextInChain(short value)
```


Obtient ou définit le suivant dans la chaîne.

Valeur : Une valeur qui DOIT être ignorée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getObjectType() {#getObjectType--}
```
public short getObjectType()
```


Obtient ou définit le type de l'objet.

Valeur : L'identifiant de la région. Il DOIT être 0x0006.

**Returns:**
short
### setObjectType(short value) {#setObjectType-short-}
```
public void setObjectType(short value)
```


Obtient ou définit le type de l'objet.

Valeur : L'identifiant de la région. Il DOIT être 0x0006.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getObjectCount() {#getObjectCount--}
```
public int getObjectCount()
```


Obtient ou définit le nombre d'objets.

Valeur : Une valeur qui DOIT être ignorée.

**Returns:**
int
### setObjectCount(int value) {#setObjectCount-int-}
```
public void setObjectCount(int value)
```


Obtient ou définit le nombre d'objets.

Valeur : Une valeur qui DOIT être ignorée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRegionSize() {#getRegionSize--}
```
public short getRegionSize()
```


Obtient ou définit la taille de la région.

Valeur : La taille de la région en octets plus la taille de aScans en octets.

**Returns:**
short
### setRegionSize(short value) {#setRegionSize-short-}
```
public void setRegionSize(short value)
```


Obtient ou définit la taille de la région.

Valeur : La taille de la région en octets plus la taille de aScans en octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getScanCount() {#getScanCount--}
```
public short getScanCount()
```


Obtient ou définit le nombre de balayages.

Valeur : Le nombre de lignes de numérisation composant la région.

**Returns:**
short
### setScanCount(short value) {#setScanCount-short-}
```
public void setScanCount(short value)
```


Obtient ou définit le nombre de balayages.

Valeur : Le nombre de lignes de numérisation composant la région.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getMaxScan() {#getMaxScan--}
```
public short getMaxScan()
```


Obtient ou définit le balayage maximum.

Valeur : Le nombre maximal de points dans une seule numérisation de cette région.

**Returns:**
short
### setMaxScan(short value) {#setMaxScan-short-}
```
public void setMaxScan(short value)
```


Obtient ou définit le balayage maximum.

Valeur : Le nombre maximal de points dans une seule numérisation de cette région.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Obtient ou définit le rectangle englobant.

Valeur : Un objet Rect (section 2.2.2.18) qui définit le rectangle englobant.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBoundingRectangle(Rectangle value) {#setBoundingRectangle-com.aspose.imaging.Rectangle-}
```
public void setBoundingRectangle(Rectangle value)
```


Obtient ou définit le rectangle englobant.

Valeur : Un objet Rect (section 2.2.2.18) qui définit le rectangle englobant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAScans() {#getAScans--}
```
public WmfScanObject[] getAScans()
```


Obtient ou définit les scans.

Valeur : Un tableau d'objets Scan (section 2.2.2.21) qui définissent les lignes de numérisation dans la région.

**Returns:**
com.aspose.imaging.fileformats.wmf.objects.WmfScanObject[]
### setAScans(WmfScanObject[] value) {#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---}
```
public void setAScans(WmfScanObject[] value)
```


Obtient ou définit les scans.

Valeur : Un tableau d'objets Scan (section 2.2.2.21) qui définissent les lignes de numérisation dans la région.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfScanObject\[\]](../../com.aspose.imaging.fileformats.wmf.objects/wmfscanobject) |  |

