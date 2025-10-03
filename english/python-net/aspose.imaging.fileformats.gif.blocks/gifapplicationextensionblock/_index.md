---
title: GifApplicationExtensionBlock Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---

**Summary:** Gif application extension block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifApplicationExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock__1) | Initializes a new instance of the [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) class. |
| [GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data)](#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2) | Initializes a new instance of the [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| APPLICATION_AUTHENTICATION_CODE_SIZE [static] | int | r | Specifies the application authentication code size. |
| APPLICATION_IDENTIFIER_SIZE [static] | int | r | Specifies the application identifier size. |
| BLOCK_HEADER_SIZE [static] | int | r | Specifies the block header size. |
| BLOCK_SIZE [static] | System.Byte | r | Extension name + version block size |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Extension introducer. |
| EXTENSION_LABEL [static] | System.Byte | r | Extension label. |
| application_authentication_code | System.Byte | r/w | Gets or sets the application authentication code. |
| application_data | System.Byte | r/w | Gets or sets the application data. |
| application_identifier | string | r/w | Gets or sets the application identifier. |
| is_changed | bool | r/w | Gets or sets a value indicating whether block has changed and requires save. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Saves the block to the specified stream. |


### Constructor: GifApplicationExtensionBlock() {#GifApplicationExtensionBlock__1}


```
 GifApplicationExtensionBlock() 
```

Initializes a new instance of the [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) class.

### Constructor: GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) {#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2}


```
 GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) 
```

Initializes a new instance of the [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| application_identifier | string | The application identifier. |
| application_authentication_code | System.Byte | The application authentication code. |
| application_data | System.Byte | The application data. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Saves the block to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save data to. |

