---
title: "EmfLogFontPanose"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet LogFontPanose spécifie les caractéristiques PANOSE d'une police logique."
type: docs
weight: 25
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
```
public final class EmfLogFontPanose extends EmfLogFont
```

L'objet LogFontPanose spécifie les caractéristiques PANOSE d'une police logique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfLogFontPanose(EmfLogFont emfLogFont)](#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Initialise une nouvelle instance de la classe `EmfLogFontPanose`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFullName()](#getFullName--) | Obtient ou définit une chaîne de 64 caractères Unicode qui définit le nom complet de la police. |
| [setFullName(String value)](#setFullName-java.lang.String-) | Obtient ou définit une chaîne de 64 caractères Unicode qui définit le nom complet de la police. |
| [getStyle()](#getStyle--) | Obtient ou définit une chaîne de 32 caractères Unicode qui définit le style de la police. |
| [setStyle(String value)](#setStyle-java.lang.String-) | Obtient ou définit une chaîne de 32 caractères Unicode qui définit le style de la police. |
| [getVersion()](#getVersion--) | Obtient ou définit Ce champ MUST être ignoré. |
| [setVersion(int value)](#setVersion-int-) | Obtient ou définit Ce champ MUST être ignoré. |
| [getStyleSize()](#getStyleSize--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en points à laquelle le lissage des polices est effectué. |
| [setStyleSize(int value)](#setStyleSize-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en points à laquelle le lissage des polices est effectué. |
| [getMatch()](#getMatch--) | Obtient ou définit Ce champ MUST être ignoré. |
| [setMatch(int value)](#setMatch-int-) | Obtient ou définit Ce champ MUST être ignoré. |
| [getVendorId()](#getVendorId--) | Obtient ou définit Ce champ MUST être ignoré. |
| [setVendorId(int value)](#setVendorId-int-) | Obtient ou définit Ce champ MUST être ignoré. |
| [getCulture()](#getCulture--) | Obtient ou définit un entier non signé de 32 bits qui MUST être mis à zéro et MUST être ignoré. |
| [setCulture(int value)](#setCulture-int-) | Obtient ou définit un entier non signé de 32 bits qui MUST être mis à zéro et MUST être ignoré. |
| [getPanose()](#getPanose--) | Obtient ou définit un objet Panose (section 2.2.21) qui spécifie les caractéristiques PANOSE de la police logique. |
| [setPanose(EmfPanose value)](#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-) | Obtient ou définit un objet Panose (section 2.2.21) qui spécifie les caractéristiques PANOSE de la police logique. |
| [getPadding()](#getPadding--) | Obtient ou définit un champ qui n'existe que pour assurer l'alignement de 32 bits de cette structure. |
| [setPadding(short value)](#setPadding-short-) | Obtient ou définit un champ qui n'existe que pour assurer l'alignement de 32 bits de cette structure. |
### EmfLogFontPanose(EmfLogFont emfLogFont) {#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public EmfLogFontPanose(EmfLogFont emfLogFont)
```


Initialise une nouvelle instance de la classe `EmfLogFontPanose`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| emfLogFont | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) | La police de base du journal. |

### getFullName() {#getFullName--}
```
public String getFullName()
```


Obtient ou définit une chaîne de 64 caractères Unicode qui définit le nom complet de la police. Si la longueur de cette chaîne est inférieure à 64 caractères, un caractère NULL de terminaison MUST être présent, après quoi le reste de ce champ MUST être ignoré.

**Returns:**
java.lang.String
### setFullName(String value) {#setFullName-java.lang.String-}
```
public void setFullName(String value)
```


Obtient ou définit une chaîne de 64 caractères Unicode qui définit le nom complet de la police. Si la longueur de cette chaîne est inférieure à 64 caractères, un caractère NULL de terminaison MUST être présent, après quoi le reste de ce champ MUST être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getStyle() {#getStyle--}
```
public String getStyle()
```


Obtient ou définit une chaîne de 32 caractères Unicode qui définit le style de la police. Si la longueur de cette chaîne est inférieure à 32 caractères, un NULL de terminaison DOIT être présent, après quoi le reste de ce champ DOIT être ignoré.

**Returns:**
java.lang.String
### setStyle(String value) {#setStyle-java.lang.String-}
```
public void setStyle(String value)
```


Obtient ou définit une chaîne de 32 caractères Unicode qui définit le style de la police. Si la longueur de cette chaîne est inférieure à 32 caractères, un NULL de terminaison DOIT être présent, après quoi le reste de ce champ DOIT être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtient ou définit Ce champ MUST être ignoré.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtient ou définit Ce champ MUST être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getStyleSize() {#getStyleSize--}
```
public int getStyleSize()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en points à laquelle le lissage des polices est effectué. Si la valeur est zéro, le lissage des polices est effectué à la taille en points correspondant au champ Height de l'objet LogFont dans le champ LogFont.

**Returns:**
int
### setStyleSize(int value) {#setStyleSize-int-}
```
public void setStyleSize(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en points à laquelle le lissage des polices est effectué. Si la valeur est zéro, le lissage des polices est effectué à la taille en points correspondant au champ Height de l'objet LogFont dans le champ LogFont.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getMatch() {#getMatch--}
```
public int getMatch()
```


Obtient ou définit Ce champ MUST être ignoré.

**Returns:**
int
### setMatch(int value) {#setMatch-int-}
```
public void setMatch(int value)
```


Obtient ou définit Ce champ MUST être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getVendorId() {#getVendorId--}
```
public int getVendorId()
```


Obtient ou définit Ce champ MUST être ignoré.

**Returns:**
int
### setVendorId(int value) {#setVendorId-int-}
```
public void setVendorId(int value)
```


Obtient ou définit Ce champ MUST être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCulture() {#getCulture--}
```
public int getCulture()
```


Obtient ou définit un entier non signé de 32 bits qui MUST être mis à zéro et MUST être ignoré.

**Returns:**
int
### setCulture(int value) {#setCulture-int-}
```
public void setCulture(int value)
```


Obtient ou définit un entier non signé de 32 bits qui MUST être mis à zéro et MUST être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPanose() {#getPanose--}
```
public EmfPanose getPanose()
```


Obtient ou définit un objet Panose (section 2.2.21) qui spécifie les caractéristiques PANOSE de la police logique. Si tous les champs de cet objet sont zéro, il MUST être ignoré.

**Returns:**
[EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose)
### setPanose(EmfPanose value) {#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-}
```
public void setPanose(EmfPanose value)
```


Obtient ou définit un objet Panose (section 2.2.21) qui spécifie les caractéristiques PANOSE de la police logique. Si tous les champs de cet objet sont zéro, il MUST être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose) |  |

### getPadding() {#getPadding--}
```
public short getPadding()
```


Obtient ou définit un champ qui n'existe que pour assurer l'alignement de 32 bits de cette structure. Il MUST être ignoré

**Returns:**
short
### setPadding(short value) {#setPadding-short-}
```
public void setPadding(short value)
```


Obtient ou définit un champ qui n'existe que pour assurer l'alignement de 32 bits de cette structure. Il MUST être ignoré

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

