---
title: "AutoWhiteBalanceFilterOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Предоставляет параметры конфигурации для фильтра Auto White Balance."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AutoWhiteBalanceFilterOptions extends FilterOptionsBase
```

Предоставляет параметры конфигурации для фильтра Auto White Balance. Позволяет настраивать параметры растягивания контраста и масштабирование каналов для улучшения внешнего вида цифровых изображений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AutoWhiteBalanceFilterOptions()](#AutoWhiteBalanceFilterOptions--) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile)](#AutoWhiteBalanceFilterOptions-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)](#AutoWhiteBalanceFilterOptions-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)](#AutoWhiteBalanceFilterOptions-int-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)](#AutoWhiteBalanceFilterOptions-int-int-int-float-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)](#AutoWhiteBalanceFilterOptions-int-int-int-float-int-) | Инициализирует новый экземпляр класса [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getTargetHighPercentile()](#getTargetHighPercentile--) | Получает целевой высокий процентиль для растягивания контраста. |
| [getTargetValue()](#getTargetValue--) | Получает целевое значение для высокого процентиля. |
| [getMaxScale()](#getMaxScale--) | Получает максимальный коэффициент масштабирования для каждого канала. |
| [getLowPercentile()](#getLowPercentile--) | Низкий процентиль для черной точки, используемый для защиты от темных областей (по умолчанию: 3). |
| [getProtectedDarkOffset()](#getProtectedDarkOffset--) | Смещение от низкого процентиля, ниже которого темные пиксели не растягиваются (защита). |
### AutoWhiteBalanceFilterOptions() {#AutoWhiteBalanceFilterOptions--}
```
public AutoWhiteBalanceFilterOptions()
```


### AutoWhiteBalanceFilterOptions(int lowPercentile) {#AutoWhiteBalanceFilterOptions-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lowPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile) {#AutoWhiteBalanceFilterOptions-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue) {#AutoWhiteBalanceFilterOptions-int-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale) {#AutoWhiteBalanceFilterOptions-int-int-int-float-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |
| maxScale | float |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset) {#AutoWhiteBalanceFilterOptions-int-int-int-float-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)
```


Инициализирует новый экземпляр класса [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lowPercentile | int | Низкий процентиль для черной точки, используемый для защиты от темных областей (по умолчанию: 3). |
| targetHighPercentile | int | Целевой высокий процентиль для растягивания контраста (по умолчанию 97). |
| targetValue | int | Целевое значение для высокого процентиля (по умолчанию 255). |
| maxScale | float | Максимальный коэффициент масштабирования для каждого канала (по умолчанию 1.4f). |
| protectedDarkOffset | int | Смещение от низкого процентиля, ниже которого темные пиксели не растягиваются (защита). |

### getTargetHighPercentile() {#getTargetHighPercentile--}
```
public final int getTargetHighPercentile()
```


Получает целевой высокий процентиль для растяжения контраста. Определяет, какой процентиль яркости будет сопоставлен с целевым значением.

**Returns:**
int — целевой высокий процентиль для растяжения контраста.
### getTargetValue() {#getTargetValue--}
```
public final int getTargetValue()
```


Получает целевое значение для высокого процентиля. Это значение будет использоваться в качестве белой ссылки для растяжения контраста.

**Returns:**
int — целевое значение для высокого процентиля.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Получает максимальный коэффициент масштабирования для каждого канала. Ограничивает усиление любого канала, чтобы избежать чрезмерных цветовых сдвигов.

**Returns:**
float — максимальный коэффициент масштабирования для каждого канала.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Низкий процентиль для черной точки, используемый для защиты от темных областей (по умолчанию: 3).

**Returns:**
int
### getProtectedDarkOffset() {#getProtectedDarkOffset--}
```
public final int getProtectedDarkOffset()
```


Смещение от низкого процентиля, ниже которого темные пиксели не растягиваются (защита).

**Returns:**
int
