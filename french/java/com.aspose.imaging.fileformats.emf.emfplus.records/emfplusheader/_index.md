---
title: "EmfPlusHeader"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusHeader spécifie le début des données EMF dans le métafichier."
type: docs
weight: 40
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusHeader extends EmfPlusControlRecordType
```

L'enregistrement EmfPlusHeader indique le début des données EMF+ dans le métafichier. L'enregistrement EmfPlusHeader DOIT être incorporé dans un enregistrement EMF EMR\_COMMENT\_EMFPLUS, qui DOIT être l'enregistrement immédiatement suivant l'en-tête EMF dans le métafichier. L'enregistrement EMR\_COMMENT\_EMFPLUS est spécifié dans la section 2.3.3.2 de [MS-EMF].
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusHeader(EmfPlusRecord source)](#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusHeader`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDualMode()](#getDualMode--) | Obtient ou définit une valeur indiquant si [dual mode]. |
| [setDualMode(boolean value)](#setDualMode-boolean-) | Obtient ou définit une valeur indiquant si [dual mode]. |
| [getVideoDisplay()](#getVideoDisplay--) | Obtient ou définit une valeur indiquant si affichage vidéo. |
| [setVideoDisplay(boolean value)](#setVideoDisplay-boolean-) | Obtient ou définit une valeur indiquant si affichage vidéo. |
| [getEmfPlusFlags()](#getEmfPlusFlags--) | Obtient ou définit les indicateurs EMF plus. |
| [setEmfPlusFlags(int value)](#setEmfPlusFlags-int-) | Obtient ou définit les indicateurs EMF plus. |
| [getLogicalDpiX()](#getLogicalDpiX--) | Obtient ou définit le DPI logique x. |
| [setLogicalDpiX(int value)](#setLogicalDpiX-int-) | Obtient ou définit le DPI logique x. |
| [getLogicalDpiY()](#getLogicalDpiY--) | Obtient ou définit le DPI logique y. |
| [setLogicalDpiY(int value)](#setLogicalDpiY-int-) | Obtient ou définit le DPI logique y. |
| [getVersion()](#getVersion--) | Obtient ou définit la version. |
| [setVersion(EmfPlusGraphicsVersion value)](#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-) | Obtient ou définit la version. |
| [isValid()](#isValid--) | Obtient une valeur indiquant si cette instance est valide. |
### EmfPlusHeader(EmfPlusRecord source) {#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusHeader(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusHeader`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getDualMode() {#getDualMode--}
```
public boolean getDualMode()
```


Obtient ou définit une valeur indiquant si [dual mode]. Si elle est définie, cet indicateur indique que ce métafichier est « dual-mode », ce qui signifie qu'il contient deux ensembles d'enregistrements, chacun spécifiant complètement le contenu graphique. Si elle est désactivée, le contenu graphique est spécifié par des enregistrements EMF+, et éventuellement des enregistrements EMF précédés d'un enregistrement EmfPlusGetDC. Si cet indicateur est défini, les enregistrements EMF seuls DEVRAIENT suffire à définir le contenu graphique. Notez que, que l'indicateur « dual-mode » soit défini ou non, certains enregistrements EMF sont toujours présents, à savoir les enregistrements de contrôle EMF et les enregistrements EMF contenant des enregistrements EMF+. Les enregistrements de contrôle EMF sont spécifiés dans la section 2.3.4 de [MS-EMF].

Valeur : `true` si [dual mode] ; sinon, `false`.

**Returns:**
boolean
### setDualMode(boolean value) {#setDualMode-boolean-}
```
public void setDualMode(boolean value)
```


Obtient ou définit une valeur indiquant si [dual mode]. Si elle est définie, cet indicateur indique que ce métafichier est « dual-mode », ce qui signifie qu'il contient deux ensembles d'enregistrements, chacun spécifiant complètement le contenu graphique. Si elle est désactivée, le contenu graphique est spécifié par des enregistrements EMF+, et éventuellement des enregistrements EMF précédés d'un enregistrement EmfPlusGetDC. Si cet indicateur est défini, les enregistrements EMF seuls DEVRAIENT suffire à définir le contenu graphique. Notez que, que l'indicateur « dual-mode » soit défini ou non, certains enregistrements EMF sont toujours présents, à savoir les enregistrements de contrôle EMF et les enregistrements EMF contenant des enregistrements EMF+. Les enregistrements de contrôle EMF sont spécifiés dans la section 2.3.4 de [MS-EMF].

Valeur : `true` si [dual mode] ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getVideoDisplay() {#getVideoDisplay--}
```
public boolean getVideoDisplay()
```


Obtient ou définit une valeur indiquant si affichage vidéo. Si elle est définie, cet indicateur indique que le métafichier a été enregistré avec un contexte de dispositif de référence pour un affichage vidéo. Si elle est désactivée, le métafichier a été enregistré avec un contexte de dispositif de référence pour une imprimante.

Valeur : `true` si [video display] ; sinon, `false`.

**Returns:**
boolean
### setVideoDisplay(boolean value) {#setVideoDisplay-boolean-}
```
public void setVideoDisplay(boolean value)
```


Obtient ou définit une valeur indiquant si affichage vidéo. Si elle est définie, cet indicateur indique que le métafichier a été enregistré avec un contexte de dispositif de référence pour un affichage vidéo. Si elle est désactivée, le métafichier a été enregistré avec un contexte de dispositif de référence pour une imprimante.

Valeur : `true` si [video display] ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getEmfPlusFlags() {#getEmfPlusFlags--}
```
public int getEmfPlusFlags()
```


Obtient ou définit les indicateurs EMF plus. Un entier non signé de 32 bits qui contient des informations sur la façon dont ce métafichier a été enregistré. Si le 31ᵉ bit du champ est défini, cet indicateur indique que le métafichier a été enregistré avec un contexte de dispositif de référence pour un affichage vidéo. Si désactivé, le métafichier a été enregistré avec un contexte de dispositif de référence pour une imprimante.

Valeur : les indicateurs EMF plus.

**Returns:**
int
### setEmfPlusFlags(int value) {#setEmfPlusFlags-int-}
```
public void setEmfPlusFlags(int value)
```


Obtient ou définit les indicateurs EMF plus. Un entier non signé de 32 bits qui contient des informations sur la façon dont ce métafichier a été enregistré. Si le 31ᵉ bit du champ est défini, cet indicateur indique que le métafichier a été enregistré avec un contexte de dispositif de référence pour un affichage vidéo. Si désactivé, le métafichier a été enregistré avec un contexte de dispositif de référence pour une imprimante.

Valeur : les indicateurs EMF plus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLogicalDpiX() {#getLogicalDpiX--}
```
public int getLogicalDpiX()
```


Obtient ou définit le DPI logique x. Un entier non signé de 32 bits qui spécifie la résolution horizontale pour laquelle le métafichier a été enregistré, en unités de pixels par pouce.

Valeur : le DPI logique x.

**Returns:**
int
### setLogicalDpiX(int value) {#setLogicalDpiX-int-}
```
public void setLogicalDpiX(int value)
```


Obtient ou définit le DPI logique x. Un entier non signé de 32 bits qui spécifie la résolution horizontale pour laquelle le métafichier a été enregistré, en unités de pixels par pouce.

Valeur : le DPI logique x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLogicalDpiY() {#getLogicalDpiY--}
```
public int getLogicalDpiY()
```


Obtient ou définit le DPI logique y. Un entier non signé de 32 bits qui spécifie la résolution verticale pour laquelle le métafichier a été enregistré, en unités de lignes par pouce.

Valeur : le DPI logique y.

**Returns:**
int
### setLogicalDpiY(int value) {#setLogicalDpiY-int-}
```
public void setLogicalDpiY(int value)
```


Obtient ou définit le DPI logique y. Un entier non signé de 32 bits qui spécifie la résolution verticale pour laquelle le métafichier a été enregistré, en unités de lignes par pouce.

Valeur : le DPI logique y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getVersion() {#getVersion--}
```
public EmfPlusGraphicsVersion getVersion()
```


Obtient ou définit la version. Un objet EmfPlusGraphicsVersion (section 2.2.2.19) qui spécifie la version des graphiques du système d'exploitation utilisée pour créer ce métafichier.

Valeur : la version.

**Returns:**
[EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion)
### setVersion(EmfPlusGraphicsVersion value) {#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-}
```
public void setVersion(EmfPlusGraphicsVersion value)
```


Obtient ou définit la version. Un objet EmfPlusGraphicsVersion (section 2.2.2.19) qui spécifie la version des graphiques du système d'exploitation utilisée pour créer ce métafichier.

Valeur : la version.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion) |  |

### isValid() {#isValid--}
```
public boolean isValid()
```


Obtient une valeur indiquant si cette instance est valide.

Valeur : `true` si cette instance est valide ; sinon, `false`.

**Returns:**
boolean
