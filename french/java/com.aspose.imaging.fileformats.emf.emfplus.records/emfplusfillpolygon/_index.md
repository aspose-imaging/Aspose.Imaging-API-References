---
title: "EmfPlusFillPolygon"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusFillPolygon spécifie le remplissage de l'intérieur d'un polygone."
type: docs
weight: 36
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPolygon extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusFillPolygon spécifie le remplissage de l'intérieur d'un polygone.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusFillPolygon(EmfPlusRecord source)](#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusFillPolygon`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isColor()](#isColor--) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [setColor(boolean value)](#setColor-boolean-) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [isCompressed()](#isCompressed--) | Obtient ou définit une valeur indiquant si cette instance est compressée. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtient ou définit une valeur indiquant si cette instance est compressée. |
| [isRelative()](#isRelative--) | Obtient ou définit une valeur indiquant si cette instance est relative. |
| [setRelative(boolean value)](#setRelative-boolean-) | Obtient ou définit une valeur indiquant si cette instance est relative. |
| [getBrushId()](#getBrushId--) | Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [getPointData()](#getPointData--) | Obtient ou définit les données de points, un tableau de Count points qui définissent les sommets du polygone. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtient ou définit les données de points, un tableau de Count points qui définissent les sommets du polygone. |
### EmfPlusFillPolygon(EmfPlusRecord source) {#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPolygon(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusFillPolygon`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Obtient ou définit une valeur indiquant si cette instance est en couleur. Si définie, BrushId spécifie une couleur sous forme d’un objet EmfPlusARGB (section 2.2.2.1). Si non définie, BrushId contient l’index d’un objet EmfPlusBrush (section 2.2.1.1) dans la table d’objets EMF+.

Valeur : `true` si cette instance est en couleur ; sinon, `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est en couleur. Si définie, BrushId spécifie une couleur sous forme d’un objet EmfPlusARGB (section 2.2.2.1). Si non définie, BrushId contient l’index d’un objet EmfPlusBrush (section 2.2.1.1) dans la table d’objets EMF+.

Valeur : `true` si cette instance est en couleur ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


Obtient ou définit une valeur indiquant si cette instance est compressée. Si elle est définie, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. Si elle est désactivée, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits.

Valeur : `true` si cette instance est compressée ; sinon, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est compressée. Si elle est définie, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. Si elle est désactivée, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits.

Valeur : `true` si cette instance est compressée ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### isRelative() {#isRelative--}
```
public boolean isRelative()
```


Obtient ou définit une valeur indiquant si cette instance est relative. Si elle est définie, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées qui est relatif à l'emplacement spécifié par l'élément précédent du tableau. Dans le cas du premier élément de PointData, on suppose un emplacement précédent aux coordonnées (0,0). Si elle est désactivée, PointData spécifie des emplacements absolus selon le drapeau C.

Valeur : `true` si cette instance est relative ; sinon, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est relative. Si elle est définie, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées qui est relatif à l'emplacement spécifié par l'élément précédent du tableau. Dans le cas du premier élément de PointData, on suppose un emplacement précédent aux coordonnées (0,0). Si elle est désactivée, PointData spécifie des emplacements absolus selon le drapeau C.

Valeur : `true` si cette instance est relative ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtient ou définit les données de point. Un tableau de Count points qui définissent les sommets du polygone. Les deux premiers points du tableau spécifient le premier côté du polygone. Chaque point supplémentaire spécifie un nouveau côté, dont les sommets comprennent le point et le point précédent. Si le dernier point et le premier point ne coïncident pas, ils spécifient le dernier côté du polygone.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtient ou définit les données de point. Un tableau de Count points qui définissent les sommets du polygone. Les deux premiers points du tableau spécifient le premier côté du polygone. Chaque point supplémentaire spécifie un nouveau côté, dont les sommets comprennent le point et le point précédent. Si le dernier point et le premier point ne coïncident pas, ils spécifient le dernier côté du polygone.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

