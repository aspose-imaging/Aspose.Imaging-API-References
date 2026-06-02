---
title: "EmfPlusDrawCurve"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusDrawCurve spécifie le tracé d'une spline cardinal NOTE ObjectID 1 octet L'index d'un objet EmfPlusPen section 2.2.1.7 dans la table d'objets EMF pour dessiner la courbe."
type: docs
weight: 19
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawCurve extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusDrawCurve spécifie le tracé d'une spline cardinal NOTE : ObjectID (1 octet) : L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner la courbe. La valeur DOIT être comprise entre 0 et 63, inclusivement.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusDrawCurve(EmfPlusRecord source)](#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusDrawCurve`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtient ou définit une valeur indiquant si ce `EmfPlusDrawClosedCurve` est compressé. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtient ou définit une valeur indiquant si ce `EmfPlusDrawClosedCurve` est compressé. |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'identifiant de l'objet. |
| [getTension()](#getTension--) | Obtient ou définit la tension Un nombre à virgule flottante de 32 bits qui spécifie à quel point la spline se plie étroitement lorsqu'elle passe à travers les points. |
| [setTension(float value)](#setTension-float-) | Obtient ou définit la tension Un nombre à virgule flottante de 32 bits qui spécifie à quel point la spline se plie étroitement lorsqu'elle passe à travers les points. |
| [getNumSegments()](#getNumSegments--) | Obtient ou définit le nombre de segments Un entier non signé de 32 bits qui spécifie le nombre de segments de ligne composant la spline. |
| [setNumSegments(int value)](#setNumSegments-int-) | Obtient ou définit le nombre de segments Un entier non signé de 32 bits qui spécifie le nombre de segments de ligne composant la spline. |
| [getPointData()](#getPointData--) | Obtient ou définit un tableau d'entiers signés de 32 bits ou de nombres à virgule flottante de 32 bits de longueur Count qui définit les valeurs de coordonnées des points d'extrémité des lignes à tracer. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtient ou définit un tableau d'entiers signés de 32 bits ou de nombres à virgule flottante de 32 bits de longueur Count qui définit les valeurs de coordonnées des points d'extrémité des lignes à tracer. |
### EmfPlusDrawCurve(EmfPlusRecord source) {#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawCurve(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusDrawCurve`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner la courbe. La valeur DOIT être comprise entre 0 et 63, inclusivement.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner la courbe. La valeur DOIT être comprise entre 0 et 63, inclusivement.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getTension() {#getTension--}
```
public float getTension()
```


Obtient ou définit la tension Un nombre à virgule flottante de 32 bits qui spécifie à quel point la spline se courbe lorsqu'elle passe par les points. Une valeur de 0 indique que la spline est une séquence de lignes droites. À mesure que la valeur augmente, la courbe devient plus arrondie. Pour plus d'informations, voir [SPLINE77] et [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Obtient ou définit la tension Un nombre à virgule flottante de 32 bits qui spécifie à quel point la spline se courbe lorsqu'elle passe par les points. Une valeur de 0 indique que la spline est une séquence de lignes droites. À mesure que la valeur augmente, la courbe devient plus arrondie. Pour plus d'informations, voir [SPLINE77] et [PETZOLD].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getNumSegments() {#getNumSegments--}
```
public int getNumSegments()
```


Obtient ou définit le nombre de segments Un entier non signé de 32 bits qui spécifie le nombre de segments de ligne composant la spline.

**Returns:**
int
### setNumSegments(int value) {#setNumSegments-int-}
```
public void setNumSegments(int value)
```


Obtient ou définit le nombre de segments Un entier non signé de 32 bits qui spécifie le nombre de segments de ligne composant la spline.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtient ou définit un tableau d'entiers signés de 32 bits ou de nombres à virgule flottante de 32 bits de longueur Count qui définit les valeurs de coordonnées des points d'extrémité des lignes à tracer.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtient ou définit un tableau d'entiers signés de 32 bits ou de nombres à virgule flottante de 32 bits de longueur Count qui définit les valeurs de coordonnées des points d'extrémité des lignes à tracer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

