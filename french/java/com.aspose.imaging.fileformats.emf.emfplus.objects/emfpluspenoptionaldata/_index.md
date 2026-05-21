---
title: "EmfPlusPenOptionalData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusPenOptionalData spécifie des données optionnelles pour un stylo graphique"
type: docs
weight: 65
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenOptionalData extends EmfPlusStructureObjectType
```

L'objet EmfPlusPenOptionalData spécifie des données optionnelles pour un stylo graphique
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Obtient ou définit un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le stylo. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Obtient ou définit un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le stylo. |
| [getStartCap()](#getStartCap--) | Obtient ou définit un entier signé de 32 bits optionnel qui spécifie la forme du début d'une ligne dans le champ CustomStartCapData. |
| [setStartCap(int value)](#setStartCap-int-) | Obtient ou définit un entier signé de 32 bits optionnel qui spécifie la forme du début d'une ligne dans le champ CustomStartCapData. |
| [getEndCap()](#getEndCap--) | Obtient ou définit un entier signé de 32 bits optionnel qui spécifie la forme de la fin d'une ligne dans le champ CustomEndCapData. |
| [setEndCap(int value)](#setEndCap-int-) | Obtient ou définit un entier signé de 32 bits optionnel qui spécifie la forme de la fin d'une ligne dans le champ CustomEndCapData. |
| [getJoin()](#getJoin--) | Obtient ou définit un entier signé de 32 bits optionnel qui spécifie comment joindre deux lignes dessinées par le même stylo et dont les extrémités se rencontrent. |
| [setJoin(int value)](#setJoin-int-) | Obtient ou définit un entier signé de 32 bits optionnel qui spécifie comment joindre deux lignes dessinées par le même stylo et dont les extrémités se rencontrent. |
| [getMiterLimit()](#getMiterLimit--) | Obtient ou définit une valeur flottante de 32 bits optionnelle qui spécifie la limite de jointure (miter), qui est le rapport maximal autorisé entre la longueur de la jointure et la largeur de la ligne. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Obtient ou définit une valeur flottante de 32 bits optionnelle qui spécifie la limite de jointure (miter), qui est le rapport maximal autorisé entre la longueur de la jointure et la largeur de la ligne. |
| [getLineStyle()](#getLineStyle--) | Obtient ou définit un entier signé de 32 bits optionnel qui spécifie le style utilisé pour les lignes dessinées avec cet objet stylo. |
| [setLineStyle(int value)](#setLineStyle-int-) | Obtient ou définit un entier signé de 32 bits optionnel qui spécifie le style utilisé pour les lignes dessinées avec cet objet stylo. |
| [getDashedLineCapType()](#getDashedLineCapType--) | Obtient ou définit un entier signé de 32 bits optionnel qui spécifie la forme des deux extrémités de chaque tiret dans une ligne pointillée. |
| [setDashedLineCapType(int value)](#setDashedLineCapType-int-) | Obtient ou définit un entier signé de 32 bits optionnel qui spécifie la forme des deux extrémités de chaque tiret dans une ligne pointillée. |
| [getDashOffset()](#getDashOffset--) | Obtient ou définit une valeur flottante de 32 bits optionnelle qui spécifie la distance du début d'une ligne au début du premier espace dans un motif de ligne pointillée. |
| [setDashOffset(float value)](#setDashOffset-float-) | Obtient ou définit une valeur flottante de 32 bits optionnelle qui spécifie la distance du début d'une ligne au début du premier espace dans un motif de ligne pointillée. |
| [getDashedLineData()](#getDashedLineData--) | Obtient ou définit un objet optionnel EmfPlusDashedLineData (section 2.2.2.16) qui spécifie les longueurs des tirets et des espaces dans une ligne pointillée personnalisée. |
| [setDashedLineData(EmfPlusDashedLineData value)](#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-) | Obtient ou définit un objet optionnel EmfPlusDashedLineData (section 2.2.2.16) qui spécifie les longueurs des tirets et des espaces dans une ligne pointillée personnalisée. |
| [getPenAlignment()](#getPenAlignment--) | Obtient ou définit un entier signé de 32 bits optionnel qui spécifie la répartition de la largeur du stylo par rapport aux coordonnées de la ligne dessinée. |
| [setPenAlignment(int value)](#setPenAlignment-int-) | Obtient ou définit un entier signé de 32 bits optionnel qui spécifie la répartition de la largeur du stylo par rapport aux coordonnées de la ligne dessinée. |
| [getCompoundLineData()](#getCompoundLineData--) | Obtient ou définit un objet optionnel EmfPlusCompoundLineData (section 2.2.2.9) qui spécifie un tableau de valeurs flottantes définissant la ligne composée d'un stylo, constituée de lignes parallèles et d'espaces. |
| [setCompoundLineData(EmfPlusCompoundLineData value)](#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-) | Obtient ou définit un objet optionnel EmfPlusCompoundLineData (section 2.2.2.9) qui spécifie un tableau de valeurs flottantes définissant la ligne composée d'un stylo, constituée de lignes parallèles et d'espaces. |
| [getCustomStartCapData()](#getCustomStartCapData--) | Obtient ou définit un objet optionnel EmfPlusCustomStartCapData (section 2.2.2.15) qui définit la forme de capuchon de départ personnalisée, qui est la forme à utiliser au début d'une ligne dessinée avec ce stylo. |
| [setCustomStartCapData(EmfPlusCustomStartCapData value)](#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-) | Obtient ou définit un objet optionnel EmfPlusCustomStartCapData (section 2.2.2.15) qui définit la forme de capuchon de départ personnalisée, qui est la forme à utiliser au début d'une ligne dessinée avec ce stylo. |
| [getCustomEndCapData()](#getCustomEndCapData--) | Obtient ou définit un objet optionnel EmfPlusCustomEndCapData (section 2.2.2.11) qui définit la forme de capuchon de fin personnalisée, qui est la forme à utiliser à la fin d'une ligne dessinée avec ce stylo. |
| [setCustomEndCapData(EmfPlusCustomEndCapData value)](#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-) | Obtient ou définit un objet optionnel EmfPlusCustomEndCapData (section 2.2.2.11) qui définit la forme de capuchon de fin personnalisée, qui est la forme à utiliser à la fin d'une ligne dessinée avec ce stylo. |
### EmfPlusPenOptionalData() {#EmfPlusPenOptionalData--}
```
public EmfPlusPenOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Obtient ou définit un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le stylo. Ce champ DOIT être présent si le drapeau PenDataTransform est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Obtient ou définit un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le stylo. Ce champ DOIT être présent si le drapeau PenDataTransform est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Obtient ou définit un entier signé de 32 bits optionnel qui spécifie la forme du début d'une ligne dans le champ CustomStartCapData. Ce champ DOIT être présent si le drapeau PenDataStartCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération LineCapType (section 2.1.1.18).

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Obtient ou définit un entier signé de 32 bits optionnel qui spécifie la forme du début d'une ligne dans le champ CustomStartCapData. Ce champ DOIT être présent si le drapeau PenDataStartCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération LineCapType (section 2.1.1.18).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Obtient ou définit un entier signé de 32 bits optionnel qui spécifie la forme de la fin d'une ligne dans le champ CustomEndCapData. Ce champ DOIT être présent si le drapeau PenDataEndCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération LineCapType.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Obtient ou définit un entier signé de 32 bits optionnel qui spécifie la forme de la fin d'une ligne dans le champ CustomEndCapData. Ce champ DOIT être présent si le drapeau PenDataEndCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération LineCapType.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getJoin() {#getJoin--}
```
public int getJoin()
```


