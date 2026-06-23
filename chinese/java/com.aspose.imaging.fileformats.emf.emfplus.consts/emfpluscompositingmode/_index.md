---
title: "EmfPlusCompositingMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "CompositingMode 枚举定义了将源颜色与背景颜色合成的模式。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingMode extends System.Enum
```

CompositingMode 枚举定义了将源颜色与背景颜色组合的模式。合成模式表示 alpha 混合的启用状态。
## 字段

| 字段 | 描述 |
| --- | --- |
| [CompositingModeSourceOver](#CompositingModeSourceOver) | 启用 alpha 混合，这表示在渲染颜色时，它会与背景颜色混合。 |
| [CompositingModeSourceCopy](#CompositingModeSourceCopy) | 禁用 alpha 混合，这意味着在渲染源颜色时，它会覆盖背景颜色。 |
### CompositingModeSourceOver {#CompositingModeSourceOver}
```
public static final byte CompositingModeSourceOver
```


启用 alpha 混合，这表示在渲染颜色时，它会与背景颜色混合。混合程度由被渲染颜色的 alpha 分量值决定。

### CompositingModeSourceCopy {#CompositingModeSourceCopy}
```
public static final byte CompositingModeSourceCopy
```


禁用 alpha 混合，这意味着在渲染源颜色时，它会覆盖背景颜色。

