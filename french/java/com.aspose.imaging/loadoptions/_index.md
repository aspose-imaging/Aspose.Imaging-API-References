---
title: "LoadOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente les options de chargement."
type: docs
weight: 70
url: /fr/java/com.aspose.imaging/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.progressmanagement.IProgressEventHandler
```
public class LoadOptions implements IProgressEventHandler
```

Représente les options de chargement.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Obtient le mode de récupération des données. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Définit le mode de récupération des données. |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Obtient le `Color` d'arrière-plan de l'`Image`. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.imaging.Color-) | Définit le `Color` d'arrière-plan de l'`Image`. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Obtient une valeur indiquant si la conversion du profil ICC doit être appliquée. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Définit une valeur indiquant si la conversion du profil ICC doit être appliquée. |
| [addCustomFontSource(CustomFontSource source, Object[] args)](#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-) | Ajoute la source de police personnalisée pour fournir des polices spécifiques à l'image. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| [getConcurrentImageProcessing()](#getConcurrentImageProcessing--) | Obtient une valeur indiquant si [concurrent image processing]. |
| [setConcurrentImageProcessing(boolean value)](#setConcurrentImageProcessing-boolean-) | Définit une valeur indiquant si [concurrent image processing]. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | Obtient le gestionnaire d'événement de progression. |
| [setIProgressEventHandler(ProgressEventHandler value)](#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Définit le gestionnaire d'événement de progression. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Obtient le mode de récupération des données.

**Returns:**
int - Le mode de récupération des données.
### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Définit le mode de récupération des données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le mode de récupération des données. |

### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Obtient le `Color` d'arrière-plan de l'`Image`.

**Returns:**
[Color](../../com.aspose.imaging/color) - The background color.

Typiquement, la couleur d'arrière-plan est définie chaque fois que la valeur du pixel ne peut pas être récupérée en raison d'une corruption des données.
### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.imaging.Color-}
```
public void setDataBackgroundColor(Color value)
```


Définit le `Color` d'arrière-plan de l'`Image`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.imaging/color) | La couleur d'arrière-plan. |

Typiquement, la couleur d'arrière-plan est définie chaque fois que la valeur du pixel ne peut pas être récupérée en raison d'une corruption des données. |

### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Obtient une valeur indiquant si la conversion du profil ICC doit être appliquée.

**Returns:**
boolean
### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Définit une valeur indiquant si la conversion du profil ICC doit être appliquée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### addCustomFontSource(CustomFontSource source, Object[] args) {#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-}
```
public final void addCustomFontSource(CustomFontSource source, Object[] args)
```


Ajoute la source de police personnalisée pour fournir des polices spécifiques à l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [CustomFontSource](../../com.aspose.imaging/customfontsource) | La fonction du fournisseur de source de police personnalisée. |
| args | java.lang.Object[] | Les arguments. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.

Valeur : L’indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes

**Returns:**
int - l’indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.

Valeur : L’indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | l’indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |


**Example: The following example shows how to set a memory limit when loading a JPEG image.**
L'exemple suivant montre comment définir une limite de mémoire lors du chargement d'une image JPEG. La limite de mémoire est la taille maximale autorisée (en mégaoctets) pour tous les tampons internes.
``` java
String workDir = "c:\\temp\\";
// Définition d'une limite de mémoire de 50 mégaoctets pour l'image cible chargée
com.aspose.imaging.LoadOptions loadOptions = new com.aspose.imaging.LoadOptions();
loadOptions.setBufferSizeHint(50);
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(workDir + "inputFile.jpg", loadOptions);
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Baseline);
    jpegOptions.setQuality(100);
    image.save(workDir + "outputFile_Baseline.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);
    image.save(workDir + "outputFile_Progressive.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Lossless);
    jpegOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);
    jpegOptions.setBitsPerChannel((byte) 4);
    image.save(workDir + "outputFile_Lossless.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.JpegLs);
    jpegOptions.setJpegLsInterleaveMode(com.aspose.imaging.fileformats.jpeg.JpegLsInterleaveMode.None);
    jpegOptions.setJpegLsAllowedLossyError(3);
    jpegOptions.setJpegLsPreset(null);
    image.save(workDir + "outputFile_JpegLs.jpg", jpegOptions);
} finally {
    image.close();
}
```

### getConcurrentImageProcessing() {#getConcurrentImageProcessing--}
```
public final boolean getConcurrentImageProcessing()
```


Obtient une valeur indiquant si [concurrent image processing].

Valeur : `true` si [concurrent image processing] ; sinon, `false`.

**Returns:**
booléen - une valeur indiquant si [concurrent image processing].
### setConcurrentImageProcessing(boolean value) {#setConcurrentImageProcessing-boolean-}
```
public final void setConcurrentImageProcessing(boolean value)
```


Définit une valeur indiquant si [concurrent image processing].

Valeur : `true` si [concurrent image processing] ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si [concurrent image processing]. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public ProgressEventHandler getIProgressEventHandler()
```


Obtient le gestionnaire d'événement de progression.

Valeur : le gestionnaire d'événement de progression.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setIProgressEventHandler(ProgressEventHandler value) {#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setIProgressEventHandler(ProgressEventHandler value)
```


Définit le gestionnaire d'événement de progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | le gestionnaire d'événement de progression. |

