---
title: "EmfText"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmrText contient des valeurs pour la sortie texte."
type: docs
weight: 35
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emftext/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfText extends EmfObject
```

L'objet EmrText contient des valeurs pour la sortie texte.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfText()](#EmfText--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getReference()](#getReference--) | Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie les coordonnées du point de référence utilisé pour positionner la chaîne. |
| [setReference(Point value)](#setReference-com.aspose.imaging.Point-) | Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie les coordonnées du point de référence utilisé pour positionner la chaîne. |
| [getChars()](#getChars--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de caractères dans la chaîne |
| [setChars(int value)](#setChars-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de caractères dans la chaîne |
| [getOptions()](#getOptions--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment utiliser le rectangle indiqué dans le champ Rectangle. |
| [setOptions(int value)](#setOptions-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment utiliser le rectangle indiqué dans le champ Rectangle. |
| [getRectangle()](#getRectangle--) | Obtient ou définit un objet WMF RectL optionnel ([MS-WMF] section 2.2.2.19) qui définit un rectangle de découpage et/ou d'opacité en unités logiques. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL optionnel ([MS-WMF] section 2.2.2.19) qui définit un rectangle de découpage et/ou d'opacité en unités logiques. |
| [getStringBuffer()](#getStringBuffer--) | Obtient ou définit le tampon de chaîne de caractères UndefinedSpace1 (variable) : un nombre optionnel d'octets inutilisés. |
| [setStringBuffer(String value)](#setStringBuffer-java.lang.String-) | Obtient ou définit le tampon de chaîne de caractères UndefinedSpace1 (variable) : un nombre optionnel d'octets inutilisés. |
| [getGlyphIndexBuffer()](#getGlyphIndexBuffer--) | Obtient le tampon d'index de glyphes optionnel. |
| [setGlyphIndexBuffer(int[] value)](#setGlyphIndexBuffer-int---) | Définit le tampon d'index de glyphes optionnel. |
| [getDxBuffer()](#getDxBuffer--) | Obtient ou définit le tampon d'espacement de caractères optionnel UndefinedSpace2 (variable) : un nombre optionnel d'octets inutilisés. |
| [setDxBuffer(int[] value)](#setDxBuffer-int---) | Obtient ou définit le tampon d'espacement de caractères optionnel UndefinedSpace2 (variable) : un nombre optionnel d'octets inutilisés. |
### EmfText() {#EmfText--}
```
public EmfText()
```


### getReference() {#getReference--}
```
public Point getReference()
```


Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie les coordonnées du point de référence utilisé pour positionner la chaîne. Le point de référence est défini par le dernier enregistrement EMR\_SETTEXTALIGN (section 2.3.11.25). Si aucun enregistrement de ce type n'a été défini, l'alignement par défaut est TA\_LEFT,TA\_TOP.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setReference(Point value) {#setReference-com.aspose.imaging.Point-}
```
public void setReference(Point value)
```


Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie les coordonnées du point de référence utilisé pour positionner la chaîne. Le point de référence est défini par le dernier enregistrement EMR\_SETTEXTALIGN (section 2.3.11.25). Si aucun enregistrement de ce type n'a été défini, l'alignement par défaut est TA\_LEFT,TA\_TOP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getChars() {#getChars--}
```
public int getChars()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de caractères dans la chaîne

**Returns:**
int
### setChars(int value) {#setChars-int-}
```
public void setChars(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de caractères dans la chaîne

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getOptions() {#getOptions--}
```
public int getOptions()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment utiliser le rectangle indiqué dans le champ Rectangle. Ce champ peut être une combinaison de plusieurs valeurs de l'énumération ExtTextOutOptions (section 2.1.11).

**Returns:**
int
### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment utiliser le rectangle indiqué dans le champ Rectangle. Ce champ peut être une combinaison de plusieurs valeurs de l'énumération ExtTextOutOptions (section 2.1.11).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Obtient ou définit un objet WMF RectL optionnel ([MS-WMF] section 2.2.2.19) qui définit un rectangle de découpage et/ou d'opacité en unités logiques. Ce rectangle est appliqué à la sortie texte effectuée par l'enregistrement contenant.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Obtient ou définit un objet WMF RectL optionnel ([MS-WMF] section 2.2.2.19) qui définit un rectangle de découpage et/ou d'opacité en unités logiques. Ce rectangle est appliqué à la sortie texte effectuée par l'enregistrement contenant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStringBuffer() {#getStringBuffer--}
```
public String getStringBuffer()
```


