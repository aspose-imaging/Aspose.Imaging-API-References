---
title: "EmfBlendFunction.AlphaFormatEnum"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Структура, определяющая, как интерпретируются пиксели исходного и целевого изображений относительно альфа-прозрачности."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class EmfBlendFunction.AlphaFormatEnum extends System.Enum
```

Структура, определяющая, как интерпретируются пиксели исходного и целевого изображений относительно альфа-прозрачности.
## Поля

| Поле | Описание |
| --- | --- |
| [NotTransparency](#NotTransparency) | Пиксели в исходном битмапе не задают альфа‑прозрачность. |
| [AC_SRC_ALPHA](#AC-SRC-ALPHA) | Указывает, что исходный битмап имеет 32 бита на пиксель и задает значение альфа‑прозрачности для каждого пикселя. |
### NotTransparency {#NotTransparency}
```
public static final byte NotTransparency
```


Пиксели в исходном битмапе не задают альфа‑прозрачность. В этом случае значение SrcConstantAlpha определяет смешивание исходного и целевого битмапов. Обратите внимание, что в последующих уравнениях SrcConstantAlpha делится на 255, что дает значение в диапазоне от 0 до 1.

### AC_SRC_ALPHA {#AC-SRC-ALPHA}
```
public static final byte AC_SRC_ALPHA
```


Указывает, что исходный битмап имеет 32 бита на пиксель и задает значение альфа‑прозрачности для каждого пикселя.

