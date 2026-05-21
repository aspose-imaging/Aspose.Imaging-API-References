---
title: "EmfColorSpace"
second_title: "Aspose.Imaging för Java API-referens"
description: "ColorSpace‑uppräkningen används för att ange när färgprovning ska slås på och av samt när transformationer ska tas bort."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfColorSpace extends System.Enum
```

ColorSpace-enumerationen används för att ange när färgprovning ska slås på och av, samt när transformationer ska tas bort.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CS_ENABLE](#CS-ENABLE) | Mappar färger till målapparatens färgomfång. |
| [CS_DISABLE](#CS-DISABLE) | Inaktiverar färgprovning. |
| [CS_DELETE_TRANSFORM](#CS-DELETE-TRANSFORM) | Om färghantering är aktiverad för målprofilen, inaktiveras den och den sammansatta transformationen tas bort. |
### CS_ENABLE {#CS-ENABLE}
```
public static final int CS_ENABLE
```


Mappar färger till målapparatens färgomfång. Detta möjliggör färgprovning. Alla efterföljande ritkommandon till uppspelningsenhetens kontext kommer att rendera färger som de skulle visas på målapparaten.

### CS_DISABLE {#CS-DISABLE}
```
public static final int CS_DISABLE
```


Inaktiverar färgprovning.

### CS_DELETE_TRANSFORM {#CS-DELETE-TRANSFORM}
```
public static final int CS_DELETE_TRANSFORM
```


Om färghantering är aktiverad för målprofilen, inaktiveras den och den sammansatta transformationen tas bort.

