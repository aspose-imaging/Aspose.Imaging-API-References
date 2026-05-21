---
title: "EmfPlusHeader"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusHeader указывает начало данных EMF в метафайле."
type: docs
weight: 40
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging/fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging/fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusHeader extends EmfPlusControlRecordType
```

Запись EmfPlusHeader указывает начало данных EMF+ в метафайле. Запись EmfPlusHeader ДОЛЖНА быть вложена в запись EMF EMR\_COMMENT\_EMFPLUS, которая ДОЛЖНА быть записью, непосредственно следующей за заголовком EMF в метафайле. Запись EMR\_COMMENT\_EMFPLUS указана в [MS-EMF] раздел 2.3.3.2.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusHeader(EmfPlusRecord source)](#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusHeader`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getDualMode()](#getDualMode--) | Получает или задает значение, указывающее, включён ли [dual mode]. |
| [setDualMode(boolean value)](#setDualMode-boolean-) | Получает или задает значение, указывающее, включён ли [dual mode]. |
| [getVideoDisplay()](#getVideoDisplay--) | Получает или задает значение, указывающее, отображается ли видео. |
| [setVideoDisplay(boolean value)](#setVideoDisplay-boolean-) | Получает или задает значение, указывающее, отображается ли видео. |
| [getEmfPlusFlags()](#getEmfPlusFlags--) | Получает или задает флаги EMF plus. |
| [setEmfPlusFlags(int value)](#setEmfPlusFlags-int-) | Получает или задает флаги EMF plus. |
| [getLogicalDpiX()](#getLogicalDpiX--) | Получает или задает логическое dpi по оси x. |
| [setLogicalDpiX(int value)](#setLogicalDpiX-int-) | Получает или задает логическое dpi по оси x. |
| [getLogicalDpiY()](#getLogicalDpiY--) | Получает или задает логическое dpi по оси y. |
| [setLogicalDpiY(int value)](#setLogicalDpiY-int-) | Получает или задает логическое dpi по оси y. |
| [getVersion()](#getVersion--) | Получает или задает версию. |
| [setVersion(EmfPlusGraphicsVersion value)](#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-) | Получает или задает версию. |
| [isValid()](#isValid--) | Получает значение, указывающее, является ли этот экземпляр действительным. |
### EmfPlusHeader(EmfPlusRecord source) {#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusHeader(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusHeader`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getDualMode() {#getDualMode--}
```
public boolean getDualMode()
```


Получает или задает значение, указывающее, включён ли [dual mode]. Если установлен, этот флаг указывает, что данный метафайл является «dual-mode», что означает, что он содержит два набора записей, каждый из которых полностью определяет графическое содержимое. Если сброшен, графическое содержимое определяется записями EMF+, а также возможными записями EMF, предшествующими записи EmfPlusGetDC. Если этот флаг установлен, записи EMF сами по себе ДОЛЖНЫ быть достаточными для определения графического содержимого. Обратите внимание, что независимо от того, установлен флаг «dual-mode» или нет, некоторые записи EMF всегда присутствуют, а именно управляющие записи EMF и записи EMF, содержащие записи EMF+. Управляющие записи EMF указаны в [MS-EMF] раздел 2.3.4.

Значение: `true`, если [dual mode]; иначе `false`.

**Returns:**
boolean
### setDualMode(boolean value) {#setDualMode-boolean-}
```
public void setDualMode(boolean value)
```


Получает или задает значение, указывающее, включён ли [dual mode]. Если установлен, этот флаг указывает, что данный метафайл является «dual-mode», что означает, что он содержит два набора записей, каждый из которых полностью определяет графическое содержимое. Если сброшен, графическое содержимое определяется записями EMF+, а также возможными записями EMF, предшествующими записи EmfPlusGetDC. Если этот флаг установлен, записи EMF сами по себе ДОЛЖНЫ быть достаточными для определения графического содержимого. Обратите внимание, что независимо от того, установлен флаг «dual-mode» или нет, некоторые записи EMF всегда присутствуют, а именно управляющие записи EMF и записи EMF, содержащие записи EMF+. Управляющие записи EMF указаны в [MS-EMF] раздел 2.3.4.

Значение: `true`, если [dual mode]; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getVideoDisplay() {#getVideoDisplay--}
```
public boolean getVideoDisplay()
```


Получает или задает значение, указывающее, отображается ли видео. Если установлен, этот флаг указывает, что метафайл был записан с контекстом устройства ссылки для видеодисплея. Если сброшен, метафайл был записан с контекстом устройства ссылки для принтера.

Значение: `true`, если [video display]; иначе `false`.

**Returns:**
boolean
### setVideoDisplay(boolean value) {#setVideoDisplay-boolean-}
```
public void setVideoDisplay(boolean value)
```


Получает или задает значение, указывающее, отображается ли видео. Если установлен, этот флаг указывает, что метафайл был записан с контекстом устройства ссылки для видеодисплея. Если сброшен, метафайл был записан с контекстом устройства ссылки для принтера.

Значение: `true`, если [video display]; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getEmfPlusFlags() {#getEmfPlusFlags--}
```
public int getEmfPlusFlags()
```


Получает или задает флаги EMF plus. 32‑битное беззнаковое целое, содержащее информацию о том, как был записан этот метафайл. Если установлен 31‑й бит поля, этот флаг указывает, что метафайл был записан с контекстом устройства ссылки для видеодисплея. Если сброшен, метафайл был записан с контекстом устройства ссылки для принтера.

Значение: флаги EMF plus.

**Returns:**
int
### setEmfPlusFlags(int value) {#setEmfPlusFlags-int-}
```
public void setEmfPlusFlags(int value)
```


Получает или задает флаги EMF plus. 32‑битное беззнаковое целое, содержащее информацию о том, как был записан этот метафайл. Если установлен 31‑й бит поля, этот флаг указывает, что метафайл был записан с контекстом устройства ссылки для видеодисплея. Если сброшен, метафайл был записан с контекстом устройства ссылки для принтера.

Значение: флаги EMF plus.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLogicalDpiX() {#getLogicalDpiX--}
```
public int getLogicalDpiX()
```


Получает или задает логическое dpi по оси x. 32‑битное беззнаковое целое, определяющее горизонтальное разрешение, для которого был записан метафайл, в единицах пикселей на дюйм.

Значение: логическое dpi по оси x.

**Returns:**
int
### setLogicalDpiX(int value) {#setLogicalDpiX-int-}
```
public void setLogicalDpiX(int value)
```


Получает или задает логическое dpi по оси x. 32‑битное беззнаковое целое, определяющее горизонтальное разрешение, для которого был записан метафайл, в единицах пикселей на дюйм.

Значение: логическое dpi по оси x.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLogicalDpiY() {#getLogicalDpiY--}
```
public int getLogicalDpiY()
```


Получает или задает логическое dpi по оси y. 32‑битное беззнаковое целое, определяющее вертикальное разрешение, для которого был записан метафайл, в единицах строк на дюйм.

Значение: логическое dpi по оси y.

**Returns:**
int
### setLogicalDpiY(int value) {#setLogicalDpiY-int-}
```
public void setLogicalDpiY(int value)
```


Получает или задает логическое dpi по оси y. 32‑битное беззнаковое целое, определяющее вертикальное разрешение, для которого был записан метафайл, в единицах строк на дюйм.

Значение: логическое dpi по оси y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public EmfPlusGraphicsVersion getVersion()
```


Получает или задает версию. Объект EmfPlusGraphicsVersion (раздел 2.2.2.19), определяющий версию графики операционной системы, использованную при создании этого метафайла.

Значение: версия.

**Returns:**
[EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion)
### setVersion(EmfPlusGraphicsVersion value) {#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-}
```
public void setVersion(EmfPlusGraphicsVersion value)
```


Получает или задает версию. Объект EmfPlusGraphicsVersion (раздел 2.2.2.19), определяющий версию графики операционной системы, использованную при создании этого метафайла.

Значение: версия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion) |  |

### isValid() {#isValid--}
```
public boolean isValid()
```


Получает значение, указывающее, является ли этот экземпляр действительным.

Значение: `true`, если этот экземпляр действителен; иначе `false`.

**Returns:**
boolean
