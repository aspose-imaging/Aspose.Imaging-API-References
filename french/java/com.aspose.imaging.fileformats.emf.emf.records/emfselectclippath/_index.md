---
title: "EmfSelectClipPath"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le enregistrement EMR_SELECTCLIPPATH spécifie le chemin actuel comme région de découpe pour un contexte de dispositif de lecture, combinant la nouvelle région avec toute région de découpe existante en utilisant le mode spécifié."
type: docs
weight: 115
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfSelectClipPath extends EmfClippingRecordType
```

L'enregistrement EMR\_SELECTCLIPPATH spécifie le chemin actuel comme région de découpage pour un contexte de dispositif de lecture, en combinant la nouvelle région avec toute région de découpage existante en utilisant le mode spécifié.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSelectClipPath(EmfRecord source)](#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSelectClipPath`. |
| [EmfSelectClipPath()](#EmfSelectClipPath--) | Initialise une nouvelle instance de la classe `EmfSelectClipPath`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRegionMode()](#getRegionMode--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la façon d'utiliser le chemin. |
| [setRegionMode(int value)](#setRegionMode-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la façon d'utiliser le chemin. |
### EmfSelectClipPath(EmfRecord source) {#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectClipPath(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSelectClipPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfSelectClipPath() {#EmfSelectClipPath--}
```
public EmfSelectClipPath()
```


Initialise une nouvelle instance de la classe `EmfSelectClipPath`.

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la façon d'utiliser le chemin. La valeur DOIT appartenir à l'énumération RegionMode (section 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la façon d'utiliser le chemin. La valeur DOIT appartenir à l'énumération RegionMode (section 2.1.29).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

