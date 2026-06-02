---
title: "EmfPlusPathPointFlags"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Un entier non signé de 32 bits qui spécifie comment interpréter les points et les types de points associés définis par cet objet."
type: docs
weight: 38
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPathPointFlags extends System.Enum
```

Un entier non signé de 32 bits qui spécifie comment interpréter les points et les types de points associés définis par cet objet. C (1 bit) : Si le drapeau est activé, le tableau PathPoints spécifie des emplacements absolus dans l’espace de coordonnées avec des coordonnées entières de 16 bits. Si le drapeau est désactivé, le tableau PathPoints spécifie des emplacements absolus dans l’espace de coordonnées avec des coordonnées à virgule flottante de 32 bits. Remarque : si le drapeau P (ci‑dessous) est activé, ce drapeau PEUT être désactivé et DOIT être ignoré. R (1 bit) : Si le drapeau est activé, les types de points dans le tableau PathPointTypes sont spécifiés par des objets EmfPlusPathPointTypeRle (section 2.2.2.32), qui utilisent la compression par codage de longueur d’exécution (RLE), et/ou des objets EmfPlusPathPointType (section 2.2.2.31). Voir la section 3.1.6 de [MS-WMF] pour plus d’informations sur la compression RLE. Si le drapeau est désactivé, les types de points dans le tableau PathPointTypes sont spécifiés par des objets EmfPlusPathPointType. P (1 bit) : Si le drapeau est activé, chaque élément du tableau PathPoints spécifie un emplacement dans l’espace de coordonnées relatif à l’emplacement spécifié par l’élément précédent du tableau. Dans le cas du premier élément de PathPoints, on suppose un emplacement précédent aux coordonnées (0,0). Si le drapeau est désactivé, chaque élément du tableau PathPoints spécifie un emplacement absolu.
## Champs

| Champ | Description |
| --- | --- |
| [C](#C) | Le drapeau c |
| [R](#R) | Le drapeau r |
| [P](#P) | Le drapeau p |
### C {#C}
```
public static final short C
```


Le drapeau c

### R {#R}
```
public static final short R
```


Le drapeau r

### P {#P}
```
public static final short P
```


Le drapeau p

