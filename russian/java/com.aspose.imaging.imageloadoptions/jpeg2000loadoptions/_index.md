---
title: "Jpeg2000LoadOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры загрузки JPEG2000"
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.imageloadoptions/jpeg2000loadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

Параметры загрузки JPEG2000
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | Инициализирует новый экземпляр класса `Jpeg2000LoadOptions`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | Получает максимальное время декодирования в секундах (этот параметр можно использовать на очень медленных машинах с небольшим объёмом памяти, чтобы предотвратить зависание процесса при работе с очень большими изображениями — разрешение более 5500×6500 пикселей). |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | Устанавливает максимальное время декодирования в секундах (этот параметр можно использовать на очень медленных машинах с небольшим объёмом памяти, чтобы предотвратить зависание процесса при работе с очень большими изображениями — разрешение более 5500×6500 пикселей). |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | Получает максимальное время декодирования для плитки. |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | Устанавливает максимальное время декодирования для плитки. |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


Инициализирует новый экземпляр класса `Jpeg2000LoadOptions`.

### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


Получает максимальное время декодирования в секундах (этот параметр можно использовать на очень медленных машинах с небольшим объёмом памяти, чтобы предотвратить зависание процесса при работе с очень большими изображениями — разрешение более 5500×6500 пикселей).

**Returns:**
int - Максимальное время декодирования.
### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


Устанавливает максимальное время декодирования в секундах (этот параметр можно использовать на очень медленных машинах с небольшим объёмом памяти, чтобы предотвратить зависание процесса при работе с очень большими изображениями — разрешение более 5500×6500 пикселей).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Максимальное время декодирования. |

### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


Получает максимальное время декодирования для плитки.

Значение: максимальное время декодирования для плитки.

**Returns:**
int - максимальное время декодирования для плитки.
### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


Устанавливает максимальное время декодирования для плитки.

Значение: максимальное время декодирования для плитки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | максимальное время декодирования для плитки. |

