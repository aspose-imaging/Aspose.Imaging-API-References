---
title: "GifApplicationExtensionBlock Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---

**Summary:** Gif application extension block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifApplicationExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock__1) | Initialisiert eine neue Instanz der [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) Klasse. |
| [GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data)](#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2) | Initialisiert eine neue Instanz der [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| APPLICATION_AUTHENTICATION_CODE_SIZE [statisch] | int | r | Gibt die Größe des Anwendungsauthentifizierungscodes an. |
| APPLICATION_IDENTIFIER_SIZE [statisch] | int | r | Gibt die Größe des Anwendungsidentifikators an. |
| BLOCK_HEADER_SIZE [statisch] | int | r | Gibt die Größe des Blockkopfes an. |
| BLOCK_SIZE [statisch] | System.Byte | r | Erweiterungsname + Versionsblockgröße |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Erweiterungs‑Einführer. |
| EXTENSION_LABEL [static] | System.Byte | r | Erweiterungsbezeichnung. |
| application_authentication_code | System.Byte | r/w | Liest oder setzt den Anwendungsauthentifizierungscode. |
| application_data | System.Byte | r/w | Liest oder setzt die Anwendungsdaten. |
| application_identifier | string | r/w | Liest oder setzt den Anwendungsidentifikator. |
| is_changed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob der Block geändert wurde und gespeichert werden muss. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream)](#save_stream_1) | Speichert den Block in den angegebenen Stream. |


### Constructor: GifApplicationExtensionBlock() {#GifApplicationExtensionBlock__1}


```
 GifApplicationExtensionBlock() 
```

Initialisiert eine neue Instanz der [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) Klasse.

### Constructor: GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) {#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2}


```
 GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) 
```

Initialisiert eine neue Instanz der [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| application_identifier | string | Der Anwendungsidentifikator. |
| application_authentication_code | System.Byte | Der Anwendungsauthentifizierungscode. |
| application_data | System.Byte | Die Anwendungsdaten. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Speichert den Block in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem Daten gespeichert werden. |

