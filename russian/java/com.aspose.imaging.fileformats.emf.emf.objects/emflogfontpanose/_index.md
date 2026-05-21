---
title: "EmfLogFontPanose"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект LogFontPanose указывает характеристики PANOSE логического шрифта."
type: docs
weight: 25
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
```
public final class EmfLogFontPanose extends EmfLogFont
```

Объект LogFontPanose указывает характеристики PANOSE логического шрифта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfLogFontPanose(EmfLogFont emfLogFont)](#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Инициализирует новый экземпляр класса `EmfLogFontPanose`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFullName()](#getFullName--) | Получает или задает строку из 64 Unicode‑символов, определяющую полное имя шрифта. |
| [setFullName(String value)](#setFullName-java.lang.String-) | Получает или задает строку из 64 Unicode‑символов, определяющую полное имя шрифта. |
| [getStyle()](#getStyle--) | Получает или задает строку из 32 символов Unicode, определяющую стиль шрифта. |
| [setStyle(String value)](#setStyle-java.lang.String-) | Получает или задает строку из 32 символов Unicode, определяющую стиль шрифта. |
| [getVersion()](#getVersion--) | Получает или задает Это поле ДОЛЖНО игнорироваться. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает Это поле ДОЛЖНО игнорироваться. |
| [getStyleSize()](#getStyleSize--) | Получает или задает 32‑битное беззнаковое целое, которое определяет размер пункта, при котором выполняется хинтинг шрифта. |
| [setStyleSize(int value)](#setStyleSize-int-) | Получает или задает 32‑битное беззнаковое целое, которое определяет размер пункта, при котором выполняется хинтинг шрифта. |
| [getMatch()](#getMatch--) | Получает или задает Это поле ДОЛЖНО игнорироваться. |
| [setMatch(int value)](#setMatch-int-) | Получает или задает Это поле ДОЛЖНО игнорироваться. |
| [getVendorId()](#getVendorId--) | Получает или задает Это поле ДОЛЖНО игнорироваться. |
| [setVendorId(int value)](#setVendorId-int-) | Получает или задает Это поле ДОЛЖНО игнорироваться. |
| [getCulture()](#getCulture--) | Получает или задает 32‑битное беззнаковое целое, которое ДОЛЖНО быть установлено в ноль и ДОЛЖНО игнорироваться. |
| [setCulture(int value)](#setCulture-int-) | Получает или задает 32‑битное беззнаковое целое, которое ДОЛЖНО быть установлено в ноль и ДОЛЖНО игнорироваться. |
| [getPanose()](#getPanose--) | Получает или задает объект Panose (раздел 2.2.21), который определяет характеристики PANOSE логического шрифта. |
| [setPanose(EmfPanose value)](#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-) | Получает или задает объект Panose (раздел 2.2.21), который определяет характеристики PANOSE логического шрифта. |
| [getPadding()](#getPadding--) | Получает или задает поле, существующее только для обеспечения 32‑битного выравнивания этой структуры. |
| [setPadding(short value)](#setPadding-short-) | Получает или задает поле, существующее только для обеспечения 32‑битного выравнивания этой структуры. |
### EmfLogFontPanose(EmfLogFont emfLogFont) {#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public EmfLogFontPanose(EmfLogFont emfLogFont)
```


Инициализирует новый экземпляр класса `EmfLogFontPanose`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| emfLogFont | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) | Базовый логический шрифт. |

### getFullName() {#getFullName--}
```
public String getFullName()
```


Получает или задает строку из 64 Unicode‑символов, определяющую полное имя шрифта. Если длина этой строки меньше 64 символов, должна присутствовать завершающая NULL, после которой оставшаяся часть этого поля ДОЛЖНА игнорироваться.

**Returns:**
java.lang.String
### setFullName(String value) {#setFullName-java.lang.String-}
```
public void setFullName(String value)
```


Получает или задает строку из 64 Unicode‑символов, определяющую полное имя шрифта. Если длина этой строки меньше 64 символов, должна присутствовать завершающая NULL, после которой оставшаяся часть этого поля ДОЛЖНА игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getStyle() {#getStyle--}
```
public String getStyle()
```


Получает или задает строку из 32 символов Unicode, определяющую стиль шрифта. Если длина этой строки менее 32 символов, должен присутствовать завершающий NULL, после чего оставшаяся часть этого поля ДОЛЖНА игнорироваться.

**Returns:**
java.lang.String
### setStyle(String value) {#setStyle-java.lang.String-}
```
public void setStyle(String value)
```


Получает или задает строку из 32 символов Unicode, определяющую стиль шрифта. Если длина этой строки менее 32 символов, должен присутствовать завершающий NULL, после чего оставшаяся часть этого поля ДОЛЖНА игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Получает или задает Это поле ДОЛЖНО игнорироваться.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Получает или задает Это поле ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getStyleSize() {#getStyleSize--}
```
public int getStyleSize()
```


Получает или задает 32‑битное беззнаковое целое, которое определяет размер пункта, при котором выполняется хинтинг шрифта. Если установлено в ноль, хинтинг шрифта выполняется при размере пункта, соответствующем полю Height в объекте LogFont в поле LogFont.

**Returns:**
int
### setStyleSize(int value) {#setStyleSize-int-}
```
public void setStyleSize(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое определяет размер пункта, при котором выполняется хинтинг шрифта. Если установлено в ноль, хинтинг шрифта выполняется при размере пункта, соответствующем полю Height в объекте LogFont в поле LogFont.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMatch() {#getMatch--}
```
public int getMatch()
```


Получает или задает Это поле ДОЛЖНО игнорироваться.

**Returns:**
int
### setMatch(int value) {#setMatch-int-}
```
public void setMatch(int value)
```


Получает или задает Это поле ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVendorId() {#getVendorId--}
```
public int getVendorId()
```


Получает или задает Это поле ДОЛЖНО игнорироваться.

**Returns:**
int
### setVendorId(int value) {#setVendorId-int-}
```
public void setVendorId(int value)
```


Получает или задает Это поле ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCulture() {#getCulture--}
```
public int getCulture()
```


Получает или задает 32‑битное беззнаковое целое, которое ДОЛЖНО быть установлено в ноль и ДОЛЖНО игнорироваться.

**Returns:**
int
### setCulture(int value) {#setCulture-int-}
```
public void setCulture(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое ДОЛЖНО быть установлено в ноль и ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPanose() {#getPanose--}
```
public EmfPanose getPanose()
```


Получает или задает объект Panose (раздел 2.2.21), который определяет характеристики PANOSE логического шрифта. Если все поля этого объекта равны нулю, он ДОЛЖЕН игнорироваться.

**Returns:**
[EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose)
### setPanose(EmfPanose value) {#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-}
```
public void setPanose(EmfPanose value)
```


Получает или задает объект Panose (раздел 2.2.21), который определяет характеристики PANOSE логического шрифта. Если все поля этого объекта равны нулю, он ДОЛЖЕН игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose) |  |

### getPadding() {#getPadding--}
```
public short getPadding()
```


Получает или задает поле, существующее только для обеспечения 32‑битного выравнивания этой структуры. Оно ДОЛЖНО игнорироваться.

**Returns:**
short
### setPadding(short value) {#setPadding-short-}
```
public void setPadding(short value)
```


Получает или задает поле, существующее только для обеспечения 32‑битного выравнивания этой структуры. Оно ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

