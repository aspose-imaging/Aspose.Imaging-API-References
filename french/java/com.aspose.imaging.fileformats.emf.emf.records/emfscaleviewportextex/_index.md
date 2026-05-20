---
title: "EmfScaleViewportExtex"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SCALEVIEWPORTEXTEX re-spécifie le viewport pour un contexte de périphérique en utilisant les rapports formés par les multiplicateurs et diviseurs spécifiés."
type: docs
weight: 113
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleViewportExtex extends EmfStateRecordType
```

L'enregistrement EMR\_SCALEVIEWPORTEXTEX re-spécifie le viewport d'un contexte de dispositif en utilisant les rapports formés par les multiplicateurs et diviseurs spécifiés.

L'étendue ne peut pas être modifiée si le contexte de périphérique utilise un mode de mappage à échelle fixe. Seuls MM\_ISOTROPIC et MM\_ANISOTROPIC ne sont pas à échelle fixe. Les dimensions du viewport sont modifiées comme suit. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfScaleViewportExtex(EmfRecord source)](#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfScaleViewportExtex`. |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex--) | Initialise une nouvelle instance de la classe [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getXNum()](#getXNum--) | Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicande horizontal. |
| [setXNum(int value)](#setXNum-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicande horizontal. |
| [getXDenom()](#getXDenom--) | Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur horizontal. |
| [setXDenom(int value)](#setXDenom-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur horizontal. |
| [getYNum()](#getYNum--) | Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicande vertical. |
| [setYNum(int value)](#setYNum-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicande vertical. |
| [getYDenom()](#getYDenom--) | Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur vertical. |
| [setYDenom(int value)](#setYDenom-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur vertical. |
### EmfScaleViewportExtex(EmfRecord source) {#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleViewportExtex(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfScaleViewportExtex`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfScaleViewportExtex() {#EmfScaleViewportExtex--}
```
public EmfScaleViewportExtex()
```


Initialise une nouvelle instance de la classe [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex).

### getXNum() {#getXNum--}
```
public int getXNum()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicande horizontal. Ne peut pas être zéro.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicande horizontal. Ne peut pas être zéro.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur horizontal. Ne peut pas être zéro.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur horizontal. Ne peut pas être zéro.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicande vertical. Ne peut pas être zéro.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicande vertical. Ne peut pas être zéro.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur vertical. Ne peut pas être zéro.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur vertical. Ne peut pas être zéro.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

