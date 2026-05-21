---
title: "EmfPlusCustomLineCapArrowData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusCustomLineCapArrowData spécifie des données de flèche réglables pour un bouchon de ligne personnalisé."
type: docs
weight: 35
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecaparrowdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapArrowData extends EmfPlusCustomBaseLineCap
```

L'objet EmfPlusCustomLineCapArrowData spécifie des données de flèche réglables pour un bouchon de ligne personnalisé.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusCustomLineCapArrowData()](#EmfPlusCustomLineCapArrowData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la largeur du cap de flèche |
| [setWidth(float value)](#setWidth-float-) | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la largeur du cap de flèche |
| [getHeight()](#getHeight--) | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la hauteur du cap de flèche. |
| [setHeight(float value)](#setHeight-float-) | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la hauteur du cap de flèche. |
| [getMiddleInset()](#getMiddleInset--) | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie le nombre de pixels entre le contour du cap de flèche et le remplissage du cap de flèche. |
| [setMiddleInset(float value)](#setMiddleInset-float-) | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie le nombre de pixels entre le contour du cap de flèche et le remplissage du cap de flèche. |
| [getFillState()](#getFillState--) | Obtient ou définit une valeur booléenne 32 bits qui indique si le cap de flèche est rempli. |
| [setFillState(boolean value)](#setFillState-boolean-) | Obtient ou définit une valeur booléenne 32 bits qui indique si le cap de flèche est rempli. |
| [getLineStartCap()](#getLineStartCap--) | Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant le cap de ligne à utiliser au début de la ligne à tracer |
| [setLineStartCap(int value)](#setLineStartCap-int-) | Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant le cap de ligne à utiliser au début de la ligne à tracer |
| [getLineEndCap()](#getLineEndCap--) | Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant le cap de ligne à utiliser à la fin de la ligne à tracer |
| [setLineEndCap(int value)](#setLineEndCap-int-) | Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant le cap de ligne à utiliser à la fin de la ligne à tracer |
| [getLineJoin()](#getLineJoin--) | Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineJoin indiquant comment joindre deux lignes tracées par le même stylo et dont les extrémités se rencontrent. |
| [setLineJoin(int value)](#setLineJoin-int-) | Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineJoin indiquant comment joindre deux lignes tracées par le même stylo et dont les extrémités se rencontrent. |
| [getLineMiterLimit()](#getLineMiterLimit--) | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la limite de l'épaisseur de la jointure sur un coin en onglet en définissant le rapport maximal autorisé entre la longueur de l'onglet et la largeur de la ligne |
| [setLineMiterLimit(float value)](#setLineMiterLimit-float-) | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la limite de l'épaisseur de la jointure sur un coin en onglet en définissant le rapport maximal autorisé entre la longueur de l'onglet et la largeur de la ligne |
| [getWidthScale()](#getWidthScale--) | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la quantité par laquelle mettre à l'échelle un objet EmfPlusCustomLineCap par rapport à la largeur du stylo graphique utilisé pour tracer les lignes |
| [setWidthScale(float value)](#setWidthScale-float-) | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la quantité par laquelle mettre à l'échelle un objet EmfPlusCustomLineCap par rapport à la largeur du stylo graphique utilisé pour tracer les lignes |
| [getFillHotSpot()](#getFillHotSpot--) | Obtient ou définit l'objet EmfPlusPointF qui n'est pas actuellement utilisé. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | Obtient ou définit l'objet EmfPlusPointF qui n'est pas actuellement utilisé. |
| [getLineHotSpot()](#getLineHotSpot--) | Obtient ou définit un objet EmfPlusPointF qui n'est pas actuellement utilisé. |
| [setLineHotSpot(PointF value)](#setLineHotSpot-com.aspose.imaging.PointF-) | Obtient ou définit un objet EmfPlusPointF qui n'est pas actuellement utilisé. |
### EmfPlusCustomLineCapArrowData() {#EmfPlusCustomLineCapArrowData--}
```
public EmfPlusCustomLineCapArrowData()
```


### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la largeur du cap de flèche

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la largeur du cap de flèche

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la hauteur du cap de flèche.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la hauteur du cap de flèche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getMiddleInset() {#getMiddleInset--}
```
public float getMiddleInset()
```


Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie le nombre de pixels entre le contour du cap de flèche et le remplissage du cap de flèche.

**Returns:**
float
### setMiddleInset(float value) {#setMiddleInset-float-}
```
public void setMiddleInset(float value)
```


Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie le nombre de pixels entre le contour du cap de flèche et le remplissage du cap de flèche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getFillState() {#getFillState--}
```
public boolean getFillState()
```


Obtient ou définit une valeur booléenne 32 bits qui indique si le cap de flèche est rempli. Si le cap de flèche n'est pas rempli, seul le contour est dessiné

**Returns:**
boolean
### setFillState(boolean value) {#setFillState-boolean-}
```
public void setFillState(boolean value)
```


Obtient ou définit une valeur booléenne 32 bits qui indique si le cap de flèche est rempli. Si le cap de flèche n'est pas rempli, seul le contour est dessiné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getLineStartCap() {#getLineStartCap--}
```
public int getLineStartCap()
```


Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant le cap de ligne à utiliser au début de la ligne à tracer

**Returns:**
int
### setLineStartCap(int value) {#setLineStartCap-int-}
```
public void setLineStartCap(int value)
```


Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant le cap de ligne à utiliser au début de la ligne à tracer

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLineEndCap() {#getLineEndCap--}
```
public int getLineEndCap()
```


Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant le cap de ligne à utiliser à la fin de la ligne à tracer

**Returns:**
int
### setLineEndCap(int value) {#setLineEndCap-int-}
```
public void setLineEndCap(int value)
```


Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant le cap de ligne à utiliser à la fin de la ligne à tracer

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineJoin indiquant comment joindre deux lignes tracées par le même stylo et dont les extrémités se rencontrent. À l'intersection des deux extrémités de ligne, une jointure de ligne rend la connexion plus continue.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineJoin indiquant comment joindre deux lignes tracées par le même stylo et dont les extrémités se rencontrent. À l'intersection des deux extrémités de ligne, une jointure de ligne rend la connexion plus continue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLineMiterLimit() {#getLineMiterLimit--}
```
public float getLineMiterLimit()
```


Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la limite de l'épaisseur de la jointure sur un coin en onglet en définissant le rapport maximal autorisé entre la longueur de l'onglet et la largeur de la ligne

**Returns:**
float
### setLineMiterLimit(float value) {#setLineMiterLimit-float-}
```
public void setLineMiterLimit(float value)
```


Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la limite de l'épaisseur de la jointure sur un coin en onglet en définissant le rapport maximal autorisé entre la longueur de l'onglet et la largeur de la ligne

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la quantité par laquelle mettre à l'échelle un objet EmfPlusCustomLineCap par rapport à la largeur du stylo graphique utilisé pour tracer les lignes

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la quantité par laquelle mettre à l'échelle un objet EmfPlusCustomLineCap par rapport à la largeur du stylo graphique utilisé pour tracer les lignes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getFillHotSpot() {#getFillHotSpot--}
```
public PointF getFillHotSpot()
```


Obtient ou définit l'objet EmfPlusPointF qui n'est pas actuellement utilisé. Il DOIT être défini sur \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setFillHotSpot(PointF value) {#setFillHotSpot-com.aspose.imaging.PointF-}
```
public void setFillHotSpot(PointF value)
```


Obtient ou définit l'objet EmfPlusPointF qui n'est pas actuellement utilisé. Il DOIT être défini sur \{0.0, 0.0\}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getLineHotSpot() {#getLineHotSpot--}
```
public PointF getLineHotSpot()
```


Obtient ou définit un objet EmfPlusPointF qui n'est pas actuellement utilisé. Il DOIT être défini sur \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setLineHotSpot(PointF value) {#setLineHotSpot-com.aspose.imaging.PointF-}
```
public void setLineHotSpot(PointF value)
```


Obtient ou définit un objet EmfPlusPointF qui n'est pas actuellement utilisé. Il DOIT être défini sur \{0.0, 0.0\}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

