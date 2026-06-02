---
title: "EmfPointEnum"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération Point est utilisée pour spécifier comment un point doit être utilisé dans un appel de dessin."
type: docs
weight: 35
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPointEnum extends System.Enum
```

L'énumération Point est utilisée pour spécifier comment un point doit être utilisé dans un appel de dessin.
## Champs

| Champ | Description |
| --- | --- |
| [PT_CLOSEFIGURE](#PT-CLOSEFIGURE) | Un type PT\_LINETO ou PT\_BEZIERTO peut être combiné avec cette valeur en utilisant l'opérateur binaire OU pour indiquer que le point correspondant est le dernier point d'une figure et que la figure est fermée |
| [PT_LINETO](#PT-LINETO) | Spécifie qu'une ligne doit être tracée depuis la position actuelle jusqu'à ce point, qui devient alors la nouvelle position actuelle |
| [PT_BEZIERTO](#PT-BEZIERTO) | Spécifie que ce point est un point de contrôle ou un point final pour une courbe de Bézier. |
| [PT_MOVETO](#PT-MOVETO) | Spécifie que ce point démarre une figure disjointe. |
### PT_CLOSEFIGURE {#PT-CLOSEFIGURE}
```
public static final byte PT_CLOSEFIGURE
```


Un type PT\_LINETO ou PT\_BEZIERTO peut être combiné avec cette valeur en utilisant l'opérateur binaire OU pour indiquer que le point correspondant est le dernier point d'une figure et que la figure est fermée

### PT_LINETO {#PT-LINETO}
```
public static final byte PT_LINETO
```


Spécifie qu'une ligne doit être tracée depuis la position actuelle jusqu'à ce point, qui devient alors la nouvelle position actuelle

### PT_BEZIERTO {#PT-BEZIERTO}
```
public static final byte PT_BEZIERTO
```


Spécifie que ce point est un point de contrôle ou un point final pour une courbe de Bézier.

### PT_MOVETO {#PT-MOVETO}
```
public static final byte PT_MOVETO
```


Spécifie que ce point démarre une figure disjointe. Ce point devient la nouvelle position actuelle.

