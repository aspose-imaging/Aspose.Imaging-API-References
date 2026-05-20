---
title: "EmfPolyTextOutA"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_POLYTEXTOUTA dessine une ou plusieurs chaînes de texte ASCII en utilisant la police et les couleurs de texte actuelles."
type: docs
weight: 97
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutA extends EmfDrawingRecordType
```

L'enregistrement EMR\_POLYTEXTOUTA dessine une ou plusieurs chaînes de texte ASCII en utilisant la police et les couleurs de texte actuelles.

La police et les couleurs de texte utilisées pour la sortie sont spécifiées par des propriétés dans l'état actuel du contexte de périphérique de lecture. EMR_POLYTEXTOUTA DOIT être émulé avec une série d'enregistrements EMR_EXTTEXTOUTW (section 2.3.5.7), un par chaîne. Cela nécessite que la chaîne de texte ASCII dans chaque objet EmrText soit convertie en encodage Unicode UTF16-LE.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPolyTextOutA(EmfRecord source)](#EmfPolyTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfPolyTextOutA`. |
| [EmfPolyTextOutA()](#EmfPolyTextOutA--) | Initialise une nouvelle instance de la classe [EmfPolyTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19), qui spécifie le rectangle englobant en unités de périphérique. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19), qui spécifie le rectangle englobant en unités de périphérique. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode graphique actuel, à partir de l'énumération GraphicsMode (section 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode graphique actuel, à partir de l'énumération GraphicsMode (section 2.1.16). |
| [getExScale()](#getExScale--) | Obtient ou définit une valeur flottante de 32 bits qui spécifie l'échelle X des unités de page aux unités de 0,01 mm si le mode graphique est GM_COMPATIBLE. |
| [setExScale(float value)](#setExScale-float-) | Obtient ou définit une valeur flottante de 32 bits qui spécifie l'échelle X des unités de page aux unités de 0,01 mm si le mode graphique est GM_COMPATIBLE. |
| [getEyScale()](#getEyScale--) | Obtient ou définit une valeur flottante de 32 bits qui spécifie l'échelle Y des unités de page aux unités de 0,01 mm si le mode graphique est GM_COMPATIBLE. |
| [setEyScale(float value)](#setEyScale-float-) | Obtient ou définit une valeur flottante de 32 bits qui spécifie l'échelle Y des unités de page aux unités de 0,01 mm si le mode graphique est GM_COMPATIBLE. |
| [getAEmrText()](#getAEmrText--) | Obtient ou définit un tableau d'objets EmrText (section 2.2.5) qui spécifient les chaînes de sortie en caractères ASCII 8 bits, avec des attributs de texte et des valeurs d'espacement. |
| [setAEmrText(EmfText[] value)](#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | Obtient ou définit un tableau d'objets EmrText (section 2.2.5) qui spécifient les chaînes de sortie en caractères ASCII 8 bits, avec des attributs de texte et des valeurs d'espacement. |
### EmfPolyTextOutA(EmfRecord source) {#EmfPolyTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutA(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfPolyTextOutA`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfPolyTextOutA() {#EmfPolyTextOutA--}
```
public EmfPolyTextOutA()
```


Initialise une nouvelle instance de la classe [EmfPolyTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta).

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19), qui spécifie le rectangle englobant en unités de périphérique.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19), qui spécifie le rectangle englobant en unités de périphérique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le mode graphique actuel, à partir de l'énumération GraphicsMode (section 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le mode graphique actuel, à partir de l'énumération GraphicsMode (section 2.1.16).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie l'échelle X des unités de page aux unités de 0,01 mm si le mode graphique est GM_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie l'échelle X des unités de page aux unités de 0,01 mm si le mode graphique est GM_COMPATIBLE.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie l'échelle Y des unités de page aux unités de 0,01 mm si le mode graphique est GM_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie l'échelle Y des unités de page aux unités de 0,01 mm si le mode graphique est GM_COMPATIBLE.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getAEmrText() {#getAEmrText--}
```
public EmfText[] getAEmrText()
```


Obtient ou définit un tableau d'objets EmrText (section 2.2.5) qui spécifient les chaînes de sortie en caractères ASCII 8 bits, avec des attributs de texte et des valeurs d'espacement. Le nombre d'objets EmrText est spécifié par cStrings.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setAEmrText(EmfText[] value) {#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setAEmrText(EmfText[] value)
```


Obtient ou définit un tableau d'objets EmrText (section 2.2.5) qui spécifient les chaînes de sortie en caractères ASCII 8 bits, avec des attributs de texte et des valeurs d'espacement. Le nombre d'objets EmrText est spécifié par cStrings.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

