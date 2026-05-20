---
title: "WmfScanObject"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet Scan spécifie une collection de lignes de balayage."
type: docs
weight: 69
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfscanobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfScanObject extends MetaObject
```

L'objet Scan spécifie une collection de lignes de balayage.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfScanObject()](#WmfScanObject--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Obtient ou définit le nombre. |
| [setCount(int value)](#setCount-int-) | Obtient ou définit le nombre. |
| [getTop()](#getTop--) | Obtient ou définit le haut. |
| [setTop(int value)](#setTop-int-) | Obtient ou définit le haut. |
| [getBottom()](#getBottom--) | Obtient ou définit le bas. |
| [setBottom(int value)](#setBottom-int-) | Obtient ou définit le bas. |
| [getScanLines()](#getScanLines--) | Obtient ou définit les lignes de numérisation. |
| [setScanLines(Point[] value)](#setScanLines-com.aspose.imaging.Point---) | Obtient ou définit les lignes de numérisation. |
| [getCount2()](#getCount2--) | Obtient ou définit le count2. |
| [setCount2(int value)](#setCount2-int-) | Obtient ou définit le count2. |
### WmfScanObject() {#WmfScanObject--}
```
public WmfScanObject()
```


### getCount() {#getCount--}
```
public int getCount()
```


Obtient ou définit le nombre.

Valeur : Le nombre de coordonnées horizontales (axe x) dans le tableau `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`. Cette valeur DOIT être un multiple de 2, car les points d'extrémité gauche et droit sont requis pour spécifier chaque ligne de numérisation.

**Returns:**
int
### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Obtient ou définit le nombre.

Valeur : Le nombre de coordonnées horizontales (axe x) dans le tableau `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`. Cette valeur DOIT être un multiple de 2, car les points d'extrémité gauche et droit sont requis pour spécifier chaque ligne de numérisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Obtient ou définit le haut.

Valeur : La coordonnée verticale (axe y), en unités logiques, de la ligne de numérisation supérieure.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Obtient ou définit le haut.

Valeur : La coordonnée verticale (axe y), en unités logiques, de la ligne de numérisation supérieure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Obtient ou définit le bas.

Valeur : La coordonnée verticale (axe y), en unités logiques, de la ligne de numérisation inférieure.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Obtient ou définit le bas.

Valeur : La coordonnée verticale (axe y), en unités logiques, de la ligne de numérisation inférieure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getScanLines() {#getScanLines--}
```
public Point[] getScanLines()
```


Obtient ou définit les lignes de numérisation.

Valeur : Un tableau de lignes de numérisation, chacune spécifiée par les coordonnées horizontales (axe x) gauche et droite de ses points d'extrémité.

**Returns:**
com.aspose.imaging.Point[]
### setScanLines(Point[] value) {#setScanLines-com.aspose.imaging.Point---}
```
public void setScanLines(Point[] value)
```


Obtient ou définit les lignes de numérisation.

Valeur : Un tableau de lignes de numérisation, chacune spécifiée par les coordonnées horizontales (axe x) gauche et droite de ses points d'extrémité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getCount2() {#getCount2--}
```
public int getCount2()
```


Obtient ou définit le count2.

Valeur : Identique à la valeur du champ `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count` ; il est présent pour permettre la navigation ascendante dans la structure.

**Returns:**
int
### setCount2(int value) {#setCount2-int-}
```
public void setCount2(int value)
```


Obtient ou définit le count2.

Valeur : Identique à la valeur du champ `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count` ; il est présent pour permettre la navigation ascendante dans la structure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

