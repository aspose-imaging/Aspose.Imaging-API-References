---
title: "EmfSetPolyFillMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETPOLYFILLMODE définit le mode de remplissage du polygone."
type: docs
weight: 136
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetPolyFillMode extends EmfStateRecordType
```

L'enregistrement EMR\_SETPOLYFILLMODE définit le mode de remplissage des polygones.

En général, les modes ne diffèrent que dans les cas où un polygone complexe et qui se chevauche DOIT être rempli ; par exemple, un polygone à cinq côtés qui forme une étoile à cinq pointes avec un pentagone au centre. Dans de tels cas, le mode ALTERNATE DOIT remplir chaque autre région enfermée à l'intérieur du polygone (les pointes de l'étoile), mais le mode WINDING DOIT remplir toutes les régions (les pointes de l'étoile et le pentagone). Lorsque le mode de remplissage est ALTERNATE, la zone entre les côtés impairs et pairs du polygone sur chaque ligne de balayage DOIT être remplie. C’est‑à‑dire, la zone entre le premier et le deuxième côté DOIT être remplie, ainsi que celle entre le troisième et le quatrième côté, etc. Lorsque le mode de remplissage est WINDING, toute région qui possède une valeur de winding non nulle DOIT être remplie. La valeur de winding correspond au nombre de fois qu'un crayon utilisé pour tracer le polygone ferait le tour de la région. La direction de chaque arête du polygone est significative.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetPolyFillMode(EmfRecord source)](#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetPolyFillMode`. |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode--) | Initialise une nouvelle instance de la classe `EmfSetPolyFillMode`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPolygonFillMode()](#getPolygonFillMode--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode de remplissage du polygone et DOIT être dans l'énumération PolygonFillMode (section 2.1.27). |
| [setPolygonFillMode(int value)](#setPolygonFillMode-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode de remplissage du polygone et DOIT être dans l'énumération PolygonFillMode (section 2.1.27). |
### EmfSetPolyFillMode(EmfRecord source) {#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPolyFillMode(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetPolyFillMode`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfSetPolyFillMode() {#EmfSetPolyFillMode--}
```
public EmfSetPolyFillMode()
```


Initialise une nouvelle instance de la classe `EmfSetPolyFillMode`.

### getPolygonFillMode() {#getPolygonFillMode--}
```
public int getPolygonFillMode()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le mode de remplissage du polygone et DOIT être dans l'énumération PolygonFillMode (section 2.1.27).

**Returns:**
int
### setPolygonFillMode(int value) {#setPolygonFillMode-int-}
```
public void setPolygonFillMode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le mode de remplissage du polygone et DOIT être dans l'énumération PolygonFillMode (section 2.1.27).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

