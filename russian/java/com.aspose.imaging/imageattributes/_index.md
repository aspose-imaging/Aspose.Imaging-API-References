---
title: "ImageAttributes"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект com.aspose.imaging.ImageAttributes содержит информацию о том, как цвета растровых изображений и метафайлов изменяются во время рендеринга."
type: docs
weight: 57
url: /ru/java/com.aspose.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Объект `com.aspose.imaging.ImageAttributes` содержит информацию о том, как цвета битмапа и метафайла изменяются во время рендеринга. Объект `com.aspose.imaging.ImageAttributes` поддерживает несколько настроек коррекции цвета, включая матрицы коррекции цвета, матрицы коррекции в градациях серого, значения гамма‑коррекции, таблицы сопоставления цветов и пороговые значения цвета. Во время рендеринга цвета могут быть скорректированы, затемнены, осветлены и удалены. Чтобы применить такие изменения, инициализируйте объект `com.aspose.imaging.ImageAttributes` и передайте путь к этому объекту `com.aspose.imaging.ImageAttributes` (а также путь к [Image](../../com.aspose.imaging/image)) в метод drawImage.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Инициализирует новый экземпляр класса `com.aspose.imaging.ImageAttributes`. |
## Методы

| Метод | Описание |
| --- | --- |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.imaging.ColorMatrix-) | Устанавливает матрицу коррекции цвета для категории по умолчанию. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-) | Устанавливает матрицу коррекции цвета для категории по умолчанию. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | Устанавливает матрицу коррекции цвета для указанной категории. |
| [clearColorMatrix()](#clearColorMatrix--) | Очищает матрицу коррекции цвета для категории по умолчанию. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Очищает матрицу коррекции цвета для указанной категории. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-) | Устанавливает матрицу коррекции цвета и матрицу коррекции в градациях серого для категории по умолчанию. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-) | Устанавливает матрицу коррекции цвета и матрицу коррекции в градациях серого для категории по умолчанию. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | Устанавливает матрицу коррекции цвета и матрицу коррекции в градациях серого для указанной категории. |
| [setThreshold(float threshold)](#setThreshold-float-) | Устанавливает порог (диапазон прозрачности) для категории по умолчанию. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Устанавливает порог (диапазон прозрачности) для указанной категории. |
| [clearThreshold()](#clearThreshold--) | Очищает значение порога для категории по умолчанию. |
| [clearThreshold(int type)](#clearThreshold-int-) | Очищает значение порога для указанной категории. |
| [setGamma(float gamma)](#setGamma-float-) | Устанавливает значение гаммы для категории по умолчанию. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Устанавливает значение гаммы для указанной категории. |
| [clearGamma()](#clearGamma--) | Отключает гамма‑коррекцию для категории по умолчанию. |
| [clearGamma(int type)](#clearGamma-int-) | Отключает гамма‑коррекцию для указанной категории. |
| [setNoOp()](#setNoOp--) | Выключает коррекцию цвета для категории по умолчанию. |
| [setNoOp(int type)](#setNoOp-int-) | Выключает коррекцию цвета для указанной категории. |
| [clearNoOp()](#clearNoOp--) | Очищает настройку NoOp для категории по умолчанию. |
| [clearNoOp(int type)](#clearNoOp-int-) | Очищает настройку NoOp для указанной категории. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Устанавливает цветовой ключ для категории по умолчанию. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-) | Устанавливает цветовой ключ (диапазон прозрачности) для указанной категории. |
| [clearColorKey()](#clearColorKey--) | Очищает цветовой ключ (диапазон прозрачности) для категории по умолчанию. |
| [clearColorKey(int type)](#clearColorKey-int-) | Очищает цветовой ключ (диапазон прозрачности) для указанной категории. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Устанавливает канал вывода CMYK (голубой‑пурпурный‑жёлтый‑чёрный) для категории по умолчанию. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Устанавливает канал вывода CMYK (cyan-magenta-yellow-black) для указанной категории. |
| [clearOutputChannel()](#clearOutputChannel--) | Очищает настройку канала вывода CMYK (cyan-magenta-yellow-black) для категории по умолчанию. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Очищает настройку канала вывода (cyan-magenta-yellow-black) для указанной категории. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Устанавливает файл цветового профиля канала вывода для категории по умолчанию. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Устанавливает файл цветового профиля канала вывода для указанной категории. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Очищает настройку цветового профиля канала вывода для категории по умолчанию. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Очищает настройку цветового профиля канала вывода для указанной категории. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.imaging.ColorMap---) | Устанавливает таблицу переопределения цветов для категории по умолчанию. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.imaging.ColorMap---int-) | Устанавливает таблицу переопределения цветов для указанной категории. |
| [clearRemapTable()](#clearRemapTable--) | Очищает таблицу переопределения цветов для категории по умолчанию. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Очищает таблицу переопределения цветов для указанной категории. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.imaging.ColorMap---) | Устанавливает таблицу переопределения цветов для категории кисти. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Очищает таблицу переопределения цветов кисти этого объекта `com.aspose.imaging.ImageAttributes`. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Устанавливает режим обтекания, который используется для определения способа наложения текстуры на форму или на границы формы. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.imaging.Color-) | Устанавливает режим обтекания и цвет, используемые для определения способа наложения текстуры на форму или на границы формы. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.imaging.Color-boolean-) | Устанавливает режим обтекания и цвет, используемые для определения способа наложения текстуры на форму или на границы формы. |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Инициализирует новый экземпляр класса `com.aspose.imaging.ImageAttributes`.

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Устанавливает матрицу коррекции цвета для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Матрица коррекции цвета. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Устанавливает матрицу коррекции цвета для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Матрица коррекции цвета. |
| флаги | int | Элемент `Aspose.Imaging.ColorMatrixFlag`, который указывает тип изображения и цвета, которые будут затронуты матрицей коррекции цвета. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Устанавливает матрицу коррекции цвета для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Матрица коррекции цвета. |
| режим | int | Элемент `Aspose.Imaging.ColorMatrixFlag`, который указывает тип изображения и цвета, которые будут затронуты матрицей коррекции цвета. |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, который указывает категорию, для которой устанавливается матрица коррекции цвета. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Очищает матрицу коррекции цвета для категории по умолчанию.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Очищает матрицу коррекции цвета для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, который указывает категорию, для которой очищается матрица коррекции цвета. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Устанавливает матрицу коррекции цвета и матрицу коррекции в градациях серого для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Матрица коррекции цвета. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Матрица коррекции градаций серого. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Устанавливает матрицу коррекции цвета и матрицу коррекции в градациях серого для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Матрица коррекции цвета. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Матрица коррекции градаций серого. |
| флаги | int | Элемент `Aspose.Imaging.ColorMatrixFlag`, который указывает тип изображения и цвета, которые будут затронуты матрицами коррекции цвета и градаций серого. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Устанавливает матрицу коррекции цвета и матрицу коррекции в градациях серого для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Матрица коррекции цвета. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Матрица коррекции градаций серого. |
| режим | int | Элемент `Aspose.Imaging.ColorMatrixFlag`, который указывает тип изображения и цвета, которые будут затронуты матрицами коррекции цвета и градаций серого. |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, который указывает категорию, для которой устанавливаются матрицы коррекции цвета и градаций серого. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Устанавливает порог (диапазон прозрачности) для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | float | Вещественное число, указывающее значение порога. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Устанавливает порог (диапазон прозрачности) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | float | Значение порога от 0.0 до 1.0, используемое в качестве точки разрыва для сортировки цветов, которые будут сопоставлены либо с максимальным, либо с минимальным значением. |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой задаётся порог цвета. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Очищает значение порога для категории по умолчанию.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Очищает значение порога для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой очищается порог. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Устанавливает значение гаммы для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| гамма | float | Значение гамма‑коррекции. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Устанавливает значение гаммы для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| гамма | float | Значение гамма‑коррекции. |
| тип | int | Элемент перечисления `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой задаётся значение гаммы. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Отключает гамма‑коррекцию для категории по умолчанию.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Отключает гамма‑коррекцию для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой отключена гамма‑коррекция. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Выключает коррекцию цвета для категории по умолчанию.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Выключает коррекцию цвета для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой отключена коррекция цвета. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Очищает настройку NoOp для категории по умолчанию.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Очищает настройку NoOp для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой очищается настройка NoOp. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Устанавливает цветовой ключ для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | Низкое значение цветового ключа. |
| colorHigh | [Color](../../com.aspose.imaging/color) | Высокое значение цветового ключа. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Устанавливает цветовой ключ (диапазон прозрачности) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | Низкое значение цветового ключа. |
| colorHigh | [Color](../../com.aspose.imaging/color) | Высокое значение цветового ключа. |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой задаётся цветовой ключ. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Очищает цветовой ключ (диапазон прозрачности) для категории по умолчанию.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Очищает цветовой ключ (диапазон прозрачности) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой очищается цветовой ключ. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Устанавливает канал вывода CMYK (голубой‑пурпурный‑жёлтый‑чёрный) для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| флаги | int | Элемент `Aspose.Imaging.ColorChannelFlag`, указывающий выходной канал. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Устанавливает канал вывода CMYK (cyan-magenta-yellow-black) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| флаги | int | Элемент `Aspose.Imaging.ColorChannelFlag`, указывающий выходной канал. |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой задаётся выходной канал. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Очищает настройку канала вывода CMYK (cyan-magenta-yellow-black) для категории по умолчанию.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Очищает настройку канала вывода (cyan-magenta-yellow-black) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой очищается настройка выходного канала. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Устанавливает файл цветового профиля канала вывода для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Путь к файлу цветового профиля. Если файл цветового профиля находится в каталоге %SystemRoot%\\System32\\Spool\\Drivers\\Color, этот параметр может быть именем файла. В противном случае параметр должен содержать полностью квалифицированный путь. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Устанавливает файл цветового профиля канала вывода для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Путь к файлу цветового профиля. Если файл цветового профиля находится в каталоге %SystemRoot%\\System32\\Spool\\Drivers\\Color, этот параметр может быть именем файла. В противном случае параметр должен содержать полностью квалифицированный путь. |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой задаётся файл цветового профиля выходного канала. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Очищает настройку цветового профиля канала вывода для категории по умолчанию.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Очищает настройку цветового профиля канала вывода для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой очищается настройка профиля выходного канала. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Устанавливает таблицу переопределения цветов для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | Массив пар цветов типа `com.aspose.imaging.ColorMap`. Каждая пара цветов содержит существующий цвет (первое значение) и цвет, к которому он будет сопоставлен (второе значение). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Устанавливает таблицу переопределения цветов для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | Массив пар цветов типа `com.aspose.imaging.ColorMap`. Каждая пара цветов содержит существующий цвет (первое значение) и цвет, к которому он будет сопоставлен (второе значение). |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой задаётся таблица переназначения цветов. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Очищает таблицу переопределения цветов для категории по умолчанию.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Очищает таблицу переопределения цветов для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int | Элемент `Aspose.Imaging.ColorAdjustType`, указывающий категорию, для которой очищается таблица переназначения. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Устанавливает таблицу переопределения цветов для категории кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | Массив объектов `com.aspose.imaging.ColorMap`. |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Очищает таблицу переопределения цветов кисти этого объекта `com.aspose.imaging.ImageAttributes`.

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Устанавливает режим обтекания, используемый для определения способа заполнять текстуру по поверхности фигуры или на её границах. Текстура заполняет фигуру, когда её размер меньше размера заполняемой фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| режим | int | Элемент `Aspose.Imaging.WrapMode`, который определяет, как повторяющиеся копии изображения используются для заполнения области плиткой. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.imaging.Color-}
```
public void setWrapMode(int mode, Color color)
```


Устанавливает режим обтекания и цвет, используемые для определения того, как текстура будет заполнять форму плиткой, в том числе по границам формы. Текстура заполняет форму плиткой, когда её размер меньше размера заполняемой формы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| режим | int | Элемент `Aspose.Imaging.WrapMode`, который определяет, как повторяющиеся копии изображения используются для заполнения области плиткой. |
| color | [Color](../../com.aspose.imaging/color) | `com.aspose.imaging.ImageAttributes` объект, который задаёт цвет пикселей за пределами отрисованного изображения. Этот цвет виден, если параметр режима установлен в `WrapMode.Clamp` и исходный прямоугольник, переданный в DrawImage, больше самого изображения. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.imaging.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Устанавливает режим обтекания и цвет, используемые для определения того, как текстура будет заполнять форму плиткой, в том числе по границам формы. Текстура заполняет форму плиткой, когда её размер меньше размера заполняемой формы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| режим | int | Элемент `Aspose.Imaging.WrapMode`, который определяет, как повторяющиеся копии изображения используются для заполнения области плиткой. |
| color | [Color](../../com.aspose.imaging/color) | Объект цвета, который задаёт цвет пикселей за пределами отрисованного изображения. Этот цвет виден, если параметр режима установлен в `WrapMode.Clamp` и исходный прямоугольник, переданный в DrawImage, больше самого изображения. |
| зажим | boolean | Этот параметр не оказывает влияния. Установите его в false. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
