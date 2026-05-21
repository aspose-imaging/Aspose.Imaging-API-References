---
title: "EmfRegionMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération RegionMode définit des valeurs utilisées avec EMR_SELECTCLIPPATH et EMR_EXTSELECTCLIPRGN spécifiant le chemin actuel ou une nouvelle région qui est combinée avec la région de découpage actuelle."
type: docs
weight: 39
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRegionMode extends System.Enum
```

L'énumération RegionMode définit des valeurs utilisées avec EMR\_SELECTCLIPPATH et EMR\_EXTSELECTCLIPRGN, spécifiant le chemin actuel ou une nouvelle région qui est combinée avec la région de découpage actuelle.
## Champs

| Champ | Description |
| --- | --- |
| [RGN_AND](#RGN-AND) | La nouvelle région de découpage inclut l'intersection (zones qui se chevauchent) de la région de découpage actuelle et du chemin actuel (ou de la nouvelle région). |
| [RGN_OR](#RGN-OR) | La nouvelle région de découpage inclut l'union (zones combinées) de la région de découpage actuelle et du chemin actuel (ou nouvelle région). |
| [RGN_XOR](#RGN-XOR) | La nouvelle région de découpage inclut l'union de la région de découpage actuelle et du chemin actuel (ou nouvelle région) mais sans les zones qui se chevauchent |
| [RGN_DIFF](#RGN-DIFF) | La nouvelle région de découpage inclut les zones de la région de découpage actuelle avec celles du chemin actuel (ou nouvelle région) exclues. |
| [RGN_COPY](#RGN-COPY) | La nouvelle région de découpage est le chemin actuel (ou la nouvelle région). |
### RGN_AND {#RGN-AND}
```
public static final int RGN_AND
```


La nouvelle région de découpage inclut l'intersection (zones qui se chevauchent) de la région de découpage actuelle et du chemin actuel (ou de la nouvelle région).

### RGN_OR {#RGN-OR}
```
public static final int RGN_OR
```


La nouvelle région de découpage inclut l'union (zones combinées) de la région de découpage actuelle et du chemin actuel (ou nouvelle région).

### RGN_XOR {#RGN-XOR}
```
public static final int RGN_XOR
```


La nouvelle région de découpage inclut l'union de la région de découpage actuelle et du chemin actuel (ou nouvelle région) mais sans les zones qui se chevauchent

### RGN_DIFF {#RGN-DIFF}
```
public static final int RGN_DIFF
```


La nouvelle région de découpage inclut les zones de la région de découpage actuelle avec celles du chemin actuel (ou nouvelle région) exclues.

### RGN_COPY {#RGN-COPY}
```
public static final int RGN_COPY
```


La nouvelle région de découpage est le chemin actuel (ou la nouvelle région).

