---
title: "StringFormat"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Encapsule les informations de mise en page du texte telles que l'alignement, l'orientation et les tabulations, ainsi que les manipulations d'affichage comme l'insertion d'ellipses, la substitution de chiffres nationaux et les fonctionnalités OpenType."
type: docs
weight: 112
url: /fr/java/com.aspose.imaging/stringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Encapsule les informations de mise en page du texte (telles que l'alignement, l'orientation et les tabulations), les manipulations d'affichage (telles que l'insertion d'ellipses et la substitution de chiffres nationaux) et les fonctionnalités OpenType. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initialise un nouvel objet `com.aspose.imaging.StringFormat`. |
| [StringFormat(int options)](#StringFormat-int-) | Initialise un nouvel objet `com.aspose.imaging.StringFormat` avec l'énumération `com.aspose.imaging.StringFormatFlags` spécifiée et la langue. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.imaging.StringFormat-) | Initialise un nouvel objet `com.aspose.imaging.StringFormat` à partir de l'objet `com.aspose.imaging.StringFormat` existant spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getGenericDefault()](#getGenericDefault--) | Obtient un objet `com.aspose.imaging.StringFormat` générique par défaut. |
| [getGenericTypographic()](#getGenericTypographic--) | Obtient un objet typographique générique `com.aspose.imaging.StringFormat`. |
| [getFormatFlags()](#getFormatFlags--) | Obtient une énumération `com.aspose.imaging.StringFormatFlags` qui contient des informations de formatage. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Définit une énumération `com.aspose.imaging.StringFormatFlags` qui contient des informations de formatage. |
| [getAlignment()](#getAlignment--) | Obtient les informations d'alignement du texte sur le plan vertical. |
| [setAlignment(int value)](#setAlignment-int-) | Définit les informations d'alignement du texte sur le plan vertical. |
| [getLineAlignment()](#getLineAlignment--) | Obtient l'alignement de ligne sur le plan horizontal. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Définit l'alignement de ligne sur le plan horizontal. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Obtient l'objet `com.aspose.imaging.HotkeyPrefix` pour cet objet `com.aspose.imaging.StringFormat`. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Définit l'objet `com.aspose.imaging.HotkeyPrefix` pour cet objet `com.aspose.imaging.StringFormat`. |
| [getTrimming()](#getTrimming--) | Obtient l'énumération `com.aspose.imaging.StringTrimming` pour cet objet `com.aspose.imaging.StringFormat`. |
| [setTrimming(int value)](#setTrimming-int-) | Définit l'énumération `com.aspose.imaging.StringTrimming` pour cet objet `com.aspose.imaging.StringFormat`. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Obtient la méthode à utiliser pour la substitution de chiffres. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Définit la méthode à utiliser pour la substitution de chiffres. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Obtient la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Définit la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Obtient le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation. |
| [getTabStops()](#getTabStops--) | Obtient un tableau de distances entre les arrêts de tabulation dans les unités spécifiées par la propriété `P:Aspose.Imaging.getGraphics().PageUnit`. |
| [getCustomCharIdent()](#getCustomCharIdent--) | Obtient l'identifiant du caractère personnalisé. |
| [setCustomCharIdent(PointF value)](#setCustomCharIdent-com.aspose.imaging.PointF-) | Définit l'identifiant du caractère personnalisé. |
| [deepClone()](#deepClone--) | Crée un clone profond de cet objet `com.aspose.imaging.StringFormat`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Définit les arrêts de tabulation pour cet objet `com.aspose.imaging.StringFormat`. |
| [toString()](#toString--) | Convertit cet objet `com.aspose.imaging.StringFormat` en une chaîne lisible par l'homme. |
| [equals(Object o)](#equals-java.lang.Object-) | Vérifie si les objets sont égaux. |
| [hashCode()](#hashCode--) | Obtient le code de hachage de l'objet actuel. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initialise un nouvel objet `com.aspose.imaging.StringFormat`.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initialise un nouvel objet `com.aspose.imaging.StringFormat` avec l'énumération `com.aspose.imaging.StringFormatFlags` spécifiée et la langue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | int | L'énumération `com.aspose.imaging.StringFormatFlags` pour le nouvel objet `com.aspose.imaging.StringFormat`. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.imaging.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initialise un nouvel objet `com.aspose.imaging.StringFormat` à partir de l'objet `com.aspose.imaging.StringFormat` existant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | L'objet `com.aspose.imaging.StringFormat` à partir duquel initialiser le nouvel objet `com.aspose.imaging.StringFormat`. |

### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Obtient un objet `com.aspose.imaging.StringFormat` générique par défaut.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The generic default `com.aspose.imaging.StringFormat` object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Obtient un objet typographique générique `com.aspose.imaging.StringFormat`.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - A generic typographic `com.aspose.imaging.StringFormat` object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Obtient une énumération `com.aspose.imaging.StringFormatFlags` qui contient des informations de formatage.

**Returns:**
int - Une énumération `com.aspose.imaging.StringFormatFlags` qui contient des informations de formatage.
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Définit une énumération `com.aspose.imaging.StringFormatFlags` qui contient des informations de formatage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Une énumération `com.aspose.imaging.StringFormatFlags` qui contient des informations de formatage. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Obtient les informations d'alignement du texte sur le plan vertical.

**Returns:**
int - Une énumération `com.aspose.imaging.StringAlignment` qui spécifie les informations d'alignement du texte.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Définit les informations d'alignement du texte sur le plan vertical.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Une énumération `com.aspose.imaging.StringAlignment` qui spécifie les informations d'alignement du texte. |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Obtient l'alignement de ligne sur le plan horizontal.

**Returns:**
int - Une énumération `com.aspose.imaging.StringAlignment` qui représente l'alignement de ligne.
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Définit l'alignement de ligne sur le plan horizontal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Une énumération `com.aspose.imaging.StringAlignment` qui représente l'alignement de ligne. |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Obtient l'objet `com.aspose.imaging.HotkeyPrefix` pour cet objet `com.aspose.imaging.StringFormat`.

**Returns:**
int - L'objet `com.aspose.imaging.HotkeyPrefix` pour cet objet `com.aspose.imaging.StringFormat`, la valeur par défaut est `F:Aspose.Imaging.HotkeyPrefix.None`.
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Définit l'objet `com.aspose.imaging.HotkeyPrefix` pour cet objet `com.aspose.imaging.StringFormat`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'objet `com.aspose.imaging.HotkeyPrefix` pour cet objet `com.aspose.imaging.StringFormat`, la valeur par défaut est `F:Aspose.Imaging.HotkeyPrefix.None`. |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Obtient l'énumération `com.aspose.imaging.StringTrimming` pour cet objet `com.aspose.imaging.StringFormat`.

**Returns:**
int - Une énumération `com.aspose.imaging.StringTrimming` qui indique comment le texte dessiné avec cet objet `com.aspose.imaging.StringFormat` est tronqué lorsqu'il dépasse les bords du rectangle de mise en page.
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Définit l'énumération `com.aspose.imaging.StringTrimming` pour cet objet `com.aspose.imaging.StringFormat`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Une énumération `com.aspose.imaging.StringTrimming` qui indique comment le texte dessiné avec cet objet `com.aspose.imaging.StringFormat` est tronqué lorsqu'il dépasse les bords du rectangle de mise en page. |

### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Obtient la méthode à utiliser pour la substitution de chiffres.

**Returns:**
int - Une valeur d'énumération `com.aspose.imaging.StringDigitSubstitute` qui spécifie comment substituer les caractères d'une chaîne qui ne peuvent pas être affichés parce qu'ils ne sont pas pris en charge par la police actuelle.

Le mutateur est introduit pour la méthode obsolète SetDigitSubstitution.
### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Définit la méthode à utiliser pour la substitution de chiffres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | Une valeur d'énumération `com.aspose.imaging.StringDigitSubstitute` qui spécifie comment substituer les caractères d'une chaîne qui ne peuvent pas être affichés parce qu'ils ne sont pas pris en charge par la police actuelle. |

Le mutateur est introduit pour la méthode obsolète SetDigitSubstitution. |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Obtient la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux.

**Returns:**
int - Un identifiant de langue National Language Support (NLS) qui identifie la langue à utiliser lorsque les chiffres locaux sont substitués aux chiffres occidentaux. Vous pouvez transmettre la propriété `P:System.Globalization.CultureInfo.LCID` d'un objet `System.Globalization.CultureInfo` comme identifiant de langue NLS. Par exemple, supposons que vous créiez et définissiez une locale "ar-EG". Si vous transmettez `com.aspose.imaging.StringDigitSubstitute.Traditional` à la méthode `com.aspose.imaging.StringFormat.setDigitSubstitution(int)`, alors les chiffres arabes-indic seront substitués aux chiffres occidentaux lors de l'affichage.
### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Définit la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Un identifiant de langue National Language Support (NLS) qui identifie la langue à utiliser lorsque les chiffres locaux sont substitués aux chiffres occidentaux. Vous pouvez transmettre la propriété `P:System.Globalization.CultureInfo.LCID` d'un objet `System.Globalization.CultureInfo` comme identifiant de langue NLS. Par exemple, supposons que vous créiez et définissiez une locale "ar-EG". Si vous transmettez `com.aspose.imaging.StringDigitSubstitute.Traditional` à la méthode `com.aspose.imaging.StringFormat.setDigitSubstitution(int)`, alors les chiffres arabes-indic seront substitués aux chiffres occidentaux lors de l'affichage. |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Obtient le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation.

**Returns:**
float - Le premier décalage de tabulation.

La propriété est introduite pour la méthode supprimée GetTabStops.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Obtient un tableau de distances entre les arrêts de tabulation dans les unités spécifiées par la propriété `P:Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - Les tabulations.

La propriété est introduite pour la méthode supprimée GetTabStops.
### getCustomCharIdent() {#getCustomCharIdent--}
```
public PointF getCustomCharIdent()
```


Obtient l'identifiant du caractère personnalisé.

Valeur : L'identifiant du caractère personnalisé.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - the custom character ident.
### setCustomCharIdent(PointF value) {#setCustomCharIdent-com.aspose.imaging.PointF-}
```
public void setCustomCharIdent(PointF value)
```


Définit l'identifiant du caractère personnalisé.

Valeur : L'identifiant du caractère personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | l'identifiant du caractère personnalisé. |

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Crée un clone profond de cet objet `com.aspose.imaging.StringFormat`.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The deep clone of the current `com.aspose.imaging.StringFormat`.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Définit les arrêts de tabulation pour cet objet `com.aspose.imaging.StringFormat`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstTabOffset | float | Le nombre d'espaces entre le début d'une ligne de texte et la première tabulation. |
| tabStops | float[] | Un tableau de distances entre les tabulations dans les unités spécifiées par la propriété `com.aspose.imaging.Graphics.PageUnit`. |

### toString() {#toString--}
```
public String toString()
```


Convertit cet objet `com.aspose.imaging.StringFormat` en une chaîne lisible par l'homme.

**Returns:**
java.lang.String - Une représentation sous forme de chaîne de cet objet `com.aspose.imaging.StringFormat`.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Vérifie si les objets sont égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | L'autre objet. |

**Returns:**
boolean - Le résultat de la comparaison d'égalité.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de l'objet actuel.

**Returns:**
int - Le code de hachage.
