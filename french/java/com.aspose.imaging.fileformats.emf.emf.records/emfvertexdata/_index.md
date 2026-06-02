---
title: "EmfVertexData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Objets qui spécifient les sommets de rectangles ou de triangles ainsi que les couleurs qui leur correspondent."
type: docs
weight: 155
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
**Inheritance:**
java.lang.Object
```
public final class EmfVertexData
```

Objets qui spécifient les sommets de rectangles ou de triangles ainsi que les couleurs qui leur correspondent.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfVertexData()](#EmfVertexData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVertexObjects()](#getVertexObjects--) | Obtient ou définit un tableau d'objets nVer TriVertex (section 2.2.26). |
| [setVertexObjects(EmfTriVertex[] value)](#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---) | Obtient ou définit un tableau d'objets nVer TriVertex (section 2.2.26). |
| [getVertexIndexes()](#getVertexIndexes--) | Obtient ou définit un tableau d'objets nTri GradientRectangle (section 2.2.7) ou d'objets GradientTriangle (section 2.2.8), selon la valeur du champ ulMode. |
| [setVertexIndexes(EmfGradientRectangle[] value)](#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---) | Obtient ou définit un tableau d'objets nTri GradientRectangle (section 2.2.7) ou d'objets GradientTriangle (section 2.2.8), selon la valeur du champ ulMode. |
| [getVertexPadding()](#getVertexPadding--) | Obtient ou définit un tableau optionnel de longueur variable de nTri fois quatre octets qui DOIT être présent si la valeur du champ ulMode indique des objets GradientRectangle (section 2.2.7). |
| [setVertexPadding(byte[] value)](#setVertexPadding-byte---) | Obtient ou définit un tableau optionnel de longueur variable de nTri fois quatre octets qui DOIT être présent si la valeur du champ ulMode indique des objets GradientRectangle (section 2.2.7). |
### EmfVertexData() {#EmfVertexData--}
```
public EmfVertexData()
```


### getVertexObjects() {#getVertexObjects--}
```
public EmfTriVertex[] getVertexObjects()
```


Obtient ou définit un tableau d'objets nVer TriVertex (section 2.2.26). Chaque objet spécifie la position et la couleur d'un sommet d'un rectangle ou d'un triangle, selon la valeur du champ ulMode.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex[]
### setVertexObjects(EmfTriVertex[] value) {#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---}
```
public void setVertexObjects(EmfTriVertex[] value)
```


Obtient ou définit un tableau d'objets nVer TriVertex (section 2.2.26). Chaque objet spécifie la position et la couleur d'un sommet d'un rectangle ou d'un triangle, selon la valeur du champ ulMode.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfTriVertex\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftrivertex) |  |

### getVertexIndexes() {#getVertexIndexes--}
```
public EmfGradientRectangle[] getVertexIndexes()
```


Obtient ou définit un tableau d'objets nTri GradientRectangle (section 2.2.7) ou d'objets GradientTriangle (section 2.2.8), selon la valeur du champ ulMode. Chaque objet spécifie des index dans le tableau d'objets TriVertex du champ VertexObjects.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle[]
### setVertexIndexes(EmfGradientRectangle[] value) {#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---}
```
public void setVertexIndexes(EmfGradientRectangle[] value)
```


Obtient ou définit un tableau d'objets nTri GradientRectangle (section 2.2.7) ou d'objets GradientTriangle (section 2.2.8), selon la valeur du champ ulMode. Chaque objet spécifie des index dans le tableau d'objets TriVertex du champ VertexObjects.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfGradientRectangle\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle) |  |

### getVertexPadding() {#getVertexPadding--}
```
public byte[] getVertexPadding()
```


Obtient ou définit un tableau optionnel de longueur variable de nTri fois quatre octets qui DOIT être présent si la valeur du champ ulMode indique des objets GradientRectangle (section 2.2.7). Si la valeur du champ ulMode indique des objets GradientTriangle (section 2.2.8), aucun VertexPadding n'est présent. Ce champ DOIT être ignoré.

**Returns:**
byte[]
### setVertexPadding(byte[] value) {#setVertexPadding-byte---}
```
public void setVertexPadding(byte[] value)
```


Obtient ou définit un tableau optionnel de longueur variable de nTri fois quatre octets qui DOIT être présent si la valeur du champ ulMode indique des objets GradientRectangle (section 2.2.7). Si la valeur du champ ulMode indique des objets GradientTriangle (section 2.2.8), aucun VertexPadding n'est présent. Ce champ DOIT être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

