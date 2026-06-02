---
title: "TextRenderingHint"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Указывает качество рендеринга текста."
type: docs
weight: 115
url: /ru/java/com.aspose.imaging/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Указывает качество рендеринга текста.
## Поля

| Поле | Описание |
| --- | --- |
| [SystemDefault](#SystemDefault) | Каждый символ отрисовывается с использованием его глифового битмапа, с системным режимом рендеринга по умолчанию. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Каждый символ отрисовывается с использованием его глифового битмапа. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Каждый символ отрисовывается с использованием его глифового битмапа. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Каждый символ отрисовывается с использованием его сглаженного глифового битмапа с хинтингом. |
| [AntiAlias](#AntiAlias) | Каждый символ отрисовывается с использованием его сглаженного глифового битмапа без хинтинга. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Каждый символ отрисовывается с использованием его глифового ClearType битмапа с хинтингом. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Каждый символ отрисовывается с использованием его глифового битмапа, с системным режимом рендеринга по умолчанию. Текст будет отрисован с учётом любых настроек сглаживания шрифтов, выбранных пользователем для системы.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Каждый символ отрисовывается с использованием его глифового битмапа. Хинтинг используется для улучшения внешнего вида символов на штрихах и кривизне.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Каждый символ отрисовывается с использованием его глифового битмапа. Хинтинг не используется.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Каждый символ отрисовывается с использованием его сглаженного глифового битмапа с хинтингом. Качество значительно лучше благодаря сглаживанию, но требует большего расхода производительности.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Каждый символ отрисовывается с использованием его сглаженного глифового битмапа без хинтинга. Качество лучше благодаря сглаживанию. Различия в ширине штрихов могут быть заметны, поскольку хинтинг отключён.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Каждый символ отрисовывается с использованием его глифового ClearType битмапа с хинтингом. Наивысшая настройка качества. Используется для получения преимуществ функций шрифтов ClearType.