Obtient ou définit un entier signé de 32 bits facultatif qui spécifie comment joindre deux lignes tracées par le même stylo et dont les extrémités se rencontrent. Ce champ DOIT être présent si le drapeau PenDataJoin est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération LineJoinType (section 2.1.1.19).

**Returns:**
int
### setJoin(int value) {#setJoin-int-}
```
public void setJoin(int value)
```


Obtient ou définit un entier signé de 32 bits facultatif qui spécifie comment joindre deux lignes tracées par le même stylo et dont les extrémités se rencontrent. Ce champ DOIT être présent si le drapeau PenDataJoin est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération LineJoinType (section 2.1.1.19).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Obtient ou définit une valeur flottante de 32 bits facultative qui spécifie la limite de jointure en onglet, qui est le rapport maximal autorisé entre la longueur de l'onglet et la largeur de la ligne. La longueur de l'onglet est la distance entre l'intersection des parois de la ligne à l'intérieur de la jointure et l'intersection des parois de la ligne à l'extérieur de la jointure. La longueur de l'onglet peut être grande lorsque l'angle entre deux lignes est petit. Ce champ DOIT être présent si le drapeau PenDataMiterLimit est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Obtient ou définit une valeur flottante de 32 bits facultative qui spécifie la limite de jointure en onglet, qui est le rapport maximal autorisé entre la longueur de l'onglet et la largeur de la ligne. La longueur de l'onglet est la distance entre l'intersection des parois de la ligne à l'intérieur de la jointure et l'intersection des parois de la ligne à l'extérieur de la jointure. La longueur de l'onglet peut être grande lorsque l'angle entre deux lignes est petit. Ce champ DOIT être présent si le drapeau PenDataMiterLimit est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getLineStyle() {#getLineStyle--}
```
public int getLineStyle()
```


Obtient ou définit un entier signé de 32 bits facultatif qui spécifie le style utilisé pour les lignes tracées avec cet objet stylo. Ce champ DOIT être présent si le drapeau PenDataLineStyle est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération LineStyle (section 2.1.1.20).

**Returns:**
int
### setLineStyle(int value) {#setLineStyle-int-}
```
public void setLineStyle(int value)
```


Obtient ou définit un entier signé de 32 bits facultatif qui spécifie le style utilisé pour les lignes tracées avec cet objet stylo. Ce champ DOIT être présent si le drapeau PenDataLineStyle est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération LineStyle (section 2.1.1.20).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDashedLineCapType() {#getDashedLineCapType--}
```
public int getDashedLineCapType()
```


Obtient ou définit un entier signé de 32 bits facultatif qui spécifie la forme des deux extrémités de chaque tiret dans une ligne pointillée. Ce champ DOIT être présent si le drapeau PenDataDashedLineCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération DashedLineCapType (section 2.1.1.10).

**Returns:**
int
### setDashedLineCapType(int value) {#setDashedLineCapType-int-}
```
public void setDashedLineCapType(int value)
```


Obtient ou définit un entier signé de 32 bits facultatif qui spécifie la forme des deux extrémités de chaque tiret dans une ligne pointillée. Ce champ DOIT être présent si le drapeau PenDataDashedLineCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération DashedLineCapType (section 2.1.1.10).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Obtient ou définit une valeur flottante de 32 bits facultative qui spécifie la distance entre le début d'une ligne et le début du premier espace dans un motif de ligne pointillée. Ce champ DOIT être présent si le drapeau PenDataDashedLineOffset est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Returns:**
float
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Obtient ou définit une valeur flottante de 32 bits facultative qui spécifie la distance entre le début d'une ligne et le début du premier espace dans un motif de ligne pointillée. Ce champ DOIT être présent si le drapeau PenDataDashedLineOffset est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getDashedLineData() {#getDashedLineData--}
```
public EmfPlusDashedLineData getDashedLineData()
```


Obtient ou définit un objet EmfPlusDashedLineData facultatif (section 2.2.2.16) qui spécifie les longueurs des tirets et des espaces dans une ligne pointillée personnalisée. Ce champ DOIT être présent si le drapeau PenDataDashedLine est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Returns:**
[EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata)
### setDashedLineData(EmfPlusDashedLineData value) {#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-}
```
public void setDashedLineData(EmfPlusDashedLineData value)
```


Obtient ou définit un objet EmfPlusDashedLineData facultatif (section 2.2.2.16) qui spécifie les longueurs des tirets et des espaces dans une ligne pointillée personnalisée. Ce champ DOIT être présent si le drapeau PenDataDashedLine est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) |  |

### getPenAlignment() {#getPenAlignment--}
```
public int getPenAlignment()
```


Obtient ou définit un entier signé de 32 bits facultatif qui spécifie la répartition de la largeur du stylo par rapport aux coordonnées de la ligne tracée. Ce champ DOIT être présent si le drapeau PenDataNonCenter est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération PenAlignment (section 2.1.1.24).

**Returns:**
int
### setPenAlignment(int value) {#setPenAlignment-int-}
```
public void setPenAlignment(int value)
```


Obtient ou définit un entier signé de 32 bits facultatif qui spécifie la répartition de la largeur du stylo par rapport aux coordonnées de la ligne tracée. Ce champ DOIT être présent si le drapeau PenDataNonCenter est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération PenAlignment (section 2.1.1.24).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCompoundLineData() {#getCompoundLineData--}
```
public EmfPlusCompoundLineData getCompoundLineData()
```


Obtient ou définit un objet EmfPlusCompoundLineData facultatif (section 2.2.2.9) qui spécifie un tableau de valeurs flottantes définissant la ligne composée d'un stylo, constituée de lignes parallèles et d'espaces. Ce champ DOIT être présent si le drapeau PenDataCompoundLine est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Returns:**
[EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)
### setCompoundLineData(EmfPlusCompoundLineData value) {#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-}
```
public void setCompoundLineData(EmfPlusCompoundLineData value)
```


Obtient ou définit un objet EmfPlusCompoundLineData facultatif (section 2.2.2.9) qui spécifie un tableau de valeurs flottantes définissant la ligne composée d'un stylo, constituée de lignes parallèles et d'espaces. Ce champ DOIT être présent si le drapeau PenDataCompoundLine est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) |  |

### getCustomStartCapData() {#getCustomStartCapData--}
```
public EmfPlusCustomStartCapData getCustomStartCapData()
```


Obtient ou définit un objet EmfPlusCustomStartCapData facultatif (section 2.2.2.15) qui définit la forme de la coiffe de départ personnalisée, c’est‑à‑dire la forme à utiliser au début d’une ligne tracée avec ce stylo. Elle peut être l’une des diverses formes, comme un carré, un cercle ou un losange. Ce champ DOIT être présent si le drapeau PenDataCustomStartCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Returns:**
[EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata)
### setCustomStartCapData(EmfPlusCustomStartCapData value) {#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-}
```
public void setCustomStartCapData(EmfPlusCustomStartCapData value)
```


Obtient ou définit un objet EmfPlusCustomStartCapData facultatif (section 2.2.2.15) qui définit la forme de la coiffe de départ personnalisée, c’est‑à‑dire la forme à utiliser au début d’une ligne tracée avec ce stylo. Elle peut être l’une des diverses formes, comme un carré, un cercle ou un losange. Ce champ DOIT être présent si le drapeau PenDataCustomStartCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) |  |

### getCustomEndCapData() {#getCustomEndCapData--}
```
public EmfPlusCustomEndCapData getCustomEndCapData()
```


Obtient ou définit un objet EmfPlusCustomEndCapData facultatif (section 2.2.2.11) qui définit la forme de la coiffe de fin personnalisée, c’est‑à‑dire la forme à utiliser à la fin d’une ligne tracée avec ce stylo. Elle peut être l’une des diverses formes, comme un carré, un cercle ou un losange. Ce champ DOIT être présent si le drapeau PenDataCustomEndCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Returns:**
[EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata)
### setCustomEndCapData(EmfPlusCustomEndCapData value) {#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-}
```
public void setCustomEndCapData(EmfPlusCustomEndCapData value)
```


Obtient ou définit un objet EmfPlusCustomEndCapData facultatif (section 2.2.2.11) qui définit la forme de la coiffe de fin personnalisée, c’est‑à‑dire la forme à utiliser à la fin d’une ligne tracée avec ce stylo. Elle peut être l’une des diverses formes, comme un carré, un cercle ou un losange. Ce champ DOIT être présent si le drapeau PenDataCustomEndCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) |  |

