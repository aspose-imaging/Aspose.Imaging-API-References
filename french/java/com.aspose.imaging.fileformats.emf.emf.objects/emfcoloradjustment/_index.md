---
title: "EmfColorAdjustment"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet ColorAdjustment définit des valeurs pour ajuster les couleurs dans les bitmaps source lors des transferts de blocs de bits."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfColorAdjustment extends EmfObject
```

L'objet ColorAdjustment définit des valeurs pour ajuster les couleurs dans les bitmaps source lors des transferts de blocs de bits.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfColorAdjustment()](#EmfColorAdjustment--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSize()](#getSize--) | Obtient ou définit un entier non signé de 16 bits qui spécifie la taille en octets de cet objet. |
| [setSize(short value)](#setSize-short-) | Obtient ou définit un entier non signé de 16 bits qui spécifie la taille en octets de cet objet. |
| [getValues()](#getValues--) | Obtient ou définit un entier non signé de 16 bits qui spécifie comment préparer l'image de sortie. |
| [setValues(int value)](#setValues-int-) | Obtient ou définit un entier non signé de 16 bits qui spécifie comment préparer l'image de sortie. |
| [getIlluminantIndex()](#getIlluminantIndex--) | Obtient ou définit un entier non signé de 16 bits qui spécifie le type de source lumineuse standard sous laquelle l'image est visualisée, à partir de l'énumération Illuminant (section 2.1.19). |
| [setIlluminantIndex(int value)](#setIlluminantIndex-int-) | Obtient ou définit un entier non signé de 16 bits qui spécifie le type de source lumineuse standard sous laquelle l'image est visualisée, à partir de l'énumération Illuminant (section 2.1.19). |
| [getRedGamma()](#getRedGamma--) | Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma à la nᵉ puissance pour le primaire rouge des couleurs source. |
| [setRedGamma(short value)](#setRedGamma-short-) | Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma à la nᵉ puissance pour le primaire rouge des couleurs source. |
| [getGreenGamma()](#getGreenGamma--) | Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma à la nᵉ puissance pour le primaire vert des couleurs source. |
| [setGreenGamma(short value)](#setGreenGamma-short-) | Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma à la nᵉ puissance pour le primaire vert des couleurs source. |
| [getBlueGamma()](#getBlueGamma--) | Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma à la nᵉ puissance pour le primaire bleu des couleurs source. |
| [setBlueGamma(short value)](#setBlueGamma-short-) | Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma à la nᵉ puissance pour le primaire bleu des couleurs source. |
| [getReferenceBlack()](#getReferenceBlack--) | Obtient ou définit un entier non signé de 16 bits qui spécifie la référence noire pour les couleurs source. |
| [setReferenceBlack(short value)](#setReferenceBlack-short-) | Obtient ou définit un entier non signé de 16 bits qui spécifie la référence noire pour les couleurs source. |
| [getReferenceWhite()](#getReferenceWhite--) | Obtient ou définit un entier non signé de 16 bits qui spécifie la référence blanche pour les couleurs source. |
| [setReferenceWhite(short value)](#setReferenceWhite-short-) | Obtient ou définit un entier non signé de 16 bits qui spécifie la référence blanche pour les couleurs source. |
| [getContrast()](#getContrast--) | Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de contraste à appliquer à l'objet source. |
| [setContrast(short value)](#setContrast-short-) | Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de contraste à appliquer à l'objet source. |
| [getBrightness()](#getBrightness--) | Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de luminosité à appliquer à l'objet source. |
| [setBrightness(short value)](#setBrightness-short-) | Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de luminosité à appliquer à l'objet source. |
| [getColorfullness()](#getColorfullness--) | Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de saturation à appliquer à l'objet source. |
| [setColorfullness(short value)](#setColorfullness-short-) | Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de saturation à appliquer à l'objet source. |
| [getRedGreenTint()](#getRedGreenTint--) | Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de réglage de teinte rouge ou verte à appliquer à l'objet source. |
| [setRedGreenTint(short value)](#setRedGreenTint-short-) | Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de réglage de teinte rouge ou verte à appliquer à l'objet source. |
### EmfColorAdjustment() {#EmfColorAdjustment--}
```
public EmfColorAdjustment()
```


### getSize() {#getSize--}
```
public short getSize()
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la taille en octets de cet objet. Cette valeur DOIT être 0x0018.

