---
title: "EmfPolyTextOutW"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_POLYTEXTOUTW dessine une ou plusieurs chaînes de texte Unicode en utilisant la police et les couleurs de texte actuelles."
type: docs
weight: 98
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutW extends EmfDrawingRecordType
```

L'enregistrement EMR\_POLYTEXTOUTW dessine une ou plusieurs chaînes de texte Unicode en utilisant la police et les couleurs de texte actuelles.

La police et les couleurs de texte utilisées pour la sortie sont spécifiées par des propriétés dans l'état actuel du contexte de périphérique de lecture. EMR\_POLYTEXTOUTW DOIT être émulé avec une série d'enregistrements EMR\_EXTTEXTOUTW (section 2.3.5.7), un par chaîne.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPolyTextOutW(EmfRecord source)](#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfPolyTextOutW`. |
| [EmfPolyTextOutW()](#EmfPolyTextOutW--) | Initialise une nouvelle instance de la classe `EmfPolyTextOutW`. |
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
| [getWEmrText()](#getWEmrText--) | Obtient ou définit un tableau d'objets EmrText (section 2.2.5) qui spécifient les chaînes de sortie en caractères Unicode UTF16-LE 16 bits, avec des attributs de texte et des valeurs d'espacement. |
| [setWEmrText(EmfText[] value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | Obtient ou définit un tableau d'objets EmrText (section 2.2.5) qui spécifient les chaînes de sortie en caractères Unicode UTF16-LE 16 bits, avec des attributs de texte et des valeurs d'espacement. |
### EmfPolyTextOutW(EmfRecord source) {#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutW(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfPolyTextOutW`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfPolyTextOutW() {#EmfPolyTextOutW--}
```
public EmfPolyTextOutW()
```


Initialise une nouvelle instance de la classe `EmfPolyTextOutW`.

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

### getWEmrText() {#getWEmrText--}
```
public EmfText[] getWEmrText()
```


Obtient ou définit un tableau d'objets EmrText (section 2.2.5) qui spécifient les chaînes de sortie en caractères Unicode UTF16-LE 16 bits, avec des attributs de texte et des valeurs d'espacement. Le nombre d'objets EmrText est spécifié par cStrings.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setWEmrText(EmfText[] value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setWEmrText(EmfText[] value)
```


Obtient ou définit un tableau d'objets EmrText (section 2.2.5) qui spécifient les chaînes de sortie en caractères Unicode UTF16-LE 16 bits, avec des attributs de texte et des valeurs d'espacement. Le nombre d'objets EmrText est spécifié par cStrings.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

