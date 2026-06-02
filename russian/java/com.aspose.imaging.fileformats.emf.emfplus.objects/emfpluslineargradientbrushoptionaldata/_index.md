---
title: "EmfPlusLinearGradientBrushOptionalData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusLinearGradientBrushOptionalData задает дополнительные данные для линейной градиентной кисти."
type: docs
weight: 54
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLinearGradientBrushOptionalData extends EmfPlusStructureObjectType
```

Объект EmfPlusLinearGradientBrushOptionalData задает дополнительные данные для линейной градиентной кисти.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для линейной градиентной кисти. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для линейной градиентной кисти. |
| [getBlendPattern()](#getBlendPattern--) | Получает или задает необязательный шаблон смешивания для линейной градиентной кисти. |
| [setBlendPattern(EmfPlusBlendBase[] value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---) | Получает или задает необязательный шаблон смешивания для линейной градиентной кисти. |
| [getBlendPatternAsPresetColors()](#getBlendPatternAsPresetColors--) | Получает шаблон смешивания в виде предустановленных цветов. |
| [getBlendPatternAsBlendFactorsH()](#getBlendPatternAsBlendFactorsH--) | Получает шаблон смешивания в виде факторов смешивания h. |
| [getBlendPatternAsBlendFactorsV()](#getBlendPatternAsBlendFactorsV--) | Получает шаблон смешивания в виде факторов смешивания v. |
### EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для линейной градиентной кисти. Это поле ДОЛЖНО присутствовать, если флаг BrushDataTransform установлен в поле BrushDataFlags объекта EmfPlusLinearGradientBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для линейной градиентной кисти. Это поле ДОЛЖНО присутствовать, если флаг BrushDataTransform установлен в поле BrushDataFlags объекта EmfPlusLinearGradientBrushData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase[] getBlendPattern()
```


Получает или задает необязательный шаблон смешивания для линейной градиентной кисти. Если это поле присутствует, оно ДОЛЖНО содержать либо объект EmfPlusBlendColors (раздел 2.2.2.4), либо один или два объекта EmfPlusBlendFactors (раздел 2.2.2.5), но НЕ ДОЛЖНО содержать оба. Таблица ниже показывает допустимые комбинации флагов BrushData объекта EmfPlusLinearGradientBrushData и соответствующие шаблоны смешивания: EmfPlusBlendFactors

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase[]
### setBlendPattern(EmfPlusBlendBase[] value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---}
```
public void setBlendPattern(EmfPlusBlendBase[] value)
```


Получает или задает необязательный шаблон смешивания для линейной градиентной кисти. Если это поле присутствует, оно ДОЛЖНО содержать либо объект EmfPlusBlendColors (раздел 2.2.2.4), либо один или два объекта EmfPlusBlendFactors (раздел 2.2.2.5), но НЕ ДОЛЖНО содержать оба. Таблица ниже показывает допустимые комбинации флагов BrushData объекта EmfPlusLinearGradientBrushData и соответствующие шаблоны смешивания: EmfPlusBlendFactors

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusBlendBase\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getBlendPatternAsPresetColors() {#getBlendPatternAsPresetColors--}
```
public EmfPlusBlendColors getBlendPatternAsPresetColors()
```


Получает шаблон смешивания в виде предустановленных цветов.

Значение: шаблон смешивания в виде предустановленных цветов.

**Returns:**
[EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors)
### getBlendPatternAsBlendFactorsH() {#getBlendPatternAsBlendFactorsH--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsH()
```


Получает шаблон смешивания в виде факторов смешивания h.

Значение: шаблон смешивания в виде факторов смешивания h.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
### getBlendPatternAsBlendFactorsV() {#getBlendPatternAsBlendFactorsV--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsV()
```


Получает шаблон смешивания в виде факторов смешивания v.

Значение: шаблон смешивания в виде факторов смешивания v.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
