---
title: "ResourceEvent"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Содержит размеры нарисованного объекта."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.xmp.types.complex.resourceevent/resourceevent/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Содержит размеры нарисованного объекта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Инициализирует новый экземпляр класса `ResourceEvent`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getAction()](#getAction--) | Получает действие. |
| [setAction(String value)](#setAction-java.lang.String-) | Устанавливает действие. |
| [getChanged()](#getChanged--) | Получает список частей ресурса, разделённых точкой с запятой, которые были изменены с момента предыдущей истории событий. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Устанавливает список частей ресурса, разделённых точкой с запятой, которые были изменены с момента предыдущей истории событий. |
| [getInstanceId()](#getInstanceId--) | Получает значение xmpMM:InstanceId. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Получает или задаёт значение xmpMM:InstanceId. |
| [getParameters()](#getParameters--) | Получает или задаёт дополнительное описание действия. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Получает или задаёт дополнительное описание действия. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Получает или задаёт имя программного агента. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Получает или задаёт имя программного агента. |
| [getActionDate()](#getActionDate--) | Получает или задаёт дату действия. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Получает или задаёт дату действия. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Получает строковое значение в формате XMP. |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Инициализирует новый экземпляр класса `ResourceEvent`.

### getAction() {#getAction--}
```
public String getAction()
```


Получает действие.

Определённые значения: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Новые значения должны быть глаголами в прошедшем времени.

**Returns:**
java.lang.String - Действие.
### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Устанавливает действие.

Определённые значения: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Новые значения должны быть глаголами в прошедшем времени.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Действие. |

### getChanged() {#getChanged--}
```
public String getChanged()
```


Получает список частей ресурса, разделённых точкой с запятой, которые были изменены с момента предыдущей истории событий.

**Returns:**
java.lang.String - Список частей ресурса, разделённых точкой с запятой, которые были изменены с момента предыдущей истории событий.
### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Устанавливает список частей ресурса, разделённых точкой с запятой, которые были изменены с момента предыдущей истории событий.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Список частей ресурса, разделённых точкой с запятой, которые были изменены с момента предыдущей истории событий. |

### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Получает значение xmpMM:InstanceId.

**Returns:**
java.util.UUID - Значение xmpMM:InstanceId.
### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Получает или задаёт значение xmpMM:InstanceId.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.UUID | Значение xmpMM:InstanceId. |

### getParameters() {#getParameters--}
```
public String getParameters()
```


Получает или задаёт дополнительное описание действия.

Значение: дополнительное описание действия.

**Returns:**
java.lang.String
### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Получает или задаёт дополнительное описание действия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Дополнительное описание действия. |

### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Получает или задаёт имя программного агента.

**Returns:**
java.lang.String - Имя программного агента.
### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Получает или задаёт имя программного агента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Имя программного агента. |

### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Получает или задаёт дату действия.

**Returns:**
java.util.Date - Дата действия.
### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Получает или задаёт дату действия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Дата действия. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Получает строковое значение в формате XMP.

**Returns:**
java.lang.String - Возвращает строковое значение в формате XMP.
