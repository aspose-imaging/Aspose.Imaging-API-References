---
title: "EmfScaleWindowExtex"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SCALEWINDOWEXTEX re-spécifie la fenêtre pour un contexte de périphérique de lecture en utilisant les rapports formés par les multiplicateurs et diviseurs spécifiés."
type: docs
weight: 114
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleWindowExtex extends EmfStateRecordType
```

L'enregistrement EMR\_SCALEWINDOWEXTEX re-spécifie la fenêtre d'un contexte de dispositif de lecture en utilisant les rapports formés par les multiplicateurs et diviseurs spécifiés.

L'étendue ne peut pas être modifiée si le contexte de périphérique utilise un mode de cartographie à échelle fixe. Seuls MM\_ISOTROPIC et MM\_ANISOTROPIC ne sont pas à échelle fixe. Les étendues de la fenêtre sont modifiées comme suit. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / xDenom
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfScaleWindowExtex(EmfRecord source)](#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfScaleWindowExtex`. |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex--) | Initialise une nouvelle instance de la classe [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex). |
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
### EmfScaleWindowExtex(EmfRecord source) {#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleWindowExtex(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfScaleWindowExtex`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfScaleWindowExtex() {#EmfScaleWindowExtex--}
```
public EmfScaleWindowExtex()
```


Initialise une nouvelle instance de la classe [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex).

### getXNum() {#getXNum--}
```
public int getXNum()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicateur horizontal. NE DOIT PAS être zéro.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicateur horizontal. NE DOIT PAS être zéro.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur horizontal. NE DOIT PAS être zéro.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur horizontal. NE DOIT PAS être zéro.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicateur vertical. NE DOIT PAS être zéro.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicateur vertical. NE DOIT PAS être zéro.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur vertical. NE DOIT PAS être zéro.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur vertical. NE DOIT PAS être zéro.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

