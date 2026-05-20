---
title: "EmfPlusStringFormat"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusStringFormat spécifie les manipulations d'affichage de la mise en page du texte et l'identification de la langue"
type: docs
weight: 74
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusStringFormat extends EmfPlusGraphicsObjectType
```

L'objet EmfPlusStringFormat spécifie la mise en page du texte, les manipulations d'affichage et l'identification de la langue.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDigitLanguage()](#getDigitLanguage--) | Obtient ou définit un objet EmfPlusLanguageIdentifier qui spécifie la langue à utiliser pour les chiffres numériques dans la chaîne. |
| [setDigitLanguage(short value)](#setDigitLanguage-short-) | Obtient ou définit un objet EmfPlusLanguageIdentifier qui spécifie la langue à utiliser pour les chiffres numériques dans la chaîne. |
| [getDigitSubstitution()](#getDigitSubstitution--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment substituer les chiffres numériques dans la chaîne selon une locale ou une langue. |
| [setDigitSubstitution(int value)](#setDigitSubstitution-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment substituer les chiffres numériques dans la chaîne selon une locale ou une langue. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation |
| [setFirstTabOffset(float value)](#setFirstTabOffset-float-) | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Obtient ou définit un entier signé de 32 bits qui spécifie le type de traitement effectué sur une chaîne lorsqu'un préfixe de raccourci clavier (c'est‑à‑dire un esperluette) est rencontré. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le type de traitement effectué sur une chaîne lorsqu'un préfixe de raccourci clavier (c'est‑à‑dire un esperluette) est rencontré. |
| [getLanguage()](#getLanguage--) | Obtient ou définit un objet EmfPlusLanguageIdentifier (section 2.2.2.23) qui spécifie la langue à utiliser pour la chaîne |
| [setLanguage(short value)](#setLanguage-short-) | Obtient ou définit un objet EmfPlusLanguageIdentifier (section 2.2.2.23) qui spécifie la langue à utiliser pour la chaîne |
| [getLeadingMargin()](#getLeadingMargin--) | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie la longueur de l'espace à ajouter à la position de départ d'une chaîne. |
| [setLeadingMargin(float value)](#setLeadingMargin-float-) | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie la longueur de l'espace à ajouter à la position de départ d'une chaîne. |
| [getLineAlign()](#getLineAlign--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment aligner la chaîne verticalement dans le rectangle de mise en page. |
| [setLineAlign(int value)](#setLineAlign-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment aligner la chaîne verticalement dans le rectangle de mise en page. |
| [getRangeCount()](#getRangeCount--) | Obtient ou définit un entier signé de 32 bits qui spécifie le nombre d'objets EmfPlusCharacterRange (section 2.2.2.8) définis dans le champ StringFormatData. |
| [setRangeCount(int value)](#setRangeCount-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le nombre d'objets EmfPlusCharacterRange (section 2.2.2.8) définis dans le champ StringFormatData. |
| [getStringAlignment()](#getStringAlignment--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment aligner la chaîne horizontalement dans le rectangle de mise en page. |
| [setStringAlignment(int value)](#setStringAlignment-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment aligner la chaîne horizontalement dans le rectangle de mise en page. |
| [getStringFormatData()](#getStringFormatData--) | Obtient ou définit un objet EmfPlusStringFormatData (section 2.2.2.44) qui spécifie les données de mise en page du texte facultatives. |
| [setStringFormatData(EmfPlusStringFormatData value)](#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-) | Obtient ou définit un objet EmfPlusStringFormatData (section 2.2.2.44) qui spécifie les données de mise en page du texte facultatives. |
| [getStringFormatFlags()](#getStringFormatFlags--) | Obtient ou définit un entier non signé de 32 bits qui spécifie les options de mise en page du texte pour le formatage, le découpage et la gestion des polices. |
| [setStringFormatFlags(long value)](#setStringFormatFlags-long-) | Obtient ou définit un entier non signé de 32 bits qui spécifie les options de mise en page du texte pour le formatage, le découpage et la gestion des polices. |
| [getTabstopCount()](#getTabstopCount--) | Obtient ou définit un entier signé de 32 bits qui spécifie le nombre d'arrêts de tabulation définis dans le champ StringFormatData. |
| [setTabstopCount(int value)](#setTabstopCount-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le nombre d'arrêts de tabulation définis dans le champ StringFormatData. |
| [getTracking()](#getTracking--) | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie le rapport de l'espace horizontal alloué à chaque caractère d'une chaîne spécifiée par rapport à la largeur du caractère définie par la police. |
| [setTracking(float value)](#setTracking-float-) | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie le rapport de l'espace horizontal alloué à chaque caractère d'une chaîne spécifiée par rapport à la largeur du caractère définie par la police. |
| [getTrailingMargin()](#getTrailingMargin--) | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie la longueur de l'espace à laisser après une chaîne. |
| [setTrailingMargin(float value)](#setTrailingMargin-float-) | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie la longueur de l'espace à laisser après une chaîne. |
| [getTrimming()](#getTrimming--) | Obtient ou définit la façon dont les caractères sont tronqués dans une chaîne trop grande pour tenir dans un rectangle de mise en page. |
| [setTrimming(int value)](#setTrimming-int-) | Obtient ou définit la façon dont les caractères sont tronqués dans une chaîne trop grande pour tenir dans un rectangle de mise en page. |
### EmfPlusStringFormat() {#EmfPlusStringFormat--}
```
public EmfPlusStringFormat()
```


### getDigitLanguage() {#getDigitLanguage--}
```
public short getDigitLanguage()
```


Obtient ou définit un objet EmfPlusLanguageIdentifier qui spécifie la langue à utiliser pour les chiffres numériques dans la chaîne. Par exemple, si cette chaîne contient des chiffres arabes, ce champ DOIT contenir un identifiant de langue qui spécifie une langue arabe

**Returns:**
short
### setDigitLanguage(short value) {#setDigitLanguage-short-}
```
public void setDigitLanguage(short value)
```


Obtient ou définit un objet EmfPlusLanguageIdentifier qui spécifie la langue à utiliser pour les chiffres numériques dans la chaîne. Par exemple, si cette chaîne contient des chiffres arabes, ce champ DOIT contenir un identifiant de langue qui spécifie une langue arabe

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getDigitSubstitution() {#getDigitSubstitution--}
```
public int getDigitSubstitution()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment substituer les chiffres numériques dans la chaîne selon une locale ou une langue. Cette valeur DOIT être définie dans l'énumération StringDigitSubstitution (section 2.1.1.30).

