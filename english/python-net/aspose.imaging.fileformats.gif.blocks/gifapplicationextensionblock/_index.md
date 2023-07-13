---
title: GifApplicationExtensionBlock Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---

Gif application extension block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifApplicationExtensionBlock

**Inheritance:** IGifBlock, GifBlock

**Aspose.Imaging Version:** 23.6

The GifApplicationExtensionBlock type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock__0) | Initializes a new instance of the [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) class. |
| [GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data)](#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_1) | Initializes a new instance of the [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| is_changed | bool | r/w | Gets or sets a value indicating whether block has changed and requires save. |
| EXTENSION_INTRODUCER [static] | byte | r | Extension introducer. |
| application_authentication_code | byte | r/w | Gets or sets the application authentication code. |
| application_identifier | string | r/w | Gets or sets the application identifier. |
| application_data | byte | r/w | Gets or sets the application data. |
| BLOCK_HEADER_SIZE [static] | int | r | Specifies the block header size. |
| EXTENSION_LABEL [static] | byte | r | Extension label. |
| BLOCK_SIZE [static] | byte | r | Extension name + version block size |
| APPLICATION_IDENTIFIER_SIZE [static] | int | r | Specifies the application identifier size. |
| APPLICATION_AUTHENTICATION_CODE_SIZE [static] | int | r | Specifies the application authentication code size. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_2) | Saves the block to the specified stream. |

### GifApplicationExtensionBlock() {#GifApplicationExtensionBlock__0}


```
 GifApplicationExtensionBlock() 
```

Initializes a new instance of the [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) class.

### GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) {#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_1}


```
 GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) 
```

Initializes a new instance of the [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| application_identifier | string | The application identifier. |
| application_authentication_code | byte | The application authentication code. |
| application_data | byte | The application data. |

### save(stream) {#save_stream_2}


```
 save(stream) 
```

Saves the block to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save data to. |

