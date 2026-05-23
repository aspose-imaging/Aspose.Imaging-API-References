---
title: "Класс GifApplicationExtensionBlock"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---

**Summary:** Gif application extension block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifApplicationExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock__1) | Инициализирует новый экземпляр класса [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/). |
| [GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data)](#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2) | Инициализирует новый экземпляр класса [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| APPLICATION_AUTHENTICATION_CODE_SIZE [static] | int | r | Указывает размер кода аутентификации приложения. |
| APPLICATION_IDENTIFIER_SIZE [static] | int | r | Указывает размер идентификатора приложения. |
| BLOCK_HEADER_SIZE [static] | int | r | Указывает размер заголовка блока. |
| BLOCK_SIZE [static] | System.Byte | r | Размер блока имени расширения и версии |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Ввод расширения. |
| EXTENSION_LABEL [static] | System.Byte | r | Метка расширения. |
| application_authentication_code | System.Byte | r/w | Получает или задает код аутентификации приложения. |
| application_data | System.Byte | r/w | Получает или задает данные приложения. |
| application_identifier | string | r/w | Получает или задает идентификатор приложения. |
| is_changed | bool | r/w | Получает или задает значение, указывающее, изменён ли блок и требует ли сохранения. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Сохраняет блок в указанный поток. |


### Constructor: GifApplicationExtensionBlock() {#GifApplicationExtensionBlock__1}


```
 GifApplicationExtensionBlock() 
```

Инициализирует новый экземпляр класса [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/).

### Constructor: GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) {#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2}


```
 GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) 
```

Инициализирует новый экземпляр класса [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| application_identifier | string | Идентификатор приложения. |
| application_authentication_code | System.Byte | Код аутентификации приложения. |
| application_data | System.Byte | Данные приложения. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Сохраняет блок в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save data to. |