**Returns:**
short
### setSize(short value) {#setSize-short-}
```
public void setSize(short value)
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la taille en octets de cet objet. Cette valeur DOIT être 0x0018.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getValues() {#getValues--}
```
public int getValues()
```


Obtient ou définit un entier non signé de 16 bits qui spécifie comment préparer l'image de sortie. Ce champ peut être réglé sur NULL ou sur toute combinaison de valeurs de l'énumération ColorAdjustment (section 2.1.5).

**Returns:**
int
### setValues(int value) {#setValues-int-}
```
public void setValues(int value)
```


Obtient ou définit un entier non signé de 16 bits qui spécifie comment préparer l'image de sortie. Ce champ peut être réglé sur NULL ou sur toute combinaison de valeurs de l'énumération ColorAdjustment (section 2.1.5).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getIlluminantIndex() {#getIlluminantIndex--}
```
public int getIlluminantIndex()
```


Obtient ou définit un entier non signé de 16 bits qui spécifie le type de source lumineuse standard sous laquelle l'image est visualisée, à partir de l'énumération Illuminant (section 2.1.19).

**Returns:**
int
### setIlluminantIndex(int value) {#setIlluminantIndex-int-}
```
public void setIlluminantIndex(int value)
```


Obtient ou définit un entier non signé de 16 bits qui spécifie le type de source lumineuse standard sous laquelle l'image est visualisée, à partir de l'énumération Illuminant (section 2.1.19).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRedGamma() {#getRedGamma--}
```
public short getRedGamma()
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma de puissance n pour le primaire rouge des couleurs sources. Cette valeur DEVRAIT être comprise entre 2 500 et 65 000. Une valeur de 10 000 signifie que la correction gamma NE DOIT PAS être effectuée.

**Returns:**
short
### setRedGamma(short value) {#setRedGamma-short-}
```
public void setRedGamma(short value)
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma de puissance n pour le primaire rouge des couleurs sources. Cette valeur DEVRAIT être comprise entre 2 500 et 65 000. Une valeur de 10 000 signifie que la correction gamma NE DOIT PAS être effectuée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getGreenGamma() {#getGreenGamma--}
```
public short getGreenGamma()
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma de puissance n pour le primaire vert des couleurs sources. Cette valeur DEVRAIT être comprise entre 2 500 et 65 000. Une valeur de 10 000 signifie que la correction gamma NE DOIT PAS être effectuée.

**Returns:**
short
### setGreenGamma(short value) {#setGreenGamma-short-}
```
public void setGreenGamma(short value)
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma de puissance n pour le primaire vert des couleurs sources. Cette valeur DEVRAIT être comprise entre 2 500 et 65 000. Une valeur de 10 000 signifie que la correction gamma NE DOIT PAS être effectuée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getBlueGamma() {#getBlueGamma--}
```
public short getBlueGamma()
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma de puissance n pour le primaire bleu des couleurs sources. Cette valeur DEVRAIT être comprise entre 2 500 et 65 000. Une valeur de 10 000 signifie que la correction gamma NE DOIT PAS être effectuée.

**Returns:**
short
### setBlueGamma(short value) {#setBlueGamma-short-}
```
public void setBlueGamma(short value)
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma de puissance n pour le primaire bleu des couleurs sources. Cette valeur DEVRAIT être comprise entre 2 500 et 65 000. Une valeur de 10 000 signifie que la correction gamma NE DOIT PAS être effectuée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getReferenceBlack() {#getReferenceBlack--}
```
public short getReferenceBlack()
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la référence noire pour les couleurs sources. Toutes les couleurs plus sombres que celle-ci sont traitées comme noires. Cette valeur DEVRAIT être comprise entre zéro et 4 000.

