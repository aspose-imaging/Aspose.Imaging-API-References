---
title: "EmfExtTextOutW"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_EXTTEXTOUTW dessine une chaîne de texte ASCII en utilisant la police et les couleurs de texte actuelles."
type: docs
weight: 57
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtTextOutW extends EmfDrawingRecordType
```

L'enregistrement EMR\_EXTTEXTOUTW dessine une chaîne de texte ASCII en utilisant la police actuelle et les couleurs du texte.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfExtTextOutW(EmfRecord source)](#EmfExtTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfExtTextOutW`. |
| [EmfExtTextOutW()](#EmfExtTextOutW--) | Initialise une nouvelle instance de la classe `EmfExtTextOutW`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19). |
| [getIGraphicsMode()](#getIGraphicsMode--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode graphique à partir de l'énumération GraphicsMode (section 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode graphique à partir de l'énumération GraphicsMode (section 2.1.16). |
| [getExScale()](#getExScale--) | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle à appliquer le long de l'axe X pour convertir les unités d'espace de page en unités de 0,01 mm. |
| [setExScale(float value)](#setExScale-float-) | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle à appliquer le long de l'axe X pour convertir les unités d'espace de page en unités de 0,01 mm. |
| [getEyScale()](#getEyScale--) | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle à appliquer le long de l'axe Y pour convertir les unités d'espace de page en unités de 0,01 mm. |
| [setEyScale(float value)](#setEyScale-float-) | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle à appliquer le long de l'axe Y pour convertir les unités d'espace de page en unités de 0,01 mm. |
| [getWEmrText()](#getWEmrText--) | Obtient ou définit un objet EmrText (section 2.2.5) qui spécifie la chaîne de sortie en caractères Unicode UTF16-LE de 16 bits, avec des attributs de texte et des valeurs d'espacement. |
| [setWEmrText(EmfText value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-) | Obtient ou définit un objet EmrText (section 2.2.5) qui spécifie la chaîne de sortie en caractères Unicode UTF16-LE de 16 bits, avec des attributs de texte et des valeurs d'espacement. |
### EmfExtTextOutW(EmfRecord source) {#EmfExtTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtTextOutW(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfExtTextOutW`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfExtTextOutW() {#EmfExtTextOutW--}
```
public EmfExtTextOutW()
```


Initialise une nouvelle instance de la classe `EmfExtTextOutW`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19). Il n'est pas utilisé et DOIT être ignoré à la réception.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19). Il n'est pas utilisé et DOIT être ignoré à la réception.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le mode graphique à partir de l'énumération GraphicsMode (section 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le mode graphique à partir de l'énumération GraphicsMode (section 2.1.16).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle à appliquer le long de l'axe X pour convertir les unités d'espace de page en unités de 0,01 mm. Cela DOIT être utilisé uniquement si le mode graphique spécifié par iGraphicsMode est GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle à appliquer le long de l'axe X pour convertir les unités d'espace de page en unités de 0,01 mm. Cela DOIT être utilisé uniquement si le mode graphique spécifié par iGraphicsMode est GM\_COMPATIBLE.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle à appliquer le long de l'axe Y pour convertir les unités d'espace de page en unités de 0,01 mm. Cela DOIT être utilisé uniquement si le mode graphique spécifié par iGraphicsMode est GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle à appliquer le long de l'axe Y pour convertir les unités d'espace de page en unités de 0,01 mm. Cela DOIT être utilisé uniquement si le mode graphique spécifié par iGraphicsMode est GM\_COMPATIBLE.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getWEmrText() {#getWEmrText--}
```
public EmfText getWEmrText()
```


Obtient ou définit un objet EmrText (section 2.2.5) qui spécifie la chaîne de sortie en caractères Unicode UTF16-LE de 16 bits, avec des attributs de texte et des valeurs d'espacement.

**Returns:**
[EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext)
### setWEmrText(EmfText value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-}
```
public void setWEmrText(EmfText value)
```


Obtient ou définit un objet EmrText (section 2.2.5) qui spécifie la chaîne de sortie en caractères Unicode UTF16-LE de 16 bits, avec des attributs de texte et des valeurs d'espacement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

