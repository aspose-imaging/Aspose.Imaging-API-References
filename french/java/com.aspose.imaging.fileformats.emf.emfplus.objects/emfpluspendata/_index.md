---
title: "EmfPlusPenData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusPenData spécifie les propriétés d'un stylo graphique."
type: docs
weight: 64
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenData extends EmfPlusStructureObjectType
```

L'objet EmfPlusPenData spécifie les propriétés d'un stylo graphique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusPenData()](#EmfPlusPenData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPenDataFlags()](#getPenDataFlags--) | Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. |
| [setPenDataFlags(int value)](#setPenDataFlags-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. |
| [getPenUnit()](#getPenUnit--) | Obtient ou définit un entier non signé de 32 bits qui spécifie les unités de mesure du stylo. |
| [setPenUnit(int value)](#setPenUnit-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie les unités de mesure du stylo. |
| [getPenWidth()](#getPenWidth--) | Obtient ou définit une valeur flottante de 32 bits qui spécifie la largeur de la ligne tracée par le stylo dans les unités spécifiées par le champ PenUnit. |
| [setPenWidth(float value)](#setPenWidth-float-) | Obtient ou définit une valeur flottante de 32 bits qui spécifie la largeur de la ligne tracée par le stylo dans les unités spécifiées par le champ PenUnit. |
| [getOptionalData()](#getOptionalData--) | Obtient ou définit l'objet optionnel EmfPlusPenOptionalData (section 2.2.2.34) qui spécifie des données supplémentaires pour l'objet stylo. |
| [setOptionalData(EmfPlusPenOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-) | Obtient ou définit l'objet optionnel EmfPlusPenOptionalData (section 2.2.2.34) qui spécifie des données supplémentaires pour l'objet stylo. |
### EmfPlusPenData() {#EmfPlusPenData--}
```
public EmfPlusPenData()
```


### getPenDataFlags() {#getPenDataFlags--}
```
public int getPenDataFlags()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. Cette valeur DOIT être composée des indicateurs PenData (section 2.1.2.7).

**Returns:**
int
### setPenDataFlags(int value) {#setPenDataFlags-int-}
```
public void setPenDataFlags(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. Cette valeur DOIT être composée des indicateurs PenData (section 2.1.2.7).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPenUnit() {#getPenUnit--}
```
public int getPenUnit()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les unités de mesure du stylo. La valeur DOIT provenir de l'énumération UnitType (section 2.1.1.33).

**Returns:**
int
### setPenUnit(int value) {#setPenUnit-int-}
```
public void setPenUnit(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les unités de mesure du stylo. La valeur DOIT provenir de l'énumération UnitType (section 2.1.1.33).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPenWidth() {#getPenWidth--}
```
public float getPenWidth()
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie la largeur de la ligne tracée par le stylo dans les unités spécifiées par le champ PenUnit. Si une largeur de zéro est spécifiée, une valeur minimale est utilisée, déterminée par les unités.

**Returns:**
float
### setPenWidth(float value) {#setPenWidth-float-}
```
public void setPenWidth(float value)
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie la largeur de la ligne tracée par le stylo dans les unités spécifiées par le champ PenUnit. Si une largeur de zéro est spécifiée, une valeur minimale est utilisée, déterminée par les unités.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPenOptionalData getOptionalData()
```


Obtient ou définit l'objet optionnel EmfPlusPenOptionalData (section 2.2.2.34) qui spécifie des données supplémentaires pour l'objet stylo. Le contenu spécifique de ce champ est déterminé par la valeur du champ PenDataFlags.

**Returns:**
[EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata)
### setOptionalData(EmfPlusPenOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-}
```
public void setOptionalData(EmfPlusPenOptionalData value)
```


Obtient ou définit l'objet optionnel EmfPlusPenOptionalData (section 2.2.2.34) qui spécifie des données supplémentaires pour l'objet stylo. Le contenu spécifique de ce champ est déterminé par la valeur du champ PenDataFlags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata) |  |

