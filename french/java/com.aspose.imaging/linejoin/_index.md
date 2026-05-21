---
title: "LineJoin"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Spécifie comment joindre des segments de ligne ou de courbe consécutifs dans un sous‑chemin de figure contenu dans un objet GraphicsPath."
type: docs
weight: 69
url: /fr/java/com.aspose.imaging/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

Spécifie comment joindre les segments de ligne ou de courbe consécutifs dans une figure (sous-chemin) contenue dans un objet `GraphicsPath`.
## Champs

| Champ | Description |
| --- | --- |
| [Miter](#Miter) | Spécifie une jointure en onglet. |
| [Bevel](#Bevel) | Spécifie une jointure biseautée. |
| [Round](#Round) | Spécifie une jointure circulaire. |
| [MiterClipped](#MiterClipped) | Spécifie une jointure en onglet. |
### Miter {#Miter}
```
public static final int Miter
```


Spécifie une jointure en onglet. Cela produit un coin aigu ou un coin tronqué, selon que la longueur de l'onglet dépasse la limite de l'onglet.

### Bevel {#Bevel}
```
public static final int Bevel
```


Spécifie une jointure biseautée. Cela produit un coin diagonal.

### Round {#Round}
```
public static final int Round
```


Spécifie une jointure circulaire. Cela produit un arc circulaire lisse entre les lignes.

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


Spécifie une jointure en onglet. Cela produit un coin aigu ou un coin biseauté, selon que la longueur de l'onglet dépasse la limite d'onglet.

