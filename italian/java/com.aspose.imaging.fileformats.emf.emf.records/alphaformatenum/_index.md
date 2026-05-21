---
title: "EmfBlendFunction.AlphaFormatEnum"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Una struttura che specifica come i pixel sorgente e di destinazione sono interpretati rispetto alla trasparenza alfa."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class EmfBlendFunction.AlphaFormatEnum extends System.Enum
```

Una struttura che specifica come i pixel sorgente e di destinazione sono interpretati rispetto alla trasparenza alfa.
## Campi

| Campo | Descrizione |
| --- | --- |
| [NotTransparency](#NotTransparency) | I pixel nella bitmap di origine non specificano la trasparenza alfa. |
| [AC_SRC_ALPHA](#AC-SRC-ALPHA) | Indica che la bitmap di origine è a 32 bit per pixel e specifica un valore di trasparenza alfa per ogni pixel. |
### NotTransparency {#NotTransparency}
```
public static final byte NotTransparency
```


I pixel nella bitmap di origine non specificano la trasparenza alfa. In questo caso, il valore SrcConstantAlpha determina la fusione delle bitmap di origine e destinazione. Nota che nelle seguenti equazioni SrcConstantAlpha è diviso per 255, producendo un valore nell'intervallo da 0 a 1.

### AC_SRC_ALPHA {#AC-SRC-ALPHA}
```
public static final byte AC_SRC_ALPHA
```


Indica che la bitmap di origine è a 32 bit per pixel e specifica un valore di trasparenza alfa per ogni pixel.

