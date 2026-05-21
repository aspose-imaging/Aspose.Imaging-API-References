---
title: "EmfPanose"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект Panose описывает значения классификации шрифтов PANOSE для TrueType шрифта."
type: docs
weight: 30
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPanose extends EmfObject
```

Объект Panose описывает значения классификации шрифтов PANOSE для шрифта TrueType. Эти характеристики используются для сопоставления шрифта с другими шрифтами схожего внешнего вида, но с разными названиями.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPanose()](#EmfPanose--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getFamilyType()](#getFamilyType--) | Получает или задает 8‑битное беззнаковое целое, которое указывает тип семейства. |
| [setFamilyType(byte value)](#setFamilyType-byte-) | Получает или задает 8‑битное беззнаковое целое, которое указывает тип семейства. |
| [getSerifStyle()](#getSerifStyle--) | Получает или задает 8‑битное беззнаковое целое, которое указывает стиль засечек. |
| [setSerifStyle(byte value)](#setSerifStyle-byte-) | Получает или задает 8‑битное беззнаковое целое, которое указывает стиль засечек. |
| [getWeight()](#getWeight--) | Получает или задает 8‑битное беззнаковое целое, которое указывает толщину шрифта. |
| [setWeight(byte value)](#setWeight-byte-) | Получает или задает 8‑битное беззнаковое целое, которое указывает толщину шрифта. |
| [getProportion()](#getProportion--) | Получает или задает 8‑битное беззнаковое целое, которое указывает пропорцию шрифта. |
| [setProportion(byte value)](#setProportion-byte-) | Получает или задает 8‑битное беззнаковое целое, которое указывает пропорцию шрифта. |
| [getContrast()](#getContrast--) | Получает или задает 8‑битное беззнаковое целое, которое указывает контраст шрифта. |
| [setContrast(byte value)](#setContrast-byte-) | Получает или задает 8‑битное беззнаковое целое, которое указывает контраст шрифта. |
| [getStrokeVariation()](#getStrokeVariation--) | Получает или задает 8‑битное беззнаковое целое, которое определяет вариацию штриха для шрифта. |
| [setStrokeVariation(byte value)](#setStrokeVariation-byte-) | Получает или задает 8‑битное беззнаковое целое, которое определяет вариацию штриха для шрифта. |
| [getArmStyle()](#getArmStyle--) | Получает или задает 8‑битное беззнаковое целое, которое определяет стиль рукоятки шрифта. |
| [setArmStyle(byte value)](#setArmStyle-byte-) | Получает или задает 8‑битное беззнаковое целое, которое определяет стиль рукоятки шрифта. |
| [getLetterform()](#getLetterform--) | Получает или задает 8‑битное беззнаковое целое, которое определяет форму букв шрифта. |
| [setLetterform(byte value)](#setLetterform-byte-) | Получает или задает 8‑битное беззнаковое целое, которое определяет форму букв шрифта. |
| [getMidline()](#getMidline--) | Получает или задает 8‑битное беззнаковое целое, которое определяет среднюю линию шрифта. |
| [setMidline(byte value)](#setMidline-byte-) | Получает или задает 8‑битное беззнаковое целое, которое определяет среднюю линию шрифта. |
| [getXHeight()](#getXHeight--) | Получает или задает 8‑битное беззнаковое целое, которое определяет высоту x шрифта. |
| [setXHeight(byte value)](#setXHeight-byte-) | Получает или задает 8‑битное беззнаковое целое, которое определяет высоту x шрифта. |
### EmfPanose() {#EmfPanose--}
```
public EmfPanose()
```


### getFamilyType() {#getFamilyType--}
```
public byte getFamilyType()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет тип семейства. Значение ДОЛЖНО быть в таблице перечисления FamilyType (раздел 2.1.12).

