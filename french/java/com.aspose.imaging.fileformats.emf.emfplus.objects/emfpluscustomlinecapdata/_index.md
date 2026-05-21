---
title: "EmfPlusCustomLineCapData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusCustomLineCapData spécifie les données par défaut pour un bouchon de ligne personnalisé."
type: docs
weight: 36
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapData extends EmfPlusCustomBaseLineCap
```

L'objet EmfPlusCustomLineCapData spécifie les données par défaut pour un bouchon de ligne personnalisé.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCustomLineCapDataFlags()](#getCustomLineCapDataFlags--) | Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData |
| [setCustomLineCapDataFlags(int value)](#setCustomLineCapDataFlags-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData |
| [getBaseCap()](#getBaseCap--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur de l'énumération LineCap (section 2.1.1.18) sur laquelle la coiffe de ligne personnalisée est basée. |
| [setBaseCap(int value)](#setBaseCap-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur de l'énumération LineCap (section 2.1.1.18) sur laquelle la coiffe de ligne personnalisée est basée. |
| [getBaseInset()](#getBaseInset--) | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie la distance entre le début de la coiffe de ligne et la fin de la ligne. |
| [setBaseInset(float value)](#setBaseInset-float-) | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie la distance entre le début de la coiffe de ligne et la fin de la ligne. |
| [getStrokeStartCap()](#getStrokeStartCap--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant la coiffe de ligne utilisée au début de la ligne à tracer |
| [setStrokeStartCap(int value)](#setStrokeStartCap-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant la coiffe de ligne utilisée au début de la ligne à tracer |
| [getStrokeEndCap()](#getStrokeEndCap--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant la coiffe de ligne à utiliser à la fin de la ligne à tracer. |
| [setStrokeEndCap(int value)](#setStrokeEndCap-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant la coiffe de ligne à utiliser à la fin de la ligne à tracer. |
| [getStrokeJoin()](#getStrokeJoin--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineJoin (section 2.1.1.19), qui indique comment joindre deux lignes tracées par le même stylo et dont les extrémités se rencontrent. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineJoin (section 2.1.1.19), qui indique comment joindre deux lignes tracées par le même stylo et dont les extrémités se rencontrent. |
| [getStrokeMiterLimit()](#getStrokeMiterLimit--) | Obtient ou définit une valeur à virgule flottante de 32 bits qui contient la limite de l'épaisseur de la jointure sur un coin en onglet en définissant le rapport maximal autorisé entre la longueur de l'onglet et la largeur de la ligne. |
| [setStrokeMiterLimit(float value)](#setStrokeMiterLimit-float-) | Obtient ou définit une valeur à virgule flottante de 32 bits qui contient la limite de l'épaisseur de la jointure sur un coin en onglet en définissant le rapport maximal autorisé entre la longueur de l'onglet et la largeur de la ligne. |
| [getWidthScale()](#getWidthScale--) | Obtient ou définit une valeur flottante 32 bits qui spécifie la quantité par laquelle mettre à l'échelle le capuchon de ligne personnalisé par rapport à la largeur de l'objet EmfPlusPen (section 2.2.1.7) utilisé pour tracer les lignes. |
| [setWidthScale(float value)](#setWidthScale-float-) | Obtient ou définit une valeur flottante 32 bits qui spécifie la quantité par laquelle mettre à l'échelle le capuchon de ligne personnalisé par rapport à la largeur de l'objet EmfPlusPen (section 2.2.1.7) utilisé pour tracer les lignes. |
| [getFillHotSpot()](#getFillHotSpot--) | Obtient ou définit l'objet EmfPlusPointF qui n'est pas actuellement utilisé. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | Obtient ou définit l'objet EmfPlusPointF qui n'est pas actuellement utilisé. |
| [getStrokeHotSpot()](#getStrokeHotSpot--) | Obtient ou définit l'objet EmfPlusPointF qui n'est pas actuellement utilisé. |
| [setStrokeHotSpot(PointF value)](#setStrokeHotSpot-com.aspose.imaging.PointF-) | Obtient ou définit l'objet EmfPlusPointF qui n'est pas actuellement utilisé. |
| [getOptionalData()](#getOptionalData--) | Obtient ou définit l'objet optionnel EmfPlusCustomLineCapOptionalData (section 2.2.2.14) qui spécifie des données supplémentaires pour le capuchon de ligne graphique personnalisé. |
| [setOptionalData(EmfPlusCustomLineCapOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-) | Obtient ou définit l'objet optionnel EmfPlusCustomLineCapOptionalData (section 2.2.2.14) qui spécifie des données supplémentaires pour le capuchon de ligne graphique personnalisé. |
### EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData--}
```
public EmfPlusCustomLineCapData()
```


### getCustomLineCapDataFlags() {#getCustomLineCapDataFlags--}
```
public int getCustomLineCapDataFlags()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData

