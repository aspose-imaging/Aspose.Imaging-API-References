---
title: "EmfPlusDriverStringOptionsFlags"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les indicateurs DriverStringOptions spécifient les propriétés du positionnement et du rendu du texte graphique."
type: docs
weight: 21
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusDriverStringOptionsFlags extends System.Enum
```

Les indicateurs DriverStringOptions spécifient les propriétés du positionnement et du rendu du texte graphique. Ces indicateurs peuvent être combinés pour spécifier plusieurs options.

--------------------

La sortie de texte graphique est spécifiée dans les enregistrements [EmfPlusDrawDriverString](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring).
## Champs

| Champ | Description |
| --- | --- |
| [DriverStringOptionsCmapLookup](#DriverStringOptionsCmapLookup) | Si défini, les positions des glyphes de caractères DOIVENT être spécifiées dans une table de recherche de carte de caractères. |
| [DriverStringOptionsVertical](#DriverStringOptionsVertical) | Si défini, la chaîne DOIT être rendue verticalement. |
| [DriverStringOptionsRealizedAdvance](#DriverStringOptionsRealizedAdvance) | Si défini, les positions des glyphes de caractères DOIVENT être calculées par rapport à la position du premier glyphe. |
| [DriverStringOptionsLimitSubpixel](#DriverStringOptionsLimitSubpixel) | Si défini, moins de mémoire DOIT être utilisée pour mettre en cache les glyphes anti-aliasés, ce qui produit un rendu de texte de moindre qualité. |
### DriverStringOptionsCmapLookup {#DriverStringOptionsCmapLookup}
```
public static final int DriverStringOptionsCmapLookup
```


Si défini, les positions des glyphes de caractères DOIVENT être spécifiées dans une table de recherche de carte de caractères. Si désactivé, les positions des glyphes DOIVENT être obtenues à partir d'un tableau de coordonnées.

### DriverStringOptionsVertical {#DriverStringOptionsVertical}
```
public static final int DriverStringOptionsVertical
```


Si défini, la chaîne DOIT être rendue verticalement. Si désactivé, la chaîne DOIT être rendue horizontalement.

### DriverStringOptionsRealizedAdvance {#DriverStringOptionsRealizedAdvance}
```
public static final int DriverStringOptionsRealizedAdvance
```


Si défini, les positions des glyphes de caractères DOIVENT être calculées par rapport à la position du premier glyphe. Si désactivé, les positions des glyphes DOIVENT être obtenues à partir d'un tableau de coordonnées.

### DriverStringOptionsLimitSubpixel {#DriverStringOptionsLimitSubpixel}
```
public static final int DriverStringOptionsLimitSubpixel
```


Si défini, moins de mémoire DOIT être utilisée pour mettre en cache les glyphes anti-aliasés, ce qui produit un rendu de texte de moindre qualité. Si désactivé, plus de mémoire DOIT être utilisée, ce qui produit un rendu de texte de meilleure qualité.

