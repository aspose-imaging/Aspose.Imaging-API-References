---
title: "AdaptiveWhiteStretchFilterOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Предоставляет параметры для настройки фильтра Adaptive White Stretch."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AdaptiveWhiteStretchFilterOptions extends FilterOptionsBase
```

Предоставляет параметры для настройки фильтра Adaptive White Stretch. Позволяет настраивать параметры растяжения гистограммы для повышения уровня белого и улучшения читаемости изображений документов с бледным текстом или низким контрастом.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions()](#AdaptiveWhiteStretchFilterOptions--) | Инициализирует новый экземпляр класса AdaptiveWhiteStretchFilter. |
| [AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)](#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-) | Инициализирует новый экземпляр класса AdaptiveWhiteStretchFilter. |
## Методы

| Метод | Описание |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Возвращает значение, указывающее, работает ли фильтр в режиме градаций серого. |
| [getLowPercentile()](#getLowPercentile--) | Получает нижний процентиль для расчёта чёрной точки. |
| [getHighPercentile()](#getHighPercentile--) | Получает верхний процентиль для расчёта белой точки. |
| [getTargetWhite()](#getTargetWhite--) | Получает целевое значение белого, к которому стремится растяжение. |
| [getMaxScale()](#getMaxScale--) | Получает максимальную допустимую шкалу яркости. |
### AdaptiveWhiteStretchFilterOptions() {#AdaptiveWhiteStretchFilterOptions--}
```
public AdaptiveWhiteStretchFilterOptions()
```


Инициализирует новый экземпляр класса AdaptiveWhiteStretchFilter.

### AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale) {#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-}
```
public AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)
```


Инициализирует новый экземпляр класса AdaptiveWhiteStretchFilter.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isGrayscale | boolean | Указывает, должен ли фильтр работать в режиме градаций серого. |
| lowPercentile | int | Нижний процентиль для чёрной точки (например, 10). |
| highPercentile | int | Верхний процентиль для белой точки (например, 90). |
| targetWhite | int | Целевое значение белого (например, 240). |
|  | maxScale | float | Максимально допустимый масштаб яркости (например, 1.7). |

--------------------

Алгоритм растягивает гистограмму так, чтобы процентиль белого приближался к `targetWhite`, но не превышал `maxScale`, чтобы избежать переосвещения. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Возвращает значение, указывающее, работает ли фильтр в режиме градаций серого.

**Returns:**
boolean — значение, указывающее, работает ли фильтр в режиме градаций серого.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Получает нижний процентиль для расчёта чёрной точки. Значения пикселей ниже этого процентиля считаются чёрными при растягивании.

**Returns:**
int - нижний процентиль для расчёта чёрной точки.
### getHighPercentile() {#getHighPercentile--}
```
public final int getHighPercentile()
```


Получает верхний процентиль для расчёта белой точки. Значения пикселей выше этого процентиля считаются белыми при растягивании.

**Returns:**
int - верхний процентиль для расчёта белой точки.
### getTargetWhite() {#getTargetWhite--}
```
public final int getTargetWhite()
```


Получает целевое значение белого, к которому стремится растяжение.

**Returns:**
int - целевое значение белого, которое должно быть достигнуто при растягивании.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Получает максимально допустимый масштаб яркости. Фактическое растягивание не превысит этот коэффициент, чтобы избежать переосвещения.

**Returns:**
float - максимально допустимый масштаб яркости.
