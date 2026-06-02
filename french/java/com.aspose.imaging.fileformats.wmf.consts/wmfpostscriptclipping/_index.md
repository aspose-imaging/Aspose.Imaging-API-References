---
title: "WmfPostScriptClipping"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération PostScriptClipping définit les fonctions qui peuvent être appliquées au chemin de découpage utilisé pour la sortie PostScript."
type: docs
weight: 32
url: /fr/java/com.aspose.imaging.fileformats.wmf.consts/wmfpostscriptclipping/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfPostScriptClipping extends System.Enum
```

L'énumération PostScriptClipping définit les fonctions qui peuvent être appliquées au chemin de découpage utilisé pour la sortie PostScript.
## Champs

| Champ | Description |
| --- | --- |
| [CLIP_SAVE](#CLIP-SAVE) | Enregistre le chemin de découpage PostScript actuel. |
| [CLIP_RESTORE](#CLIP-RESTORE) | Restaure le chemin de découpage PostScript au dernier chemin de découpage qui a été enregistré par une fonction CLIP\_SAVE précédente appliquée par un enregistrement CLIP\_TO\_PATH (section 2.3.6.6). |
| [CLIP_INCLUSIVE](#CLIP-INCLUSIVE) | Intersecte le chemin de découpe PostScript actuel avec le chemin de découpe actuel et enregistre le résultat comme le nouveau chemin de découpe PostScript. |
### CLIP_SAVE {#CLIP-SAVE}
```
public static final int CLIP_SAVE
```


Enregistre le chemin de découpage PostScript actuel.

### CLIP_RESTORE {#CLIP-RESTORE}
```
public static final int CLIP_RESTORE
```


Restaure le chemin de découpage PostScript au dernier chemin de découpage qui a été enregistré par une fonction CLIP\_SAVE précédente appliquée par un enregistrement CLIP\_TO\_PATH (section 2.3.6.6).

### CLIP_INCLUSIVE {#CLIP-INCLUSIVE}
```
public static final int CLIP_INCLUSIVE
```


Intersecte le chemin de découpe PostScript actuel avec le chemin de découpe actuel et enregistre le résultat comme le nouveau chemin de découpe PostScript.

