---
title: "EmfSmallTextOut"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SMALLTEXTOUT génère une chaîne."
type: docs
weight: 147
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSmallTextOut extends EmfDrawingRecordType
```

L'enregistrement EMR\_SMALLTEXTOUT génère une chaîne.

Si ETO\_SMALL\_CHARS est défini dans le champ fuOptions, TextString contient des codes de caractères sur 8 bits, dérivés des octets de poids faible des codes de caractères Unicode UTF16-LE sur 16 bits, où l'octet de poids fort est supposé être 0. Si ETO\_NO\_RECT est défini dans le champ fuOptions, le champ Bounds n'est pas inclus dans l'enregistrement.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSmallTextOut(EmfRecord source)](#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSmallTextOut`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getX()](#getX--) | Obtient ou définit un entier signé de 32 bits spécifiant la coordonnée x où placer la chaîne. |
| [setX(int value)](#setX-int-) | Obtient ou définit un entier signé de 32 bits spécifiant la coordonnée x où placer la chaîne. |
| [getY()](#getY--) | Obtient ou définit un entier signé de 32 bits spécifiant la coordonnée y où placer la chaîne. |
| [setY(int value)](#setY-int-) | Obtient ou définit un entier signé de 32 bits spécifiant la coordonnée y où placer la chaîne. |
| [getCChars()](#getCChars--) | Obtient ou définit un entier non signé de 32 bits spécifiant le nombre de caractères de 16 bits dans la chaîne. |
| [setCChars(int value)](#setCChars-int-) | Obtient ou définit un entier non signé de 32 bits spécifiant le nombre de caractères de 16 bits dans la chaîne. |
| [getFuOptions()](#getFuOptions--) | Obtient ou définit un entier non signé de 32 bits spécifiant les options de sortie de texte à utiliser. |
| [setFuOptions(int value)](#setFuOptions-int-) | Obtient ou définit un entier non signé de 32 bits spécifiant les options de sortie de texte à utiliser. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Obtient ou définit un entier non signé de 32 bits spécifiant le mode graphique, provenant de l'énumération GraphicsMode (section 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Obtient ou définit un entier non signé de 32 bits spécifiant le mode graphique, provenant de l'énumération GraphicsMode (section 2.1.16). |
| [getExScale()](#getExScale--) | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle du texte dans la direction x. |
| [setExScale(float value)](#setExScale-float-) | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle du texte dans la direction x. |
| [getEyScale()](#getEyScale--) | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle du texte dans la direction y. |
| [setEyScale(float value)](#setEyScale-float-) | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle du texte dans la direction y. |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL optionnel de 128 bits ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle englobant en unités de dispositif. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL optionnel de 128 bits ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle englobant en unités de dispositif. |
| [getTextString()](#getTextString--) | Obtient ou définit une chaîne de longueur variable contenant le texte à dessiner, en codes de caractères sur 8 bits ou 16 bits, selon la valeur du champ fuOptions. |
| [setTextString(String value)](#setTextString-java.lang.String-) | Obtient ou définit une chaîne de longueur variable contenant le texte à dessiner, en codes de caractères sur 8 bits ou 16 bits, selon la valeur du champ fuOptions. |
### EmfSmallTextOut(EmfRecord source) {#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSmallTextOut(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSmallTextOut`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getX() {#getX--}
```
public int getX()
```


Obtient ou définit un entier signé de 32 bits spécifiant la coordonnée x où placer la chaîne.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Obtient ou définit un entier signé de 32 bits spécifiant la coordonnée x où placer la chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getY() {#getY--}
```
public int getY()
```


Obtient ou définit un entier signé de 32 bits spécifiant la coordonnée y où placer la chaîne.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Obtient ou définit un entier signé de 32 bits spécifiant la coordonnée y où placer la chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCChars() {#getCChars--}
```
public int getCChars()
```


Obtient ou définit un entier non signé de 32 bits spécifiant le nombre de caractères de 16 bits dans la chaîne. La chaîne n'est PAS terminée par un caractère nul.

**Returns:**
int
### setCChars(int value) {#setCChars-int-}
```
public void setCChars(int value)
```


Obtient ou définit un entier non signé de 32 bits spécifiant le nombre de caractères de 16 bits dans la chaîne. La chaîne n'est PAS terminée par un caractère nul.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFuOptions() {#getFuOptions--}
```
public int getFuOptions()
```


Obtient ou définit un entier non signé de 32 bits spécifiant les options de sortie de texte à utiliser. Ces options sont spécifiées par une ou plusieurs valeurs de l'énumération ExtTextOutOptions (section 2.1.11).

**Returns:**
int
### setFuOptions(int value) {#setFuOptions-int-}
```
public void setFuOptions(int value)
```


Obtient ou définit un entier non signé de 32 bits spécifiant les options de sortie de texte à utiliser. Ces options sont spécifiées par une ou plusieurs valeurs de l'énumération ExtTextOutOptions (section 2.1.11).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Obtient ou définit un entier non signé de 32 bits spécifiant le mode graphique, provenant de l'énumération GraphicsMode (section 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Obtient ou définit un entier non signé de 32 bits spécifiant le mode graphique, provenant de l'énumération GraphicsMode (section 2.1.16).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle du texte dans la direction x.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle du texte dans la direction x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle du texte dans la direction y.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle du texte dans la direction y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient ou définit un objet WMF RectL optionnel de 128 bits ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle englobant en unités de dispositif.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtient ou définit un objet WMF RectL optionnel de 128 bits ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle englobant en unités de dispositif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getTextString() {#getTextString--}
```
public String getTextString()
```


Obtient ou définit une chaîne de longueur variable contenant le texte à dessiner, en codes de caractères sur 8 bits ou 16 bits, selon la valeur du champ fuOptions.

**Returns:**
java.lang.String
### setTextString(String value) {#setTextString-java.lang.String-}
```
public void setTextString(String value)
```


Obtient ou définit une chaîne de longueur variable contenant le texte à dessiner, en codes de caractères sur 8 bits ou 16 bits, selon la valeur du champ fuOptions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

