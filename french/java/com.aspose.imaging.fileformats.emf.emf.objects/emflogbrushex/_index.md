---
title: "EmfLogBrushEx"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet LogBrushEx définit la couleur de style et le motif d'un pinceau indépendant du dispositif."
type: docs
weight: 21
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfLogBrushEx extends EmfObject
```

L'objet LogBrushEx définit le style, la couleur et le motif d'un pinceau indépendant du dispositif.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfLogBrushEx()](#EmfLogBrushEx--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBrushStyle()](#getBrushStyle--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le style du pinceau. |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le style du pinceau. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Obtient ou définit un objet WMF ColorRef de 32 bits ([MS-WMF] section 2.2.2.8) qui spécifie une couleur. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Obtient ou définit un objet WMF ColorRef de 32 bits ([MS-WMF] section 2.2.2.8) qui spécifie une couleur. |
| [getBrushHatch()](#getBrushHatch--) | Obtient ou définit un champ non signé de 32 bits qui contient les données de hachure du pinceau. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Obtient ou définit un champ non signé de 32 bits qui contient les données de hachure du pinceau. |
### EmfLogBrushEx() {#EmfLogBrushEx--}
```
public EmfLogBrushEx()
```


### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le style du pinceau. La valeur DOIT être une énumération provenant de l'énumération WMF BrushStyle ([MS-WMF] section 2.1.1.4). Les valeurs de style prises en charge dans cette structure sont listées plus loin dans cette section. Le style BS\_NULL DOIT être utilisé pour spécifier un pinceau qui n'a aucun effet.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le style du pinceau. La valeur DOIT être une énumération provenant de l'énumération WMF BrushStyle ([MS-WMF] section 2.1.1.4). Les valeurs de style prises en charge dans cette structure sont listées plus loin dans cette section. Le style BS\_NULL DOIT être utilisé pour spécifier un pinceau qui n'a aucun effet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Obtient ou définit un objet WMF ColorRef de 32 bits ([MS-WMF] section 2.2.2.8) qui spécifie une couleur. L'interprétation de ce champ dépend de la valeur de BrushStyle, comme expliqué dans le tableau suivant.

Valeur : la couleur ARGB de 32 bits

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Obtient ou définit un objet WMF ColorRef de 32 bits ([MS-WMF] section 2.2.2.8) qui spécifie une couleur. L'interprétation de ce champ dépend de la valeur de BrushStyle, comme expliqué dans le tableau suivant.

Valeur : la couleur ARGB de 32 bits

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Obtient ou définit un champ non signé de 32 bits qui contient les données de hachure du pinceau. Son interprétation dépend de la valeur de BrushStyle,

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Obtient ou définit un champ non signé de 32 bits qui contient les données de hachure du pinceau. Son interprétation dépend de la valeur de BrushStyle,

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