**Returns:**
byte
### setFamilyType(byte value) {#setFamilyType-byte-}
```
public void setFamilyType(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет тип семейства. Значение ДОЛЖНО быть в таблице перечисления FamilyType (раздел 2.1.12).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getSerifStyle() {#getSerifStyle--}
```
public byte getSerifStyle()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет стиль засечек. Значение ДОЛЖНО быть в таблице перечисления SerifType (раздел 2.1.30).

**Returns:**
byte
### setSerifStyle(byte value) {#setSerifStyle-byte-}
```
public void setSerifStyle(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет стиль засечек. Значение ДОЛЖНО быть в таблице перечисления SerifType (раздел 2.1.30).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getWeight() {#getWeight--}
```
public byte getWeight()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет толщину шрифта. Значение ДОЛЖНО быть в таблице перечисления Weight (раздел 2.1.34).

**Returns:**
byte
### setWeight(byte value) {#setWeight-byte-}
```
public void setWeight(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет толщину шрифта. Значение ДОЛЖНО быть в таблице перечисления Weight (раздел 2.1.34).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getProportion() {#getProportion--}
```
public byte getProportion()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет пропорцию шрифта. Значение ДОЛЖНО быть в таблице перечисления Proportion (раздел 2.1.28).

**Returns:**
byte
### setProportion(byte value) {#setProportion-byte-}
```
public void setProportion(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет пропорцию шрифта. Значение ДОЛЖНО быть в таблице перечисления Proportion (раздел 2.1.28).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getContrast() {#getContrast--}
```
public byte getContrast()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет контраст шрифта. Значение ДОЛЖНО быть в таблице перечисления Contrast (раздел 2.1.8).

**Returns:**
byte
### setContrast(byte value) {#setContrast-byte-}
```
public void setContrast(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет контраст шрифта. Значение ДОЛЖНО быть в таблице перечисления Contrast (раздел 2.1.8).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getStrokeVariation() {#getStrokeVariation--}
```
public byte getStrokeVariation()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет вариацию штриха для шрифта. Значение ДОЛЖНО быть в таблице перечисления StrokeVariation (раздел 2.1.33).

**Returns:**
byte
### setStrokeVariation(byte value) {#setStrokeVariation-byte-}
```
public void setStrokeVariation(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет вариацию штриха для шрифта. Значение ДОЛЖНО быть в таблице перечисления StrokeVariation (раздел 2.1.33).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getArmStyle() {#getArmStyle--}
```
public byte getArmStyle()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет стиль рукоятки шрифта. Значение ДОЛЖНО быть в таблице перечисления ArmStyle (раздел 2.1.3).

**Returns:**
byte
### setArmStyle(byte value) {#setArmStyle-byte-}
```
public void setArmStyle(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет стиль рукоятки шрифта. Значение ДОЛЖНО быть в таблице перечисления ArmStyle (раздел 2.1.3).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getLetterform() {#getLetterform--}
```
public byte getLetterform()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет форму букв шрифта. Значение ДОЛЖНО быть в таблице перечисления Letterform (раздел 2.1.20).

**Returns:**
byte
### setLetterform(byte value) {#setLetterform-byte-}
```
public void setLetterform(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет форму букв шрифта. Значение ДОЛЖНО быть в таблице перечисления Letterform (раздел 2.1.20).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getMidline() {#getMidline--}
```
public byte getMidline()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет среднюю линию шрифта. Значение ДОЛЖНО быть в таблице перечисления MidLine (раздел 2.1.23).

**Returns:**
byte
### setMidline(byte value) {#setMidline-byte-}
```
public void setMidline(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет среднюю линию шрифта. Значение ДОЛЖНО быть в таблице перечисления MidLine (раздел 2.1.23).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getXHeight() {#getXHeight--}
```
public byte getXHeight()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет высоту x шрифта. Значение ДОЛЖНО быть в таблице перечисления XHeight (раздел 2.1.35).

**Returns:**
byte
### setXHeight(byte value) {#setXHeight-byte-}
```
public void setXHeight(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет высоту x шрифта. Значение ДОЛЖНО быть в таблице перечисления XHeight (раздел 2.1.35).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

