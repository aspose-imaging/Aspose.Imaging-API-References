---
title: "EmfGradientRectangle"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet GradientRectangle définit un rectangle en utilisant des objets TriVertex section 2.2.26 dans un enregistrement EMR_GRADIENTFILL section 2.3.5.12."
type: docs
weight: 16
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfGradientRectangle extends EmfObject
```

L'objet GradientRectangle définit un rectangle en utilisant des objets TriVertex (section 2.2.26) dans un enregistrement EMR\_GRADIENTFILL (section 2.3.5.12).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfGradientRectangle()](#EmfGradientRectangle--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getUpperLeft()](#getUpperLeft--) | Obtient ou définit un indice dans un tableau d'objets TriVertex qui spécifie le sommet supérieur gauche d'un rectangle. |
| [setUpperLeft(int value)](#setUpperLeft-int-) | Obtient ou définit un indice dans un tableau d'objets TriVertex qui spécifie le sommet supérieur gauche d'un rectangle. |
| [getLowerRight()](#getLowerRight--) | Obtient ou définit un indice dans un tableau d'objets TriVertex qui spécifie le sommet inférieur droit d'un rectangle. |
| [setLowerRight(int value)](#setLowerRight-int-) | Obtient ou définit un indice dans un tableau d'objets TriVertex qui spécifie le sommet inférieur droit d'un rectangle. |
### EmfGradientRectangle() {#EmfGradientRectangle--}
```
public EmfGradientRectangle()
```


### getUpperLeft() {#getUpperLeft--}
```
public int getUpperLeft()
```


Obtient ou définit un indice dans un tableau d'objets TriVertex qui spécifie le sommet supérieur gauche d'un rectangle. L'indice MUST être inférieur à la taille du tableau, tel que défini par le champ nVer de l'enregistrement EMR\_GRADIENTFILL.

**Returns:**
int
### setUpperLeft(int value) {#setUpperLeft-int-}
```
public void setUpperLeft(int value)
```


Obtient ou définit un indice dans un tableau d'objets TriVertex qui spécifie le sommet supérieur gauche d'un rectangle. L'indice MUST être inférieur à la taille du tableau, tel que défini par le champ nVer de l'enregistrement EMR\_GRADIENTFILL.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLowerRight() {#getLowerRight--}
```
public int getLowerRight()
```


Obtient ou définit un indice dans un tableau d'objets TriVertex qui spécifie le sommet inférieur droit d'un rectangle. L'indice MUST être inférieur à la taille du tableau, tel que défini par le champ nVer de l'enregistrement EMR\_GRADIENTFILL.

**Returns:**
int
### setLowerRight(int value) {#setLowerRight-int-}
```
public void setLowerRight(int value)
```


Obtient ou définit un indice dans un tableau d'objets TriVertex qui spécifie le sommet inférieur droit d'un rectangle. L'indice MUST être inférieur à la taille du tableau, tel que défini par le champ nVer de l'enregistrement EMR\_GRADIENTFILL.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

