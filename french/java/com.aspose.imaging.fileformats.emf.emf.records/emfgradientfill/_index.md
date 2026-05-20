---
title: "EmfGradientFill"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_GRADIENTFILL spécifie le remplissage de rectangles ou de triangles avec des dégradés de couleur."
type: docs
weight: 65
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfGradientFill extends EmfDrawingRecordType
```

L'enregistrement EMR\_GRADIENTFILL spécifie le remplissage de rectangles ou de triangles avec des dégradés de couleur.

Un enregistrement EMR_GRADIENTFILL qui indique que les trois sommets d'un triangle DOIVENT remplir la figure avec des dégradés lisses de couleurs.[85] Un enregistrement EMR_GRADIENTFILL qui indique que les sommets supérieur gauche et inférieur droit d'un rectangle DOIVENT remplir la figure avec des dégradés lisses de couleur. Il existe deux modes de remplissage de dégradé dans l'énumération GradientFill qui peuvent être utilisés lors du dessin d'un rectangle. En mode GRADIENT_FILL_RECT_H, le rectangle est rempli de gauche à droite. En mode GRADIENT_FILL_RECT_V, le rectangle est rempli de haut en bas. Note : Un enregistrement EMR_GRADIENTFILL DOIT ignorer les champs Alpha dans les objets TriVertex. Un enregistrement EMR_ALPHABLEND (section 2.3.1.1) qui suit immédiatement l'enregistrement EMR_GRADIENTFILL peut être utilisé pour appliquer un dégradé de transparence alpha à la zone remplie.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfGradientFill(EmfRecord source)](#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfGradientFill`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie un rectangle englobant, en unités de périphérique inclusives. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie un rectangle englobant, en unités de périphérique inclusives. |
| [getNVer()](#getNVer--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de sommets. |
| [setNVer(int value)](#setNVer-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de sommets. |
| [getNTri()](#getNTri--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de rectangles ou de triangles à remplir. |
| [setNTri(int value)](#setNTri-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de rectangles ou de triangles à remplir. |
| [getUlMode()](#getUlMode--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode de remplissage de dégradé. |
| [setUlMode(int value)](#setUlMode-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode de remplissage de dégradé. |
| [getVertexData()](#getVertexData--) | Obtient ou définit les objets qui spécifient les sommets de rectangles ou de triangles ainsi que les couleurs qui leur correspondent. |
| [setVertexData(EmfVertexData value)](#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-) | Obtient ou définit les objets qui spécifient les sommets de rectangles ou de triangles ainsi que les couleurs qui leur correspondent. |
### EmfGradientFill(EmfRecord source) {#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGradientFill(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfGradientFill`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie un rectangle englobant, en unités de périphérique inclusives.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie un rectangle englobant, en unités de périphérique inclusives.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNVer() {#getNVer--}
```
public int getNVer()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de sommets.

**Returns:**
int
### setNVer(int value) {#setNVer-int-}
```
public void setNVer(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de sommets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getNTri() {#getNTri--}
```
public int getNTri()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de rectangles ou de triangles à remplir.

**Returns:**
int
### setNTri(int value) {#setNTri-int-}
```
public void setNTri(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de rectangles ou de triangles à remplir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getUlMode() {#getUlMode--}
```
public int getUlMode()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le mode de remplissage en dégradé. La valeur DOIT appartenir à l'énumération GradientFill (section 2.1.15).

**Returns:**
int
### setUlMode(int value) {#setUlMode-int-}
```
public void setUlMode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le mode de remplissage en dégradé. La valeur DOIT appartenir à l'énumération GradientFill (section 2.1.15).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getVertexData() {#getVertexData--}
```
public EmfVertexData getVertexData()
```


Obtient ou définit les objets qui spécifient les sommets de rectangles ou de triangles ainsi que les couleurs qui leur correspondent.

**Returns:**
[EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata)
### setVertexData(EmfVertexData value) {#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-}
```
public void setVertexData(EmfVertexData value)
```


Obtient ou définit les objets qui spécifient les sommets de rectangles ou de triangles ainsi que les couleurs qui leur correspondent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata) |  |

