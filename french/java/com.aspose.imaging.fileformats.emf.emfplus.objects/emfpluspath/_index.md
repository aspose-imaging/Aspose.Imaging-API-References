---
title: "EmfPlusPath"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusPath spécifie une série de segments de ligne et de courbe qui forment un chemin graphique."
type: docs
weight: 58
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusPath extends EmfPlusGraphicsObjectType
```

L'objet EmfPlusPath spécifie une série de segments de ligne et de courbe qui forment un chemin graphique. L'ordre des points de données Bézier est le point de départ, le point de contrôle 1, le point de contrôle 2 et le point final. Pour plus d'informations, voir [MSDN - DrawBeziers].
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusPath()](#EmfPlusPath--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPathPointFlags()](#getPathPointFlags--) | Obtient ou définit le nombre de points du chemin, un entier non signé de 32 bits qui spécifie comment interpréter les points et les types de points associés qui sont définis par cet objet. |
| [setPathPointFlags(short value)](#setPathPointFlags-short-) | Obtient ou définit le nombre de points du chemin, un entier non signé de 32 bits qui spécifie comment interpréter les points et les types de points associés qui sont définis par cet objet. |
| [getPathPoints()](#getPathPoints--) | Obtient ou définit un tableau de points de chemin. Un tableau de PathPointCount points qui spécifient le chemin. |
| [setPathPoints(PointF[] value)](#setPathPoints-com.aspose.imaging.PointF---) | Obtient ou définit un tableau de points de chemin. Un tableau de PathPointCount points qui spécifient le chemin. |
| [getPathPointTypes()](#getPathPointTypes--) | Obtient ou définit un tableau qui spécifie comment les points du champ PathPoints sont utilisés pour tracer le chemin. |
| [setPathPointTypes(EmfPlusBasePointType[] value)](#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---) | Obtient ou définit un tableau qui spécifie comment les points du champ PathPoints sont utilisés pour tracer le chemin. |
### EmfPlusPath() {#EmfPlusPath--}
```
public EmfPlusPath()
```


### getPathPointFlags() {#getPathPointFlags--}
```
public short getPathPointFlags()
```


Obtient ou définit le nombre de points du chemin, un entier non signé de 32 bits qui spécifie comment interpréter les points et les types de points associés qui sont définis par cet objet.

**Returns:**
short
### setPathPointFlags(short value) {#setPathPointFlags-short-}
```
public void setPathPointFlags(short value)
```


Obtient ou définit le nombre de points du chemin, un entier non signé de 32 bits qui spécifie comment interpréter les points et les types de points associés qui sont définis par cet objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Obtient ou définit un tableau de points de chemin. Un tableau de PathPointCount points qui spécifient le chemin. Le type d'objets dans ce tableau est spécifié par le champ PathPointFlags, comme suit : Si le drapeau P est activé, les points sont des emplacements relatifs spécifiés par des objets EmfPlusPointR (section 2.2.2.37). Si le drapeau P est désactivé et le drapeau C est activé, les points sont des emplacements absolus spécifiés par des objets EmfPlusPoint (section 2.2.2.35). Si le drapeau P est désactivé et le drapeau C est désactivé, les points sont des emplacements absolus spécifiés par des objets EmfPlusPointF (section 2.2.2.36).

**Returns:**
com.aspose.imaging.PointF[]
### setPathPoints(PointF[] value) {#setPathPoints-com.aspose.imaging.PointF---}
```
public void setPathPoints(PointF[] value)
```


Obtient ou définit un tableau de points de chemin. Un tableau de PathPointCount points qui spécifient le chemin. Le type d'objets dans ce tableau est spécifié par le champ PathPointFlags, comme suit : Si le drapeau P est activé, les points sont des emplacements relatifs spécifiés par des objets EmfPlusPointR (section 2.2.2.37). Si le drapeau P est désactivé et le drapeau C est activé, les points sont des emplacements absolus spécifiés par des objets EmfPlusPoint (section 2.2.2.35). Si le drapeau P est désactivé et le drapeau C est désactivé, les points sont des emplacements absolus spécifiés par des objets EmfPlusPointF (section 2.2.2.36).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getPathPointTypes() {#getPathPointTypes--}
```
public EmfPlusBasePointType[] getPathPointTypes()
```


Obtient ou définit un tableau qui spécifie comment les points du champ PathPoints sont utilisés pour tracer le chemin. Le type d'objets dans ce tableau est spécifié par le drapeau R dans le champ PathPointFlags.

Valeur : les types de points de chemin.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType[]
### setPathPointTypes(EmfPlusBasePointType[] value) {#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---}
```
public void setPathPointTypes(EmfPlusBasePointType[] value)
```


Obtient ou définit un tableau qui spécifie comment les points du champ PathPoints sont utilisés pour tracer le chemin. Le type d'objets dans ce tableau est spécifié par le drapeau R dans le champ PathPointFlags.

Valeur : les types de points de chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBasePointType\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype) |  |

