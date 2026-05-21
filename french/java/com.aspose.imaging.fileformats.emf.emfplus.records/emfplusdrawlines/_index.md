---
title: "EmfPlusDrawLines"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusDrawlLines spécifie le dessin d'une série de lignes connectées"
type: docs
weight: 24
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawLines extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusDrawlLines spécifie le dessin d'une série de lignes connectées
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusDrawLines(EmfPlusRecord source)](#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusDrawLines`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'identifiant de l'objet. |
| [getCompressed()](#getCompressed--) | Obtient ou définit une valeur indiquant si ce `EmfPlusDrawClosedCurve` est compressé. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtient ou définit une valeur indiquant si ce `EmfPlusDrawClosedCurve` est compressé. |
| [getRelative()](#getRelative--) | Obtient ou définit une valeur indiquant si ce `EmfPlusDrawClosedCurve` est relatif. |
| [setRelative(boolean value)](#setRelative-boolean-) | Obtient ou définit une valeur indiquant si ce `EmfPlusDrawClosedCurve` est relatif. |
| [getClosedShape()](#getClosedShape--) | Obtient ou définit une valeur indiquant si [forme fermée]. |
| [setClosedShape(boolean value)](#setClosedShape-boolean-) | Obtient ou définit une valeur indiquant si [forme fermée]. |
| [getPointData()](#getPointData--) | Obtient ou définit les données de points, un tableau de points Count qui spécifient les points de départ et d'arrivée des lignes à tracer. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtient ou définit les données de points, un tableau de points Count qui spécifient les points de départ et d'arrivée des lignes à tracer. |
### EmfPlusDrawLines(EmfPlusRecord source) {#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawLines(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusDrawLines`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner les lignes. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner les lignes. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtient ou définit une valeur indiquant si ce `EmfPlusDrawClosedCurve` est compressé. Ce bit indique si le champ PointData spécifie des données compressées. Si défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. Si non défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits Remarque Si le drapeau Relative (ci‑dessous) est défini, ce drapeau est indéfini et DOIT être ignoré

Valeur : `true` si compressé ; sinon, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtient ou définit une valeur indiquant si ce `EmfPlusDrawClosedCurve` est compressé. Ce bit indique si le champ PointData spécifie des données compressées. Si défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. Si non défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits Remarque Si le drapeau Relative (ci‑dessous) est défini, ce drapeau est indéfini et DOIT être ignoré

Valeur : `true` si compressé ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Obtient ou définit une valeur indiquant si ce `EmfPlusDrawClosedCurve` est relatif. Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus. Si défini, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées qui est relatif à l'emplacement spécifié par l'élément précédent du tableau. Dans le cas du premier élément de PointData, un emplacement précédent aux coordonnées (0,0) est supposé. Si non défini, PointData spécifie des emplacements absolus selon le drapeau C. Remarque Si ce drapeau est défini, le drapeau Compressed (ci‑dessus) est indéfini et DOIT être ignoré

Valeur : `true` si relatif ; sinon, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Obtient ou définit une valeur indiquant si ce `EmfPlusDrawClosedCurve` est relatif. Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus. Si défini, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées qui est relatif à l'emplacement spécifié par l'élément précédent du tableau. Dans le cas du premier élément de PointData, un emplacement précédent aux coordonnées (0,0) est supposé. Si non défini, PointData spécifie des emplacements absolus selon le drapeau C. Remarque Si ce drapeau est défini, le drapeau Compressed (ci‑dessus) est indéfini et DOIT être ignoré

Valeur : `true` si relatif ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getClosedShape() {#getClosedShape--}
```
public boolean getClosedShape()
```


Obtient ou définit une valeur indiquant si [forme fermée].

Valeur : `true` si [closed shape] ; sinon, `false`.

**Returns:**
boolean
### setClosedShape(boolean value) {#setClosedShape-boolean-}
```
public void setClosedShape(boolean value)
```


Obtient ou définit une valeur indiquant si [forme fermée].

Valeur : `true` si [closed shape] ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtient ou définit les données de points, un tableau de points Count qui spécifient les points de départ et d'arrivée des lignes à tracer.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtient ou définit les données de points, un tableau de points Count qui spécifient les points de départ et d'arrivée des lignes à tracer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

