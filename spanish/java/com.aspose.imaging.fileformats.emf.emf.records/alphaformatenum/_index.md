---
title: "EmfBlendFunction.AlphaFormatEnum"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Una estructura que especifica cómo se interpretan los píxeles fuente y destino con respecto a la transparencia alfa."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class EmfBlendFunction.AlphaFormatEnum extends System.Enum
```

Una estructura que especifica cómo se interpretan los píxeles fuente y destino con respecto a la transparencia alfa.
## Campos

| Campo | Descripción |
| --- | --- |
| [NotTransparency](#NotTransparency) | Los píxeles en el mapa de bits de origen no especifican transparencia alfa. |
| [AC_SRC_ALPHA](#AC-SRC-ALPHA) | Indica que el mapa de bits de origen tiene 32 bits por píxel y especifica un valor de transparencia alfa para cada píxel. |
### NotTransparency {#NotTransparency}
```
public static final byte NotTransparency
```


Los píxeles en el mapa de bits de origen no especifican transparencia alfa. En este caso, el valor SrcConstantAlpha determina la combinación de los mapas de bits de origen y destino. Observe que en las siguientes ecuaciones SrcConstantAlpha se divide por 255, lo que produce un valor en el rango de 0 a 1.

### AC_SRC_ALPHA {#AC-SRC-ALPHA}
```
public static final byte AC_SRC_ALPHA
```


Indica que el mapa de bits de origen tiene 32 bits por píxel y especifica un valor de transparencia alfa para cada píxel.

