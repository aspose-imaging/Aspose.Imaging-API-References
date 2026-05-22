---
title: "GifApplicationExtensionBlock 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---

**Summary:** Gif application extension block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifApplicationExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock__1) | 初始化 [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) 类的新实例。 |
| [GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data)](#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2) | 初始化 [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| APPLICATION_AUTHENTICATION_CODE_SIZE [static] | int | r | 指定应用程序认证代码大小。 |
| APPLICATION_IDENTIFIER_SIZE [static] | int | r | 指定应用程序标识符大小。 |
| BLOCK_HEADER_SIZE [static] | int | r | 指定块头大小。 |
| BLOCK_SIZE [static] | System.Byte | r | 扩展名 + 版本块大小 |
| EXTENSION_INTRODUCER [static] | System.Byte | r | 扩展引入器。 |
| EXTENSION_LABEL [static] | System.Byte | r | 扩展标签。 |
| application_authentication_code | System.Byte | r/w | 获取或设置应用程序认证代码。 |
| application_data | System.Byte | r/w | 获取或设置应用程序数据。 |
| application_identifier | string | r/w | 获取或设置应用程序标识符。 |
| is_changed | bool | r/w | 获取或设置一个值，指示块是否已更改并需要保存。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [save(stream)](#save_stream_1) | 将块保存到指定的流。 |


### Constructor: GifApplicationExtensionBlock() {#GifApplicationExtensionBlock__1}


```
 GifApplicationExtensionBlock() 
```

初始化 [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) 类的新实例。

### Constructor: GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) {#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2}


```
 GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) 
```

初始化 [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| application_identifier | string | 应用程序标识符。 |
| application_authentication_code | System.Byte | 应用程序认证代码。 |
| application_data | System.Byte | 应用程序数据。 |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

将块保存到指定的流。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存数据的流。 |

