---
title: "EmfBlendFunction.AlphaFormatEnum"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Une structure qui spécifie comment les pixels source et destination sont interprétés par rapport à la transparence alpha."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class EmfBlendFunction.AlphaFormatEnum extends System.Enum
```

Une structure qui spécifie comment les pixels source et destination sont interprétés par rapport à la transparence alpha.
## Champs

| Champ | Description |
| --- | --- |
| [NotTransparency](#NotTransparency) | Les pixels du bitmap source ne spécifient pas de transparence alpha. |
| [AC_SRC_ALPHA](#AC-SRC-ALPHA) | Indique que le bitmap source est de 32 bits par pixel et spécifie une valeur de transparence alpha pour chaque pixel. |
### NotTransparency {#NotTransparency}
```
public static final byte NotTransparency
```


Les pixels du bitmap source ne spécifient pas de transparence alpha. Dans ce cas, la valeur SrcConstantAlpha détermine le mélange des bitmaps source et destination. Notez que dans les équations suivantes, SrcConstantAlpha est divisé par 255, ce qui produit une valeur comprise entre 0 et 1.

### AC_SRC_ALPHA {#AC-SRC-ALPHA}
```
public static final byte AC_SRC_ALPHA
```


Indique que le bitmap source est de 32 bits par pixel et spécifie une valeur de transparence alpha pour chaque pixel.

