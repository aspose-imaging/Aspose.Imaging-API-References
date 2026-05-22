---
title: "Énumération WmfCompression"
type: docs
weight: 70
url: /fr/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/
---

L'énumération Compression spécifie le type de compression pour une image bitmap.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfCompression

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| BI_BITFIELDS | Le bitmap n’est pas compressé et la table de couleurs se compose de trois masques de couleur DWORD qui<br/>                spécifient respectivement les composantes rouge, verte et bleue de chaque pixel.<br/>                Ceci est valable lorsqu’il est utilisé avec des bitmaps de 16 et 32 bits par pixel. |
| BI_CMYK | L’image est au format CMYK non compressé. |
| BI_CMYKRLE4 | Un format CMYK qui utilise la compression RLE pour les bitmaps de 4 bits par pixel.<br/>                La compression utilise un format de 2 octets composé d’un octet de compteur suivi de deux index de couleur de longueur mot. |
| BI_CMYKRLE8 | Un format CMYK qui utilise la compression RLE pour les bitmaps de 8 bits par pixel.<br/>                La compression utilise un format de 2 octets composé d’un octet de compteur suivi d’un octet contenant un index de couleur. |
| BI_JPEG | L’image est une image JPEG, comme spécifié dans [JFIF]. Cette valeur DOIT uniquement être utilisée dans certaines opérations de bitmap<br/>                , telles que le passage direct JPEG. L’application DOIT interroger la prise en charge du passage direct,<br/>                car tous les appareils ne supportent pas le passage direct JPEG. L’utilisation de bitmaps non RGB PEUT limiter la portabilité<br/>                du métafichier vers d’autres appareils. Par exemple, les contextes de périphérique d’affichage ne supportent généralement pas ce passage direct |
| BI_PNG | L’image est une image PNG, comme spécifié dans [RFC2083]. Cette valeur DOIT uniquement être utilisée dans certaines opérations de bitmap,<br/>                telles que le passage direct JPEG/PNG. L’application DOIT interroger la prise en charge du passage direct, car tous les appareils<br/>                ne supportent pas le passage direct JPEG/PNG. L’utilisation de bitmaps non RGB PEUT limiter la portabilité du métafichier vers d’autres appareils.<br/>                Par exemple, les contextes de périphérique d’affichage ne supportent généralement pas ce passage direct. |
| BI_RGB | Le bitmap est au format rouge vert bleu (RGB) non compressé, qui n'est pas compressé et n'utilise pas de masques de couleur. |
| BI_RLE4 | Un format RGB qui utilise la compression RLE pour les bitmaps avec 4 bits par pixel.<br/>                La compression utilise un format de 2 octets composé d'un octet de comptage suivi de deux index de couleur de longueur mot |
| BI_RLE8 | Un format RGB qui utilise la compression par codage de longueur d'exécution (RLE) pour les bitmaps avec 8 bits par pixel.<br/>                La compression utilise un format de 2 octets composé d'un octet de comptage suivi d'un octet contenant un index de couleur. |
