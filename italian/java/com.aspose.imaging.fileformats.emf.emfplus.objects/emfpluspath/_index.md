---
title: "EmfPlusPath"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusPath specifica una serie di segmenti di linee e curve che formano un percorso grafico."
type: docs
weight: 58
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusPath extends EmfPlusGraphicsObjectType
```

L'oggetto EmfPlusPath specifica una serie di segmenti di linee e curve che formano un percorso grafico. L'ordine dei punti dati Bezier è: punto iniziale, punto di controllo 1, punto di controllo 2 e punto finale. Per ulteriori informazioni vedere[MSDN - DrawBeziers].
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusPath()](#EmfPlusPath--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPathPointFlags()](#getPathPointFlags--) | Ottiene o imposta il conteggio dei punti del percorso, un intero senza segno a 32 bit che specifica come interpretare i punti e i tipi di punto associati definiti da questo oggetto. |
| [setPathPointFlags(short value)](#setPathPointFlags-short-) | Ottiene o imposta il conteggio dei punti del percorso, un intero senza segno a 32 bit che specifica come interpretare i punti e i tipi di punto associati definiti da questo oggetto. |
| [getPathPoints()](#getPathPoints--) | Ottiene o imposta un array di punti del percorso. Un array di punti PathPointCount che specificano il percorso. |
| [setPathPoints(PointF[] value)](#setPathPoints-com.aspose.imaging.PointF---) | Ottiene o imposta un array di punti del percorso. Un array di punti PathPointCount che specificano il percorso. |
| [getPathPointTypes()](#getPathPointTypes--) | Ottiene o imposta un array che specifica come i punti nel campo PathPoints vengono utilizzati per disegnare il percorso. |
| [setPathPointTypes(EmfPlusBasePointType[] value)](#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---) | Ottiene o imposta un array che specifica come i punti nel campo PathPoints vengono utilizzati per disegnare il percorso. |
### EmfPlusPath() {#EmfPlusPath--}
```
public EmfPlusPath()
```


### getPathPointFlags() {#getPathPointFlags--}
```
public short getPathPointFlags()
```


Ottiene o imposta il conteggio dei punti del percorso, un intero senza segno a 32 bit che specifica come interpretare i punti e i tipi di punto associati definiti da questo oggetto.

**Returns:**
short
### setPathPointFlags(short value) {#setPathPointFlags-short-}
```
public void setPathPointFlags(short value)
```


Ottiene o imposta il conteggio dei punti del percorso, un intero senza segno a 32 bit che specifica come interpretare i punti e i tipi di punto associati definiti da questo oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Ottiene o imposta un array di punti del percorso. Un array di punti PathPointCount che specificano il percorso. Il tipo di oggetti in questo array è specificato dal campo PathPointFlags, come segue: Se il flag P è impostato, i punti sono posizioni relative specificate da oggetti EmfPlusPointR (sezione 2.2.2.37). Se il flag P è non impostato e il flag C è impostato, i punti sono posizioni assolute specificate da oggetti EmfPlusPoint (sezione 2.2.2.35). Se sia il flag P sia il flag C sono non impostati, i punti sono posizioni assolute specificate da oggetti EmfPlusPointF (sezione 2.2.2.36).

**Returns:**
com.aspose.imaging.PointF[]
### setPathPoints(PointF[] value) {#setPathPoints-com.aspose.imaging.PointF---}
```
public void setPathPoints(PointF[] value)
```


Ottiene o imposta un array di punti del percorso. Un array di punti PathPointCount che specificano il percorso. Il tipo di oggetti in questo array è specificato dal campo PathPointFlags, come segue: Se il flag P è impostato, i punti sono posizioni relative specificate da oggetti EmfPlusPointR (sezione 2.2.2.37). Se il flag P è non impostato e il flag C è impostato, i punti sono posizioni assolute specificate da oggetti EmfPlusPoint (sezione 2.2.2.35). Se sia il flag P sia il flag C sono non impostati, i punti sono posizioni assolute specificate da oggetti EmfPlusPointF (sezione 2.2.2.36).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getPathPointTypes() {#getPathPointTypes--}
```
public EmfPlusBasePointType[] getPathPointTypes()
```


Ottiene o imposta un array che specifica come i punti nel campo PathPoints vengono utilizzati per disegnare il percorso. Il tipo di oggetti in questo array è specificato dal flag R nel campo PathPointFlags.

Valore: I tipi di punti del percorso.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType[]
### setPathPointTypes(EmfPlusBasePointType[] value) {#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---}
```
public void setPathPointTypes(EmfPlusBasePointType[] value)
```


Ottiene o imposta un array che specifica come i punti nel campo PathPoints vengono utilizzati per disegnare il percorso. Il tipo di oggetti in questo array è specificato dal flag R nel campo PathPointFlags.

Valore: I tipi di punti del percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusBasePointType\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype) |  |

