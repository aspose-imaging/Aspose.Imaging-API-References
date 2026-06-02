---
title: "EmfPlusFillClosedCurve"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusFillClosedCurve spécifie le remplissage de l'intérieur d'une spline cardinale fermée"
type: docs
weight: 32
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillClosedCurve extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusFillClosedCurve spécifie le remplissage de l'intérieur d'une spline cardinale fermée
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusFillClosedCurve(EmfPlusRecord source)](#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusFillClosedCurve`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isColor()](#isColor--) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [setColor(boolean value)](#setColor-boolean-) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [getCompressed()](#getCompressed--) | Obtient ou définit une valeur indiquant si ce `EmfPlusFillClosedCurve` est compressé. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtient ou définit une valeur indiquant si ce `EmfPlusFillClosedCurve` est compressé. |
| [getWinding()](#getWinding--) | Obtient ou définit une valeur indiquant si ce `EmfPlusFillClosedCurve` est en mode winding. |
| [setWinding(boolean value)](#setWinding-boolean-) | Obtient ou définit une valeur indiquant si ce `EmfPlusFillClosedCurve` est en mode winding. |
| [getRelative()](#getRelative--) | Obtient ou définit une valeur indiquant si ce `EmfPlusFillClosedCurve` est relatif. |
| [setRelative(boolean value)](#setRelative-boolean-) | Obtient ou définit une valeur indiquant si ce `EmfPlusFillClosedCurve` est relatif. |
| [getBrushId()](#getBrushId--) | Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui spécifie le EmfPlusBrush, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui spécifie le EmfPlusBrush, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [getTension()](#getTension--) | Obtient ou définit la tension, une valeur flottante de 32 bits qui spécifie la raideur de la courbe spline lorsqu'elle passe par les points. |
| [setTension(float value)](#setTension-float-) | Obtient ou définit la tension, une valeur flottante de 32 bits qui spécifie la raideur de la courbe spline lorsqu'elle passe par les points. |
| [getPointData()](#getPointData--) | Obtient ou définit les données de points, un tableau de Count points qui spécifient les extrémités des lignes définissant la spline. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtient ou définit les données de points, un tableau de Count points qui spécifient les extrémités des lignes définissant la spline. |
### EmfPlusFillClosedCurve(EmfPlusRecord source) {#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillClosedCurve(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusFillClosedCurve`.

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

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtient ou définit une valeur indiquant si ce `EmfPlusFillClosedCurve` est compressé. Ce bit indique si le champ PointData spécifie des données compressées. S'il est activé, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. S'il est désactivé, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées flottantes de 32 bits. ---------------------- Une opération de remplissage "winding" remplit les zones selon la règle de la parité "pair-impair". Selon cette règle, un point de test peut être déterminé comme étant à l'intérieur ou à l'extérieur d'une courbe fermée de la manière suivante : tracer une ligne du point de test vers un point éloigné de la courbe. Si cette ligne croise la courbe un nombre impair de fois, le point de test est à l'intérieur de la courbe ; sinon, il est à l'extérieur de la courbe. --------------------- Une opération de remplissage "alternate" remplit les zones selon la règle du "non-zéro". Selon cette règle, un point de test peut être déterminé comme étant à l'intérieur ou à l'extérieur d'une courbe fermée de la manière suivante : tracer une ligne d'un point de test vers un point éloigné de la courbe. Compter le nombre de fois où la courbe traverse la ligne de test de gauche à droite, et le nombre de fois où elle la traverse de droite à gauche. Si ces deux nombres sont identiques, le point de test est à l'extérieur de la courbe ; sinon, il est à l'intérieur de la courbe.

Valeur : `true` si compressé ; sinon, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtient ou définit une valeur indiquant si ce `EmfPlusFillClosedCurve` est compressé. Ce bit indique si le champ PointData spécifie des données compressées. S'il est activé, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. S'il est désactivé, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées flottantes de 32 bits. ---------------------- Une opération de remplissage "winding" remplit les zones selon la règle de la parité "pair-impair". Selon cette règle, un point de test peut être déterminé comme étant à l'intérieur ou à l'extérieur d'une courbe fermée de la manière suivante : tracer une ligne du point de test vers un point éloigné de la courbe. Si cette ligne croise la courbe un nombre impair de fois, le point de test est à l'intérieur de la courbe ; sinon, il est à l'extérieur de la courbe. --------------------- Une opération de remplissage "alternate" remplit les zones selon la règle du "non-zéro". Selon cette règle, un point de test peut être déterminé comme étant à l'intérieur ou à l'extérieur d'une courbe fermée de la manière suivante : tracer une ligne d'un point de test vers un point éloigné de la courbe. Compter le nombre de fois où la courbe traverse la ligne de test de gauche à droite, et le nombre de fois où elle la traverse de droite à gauche. Si ces deux nombres sont identiques, le point de test est à l'extérieur de la courbe ; sinon, il est à l'intérieur de la courbe.

Valeur : `true` si compressé ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getWinding() {#getWinding--}
```
public boolean getWinding()
```


Obtient ou définit une valeur indiquant si ce `EmfPlusFillClosedCurve` est en mode winding. Ce bit indique comment effectuer l'opération de remplissage. S'il est activé, le remplissage est de type "winding". S'il est désactivé, le remplissage est de type "alternate".

Valeur : `true` si winding ; sinon, `false`.

**Returns:**
boolean
### setWinding(boolean value) {#setWinding-boolean-}
```
public void setWinding(boolean value)
```


Obtient ou définit une valeur indiquant si ce `EmfPlusFillClosedCurve` est en mode winding. Ce bit indique comment effectuer l'opération de remplissage. S'il est activé, le remplissage est de type "winding". S'il est désactivé, le remplissage est de type "alternate".

Valeur : `true` si winding ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Obtient ou définit une valeur indiquant si ce `EmfPlusFillClosedCurve` est relatif. Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus. S'il est activé, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées relatif à l'emplacement indiqué par l'élément précédent du tableau. Dans le cas du premier élément de PointData, on suppose un emplacement précédent aux coordonnées (0,0). S'il est désactivé, PointData spécifie des emplacements absolus selon le drapeau C. Remarque : si ce drapeau est activé, le drapeau C (ci‑dessus) est indéfini et DOIT être ignoré.

Valeur : `true` si relatif ; sinon, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Obtient ou définit une valeur indiquant si ce `EmfPlusFillClosedCurve` est relatif. Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus. S'il est activé, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées relatif à l'emplacement indiqué par l'élément précédent du tableau. Dans le cas du premier élément de PointData, on suppose un emplacement précédent aux coordonnées (0,0). S'il est désactivé, PointData spécifie des emplacements absolus selon le drapeau C. Remarque : si ce drapeau est activé, le drapeau C (ci‑dessus) est indéfini et DOIT être ignoré.

Valeur : `true` si relatif ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui spécifie le EmfPlusBrush, dont le contenu est déterminé par le bit S dans le champ Flags. Ce pinceau est utilisé pour remplir l'intérieur de la spline cardinal fermée.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui spécifie le EmfPlusBrush, dont le contenu est déterminé par le bit S dans le champ Flags. Ce pinceau est utilisé pour remplir l'intérieur de la spline cardinal fermée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTension() {#getTension--}
```
public float getTension()
```


Obtient ou définit la tension, une valeur flottante de 32 bits qui spécifie la raideur de la spline lorsqu'elle passe par les points. Une valeur de 0,0 indique que la spline est une séquence de lignes droites. À mesure que la valeur augmente, la courbe devient plus arrondie. Pour plus d'informations, voir [SPLINE77] et [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Obtient ou définit la tension, une valeur flottante de 32 bits qui spécifie la raideur de la spline lorsqu'elle passe par les points. Une valeur de 0,0 indique que la spline est une séquence de lignes droites. À mesure que la valeur augmente, la courbe devient plus arrondie. Pour plus d'informations, voir [SPLINE77] et [PETZOLD].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtient ou définit les données de points, un tableau de Count points qui spécifient les extrémités des lignes définissant la spline. Dans une spline cardinal fermée, la courbe continue à travers le dernier point du tableau PointData et se connecte au premier point du tableau.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtient ou définit les données de points, un tableau de Count points qui spécifient les extrémités des lignes définissant la spline. Dans une spline cardinal fermée, la courbe continue à travers le dernier point du tableau PointData et se connecte au premier point du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

