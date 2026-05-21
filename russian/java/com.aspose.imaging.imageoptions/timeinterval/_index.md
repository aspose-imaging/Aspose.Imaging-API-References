---
title: "TimeInterval"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет интервал времени в миллисекундах"
type: docs
weight: 50
url: /ru/java/com.aspose.imaging.imageoptions/timeinterval/
---
**Inheritance:**
java.lang.Object
```
public class TimeInterval
```

Представляет интервал времени в миллисекундах
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TimeInterval(long from, long to)](#TimeInterval-long-long-) | Создаёт новый экземпляр класса [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval). |
## Методы

| Метод | Описание |
| --- | --- |
| [getFrom()](#getFrom--) | Получает значение From в миллисекундах. |
| [setFrom(long value)](#setFrom-long-) | Устанавливает значение From в миллисекундах. |
| [getTo()](#getTo--) | Получает значение To в миллисекундах. |
| [setTo(long value)](#setTo-long-) | Устанавливает значение To в миллисекундах. |

## Example: Export of part of animation from GIF image based on time interval.

``` java
try (Image image = Image.load("Animation.gif"))
{
    GifOptions options = new GifOptions();
    options.setFullFrame(true);
    final MultiPageOptions multiPageOptions = new MultiPageOptions();
    multiPageOptions.setMode(MultiPageMode.TimeInterval);
    multiPageOptions.setTimeInterval(new TimeInterval(0, 400));
    options.setMultiPageOptions(multiPageOptions);

    image.save("PartOfAnimation.gif", options);
}
```

### TimeInterval(long from, long to) {#TimeInterval-long-long-}
```
public TimeInterval(long from, long to)
```


Создаёт новый экземпляр класса [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| from | long | From в миллисекундах. |
| to | long | В миллисекунды. |

### getFrom() {#getFrom--}
```
public final long getFrom()
```


Получает значение From в миллисекундах.

**Returns:**
long
### setFrom(long value) {#setFrom-long-}
```
public final void setFrom(long value)
```


Устанавливает значение From в миллисекундах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getTo() {#getTo--}
```
public final long getTo()
```


Получает значение To в миллисекундах.

**Returns:**
long
### setTo(long value) {#setTo-long-}
```
public final void setTo(long value)
```


Устанавливает значение To в миллисекундах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

