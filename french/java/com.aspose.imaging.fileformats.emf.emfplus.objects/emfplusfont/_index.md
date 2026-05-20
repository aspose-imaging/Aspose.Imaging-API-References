---
title: "EmfPlusFont"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusFont spécifie les propriétés qui déterminent l'apparence du texte, y compris la taille et le style de la police."
type: docs
weight: 42
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusFont extends EmfPlusGraphicsObjectType
```

L'objet EmfPlusFont spécifie les propriétés qui déterminent l'apparence du texte, y compris la police, la taille et le style.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusFont()](#EmfPlusFont--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Obtient ou définit une chaîne de caractères Unicode de longueur Length qui contient le nom de la famille de polices |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | Obtient ou définit une chaîne de caractères Unicode de longueur Length qui contient le nom de la famille de polices |
| [getFontStyleFlags()](#getFontStyleFlags--) | Obtient ou définit un entier signé 32 bits qui spécifie les attributs des glyphes de caractères qui affectent l'apparence de la police, tels que gras et italique. |
| [setFontStyleFlags(int value)](#setFontStyleFlags-int-) | Obtient ou définit un entier signé 32 bits qui spécifie les attributs des glyphes de caractères qui affectent l'apparence de la police, tels que gras et italique. |
| [getSizeUnit()](#getSizeUnit--) | Obtient ou définit un entier non signé 32 bits qui spécifie les unités utilisées pour le champ EmSize. |
| [setSizeUnit(int value)](#setSizeUnit-int-) | Obtient ou définit un entier non signé 32 bits qui spécifie les unités utilisées pour le champ EmSize. |
| [getEmSize()](#getEmSize--) | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la taille em de la police dans les unités spécifiées par le champ SizeUnit. |
| [setEmSize(float value)](#setEmSize-float-) | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la taille em de la police dans les unités spécifiées par le champ SizeUnit. |
### EmfPlusFont() {#EmfPlusFont--}
```
public EmfPlusFont()
```


### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Obtient ou définit une chaîne de caractères Unicode de longueur Length qui contient le nom de la famille de polices

**Returns:**
java.lang.String
### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


Obtient ou définit une chaîne de caractères Unicode de longueur Length qui contient le nom de la famille de polices

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getFontStyleFlags() {#getFontStyleFlags--}
```
public int getFontStyleFlags()
```


Obtient ou définit un entier signé 32 bits qui spécifie les attributs des glyphes de caractères qui affectent l'apparence de la police, tels que gras et italique. Cette valeur DOIT être composée des indicateurs FontStyle (section 2.1.2.4).

**Returns:**
int
### setFontStyleFlags(int value) {#setFontStyleFlags-int-}
```
public void setFontStyleFlags(int value)
```


Obtient ou définit un entier signé 32 bits qui spécifie les attributs des glyphes de caractères qui affectent l'apparence de la police, tels que gras et italique. Cette valeur DOIT être composée des indicateurs FontStyle (section 2.1.2.4).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSizeUnit() {#getSizeUnit--}
```
public int getSizeUnit()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les unités utilisées pour le champ EmSize. Il s'agit généralement des unités qui ont été employées lors de la conception de la police. La valeur DOIT être dans l'énumération UnitType (section 2.1.1.33).

**Returns:**
int
### setSizeUnit(int value) {#setSizeUnit-int-}
```
public void setSizeUnit(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les unités utilisées pour le champ EmSize. Il s'agit généralement des unités qui ont été employées lors de la conception de la police. La valeur DOIT être dans l'énumération UnitType (section 2.1.1.33).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getEmSize() {#getEmSize--}
```
public float getEmSize()
```


Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la taille em de la police dans les unités spécifiées par le champ SizeUnit.

**Returns:**
float
### setEmSize(float value) {#setEmSize-float-}
```
public void setEmSize(float value)
```


Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la taille em de la police dans les unités spécifiées par le champ SizeUnit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

