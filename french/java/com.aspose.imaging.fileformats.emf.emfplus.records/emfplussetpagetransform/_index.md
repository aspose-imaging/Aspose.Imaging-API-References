---
title: "EmfPlusSetPageTransform"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusSetPageTransform spécifie les facteurs d'échelle et les unités pour convertir les coordonnées de l'espace page en coordonnées de l'espace dispositif."
type: docs
weight: 61
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetPageTransform extends EmfPlusTerminalServerRecordType
```

L'enregistrement EmfPlusSetPageTransform spécifie les facteurs d'échelle et les unités pour convertir les coordonnées de l'espace page en coordonnées de l'espace dispositif.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSetPageTransform(EmfPlusRecord source)](#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusSetPageTransform`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Obtient l'unité de mesure pour les coordonnées de l'espace page, à partir de l'énumération UnitType (section 2.1.1.33). |
| [getPageScale()](#getPageScale--) | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle pour convertir les coordonnées de l'espace page en coordonnées de l'espace dispositif. |
| [setPageScale(float value)](#setPageScale-float-) | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle pour convertir les coordonnées de l'espace page en coordonnées de l'espace dispositif. |
### EmfPlusSetPageTransform(EmfPlusRecord source) {#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetPageTransform(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusSetPageTransform`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Obtient l'unité de mesure pour les coordonnées de l'espace page, à partir de l'énumération UnitType (section 2.1.1.33). Cette valeur NE DOIT PAS être UnitTypeDisplay ou UnitTypeWorld.

Valeur : l'unité de page.

**Returns:**
int
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle pour convertir les coordonnées de l'espace page en coordonnées de l'espace dispositif.

Valeur : l'échelle de la page.

**Returns:**
float
### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle pour convertir les coordonnées de l'espace page en coordonnées de l'espace dispositif.

Valeur : l'échelle de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

