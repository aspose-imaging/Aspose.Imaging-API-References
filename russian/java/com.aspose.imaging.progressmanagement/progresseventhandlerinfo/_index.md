---
title: "ProgressEventHandlerInfo"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Этот класс представляет информацию о прогрессе операций загрузки/сохранения/экспорта изображений, которую можно использовать во внешнем приложении для отображения прогресса конвертации конечному пользователю"
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Этот класс представляет информацию о прогрессе операций загрузки/сохранения/экспорта изображений, которую можно использовать во внешнем приложении для отображения прогресса конвертации пользователю.
## Методы

| Метод | Описание |
| --- | --- |
| [getDescription()](#getDescription--) | Получает описание события |
| [getEventType()](#getEventType--) | Получает тип события. |
| [getMaxValue()](#getMaxValue--) | Получает верхний предел значения прогресса. |
| [getValue()](#getValue--) | Получает текущее значение прогресса. |

## Example: The following example shows how to print information about progress events for load/export operations.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Пример использования отдельных обработчиков событий прогресса операции для загрузки/экспорта.
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// Журнал STDOUT может выглядеть так:
//        Событие загрузки Инициализация : 1/4
//        Событие загрузки Предобработка : 2/4
//        Событие загрузки Обработка : 3/4
//        Событие загрузки Завершение : 4/4
//        Событие экспорта Инициализация : 1/4
//        Событие экспорта Предобработка : 2/4
//        Событие экспорта Обработка : 3/4
//        Событие экспорта RelativeProgress : 1/1
//        Событие загрузки RelativeProgress : 1/1
//        Событие экспорта Завершение : 4/4
```

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Получает описание события

Значение: Описание.

**Returns:**
java.lang.String - описание события
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Получает тип события.

Значение: Тип события.

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype) - the type of the event.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Получает верхний предел значения прогресса.

Значение: Верхний предел значения прогресса.

**Returns:**
int - верхний предел значения прогресса.
### getValue() {#getValue--}
```
public final int getValue()
```


Получает текущее значение прогресса.

Значение: Значение прогресса.

**Returns:**
int - текущее значение прогресса.
