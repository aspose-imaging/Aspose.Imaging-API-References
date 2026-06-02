---
title: "Класс FontSettings"
type: docs
weight: 4850
url: /ru/python-net/aspose.imaging/fontsettings/
---

**Summary:** General imaging vector formats renderer font settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FontSettings

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Получает или задает имя шрифта по умолчанию. |
| get_system_alternative_font [static] | bool | r/w | Получает или задает значение, указывающее, следует ли [get alternative font]. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_default_fonts_folders()](#get_default_fonts_folders__1) | Получает папки шрифтов по умолчанию. |
| [get_fonts_folders()](#get_fonts_folders__2) | Получает копию массива, содержащего список папок, где Aspose.Words ищет TrueType‑шрифты. |
| reset() | Сбрасывает папку шрифтов и имя шрифта по умолчанию к системным настройкам. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_3) | Это сокращение к [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) для установки только одной папки шрифтов.<br/>            Проверки папки шрифтов не выполняются. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_4) | Устанавливает папки, из которых загружаются TrueType‑шрифты, и очищает все загруженные шрифты.<br/>            Проверки папок шрифтов не выполняются. |
| update_fonts() | Обновляет кэш шрифтов для PSD‑файлов, содержащих текстовые слои. Этот метод гарантирует, что шрифты из папки fontsFolder, использующие<br/>            метод FontSettings.SetFontsFolder(fontsFolder) или после сброса шрифтов с помощью FontSettings.Reset(), будут учитываться при обработке PSD‑файлов. Пожалуйста, используйте этот метод каждый раз, когда <br/>            вызываются FontSettings.SetFontsFolder(fontsFolder) или FontSettings.Reset() для PSD‑изображений. Без вызова этого метода нет гарантии, что шрифты будут обновлены. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__1}


```
 get_default_fonts_folders() 
```

Получает папки шрифтов по умолчанию.

**Returns**

| Тип | Описание |
| :- | :- |
| string[] | Возвращает системную папку |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__2}


```
 get_fonts_folders() 
```

Получает копию массива, содержащего список папок, где Aspose.Words ищет TrueType‑шрифты.

**Returns**

| Тип | Описание |
| :- | :- |
| string[] | Копия текущих расположений шрифтов. |


### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_3}


```
 set_fonts_folder(font_folder) 
```

Это сокращение к [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) для установки только одной папки шрифтов.<br/>            Проверки папки шрифтов не выполняются.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_folder | string | Папка шрифтов. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_4}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Устанавливает папки, из которых загружаются TrueType‑шрифты, и очищает все загруженные шрифты.<br/>            Проверки папок шрифтов не выполняются.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| fonts_folders | string[] | Папки шрифтов. |
| recursive | bool | если установлено в <c>true</c> [recursive]. |