Obtient ou définit le tampon de chaîne de caractères UndefinedSpace1 (variable) : un nombre optionnel d'octets inutilisés. Le champ OutputString n'est pas obligé de suivre immédiatement la partie précédente de cette structure. OutputString (variable) : un tableau de caractères qui spécifient la chaîne à afficher. L'emplacement de ce champ est indiqué par la valeur de offString en octets depuis le début de cet enregistrement. Le nombre de caractères est indiqué par la valeur de Chars.

**Returns:**
java.lang.String
### setStringBuffer(String value) {#setStringBuffer-java.lang.String-}
```
public void setStringBuffer(String value)
```


Obtient ou définit le tampon de chaîne de caractères UndefinedSpace1 (variable) : un nombre optionnel d'octets inutilisés. Le champ OutputString n'est pas obligé de suivre immédiatement la partie précédente de cette structure. OutputString (variable) : un tableau de caractères qui spécifient la chaîne à afficher. L'emplacement de ce champ est indiqué par la valeur de offString en octets depuis le début de cet enregistrement. Le nombre de caractères est indiqué par la valeur de Chars.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGlyphIndexBuffer() {#getGlyphIndexBuffer--}
```
public int[] getGlyphIndexBuffer()
```


Obtient le tampon d'index de glyphes optionnel. Si les options possèdent le drapeau ETO\_GLYPH\_INDEX, alors les codes des caractères d'une chaîne de texte en sortie sont en fait des index des glyphes de caractères dans une police TrueType (énumération ExtTextOutOptions 2.1.11). Les index de glyphes sont spécifiques à la police, ainsi, pour afficher correctement les caractères lors de la lecture, la police utilisée DOIT être identique à celle utilisée pour générer les index.

**Returns:**
int[] - le tampon d'index de glyphes optionnel.
### setGlyphIndexBuffer(int[] value) {#setGlyphIndexBuffer-int---}
```
public void setGlyphIndexBuffer(int[] value)
```


Définit le tampon d'index de glyphes optionnel. Si les options possèdent le drapeau ETO\_GLYPH\_INDEX, alors les codes des caractères d'une chaîne de texte en sortie sont en fait des index des glyphes de caractères dans une police TrueType (énumération ExtTextOutOptions 2.1.11). Les index de glyphes sont spécifiques à la police, ainsi, pour afficher correctement les caractères lors de la lecture, la police utilisée DOIT être identique à celle utilisée pour générer les index.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | le tampon d'index de glyphes optionnel. |

### getDxBuffer() {#getDxBuffer--}
```
public int[] getDxBuffer()
```


Obtient ou définit le tampon d'espacement de caractères optionnel UndefinedSpace2 (variable) : un nombre optionnel d'octets inutilisés. Le champ OutputDx n'est pas obligé de suivre immédiatement la partie précédente de cette structure. OutputDx (variable) : un tableau d'entiers non signés de 32 bits qui spécifient l'espacement de sortie entre les origines des cellules de caractères adjacentes en unités logiques. L'emplacement de ce champ est indiqué par la valeur de offDx en octets depuis le début de cet enregistrement. Si un espacement est défini, ce champ contient le même nombre de valeurs que le nombre de caractères dans la chaîne de sortie. Si le champ Options de l'objet EmrText contient le drapeau ETO\_PDY, alors ce tampon contient deux fois plus de valeurs que le nombre de caractères dans la chaîne de sortie, un décalage horizontal et un décalage vertical pour chacun, dans cet ordre. Si ETO\_RTLREADING est spécifié, les caractères sont disposés de droite à gauche au lieu de gauche à droite. Aucune autre option n'affecte l'interprétation de ce champ.

**Returns:**
int[]
### setDxBuffer(int[] value) {#setDxBuffer-int---}
```
public void setDxBuffer(int[] value)
```


Obtient ou définit le tampon d'espacement de caractères optionnel UndefinedSpace2 (variable) : un nombre optionnel d'octets inutilisés. Le champ OutputDx n'est pas obligé de suivre immédiatement la partie précédente de cette structure. OutputDx (variable) : un tableau d'entiers non signés de 32 bits qui spécifient l'espacement de sortie entre les origines des cellules de caractères adjacentes en unités logiques. L'emplacement de ce champ est indiqué par la valeur de offDx en octets depuis le début de cet enregistrement. Si un espacement est défini, ce champ contient le même nombre de valeurs que le nombre de caractères dans la chaîne de sortie. Si le champ Options de l'objet EmrText contient le drapeau ETO\_PDY, alors ce tampon contient deux fois plus de valeurs que le nombre de caractères dans la chaîne de sortie, un décalage horizontal et un décalage vertical pour chacun, dans cet ordre. Si ETO\_RTLREADING est spécifié, les caractères sont disposés de droite à gauche au lieu de gauche à droite. Aucune autre option n'affecte l'interprétation de ce champ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

