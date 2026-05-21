---
title: "EmfPlusFont"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusFont определяет свойства, которые задают внешний вид текста, включая размер шрифта и стиль."
type: docs
weight: 42
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusFont extends EmfPlusGraphicsObjectType
```

Объект EmfPlusFont определяет свойства, которые определяют внешний вид текста, включая гарнитуру, размер и стиль.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusFont()](#EmfPlusFont--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Получает или задает строку из Length символов Unicode, содержащую название семейства шрифтов |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | Получает или задает строку из Length символов Unicode, содержащую название семейства шрифтов |
| [getFontStyleFlags()](#getFontStyleFlags--) | Получает или задает 32-битное знаковое целое значение, определяющее атрибуты глифов символов, влияющие на внешний вид шрифта, такие как полужирный и курсив. |
| [setFontStyleFlags(int value)](#setFontStyleFlags-int-) | Получает или задает 32-битное знаковое целое значение, определяющее атрибуты глифов символов, влияющие на внешний вид шрифта, такие как полужирный и курсив. |
| [getSizeUnit()](#getSizeUnit--) | Получает или задает 32-битное беззнаковое целое значение, определяющее единицы измерения, используемые для поля EmSize. |
| [setSizeUnit(int value)](#setSizeUnit-int-) | Получает или задает 32-битное беззнаковое целое значение, определяющее единицы измерения, используемые для поля EmSize. |
| [getEmSize()](#getEmSize--) | Получает или задает 32-битное значение с плавающей запятой, определяющее размер em шрифта в единицах, указанных в поле SizeUnit. |
| [setEmSize(float value)](#setEmSize-float-) | Получает или задает 32-битное значение с плавающей запятой, определяющее размер em шрифта в единицах, указанных в поле SizeUnit. |
### EmfPlusFont() {#EmfPlusFont--}
```
public EmfPlusFont()
```


### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Получает или задает строку из Length символов Unicode, содержащую название семейства шрифтов

**Returns:**
java.lang.String
### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


Получает или задает строку из Length символов Unicode, содержащую название семейства шрифтов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontStyleFlags() {#getFontStyleFlags--}
```
public int getFontStyleFlags()
```


Получает или задает 32-битное знаковое целое значение, определяющее атрибуты глифов символов, влияющие на внешний вид шрифта, такие как полужирный и курсив. Это значение ДОЛЖНО состоять из флагов FontStyle (раздел 2.1.2.4).

**Returns:**
int
### setFontStyleFlags(int value) {#setFontStyleFlags-int-}
```
public void setFontStyleFlags(int value)
```


Получает или задает 32-битное знаковое целое значение, определяющее атрибуты глифов символов, влияющие на внешний вид шрифта, такие как полужирный и курсив. Это значение ДОЛЖНО состоять из флагов FontStyle (раздел 2.1.2.4).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSizeUnit() {#getSizeUnit--}
```
public int getSizeUnit()
```


Получает или задает 32-битное беззнаковое целое, которое указывает единицы измерения, используемые для поля EmSize. Обычно это единицы, применявшиеся при проектировании шрифта. Значение ДОЛЖНО быть из перечисления UnitType (раздел 2.1.1.33).

**Returns:**
int
### setSizeUnit(int value) {#setSizeUnit-int-}
```
public void setSizeUnit(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает единицы измерения, используемые для поля EmSize. Обычно это единицы, применявшиеся при проектировании шрифта. Значение ДОЛЖНО быть из перечисления UnitType (раздел 2.1.1.33).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEmSize() {#getEmSize--}
```
public float getEmSize()
```


Получает или задает 32-битное значение с плавающей запятой, определяющее размер em шрифта в единицах, указанных в поле SizeUnit.

**Returns:**
float
### setEmSize(float value) {#setEmSize-float-}
```
public void setEmSize(float value)
```


Получает или задает 32-битное значение с плавающей запятой, определяющее размер em шрифта в единицах, указанных в поле SizeUnit.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

