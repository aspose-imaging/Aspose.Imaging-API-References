---
title: "EmfPlusDrawBeziers"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusDrawBeziers spécifie le dessin d'une séquence de courbes de Bézier connectées."
type: docs
weight: 17
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawBeziers extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusDrawBeziers spécifie le dessin d'une séquence de courbes de Bézier connectées. L'ordre des points de données Bézier est le point de départ, le point de contrôle 1, le point de contrôle 2 et le point final. Pour plus d'informations, voir [MSDN-DrawBeziers].
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusDrawBeziers(EmfPlusRecord source)](#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusDrawBeziers`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtient ou définit une valeur indiquant si le PointData est compressé. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtient ou définit une valeur indiquant si le PointData est compressé. |
| [getRelative()](#getRelative--) | Obtient ou définit une valeur indiquant si le PointData est relatif. |
| [setRelative(boolean value)](#setRelative-boolean-) | Obtient ou définit une valeur indiquant si le PointData est relatif. |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'identifiant de l'objet. |
| [getPointData()](#getPointData--) | Obtient ou définit les données de point : un tableau de Count points qui spécifient les points de départ, d'arrivée et de contrôle des courbes de Bézier. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtient ou définit les données de point : un tableau de Count points qui spécifient les points de départ, d'arrivée et de contrôle des courbes de Bézier. |
### EmfPlusDrawBeziers(EmfPlusRecord source) {#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawBeziers(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusDrawBeziers`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtient ou définit une valeur indiquant si le PointData est compressé. Si le bit est défini, PointData indique des positions absolues dans l'espace de coordonnées avec des coordonnées entières de 16 bits. Si le bit est dégagé, PointData indique des positions absolues dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits. Remarque : si le drapeau Relative (ci‑dessus) est défini, ce drapeau est indéfini et DOIT être ignoré.

Valeur : `true` si compressé ; sinon, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtient ou définit une valeur indiquant si le PointData est compressé. Si le bit est défini, PointData indique des positions absolues dans l'espace de coordonnées avec des coordonnées entières de 16 bits. Si le bit est dégagé, PointData indique des positions absolues dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits. Remarque : si le drapeau Relative (ci‑dessus) est défini, ce drapeau est indéfini et DOIT être ignoré.

Valeur : `true` si compressé ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Obtient ou définit une valeur indiquant si le PointData est relatif. Si le bit est défini, chaque élément de PointData indique une position dans l'espace de coordonnées relative à la position spécifiée par l'élément précédent du tableau. Dans le cas du premier élément de PointData, on suppose une position précédente aux coordonnées (0,0). Si le bit est dégagé, PointData indique des positions absolues selon le drapeau C. Remarque : si ce drapeau est défini, le drapeau C (ci‑dessus) est indéfini et DOIT être ignoré.

Valeur : `true` si relatif ; sinon, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Obtient ou définit une valeur indiquant si le PointData est relatif. Si le bit est défini, chaque élément de PointData indique une position dans l'espace de coordonnées relative à la position spécifiée par l'élément précédent du tableau. Dans le cas du premier élément de PointData, on suppose une position précédente aux coordonnées (0,0). Si le bit est dégagé, PointData indique des positions absolues selon le drapeau C. Remarque : si ce drapeau est défini, le drapeau C (ci‑dessus) est indéfini et DOIT être ignoré.

Valeur : `true` si relatif ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ utilisé pour dessiner les courbes de Bézier. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ utilisé pour dessiner les courbes de Bézier. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtient ou définit les données de point : un tableau de Count points qui spécifient les points de départ, d'arrivée et de contrôle des courbes de Bézier. La coordonnée finale d'une courbe de Bézier est la coordonnée de départ de la suivante. Les points de contrôle sont utilisés pour produire l'effet Bézier. Le type de données dans ce tableau est spécifié par le champ Flags, comme suit : Type de données — Signification ; objet EmfPlusPointR (section 2.2.2.37) — si le drapeau P est défini dans Flags, les points indiquent des positions relatives. objet EmfPlusPointF (section 2.2.2.36) — si les bits P et C sont dégagés dans Flags, les points indiquent des positions absolues. objet EmfPlusPoint (section 2.2.2.35) — si le bit P est dégagé et le bit C est défini dans Flags, les points indiquent des positions relatives. Une courbe de Bézier ne passe pas par ses points de contrôle. Les points de contrôle servent de

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtient ou définit les données de point : un tableau de Count points qui spécifient les points de départ, d'arrivée et de contrôle des courbes de Bézier. La coordonnée finale d'une courbe de Bézier est la coordonnée de départ de la suivante. Les points de contrôle sont utilisés pour produire l'effet Bézier. Le type de données dans ce tableau est spécifié par le champ Flags, comme suit : Type de données — Signification ; objet EmfPlusPointR (section 2.2.2.37) — si le drapeau P est défini dans Flags, les points indiquent des positions relatives. objet EmfPlusPointF (section 2.2.2.36) — si les bits P et C sont dégagés dans Flags, les points indiquent des positions absolues. objet EmfPlusPoint (section 2.2.2.35) — si le bit P est dégagé et le bit C est défini dans Flags, les points indiquent des positions relatives. Une courbe de Bézier ne passe pas par ses points de contrôle. Les points de contrôle servent de

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

