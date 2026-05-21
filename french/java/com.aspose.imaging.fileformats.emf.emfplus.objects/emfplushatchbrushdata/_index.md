---
title: "EmfPlusHatchBrushData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusHatchBrushData spécifie un motif hachuré pour une brosse graphique."
type: docs
weight: 45
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusHatchBrushData extends EmfPlusBaseBrushData
```

L'objet EmfPlusHatchBrushData spécifie un motif hachuré pour une brosse graphique.

Les brosses graphiques sont spécifiées par des objets `EmfPlusBrush` (section 2.2.1.1). Une brosse à hachures peint un arrière‑plan et dessine un motif de lignes, points, tirets, carrés et lignes en croix sur cet arrière‑plan. La brosse à hachures définit deux couleurs : une pour l'arrière‑plan et une pour le motif sur l'arrière‑plan. La couleur de l'arrière‑plan est appelée couleur d'arrière‑plan, et la couleur du motif est appelée couleur de premier plan.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusHatchBrushData()](#EmfPlusHatchBrushData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBackArgb32Color()](#getBackArgb32Color--) | Obtient ou définit un objet EmfPlusArgb 32 bits qui spécifie la couleur utilisée pour peindre l'arrière‑plan du motif à hachures. |
| [setBackArgb32Color(int value)](#setBackArgb32Color-int-) | Obtient ou définit un objet EmfPlusArgb 32 bits qui spécifie la couleur utilisée pour peindre l'arrière‑plan du motif à hachures. |
| [getForeArgb32Color()](#getForeArgb32Color--) | Obtient ou définit un objet EmfPlusArgb 32 bits qui spécifie la couleur utilisée pour dessiner les lignes du motif à hachures. |
| [setForeArgb32Color(int value)](#setForeArgb32Color-int-) | Obtient ou définit un objet EmfPlusArgb 32 bits qui spécifie la couleur utilisée pour dessiner les lignes du motif à hachures. |
| [getHatchStyle()](#getHatchStyle--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le style de hachure de la brosse. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le style de hachure de la brosse. |
### EmfPlusHatchBrushData() {#EmfPlusHatchBrushData--}
```
public EmfPlusHatchBrushData()
```


### getBackArgb32Color() {#getBackArgb32Color--}
```
public int getBackArgb32Color()
```


Obtient ou définit un objet EmfPlusArgb 32 bits qui spécifie la couleur utilisée pour peindre l'arrière‑plan du motif à hachures.

**Returns:**
int
### setBackArgb32Color(int value) {#setBackArgb32Color-int-}
```
public void setBackArgb32Color(int value)
```


Obtient ou définit un objet EmfPlusArgb 32 bits qui spécifie la couleur utilisée pour peindre l'arrière‑plan du motif à hachures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getForeArgb32Color() {#getForeArgb32Color--}
```
public int getForeArgb32Color()
```


Obtient ou définit un objet EmfPlusArgb 32 bits qui spécifie la couleur utilisée pour dessiner les lignes du motif à hachures.

**Returns:**
int
### setForeArgb32Color(int value) {#setForeArgb32Color-int-}
```
public void setForeArgb32Color(int value)
```


Obtient ou définit un objet EmfPlusArgb 32 bits qui spécifie la couleur utilisée pour dessiner les lignes du motif à hachures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le style de hachure de la brosse. Il DOIT être défini dans l'énumération `EmfPlusHatchStyle`.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le style de hachure de la brosse. Il DOIT être défini dans l'énumération `EmfPlusHatchStyle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

