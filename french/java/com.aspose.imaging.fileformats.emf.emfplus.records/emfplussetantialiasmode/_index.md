---
title: "EmfPlusSetAntiAliasMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusSetAntiAliasMode spécifie le mode d'anticrénelage pour la sortie de texte."
type: docs
weight: 54
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetAntiAliasMode extends EmfPlusPropertyRecordType
```

L'enregistrement EmfPlusSetAntiAliasMode spécifie le mode d'anticrénelage pour la sortie de texte.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSetAntiAliasMode(EmfPlusRecord source)](#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusSetAntiAliasMode`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Obtient ou définit le mode de lissage. |
| [setSmoothingMode(byte value)](#setSmoothingMode-byte-) | Obtient ou définit le mode de lissage. |
| [getAntiAliasing()](#getAntiAliasing--) | Obtient ou définit une valeur indiquant si [anti aliasing]. |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Obtient ou définit une valeur indiquant si [anti aliasing]. |
### EmfPlusSetAntiAliasMode(EmfPlusRecord source) {#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetAntiAliasMode(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusSetAntiAliasMode`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getSmoothingMode() {#getSmoothingMode--}
```
public byte getSmoothingMode()
```


Obtient ou définit le mode de lissage. (7 bits) : la valeur du mode de lissage, provenant de l'énumération SmoothingMode (section 2.1.1.28).

Valeur : le mode de lissage.

**Returns:**
byte
### setSmoothingMode(byte value) {#setSmoothingMode-byte-}
```
public void setSmoothingMode(byte value)
```


Obtient ou définit le mode de lissage. (7 bits) : la valeur du mode de lissage, provenant de l'énumération SmoothingMode (section 2.1.1.28).

Valeur : le mode de lissage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getAntiAliasing() {#getAntiAliasing--}
```
public boolean getAntiAliasing()
```


Obtient ou définit une valeur indiquant si [anti aliasing]. Si définie, l'anti-aliasing DOIT être appliqué. Si désactivée, l'anti-aliasing NE DOIT PAS être appliqué.

Valeur : `true` si [anti aliasing] ; sinon, `false`.

**Returns:**
boolean
### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public void setAntiAliasing(boolean value)
```


Obtient ou définit une valeur indiquant si [anti aliasing]. Si définie, l'anti-aliasing DOIT être appliqué. Si désactivée, l'anti-aliasing NE DOIT PAS être appliqué.

Valeur : `true` si [anti aliasing] ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

