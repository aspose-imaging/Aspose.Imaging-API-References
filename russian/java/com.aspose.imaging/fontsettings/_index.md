---
title: "FontSettings"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Настройки шрифтов рендерера общих векторных форматов изображений."
type: docs
weight: 49
url: /ru/java/com.aspose.imaging/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Настройки шрифтов рендерера общих векторных форматов изображений.
## Методы

| Метод | Описание |
| --- | --- |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Получает значение, указывающее, следует ли [get alternative font]. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Устанавливает значение, указывающее, следует ли [get alternative font]. |
| [getDefaultFontName()](#getDefaultFontName--) | Получает имя шрифта по умолчанию. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Устанавливает имя шрифта по умолчанию. |
| [getFontsFolders()](#getFontsFolders--) | Получает копию массива, содержащего список папок, где Aspose.Imaging ищет TrueType‑шрифты. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Получает папки шрифтов по умолчанию. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Переопределить список папок шрифтов для `folder` |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Переопределить список папок шрифтов для `folders` |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Устанавливает папки, из которых загружаются TrueType‑шрифты, и очищает все загруженные шрифты. |
| [reset()](#reset--) | Сбрасывает папку шрифтов и имя шрифта по умолчанию до системных значений. |
| [updateFonts()](#updateFonts--) | Обновляет кэш шрифтов для PSD‑файлов, содержащих текстовые слои. |
| [addFontsFolder(String fontFolder)](#addFontsFolder-java.lang.String-) | Добавляет `fontFolder` в список каталогов шрифтов и отмечает его как первую папку для поиска шрифтов. |
| [removeFontsFolder(String folder)](#removeFontsFolder-java.lang.String-) | Удаляет `folder` из списка папок. |
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Получает значение, указывающее, следует ли [get alternative font].

Значение: `true`, если [get alternative font]; иначе `false`.

**Returns:**
boolean - значение, указывающее, [get alternative font].
### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Устанавливает значение, указывающее, следует ли [get alternative font].

Значение: `true`, если [get alternative font]; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, [get alternative font]. |

### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Получает имя шрифта по умолчанию.

**Returns:**
java.lang.String — имя шрифта по умолчанию
### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Устанавливает имя шрифта по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта по умолчанию. |

### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Получает копию массива, содержащего список папок, где Aspose.Imaging ищет TrueType‑шрифты.

Возвращаемое значение является копией данных, используемых Aspose.Imaging. Если изменить элементы в возвращённом массиве, это не повлияет на рендеринг документа. Чтобы указать новые расположения шрифтов, используйте метод `setFontsFolders`.

**Returns:**
java.lang.String[] — копия текущих расположений шрифтов.
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Получает папки шрифтов по умолчанию.

**Returns:**
java.lang.String[] — возвращает системную папку.
### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Переопределить список папок шрифтов для `folder`

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | java.lang.String | Папка с TrueType‑шрифтами. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Переопределить список папок шрифтов для `folders`

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| folders | java.lang.String[] | Массив папок |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Устанавливает папки, из которых загружаются TrueType‑шрифты, и очищает все загруженные шрифты. Проверка папок шрифтов не выполняется.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| folders | java.lang.String[] | Папки шрифтов. |
| recursive | boolean | если установлено `true` [recursive]. |

### reset() {#reset--}
```
public static void reset()
```


Сбрасывает папку шрифтов и имя шрифта по умолчанию до системных значений.

### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Обновляет кэш шрифтов для PSD‑файлов, содержащих текстовые слои. Этот метод гарантирует, что шрифты из папки fontsFolder, указанные с помощью метода FontSettings.setFontsFolder(fontsFolder) или после сброса шрифтов с помощью FontSettings.reset(), будут учитываться при обработке PSD‑файлов. Пожалуйста, используйте этот метод каждый раз, когда вызываются FontSettings.setFontsFolder(fontsFolder) или FontSettings.reset() для PSD‑изображений. Без вызова этого метода нет гарантии, что шрифты будут обновлены.

### addFontsFolder(String fontFolder) {#addFontsFolder-java.lang.String-}
```
public static void addFontsFolder(String fontFolder)
```


Добавляет `fontFolder` в список каталогов шрифтов и отмечает его как первую папку для поиска шрифтов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFolder | java.lang.String | Папка, содержащая TrueType‑шрифты, или путь к отдельному файлу шрифта. |

### removeFontsFolder(String folder) {#removeFontsFolder-java.lang.String-}
```
public static void removeFontsFolder(String folder)
```


Удаляет `folder` из списка папок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | java.lang.String | Папка для удаления |