**Returns:**
int
### setCustomLineCapDataFlags(int value) {#setCustomLineCapDataFlags-int-}
```
public void setCustomLineCapDataFlags(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur de l'énumération LineCap (section 2.1.1.18) sur laquelle la coiffe de ligne personnalisée est basée.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur de l'énumération LineCap (section 2.1.1.18) sur laquelle la coiffe de ligne personnalisée est basée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie la distance entre le début de la coiffe de ligne et la fin de la ligne.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie la distance entre le début de la coiffe de ligne et la fin de la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getStrokeStartCap() {#getStrokeStartCap--}
```
public int getStrokeStartCap()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant la coiffe de ligne utilisée au début de la ligne à tracer

**Returns:**
int
### setStrokeStartCap(int value) {#setStrokeStartCap-int-}
```
public void setStrokeStartCap(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant la coiffe de ligne utilisée au début de la ligne à tracer

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getStrokeEndCap() {#getStrokeEndCap--}
```
public int getStrokeEndCap()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant la coiffe de ligne à utiliser à la fin de la ligne à tracer.

**Returns:**
int
### setStrokeEndCap(int value) {#setStrokeEndCap-int-}
```
public void setStrokeEndCap(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineCap indiquant la coiffe de ligne à utiliser à la fin de la ligne à tracer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineJoin (section 2.1.1.19), laquelle indique comment joindre deux lignes tracées par le même stylo et dont les extrémités se rencontrent. À l'intersection des deux extrémités de ligne, une jointure de ligne rend la connexion plus continue.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Obtient ou définit un entier non signé 32 bits qui spécifie la valeur dans l'énumération LineJoin (section 2.1.1.19), laquelle indique comment joindre deux lignes tracées par le même stylo et dont les extrémités se rencontrent. À l'intersection des deux extrémités de ligne, une jointure de ligne rend la connexion plus continue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getStrokeMiterLimit() {#getStrokeMiterLimit--}
```
public float getStrokeMiterLimit()
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui contient la limite de l'épaisseur de la jointure sur un coin en onglet en définissant le rapport maximal autorisé entre la longueur de l'onglet et la largeur de la ligne.

**Returns:**
float
### setStrokeMiterLimit(float value) {#setStrokeMiterLimit-float-}
```
public void setStrokeMiterLimit(float value)
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui contient la limite de l'épaisseur de la jointure sur un coin en onglet en définissant le rapport maximal autorisé entre la longueur de l'onglet et la largeur de la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Obtient ou définit une valeur flottante 32 bits qui spécifie la quantité par laquelle mettre à l'échelle le capuchon de ligne personnalisé par rapport à la largeur de l'objet EmfPlusPen (section 2.2.1.7) utilisé pour tracer les lignes.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Obtient ou définit une valeur flottante 32 bits qui spécifie la quantité par laquelle mettre à l'échelle le capuchon de ligne personnalisé par rapport à la largeur de l'objet EmfPlusPen (section 2.2.1.7) utilisé pour tracer les lignes.

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

### getStrokeHotSpot() {#getStrokeHotSpot--}
```
public PointF getStrokeHotSpot()
```


Obtient ou définit l'objet EmfPlusPointF qui n'est pas actuellement utilisé. Il DOIT être défini sur \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setStrokeHotSpot(PointF value) {#setStrokeHotSpot-com.aspose.imaging.PointF-}
```
public void setStrokeHotSpot(PointF value)
```


Obtient ou définit l'objet EmfPlusPointF qui n'est pas actuellement utilisé. Il DOIT être défini sur \{0.0, 0.0\}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusCustomLineCapOptionalData getOptionalData()
```


Obtient ou définit l'objet optionnel EmfPlusCustomLineCapOptionalData (section 2.2.2.14) qui spécifie des données supplémentaires pour le capuchon de ligne graphique personnalisé. Le contenu spécifique de ce champ est déterminé par la valeur du champ CustomLineCapDataFlags.

**Returns:**
[EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata)
### setOptionalData(EmfPlusCustomLineCapOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-}
```
public void setOptionalData(EmfPlusCustomLineCapOptionalData value)
```


Obtient ou définit l'objet optionnel EmfPlusCustomLineCapOptionalData (section 2.2.2.14) qui spécifie des données supplémentaires pour le capuchon de ligne graphique personnalisé. Le contenu spécifique de ce champ est déterminé par la valeur du champ CustomLineCapDataFlags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata) |  |

