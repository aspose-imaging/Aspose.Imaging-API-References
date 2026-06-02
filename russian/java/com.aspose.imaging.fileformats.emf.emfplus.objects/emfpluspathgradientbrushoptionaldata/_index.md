---
title: "EmfPlusPathGradientBrushOptionalData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusPathGradientBrushOptionalData задает дополнительные данные для кисти с градиентом по пути."
type: docs
weight: 60
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPathGradientBrushOptionalData extends EmfPlusStructureObjectType
```

Объект EmfPlusPathGradientBrushOptionalData задает дополнительные данные для кисти с градиентом по пути.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для кисти градиента пути. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для кисти градиента пути. |
| [getBlendPattern()](#getBlendPattern--) | Получает или задает необязательный шаблон смешивания для кисти градиента пути. |
| [setBlendPattern(EmfPlusBlendBase value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-) | Получает или задает необязательный шаблон смешивания для кисти градиента пути. |
| [getFocusScaleData()](#getFocusScaleData--) | Получает или задает необязательный объект EmfPlusFocusScaleData (раздел 2.2.2.18), который указывает масштабы фокуса для кисти градиента пути. |
| [setFocusScaleData(EmfPlusFocusScaleData value)](#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-) | Получает или задает необязательный объект EmfPlusFocusScaleData (раздел 2.2.2.18), который указывает масштабы фокуса для кисти градиента пути. |
### EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для кисти градиента пути. Это поле ДОЛЖНО присутствовать, если флаг BrushDataTransform установлен в поле BrushDataFlags объекта EmfPlusPathGradientBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для кисти градиента пути. Это поле ДОЛЖНО присутствовать, если флаг BrushDataTransform установлен в поле BrushDataFlags объекта EmfPlusPathGradientBrushData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase getBlendPattern()
```


Получает или задает необязательный шаблон смешивания для кисти градиента пути. Если это поле присутствует, оно ДОЛЖНО содержать либо объект EmfPlusBlendColors (раздел 2.2.2.4), либо объект EmfPlusBlendFactors (раздел 2.2.2.5), но НЕ ДОЛЖНО содержать оба. Таблица ниже показывает допустимые комбинации флагов BrushData объекта EmfPlusPathGradientBrushData и соответствующие шаблоны смешивания:

**Returns:**
[EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
### setBlendPattern(EmfPlusBlendBase value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-}
```
public void setBlendPattern(EmfPlusBlendBase value)
```


Получает или задает необязательный шаблон смешивания для кисти градиента пути. Если это поле присутствует, оно ДОЛЖНО содержать либо объект EmfPlusBlendColors (раздел 2.2.2.4), либо объект EmfPlusBlendFactors (раздел 2.2.2.5), но НЕ ДОЛЖНО содержать оба. Таблица ниже показывает допустимые комбинации флагов BrushData объекта EmfPlusPathGradientBrushData и соответствующие шаблоны смешивания:

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getFocusScaleData() {#getFocusScaleData--}
```
public EmfPlusFocusScaleData getFocusScaleData()
```


Получает или задает необязательный объект EmfPlusFocusScaleData (раздел 2.2.2.18), который указывает масштабы фокуса для кисти градиента пути. Это поле ДОЛЖНО присутствовать, если флаг BrushDataFocusScales установлен в поле BrushDataFlags объекта EmfPlusPathGradientBrushData.

**Returns:**
[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata)
### setFocusScaleData(EmfPlusFocusScaleData value) {#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-}
```
public void setFocusScaleData(EmfPlusFocusScaleData value)
```


Получает или задает необязательный объект EmfPlusFocusScaleData (раздел 2.2.2.18), который указывает масштабы фокуса для кисти градиента пути. Это поле ДОЛЖНО присутствовать, если флаг BrushDataFocusScales установлен в поле BrushDataFlags объекта EmfPlusPathGradientBrushData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) |  |

