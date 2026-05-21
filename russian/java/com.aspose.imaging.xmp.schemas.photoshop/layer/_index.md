---
title: "Слой"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет текстовый слой Photoshop."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.xmp.schemas.photoshop/layer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Layer extends XmpTypeBase implements System.IEquatable<Layer>
```

Представляет текстовый слой Photoshop.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Layer(String layerName, String layerText)](#Layer-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса `Layer`. |
| [Layer()](#Layer--) | Инициализирует новый экземпляр класса `Layer`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Получает или задает имя текстового слоя. |
| [setName(String value)](#setName-java.lang.String-) | Получает или задает имя текстового слоя. |
| [getText()](#getText--) | Получает или задает текстовое содержимое слоя. |
| [setText(String value)](#setText-java.lang.String-) | Получает или задает текстовое содержимое слоя. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Возвращает строковое значение в формате XMP. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный `System.Object` этому экземпляру. |
| [isEquals(Layer other)](#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
### Layer(String layerName, String layerText) {#Layer-java.lang.String-java.lang.String-}
```
public Layer(String layerName, String layerText)
```


Инициализирует новый экземпляр класса `Layer`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layerName | java.lang.String | Имя слоя. |
| layerText | java.lang.String | Текст слоя. |

### Layer() {#Layer--}
```
public Layer()
```


Инициализирует новый экземпляр класса `Layer`.

### getName() {#getName--}
```
public String getName()
```


Получает или задает имя текстового слоя.

Значение: имя текстового слоя.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Получает или задает имя текстового слоя.

Значение: имя текстового слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getText() {#getText--}
```
public String getText()
```


Получает или задает текстовое содержимое слоя.

Значение: текстовое содержимое слоя.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Получает или задает текстовое содержимое слоя.

Значение: текстовое содержимое слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Возвращает строковое значение в формате XMP.

**Returns:**
java.lang.String - Возвращает строковое значение в формате XMP.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный `System.Object` этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект `System.Object` для сравнения с этим экземпляром. |

**Returns:**
boolean - `true`, если указанный `System.Object` равен этому экземпляру; иначе `false`.
### isEquals(Layer other) {#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-}
```
public boolean isEquals(Layer other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Layer](../../com.aspose.imaging.xmp.schemas.photoshop/layer) | Объект для сравнения с этим объектом. |

**Returns:**
boolean - true, если текущий объект равен параметру `other`; в противном случае false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — хеш-код для этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