**Returns:**
short
### setReferenceBlack(short value) {#setReferenceBlack-short-}
```
public void setReferenceBlack(short value)
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la référence noire pour les couleurs sources. Toutes les couleurs plus sombres que celle-ci sont traitées comme noires. Cette valeur DEVRAIT être comprise entre zéro et 4 000.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getReferenceWhite() {#getReferenceWhite--}
```
public short getReferenceWhite()
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la référence blanche pour les couleurs sources. Toutes les couleurs plus claires que celle-ci sont traitées comme blanches. Cette valeur DEVRAIT être comprise entre 6 000 et 10 000.

**Returns:**
short
### setReferenceWhite(short value) {#setReferenceWhite-short-}
```
public void setReferenceWhite(short value)
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la référence blanche pour les couleurs sources. Toutes les couleurs plus claires que celle-ci sont traitées comme blanches. Cette valeur DEVRAIT être comprise entre 6 000 et 10 000.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getContrast() {#getContrast--}
```
public short getContrast()
```


Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de contraste à appliquer à l'objet source. Cette valeur DEVRAIT être comprise entre –100 et 100. Une valeur de zéro signifie que le réglage du contraste NE DOIT PAS être effectué.

**Returns:**
short
### setContrast(short value) {#setContrast-short-}
```
public void setContrast(short value)
```


Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de contraste à appliquer à l'objet source. Cette valeur DEVRAIT être comprise entre –100 et 100. Une valeur de zéro signifie que le réglage du contraste NE DOIT PAS être effectué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getBrightness() {#getBrightness--}
```
public short getBrightness()
```


Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de luminosité à appliquer à l'objet source. Cette valeur DEVRAIT être comprise entre –100 et 100. Une valeur de zéro signifie que le réglage de la luminosité NE DOIT PAS être effectué.

**Returns:**
short
### setBrightness(short value) {#setBrightness-short-}
```
public void setBrightness(short value)
```


Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de luminosité à appliquer à l'objet source. Cette valeur DEVRAIT être comprise entre –100 et 100. Une valeur de zéro signifie que le réglage de la luminosité NE DOIT PAS être effectué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getColorfullness() {#getColorfullness--}
```
public short getColorfullness()
```


Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de saturation à appliquer à l'objet source. Cette valeur DEVRAIT être comprise entre –100 et 100. Une valeur de zéro signifie que le réglage de la saturation NE DOIT PAS être effectué.

**Returns:**
short
### setColorfullness(short value) {#setColorfullness-short-}
```
public void setColorfullness(short value)
```


Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de saturation à appliquer à l'objet source. Cette valeur DEVRAIT être comprise entre –100 et 100. Une valeur de zéro signifie que le réglage de la saturation NE DOIT PAS être effectué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getRedGreenTint() {#getRedGreenTint--}
```
public short getRedGreenTint()
```


Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de réglage de teinte rouge ou verte à appliquer à l'objet source. Cette valeur DEVRAIT être comprise entre –100 et 100. Les nombres positifs ajustent vers le rouge et les nombres négatifs ajustent vers le vert. Une valeur de zéro signifie que le réglage de la teinte NE DOIT PAS être effectué.

**Returns:**
short
### setRedGreenTint(short value) {#setRedGreenTint-short-}
```
public void setRedGreenTint(short value)
```


Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de réglage de teinte rouge ou verte à appliquer à l'objet source. Cette valeur DEVRAIT être comprise entre –100 et 100. Les nombres positifs ajustent vers le rouge et les nombres négatifs ajustent vers le vert. Une valeur de zéro signifie que le réglage de la teinte NE DOIT PAS être effectué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

