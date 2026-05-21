---
title: "EmfBlendFunction.AlphaFormatEnum"
second_title: "Aspose.Imaging för Java API-referens"
description: "En struktur som specificerar hur käll- och destinationspixlar tolkas med avseende på alfa‑transparens."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class EmfBlendFunction.AlphaFormatEnum extends System.Enum
```

En struktur som specificerar hur käll- och destinationspixlar tolkas med avseende på alfa‑transparens.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [NotTransparency](#NotTransparency) | Pixlarna i källbitmapen specificerar inte alfa‑transparens. |
| [AC_SRC_ALPHA](#AC-SRC-ALPHA) | Indikerar att källbitmapen har 32 bitar per pixel och specificerar ett alfa‑transparensvärde för varje pixel. |
### NotTransparency {#NotTransparency}
```
public static final byte NotTransparency
```


Pixlarna i källbitmapen specificerar inte alfa‑transparens. I detta fall bestämmer värdet SrcConstantAlpha blandningen av käll- och destinationsbitmaparna. Observera att i följande ekvationer delas SrcConstantAlpha med 255, vilket ger ett värde i intervallet 0 till 1.

### AC_SRC_ALPHA {#AC-SRC-ALPHA}
```
public static final byte AC_SRC_ALPHA
```


Indikerar att källbitmapen har 32 bitar per pixel och specificerar ett alfa‑transparensvärde för varje pixel.

