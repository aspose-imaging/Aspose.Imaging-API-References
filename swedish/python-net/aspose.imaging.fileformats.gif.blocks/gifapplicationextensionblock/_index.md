---
title: "GifApplicationExtensionBlock-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---

**Summary:** Gif application extension block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifApplicationExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock__1) | Initierar en ny instans av klassen [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/). |
| [GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data)](#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2) | Initierar en ny instans av klassen [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| APPLICATION_AUTHENTICATION_CODE_SIZE [static] | int | r | Anger storleken på applikationsautentiseringskoden. |
| APPLICATION_IDENTIFIER_SIZE [static] | int | r | Anger storleken på applikationsidentifieraren. |
| BLOCK_HEADER_SIZE [static] | int | r | Anger storleken på blockhuvudet. |
| BLOCK_SIZE [static] | System.Byte | r | Utökningens namn + versionsblockets storlek. |
| EXTENSION_INTRODUCER [statisk] | System.Byte | r | Extension‑introducer. |
| EXTENSION_LABEL [statisk] | System.Byte | r | Utökningens etikett. |
| application_authentication_code | System.Byte | r/w | Hämtar eller anger applikationsautentiseringskoden. |
| application_data | System.Byte | r/w | Hämtar eller anger applikationsdata. |
| application_identifier | string | r/w | Hämtar eller anger applikationsidentifieraren. |
| is_changed | bool | r/w | Hämtar eller anger ett värde som indikerar om blocket har ändrats och kräver sparning. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Sparar blocket till den angivna strömmen. |


### Constructor: GifApplicationExtensionBlock() {#GifApplicationExtensionBlock__1}


```
 GifApplicationExtensionBlock() 
```

Initierar en ny instans av klassen [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/).

### Constructor: GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) {#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2}


```
 GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) 
```

Initierar en ny instans av klassen [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| application_identifier | string | Applikationsidentifieraren. |
| application_authentication_code | System.Byte | Applikationsautentiseringskoden. |
| application_data | System.Byte | Applikationsdata. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Sparar blocket till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara data till. |

