---
title: "EmfPlusTextRenderingHint"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление TextRenderingHint определяет типы подсказок текста и сглаживания, которые влияют на качество отображения текста."
type: docs
weight: 52
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusTextRenderingHint extends System.Enum
```

Перечисление TextRenderingHint определяет типы подсказок текста и сглаживания, которые влияют на качество рендеринга текста.
## Поля

| Поле | Описание |
| --- | --- |
| [TextRenderingHintSystemDefault](#TextRenderingHintSystemDefault) | Указывает, что каждый символ текста ДОЛЖЕН отображаться с использованием настроек сглаживания шрифтов, сконфигурированных в операционной системе. |
| [TextRenderingHintSingleBitPerPixelGridFit](#TextRenderingHintSingleBitPerPixelGridFit) | Указывает, что каждый символ текста ДОЛЖЕН отображаться с использованием его растрового глифа. |
| [TextRenderingHintSingleBitPerPixel](#TextRenderingHintSingleBitPerPixel) | Указывает, что каждый символ текста ДОЛЖЕН отображаться с использованием его растрового глифа. |
| [TextRenderingHintAntialiasGridFit](#TextRenderingHintAntialiasGridFit) | Указывает, что каждый символ текста ДОЛЖЕН отображаться с использованием его антиалиасного растрового глифа со сглаживанием. |
| [TextRenderingHintAntialias](#TextRenderingHintAntialias) | Указывает, что каждый символ текста отображается с использованием его антиалиасного растрового глифа без подсказок. |
| [TextRenderingHintClearTypeGridFit](#TextRenderingHintClearTypeGridFit) | Указывает, что каждый символ текста ДОЛЖЕН отображаться с использованием его ClearType растрового глифа со сглаживанием. |
### TextRenderingHintSystemDefault {#TextRenderingHintSystemDefault}
```
public static final byte TextRenderingHintSystemDefault
```


Указывает, что каждый символ текста ДОЛЖЕН отображаться с использованием настроек сглаживания шрифтов, сконфигурированных в операционной системе.

### TextRenderingHintSingleBitPerPixelGridFit {#TextRenderingHintSingleBitPerPixelGridFit}
```
public static final byte TextRenderingHintSingleBitPerPixelGridFit
```


Указывает, что каждый символ текста ДОЛЖЕН отображаться с использованием его растрового глифа. Сглаживание МОЖЕТ использоваться для улучшения внешнего вида штрихов и кривизны глифов.

### TextRenderingHintSingleBitPerPixel {#TextRenderingHintSingleBitPerPixel}
```
public static final byte TextRenderingHintSingleBitPerPixel
```


Указывает, что каждый символ текста ДОЛЖЕН отображаться с использованием его растрового глифа. Сглаживание не используется.

### TextRenderingHintAntialiasGridFit {#TextRenderingHintAntialiasGridFit}
```
public static final byte TextRenderingHintAntialiasGridFit
```


Указывает, что каждый символ текста ДОЛЖЕН отображаться с использованием его антиалиасного растрового глифа со сглаживанием. Отображение имеет высокое качество благодаря антиалиасингу, но требует больших ресурсов.

### TextRenderingHintAntialias {#TextRenderingHintAntialias}
```
public static final byte TextRenderingHintAntialias
```


Указывает, что каждый символ текста отображается с использованием его антиалиасного растрового глифа без подсказок. Лучшее качество достигается за счёт антиалиасинга, но различия в ширине штрихов МОГУТ быть заметны, поскольку подсказки отключены.

### TextRenderingHintClearTypeGridFit {#TextRenderingHintClearTypeGridFit}
```
public static final byte TextRenderingHintClearTypeGridFit
```


Указывает, что каждый символ текста ДОЛЖЕН отображаться с использованием его ClearType растрового глифа со сглаживанием. Это настройка подсказок текста наивысшего качества, позволяющая использовать возможности шрифтов ClearType.

