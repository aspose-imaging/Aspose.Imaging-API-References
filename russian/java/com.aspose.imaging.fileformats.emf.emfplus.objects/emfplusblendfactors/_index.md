---
title: "EmfPlusBlendFactors"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusBlendFactors указывает позиции и коэффициенты для шаблона смешивания градиентной кисти."
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
```
public final class EmfPlusBlendFactors extends EmfPlusBlendBase
```

Объект EmfPlusBlendFactors указывает позиции и коэффициенты для шаблона смешивания градиентной кисти.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusBlendFactors()](#EmfPlusBlendFactors--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBlendFactors()](#getBlendFactors--) | Получает или задает массив из PositionCount 32‑битных значений с плавающей точкой, которые указывают пропорции цветов в позициях, определённых в поле BlendPositions. |
| [setBlendFactors(float[] value)](#setBlendFactors-float---) | Получает или задает массив из PositionCount 32‑битных значений с плавающей точкой, которые указывают пропорции цветов в позициях, определённых в поле BlendPositions. |
### EmfPlusBlendFactors() {#EmfPlusBlendFactors--}
```
public EmfPlusBlendFactors()
```


### getBlendFactors() {#getBlendFactors--}
```
public float[] getBlendFactors()
```


Получает или задает массив из PositionCount 32‑битных значений с плавающей точкой, которые указывают пропорции цветов в позициях, определённых в поле BlendPositions. Каждое значение ДОЛЖНО быть числом от 0.0 до 1.0 включительно.

**Returns:**
float[]
### setBlendFactors(float[] value) {#setBlendFactors-float---}
```
public void setBlendFactors(float[] value)
```


Получает или задает массив из PositionCount 32‑битных значений с плавающей точкой, которые указывают пропорции цветов в позициях, определённых в поле BlendPositions. Каждое значение ДОЛЖНО быть числом от 0.0 до 1.0 включительно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |

