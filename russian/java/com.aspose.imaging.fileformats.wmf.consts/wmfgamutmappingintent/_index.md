---
title: "WmfGamutMappingIntent"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление GamutMappingIntent указывает взаимосвязь между логическими и физическими цветами."
type: docs
weight: 20
url: /ru/java/com.aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfGamutMappingIntent extends System.Enum
```

Перечисление GamutMappingIntent указывает взаимосвязь между логическими и физическими цветами.
## Поля

| Поле | Описание |
| --- | --- |
| [LCS_GM_ABS_COLORIMETRIC](#LCS-GM-ABS-COLORIMETRIC) | Указывает, что белая точка ДОЛЖНА сохраняться. |
| [LCS_GM_BUSINESS](#LCS-GM-BUSINESS) | Указывает, что насыщенность ДОЛЖНА быть поддержана. |
| [LCS_GM_GRAPHICS](#LCS-GM-GRAPHICS) | Указывает, что колориметрическое соответствие ДОЛЖНО быть поддержано. |
| [LCS_GM_IMAGES](#LCS-GM-IMAGES) | Указывает, что контраст ДОЛЖЕН быть поддержан. |
### LCS_GM_ABS_COLORIMETRIC {#LCS-GM-ABS-COLORIMETRIC}
```
public static final int LCS_GM_ABS_COLORIMETRIC
```


Указывает, что точка белого ДОЛЖНА быть поддержана. Обычно используется, когда логические цвета ДОЛЖНЫ быть сопоставлены с их ближайшим физическим цветом в целевом цветовом охвате. Intent: Match ICC name: Absolute Colorimetric

### LCS_GM_BUSINESS {#LCS-GM-BUSINESS}
```
public static final int LCS_GM_BUSINESS
```


Указывает, что насыщенность ДОЛЖНА быть поддержана. Обычно используется для бизнес-диаграмм и других ситуаций, в которых дизеринг не требуется. Intent: Graphic ICC name: Saturation

### LCS_GM_GRAPHICS {#LCS-GM-GRAPHICS}
```
public static final int LCS_GM_GRAPHICS
```


Указывает, что колориметрическое соответствие ДОЛЖНО быть поддержано. Обычно используется для графических дизайнов и именованных цветов. Intent: Proof ICC name: Relative Colorimetric

### LCS_GM_IMAGES {#LCS-GM-IMAGES}
```
public static final int LCS_GM_IMAGES
```


Указывает, что контраст ДОЛЖЕН быть поддержан. Обычно используется для фотографий и естественных изображений. Intent: Picture ICC name: Perceptual

