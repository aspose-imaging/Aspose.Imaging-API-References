---
title: "EmfPlusStringFormatData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusStringFormatData spécifie les tabulations et les positions des caractères pour une chaîne graphique."
type: docs
weight: 75
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusStringFormatData extends EmfPlusStructureObjectType
```

L'objet EmfPlusStringFormatData spécifie les tabulations et les positions des caractères pour une chaîne graphique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTabStops()](#getTabStops--) | Obtient ou définit un tableau optionnel de valeurs à virgule flottante qui spécifient les emplacements des tabulations optionnelles pour cet objet. |
| [setTabStops(float[] value)](#setTabStops-float---) | Obtient ou définit un tableau optionnel de valeurs à virgule flottante qui spécifient les emplacements des tabulations optionnelles pour cet objet. |
| [getCharRange()](#getCharRange--) | Obtient ou définit un tableau optionnel d'objets RangeCount EmfPlusCharacterRange qui spécifient la plage des positions de caractères dans une chaîne de texte. |
| [setCharRange(EmfPlusCharacterRange[] value)](#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---) | Obtient ou définit un tableau optionnel d'objets RangeCount EmfPlusCharacterRange qui spécifient la plage des positions de caractères dans une chaîne de texte. |
### EmfPlusStringFormatData() {#EmfPlusStringFormatData--}
```
public EmfPlusStringFormatData()
```


### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Obtient ou définit un tableau optionnel de valeurs à virgule flottante qui spécifient les emplacements des tabulations optionnelles pour cet objet. Chaque valeur de tabulation représente le nombre d'espaces entre les tabulations ou, pour la première tabulation, le nombre d'espaces entre le début d'une ligne de texte et la première tabulation. Ce champ DOIT être présent si la valeur du champ TabStopCount dans l'objet EmfPlusStringFormat est supérieure à 0.

**Returns:**
float[]
### setTabStops(float[] value) {#setTabStops-float---}
```
public void setTabStops(float[] value)
```


Obtient ou définit un tableau optionnel de valeurs à virgule flottante qui spécifient les emplacements des tabulations optionnelles pour cet objet. Chaque valeur de tabulation représente le nombre d'espaces entre les tabulations ou, pour la première tabulation, le nombre d'espaces entre le début d'une ligne de texte et la première tabulation. Ce champ DOIT être présent si la valeur du champ TabStopCount dans l'objet EmfPlusStringFormat est supérieure à 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float[] |  |

### getCharRange() {#getCharRange--}
```
public EmfPlusCharacterRange[] getCharRange()
```


Obtient ou définit un tableau optionnel d'objets RangeCount EmfPlusCharacterRange qui spécifient la plage des positions de caractères dans une chaîne de texte. La région de délimitation est définie par la zone d'affichage occupée par un groupe de caractères spécifié par la plage de caractères. Ce champ DOIT être présent si la valeur du champ RangeCount dans l'objet EmfPlusStringFormat est supérieure à 0.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange[]
### setCharRange(EmfPlusCharacterRange[] value) {#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---}
```
public void setCharRange(EmfPlusCharacterRange[] value)
```


Obtient ou définit un tableau optionnel d'objets RangeCount EmfPlusCharacterRange qui spécifient la plage des positions de caractères dans une chaîne de texte. La région de délimitation est définie par la zone d'affichage occupée par un groupe de caractères spécifié par la plage de caractères. Ce champ DOIT être présent si la valeur du champ RangeCount dans l'objet EmfPlusStringFormat est supérieure à 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusCharacterRange\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange) |  |

