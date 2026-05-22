---
title: "Classe GifApplicationExtensionBlock"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---

**Summary:** Gif application extension block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifApplicationExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock__1) | Initialise une nouvelle instance de la classe [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/). |
| [GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data)](#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2) | Initialise une nouvelle instance de la classe [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| APPLICATION_AUTHENTICATION_CODE_SIZE [static] | int | r | Spécifie la taille du code d'authentification de l'application. |
| APPLICATION_IDENTIFIER_SIZE [static] | int | r | Spécifie la taille de l'identifiant de l'application. |
| BLOCK_HEADER_SIZE [static] | int | r | Spécifie la taille de l'en-tête du bloc. |
| BLOCK_SIZE [static] | System.Byte | r | Taille du bloc nom de l'extension + version |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introduiseur d'extension. |
| EXTENSION_LABEL [statique] | System.Byte | r | Étiquette de l'extension. |
| application_authentication_code | System.Byte | r/w | Obtient ou définit le code d'authentification de l'application. |
| application_data | System.Byte | r/w | Obtient ou définit les données de l'application. |
| application_identifier | string | r/w | Obtient ou définit l'identifiant de l'application. |
| is_changed | bool | r/w | Obtient ou définit une valeur indiquant si le bloc a changé et nécessite une sauvegarde. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Enregistre le bloc dans le flux spécifié. |


### Constructor: GifApplicationExtensionBlock() {#GifApplicationExtensionBlock__1}


```
 GifApplicationExtensionBlock() 
```

Initialise une nouvelle instance de la classe [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/).

### Constructor: GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) {#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2}


```
 GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) 
```

Initialise une nouvelle instance de la classe [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| application_identifier | string | L'identifiant de l'application. |
| application_authentication_code | System.Byte | Le code d'authentification de l'application. |
| application_data | System.Byte | Les données de l'application. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Enregistre le bloc dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données. |

