---
title: "GifApplicationExtensionBlock Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---

**Summary:** Gif application extension block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifApplicationExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock__1) | Yeni bir [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) sınıfının örneğini başlatır. |
| [GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data)](#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2) | Yeni bir [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| APPLICATION_AUTHENTICATION_CODE_SIZE [static] | int | r | Uygulama kimlik doğrulama kodu boyutunu belirtir. |
| APPLICATION_IDENTIFIER_SIZE [static] | int | r | Uygulama tanımlayıcı boyutunu belirtir. |
| BLOCK_HEADER_SIZE [static] | int | r | Blok başlık boyutunu belirtir. |
| BLOCK_SIZE [static] | System.Byte | r | Uzantı adı + sürüm blok boyutu |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Uzantı tanıtıcı. |
| EXTENSION_LABEL [static] | System.Byte | r | Uzantı etiketi. |
| application_authentication_code | System.Byte | r/w | Uygulama kimlik doğrulama kodunu alır veya ayarlar. |
| application_data | System.Byte | r/w | Uygulama verisini alır veya ayarlar. |
| application_identifier | string | r/w | Uygulama tanımlayıcısını alır veya ayarlar. |
| is_changed | bool | r/w | Blok değişti ve kaydedilmesi gerekiyor mu gösteren bir değeri alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream)](#save_stream_1) | Bloğu belirtilen akışa kaydeder. |


### Constructor: GifApplicationExtensionBlock() {#GifApplicationExtensionBlock__1}


```
 GifApplicationExtensionBlock() 
```

Yeni bir [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) sınıfının örneğini başlatır.

### Constructor: GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) {#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2}


```
 GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) 
```

Yeni bir [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| application_identifier | string | Uygulama tanımlayıcısı. |
| application_authentication_code | System.Byte | Uygulama kimlik doğrulama kodu. |
| application_data | System.Byte | Uygulama verileri. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Bloğu belirtilen akışa kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Verinin kaydedileceği akış. |

