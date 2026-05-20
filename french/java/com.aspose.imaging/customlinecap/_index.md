---
title: "CustomLineCap"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Encapsule une extrémité de ligne personnalisée définie par l'utilisateur."
type: docs
weight: 35
url: /fr/java/com.aspose.imaging/customlinecap/
---
**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Encapsule une extrémité de ligne personnalisée définie par l'utilisateur.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-) | Initialise une nouvelle instance de la classe `CustomLineCap` avec le contour et le remplissage spécifiés. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-) | Initialise une nouvelle instance de la classe `CustomLineCap` à partir de l'énumération `LineCap` existante spécifiée avec le contour et le remplissage spécifiés. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-) | Initialise une nouvelle instance de la classe `CustomLineCap` à partir de l'énumération `LineCap` existante spécifiée avec le contour, le remplissage et le retrait spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillPath()](#getFillPath--) | Obtient l'objet qui définit le remplissage pour le cap personnalisé. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.imaging.GraphicsPath-) | Définit l'objet qui définit le remplissage du capuchon personnalisé. |
| [getStrokePath()](#getStrokePath--) | Obtient l'objet qui définit le contour du capuchon personnalisé. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.imaging.GraphicsPath-) | Définit l'objet qui définit le contour du capuchon personnalisé. |
| [getStrokeJoin()](#getStrokeJoin--) | Obtient l'énumération `LineJoin` qui détermine comment les lignes qui composent cet objet `CustomLineCap` sont jointes. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Définit l'énumération `LineJoin` qui détermine comment les lignes qui composent cet objet `CustomLineCap` sont jointes. |
| [getBaseCap()](#getBaseCap--) | Obtient l'énumération `LineCap` sur laquelle cet `CustomLineCap` est basé. |
| [setBaseCap(int value)](#setBaseCap-int-) | Définit l'énumération `LineCap` sur laquelle cet `CustomLineCap` est basé. |
| [getBaseInset()](#getBaseInset--) | Obtient la distance entre le capuchon et la ligne. |
| [setBaseInset(float value)](#setBaseInset-float-) | Définit la distance entre le capuchon et la ligne. |
| [getWidthScale()](#getWidthScale--) | Obtient la quantité par laquelle mettre à l'échelle cet objet de classe `CustomLineCap` par rapport à la largeur de l'objet `System.Drawing.Pen`. |
| [setWidthScale(float value)](#setWidthScale-float-) | Définit la quantité par laquelle mettre à l'échelle cet objet de classe `CustomLineCap` par rapport à la largeur de l'objet `System.Drawing.Pen`. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Définit les capuchons utilisés pour commencer et terminer les lignes qui composent ce capuchon personnalisé. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Obtient les capuchons utilisés pour commencer et terminer les lignes qui composent ce capuchon personnalisé. |
| [equals(Object o)](#equals-java.lang.Object-) | Vérifie si les objets sont égaux. |
| [hashCode()](#hashCode--) | Obtient le code de hachage de l'objet actuel. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Initialise une nouvelle instance de la classe `CustomLineCap` avec le contour et le remplissage spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un objet `GraphicsPath` qui définit le remplissage du capuchon personnalisé. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un objet `GraphicsPath` qui définit le contour du capuchon personnalisé. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Initialise une nouvelle instance de la classe `CustomLineCap` à partir de l'énumération `LineCap` existante spécifiée avec le contour et le remplissage spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un objet `GraphicsPath` qui définit le remplissage du capuchon personnalisé. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un objet `GraphicsPath` qui définit le contour du capuchon personnalisé. |
| baseCap | int | Le capuchon de ligne à partir duquel créer le capuchon personnalisé. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Initialise une nouvelle instance de la classe `CustomLineCap` à partir de l'énumération `LineCap` existante spécifiée avec le contour, le remplissage et le retrait spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un objet `GraphicsPath` qui définit le remplissage du capuchon personnalisé. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un objet `GraphicsPath` qui définit le contour du capuchon personnalisé. |
| baseCap | int | Le capuchon de ligne à partir duquel créer le capuchon personnalisé. |
| baseInset | float | La distance entre le capuchon et la ligne. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Obtient l'objet qui définit le remplissage pour le cap personnalisé.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the fill for the custom cap.
### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.imaging.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Définit l'objet qui définit le remplissage du capuchon personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | L'objet qui définit le remplissage du capuchon personnalisé. |

### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Obtient l'objet qui définit le contour du capuchon personnalisé.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the outline of the custom cap.
### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.imaging.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Définit l'objet qui définit le contour du capuchon personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | L'objet qui définit le contour du capuchon personnalisé. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Obtient l'énumération `LineJoin` qui détermine comment les lignes qui composent cet objet `CustomLineCap` sont jointes.

**Returns:**
int - L'énumération `LineJoin` que cet objet `CustomLineCap` utilise pour joindre les lignes.
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Définit l'énumération `LineJoin` qui détermine comment les lignes qui composent cet objet `CustomLineCap` sont jointes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'énumération `LineJoin` que cet objet `CustomLineCap` utilise pour joindre les lignes. |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Obtient l'énumération `LineCap` sur laquelle cet `CustomLineCap` est basé.

**Returns:**
int - L'énumération `LineCap` sur laquelle cet `CustomLineCap` est basé.
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Définit l'énumération `LineCap` sur laquelle cet `CustomLineCap` est basé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'énumération `LineCap` sur laquelle cet `CustomLineCap` est basé. |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Obtient la distance entre le capuchon et la ligne.

**Returns:**
float - La distance entre le début du cap et la fin de la ligne.
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Définit la distance entre le capuchon et la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La distance entre le début du cap et la fin de la ligne. |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Obtient la quantité par laquelle mettre à l'échelle cet objet de classe `CustomLineCap` par rapport à la largeur de l'objet `System.Drawing.Pen`.

**Returns:**
float - La quantité par laquelle mettre à l'échelle le cap.
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Définit la quantité par laquelle mettre à l'échelle cet objet de classe `CustomLineCap` par rapport à la largeur de l'objet `System.Drawing.Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La quantité par laquelle mettre à l'échelle le cap. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Définit les capuchons utilisés pour commencer et terminer les lignes qui composent ce capuchon personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startCap | int | L'énumération `LineCap` utilisée au début d'une ligne dans ce cap. |
| endCap | int | L'énumération `LineCap` utilisée à la fin d'une ligne dans ce cap. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Obtient les capuchons utilisés pour commencer et terminer les lignes qui composent ce capuchon personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startCap | int[] | L'énumération `LineCap` utilisée au début d'une ligne dans ce cap. |
| endCap | int[] | L'énumération `LineCap` utilisée à la fin d'une ligne dans ce cap. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Vérifie si les objets sont égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | L'autre objet. |

**Returns:**
boolean - Le résultat de la comparaison d'égalité.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de l'objet actuel.

**Returns:**
int - Le code de hachage.
