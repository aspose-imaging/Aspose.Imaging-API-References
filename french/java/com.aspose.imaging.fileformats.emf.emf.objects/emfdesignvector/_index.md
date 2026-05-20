---
title: "EmfDesignVector"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet DesignVector de la section 2.2.3 définit le vecteur de conception qui spécifie les valeurs pour les axes de police d'une police multiple master."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfDesignVector extends EmfObject
```

L'objet DesignVector (section 2.2.3) définit le vecteur de conception, qui spécifie les valeurs pour les axes de police d'une police à maîtres multiples.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfDesignVector()](#EmfDesignVector--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSignature()](#getSignature--) | Obtient ou définit un entier non signé de 32 bits qui DOIT être réglé sur la valeur 0x08007664. |
| [setSignature(int value)](#setSignature-int-) | Obtient ou définit un entier non signé de 32 bits qui DOIT être réglé sur la valeur 0x08007664. |
| [getNumAxes()](#getNumAxes--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'éléments dans le tableau Values. |
| [setNumAxes(int value)](#setNumAxes-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'éléments dans le tableau Values. |
| [getValues()](#getValues--) | Obtient ou définit un tableau optionnel d'entiers signés de 32 bits qui spécifient les valeurs des axes de police d'une police multiple master OpenType. |
| [setValues(int[] value)](#setValues-int---) | Obtient ou définit un tableau optionnel d'entiers signés de 32 bits qui spécifient les valeurs des axes de police d'une police multiple master OpenType. |
### EmfDesignVector() {#EmfDesignVector--}
```
public EmfDesignVector()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtient ou définit un entier non signé de 32 bits qui DOIT être réglé sur la valeur 0x08007664.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Obtient ou définit un entier non signé de 32 bits qui DOIT être réglé sur la valeur 0x08007664.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getNumAxes() {#getNumAxes--}
```
public int getNumAxes()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'éléments dans le tableau Values. Il DOIT être compris entre 0 et 16, inclus.

**Returns:**
int
### setNumAxes(int value) {#setNumAxes-int-}
```
public void setNumAxes(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'éléments dans le tableau Values. Il DOIT être compris entre 0 et 16, inclus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


Obtient ou définit un tableau optionnel d'entiers signés de 32 bits qui spécifient les valeurs des axes de police d'une police multiple master OpenType. Le nombre maximal de valeurs dans le tableau est de 16.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


Obtient ou définit un tableau optionnel d'entiers signés de 32 bits qui spécifient les valeurs des axes de police d'une police multiple master OpenType. Le nombre maximal de valeurs dans le tableau est de 16.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