**Returns:**
int
### setDigitSubstitution(int value) {#setDigitSubstitution-int-}
```
public void setDigitSubstitution(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment substituer les chiffres numériques dans la chaîne selon une locale ou une langue. Cette valeur DOIT être définie dans l'énumération StringDigitSubstitution (section 2.1.1.30).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation

**Returns:**
float
### setFirstTabOffset(float value) {#setFirstTabOffset-float-}
```
public void setFirstTabOffset(float value)
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le type de traitement effectué sur une chaîne lorsqu'un préfixe de raccourci clavier (c'est‑à‑dire une esperluette) est rencontré. En pratique, ce champ indique s'il faut afficher les préfixes de raccourci clavier liés au texte. La valeur DOIT être définie dans l'énumération HotkeyPrefix (section 2.1.1.14).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le type de traitement effectué sur une chaîne lorsqu'un préfixe de raccourci clavier (c'est‑à‑dire une esperluette) est rencontré. En pratique, ce champ indique s'il faut afficher les préfixes de raccourci clavier liés au texte. La valeur DOIT être définie dans l'énumération HotkeyPrefix (section 2.1.1.14).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLanguage() {#getLanguage--}
```
public short getLanguage()
```


Obtient ou définit un objet EmfPlusLanguageIdentifier (section 2.2.2.23) qui spécifie la langue à utiliser pour la chaîne

**Returns:**
short
### setLanguage(short value) {#setLanguage-short-}
```
public void setLanguage(short value)
```


Obtient ou définit un objet EmfPlusLanguageIdentifier (section 2.2.2.23) qui spécifie la langue à utiliser pour la chaîne

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getLeadingMargin() {#getLeadingMargin--}
```
public float getLeadingMargin()
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie la longueur de l'espace à ajouter à la position de départ d'une chaîne. La valeur par défaut est 1/6 pouce ; pour les polices typographiques, la valeur par défaut est 0.

**Returns:**
float
### setLeadingMargin(float value) {#setLeadingMargin-float-}
```
public void setLeadingMargin(float value)
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie la longueur de l'espace à ajouter à la position de départ d'une chaîne. La valeur par défaut est 1/6 pouce ; pour les polices typographiques, la valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getLineAlign() {#getLineAlign--}
```
public int getLineAlign()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment aligner la chaîne verticalement dans le rectangle de mise en page. Cette valeur DOIT être définie dans l'énumération StringAlignment.

**Returns:**
int
### setLineAlign(int value) {#setLineAlign-int-}
```
public void setLineAlign(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment aligner la chaîne verticalement dans le rectangle de mise en page. Cette valeur DOIT être définie dans l'énumération StringAlignment.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRangeCount() {#getRangeCount--}
```
public int getRangeCount()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le nombre d'objets EmfPlusCharacterRange (section 2.2.2.8) définis dans le champ StringFormatData.

**Returns:**
int
### setRangeCount(int value) {#setRangeCount-int-}
```
public void setRangeCount(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le nombre d'objets EmfPlusCharacterRange (section 2.2.2.8) définis dans le champ StringFormatData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getStringAlignment() {#getStringAlignment--}
```
public int getStringAlignment()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment aligner la chaîne horizontalement dans le rectangle de mise en page. Cette valeur DOIT être définie dans l'énumération StringAlignment (section 2.1.1.29).

**Returns:**
int
### setStringAlignment(int value) {#setStringAlignment-int-}
```
public void setStringAlignment(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment aligner la chaîne horizontalement dans le rectangle de mise en page. Cette valeur DOIT être définie dans l'énumération StringAlignment (section 2.1.1.29).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getStringFormatData() {#getStringFormatData--}
```
public EmfPlusStringFormatData getStringFormatData()
```


Obtient ou définit un objet EmfPlusStringFormatData (section 2.2.2.44) qui spécifie les données de mise en page du texte facultatives.

**Returns:**
[EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata)
### setStringFormatData(EmfPlusStringFormatData value) {#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-}
```
public void setStringFormatData(EmfPlusStringFormatData value)
```


Obtient ou définit un objet EmfPlusStringFormatData (section 2.2.2.44) qui spécifie les données de mise en page du texte facultatives.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata) |  |

### getStringFormatFlags() {#getStringFormatFlags--}
```
public long getStringFormatFlags()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les options de mise en page du texte pour le formatage, le rognage et la gestion des polices. Cette valeur DOIT être composée des indicateurs StringFormat (section 2.1.2.8).

**Returns:**
long
### setStringFormatFlags(long value) {#setStringFormatFlags-long-}
```
public void setStringFormatFlags(long value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les options de mise en page du texte pour le formatage, le rognage et la gestion des polices. Cette valeur DOIT être composée des indicateurs StringFormat (section 2.1.2.8).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getTabstopCount() {#getTabstopCount--}
```
public int getTabstopCount()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le nombre d'arrêts de tabulation définis dans le champ StringFormatData.

**Returns:**
int
### setTabstopCount(int value) {#setTabstopCount-int-}
```
public void setTabstopCount(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le nombre d'arrêts de tabulation définis dans le champ StringFormatData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTracking() {#getTracking--}
```
public float getTracking()
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie le rapport entre l'espace horizontal attribué à chaque caractère d'une chaîne donnée et la largeur du caractère définie par la police. Des valeurs élevées pour cette propriété indiquent un espace généreux entre les caractères ; des valeurs inférieures à 1 peuvent entraîner un chevauchement des caractères. La valeur par défaut est 1,03 ; pour les polices typographiques, la valeur par défaut est 1,00.

**Returns:**
float
### setTracking(float value) {#setTracking-float-}
```
public void setTracking(float value)
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie le rapport entre l'espace horizontal attribué à chaque caractère d'une chaîne donnée et la largeur du caractère définie par la police. Des valeurs élevées pour cette propriété indiquent un espace généreux entre les caractères ; des valeurs inférieures à 1 peuvent entraîner un chevauchement des caractères. La valeur par défaut est 1,03 ; pour les polices typographiques, la valeur par défaut est 1,00.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getTrailingMargin() {#getTrailingMargin--}
```
public float getTrailingMargin()
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie la longueur de l'espace à laisser après une chaîne. La valeur par défaut est 1/6 pouce ; pour les polices typographiques, la valeur par défaut est 0.

**Returns:**
float
### setTrailingMargin(float value) {#setTrailingMargin-float-}
```
public void setTrailingMargin(float value)
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie la longueur de l'espace à laisser après une chaîne. La valeur par défaut est 1/6 pouce ; pour les polices typographiques, la valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Obtient ou définit la façon de tronquer les caractères d'une chaîne trop grande pour tenir dans un rectangle de mise en page. Cette valeur DOIT être définie dans l'énumération StringTrimming (section 2.1.1.31).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Obtient ou définit la façon de tronquer les caractères d'une chaîne trop grande pour tenir dans un rectangle de mise en page. Cette valeur DOIT être définie dans l'énumération StringTrimming (section 2.1.1.31).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

