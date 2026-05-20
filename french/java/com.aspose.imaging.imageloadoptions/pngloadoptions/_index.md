---
title: "PngLoadOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options de chargement png."
type: docs
weight: 18
url: /fr/java/com.aspose.imaging.imageloadoptions/pngloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

Les options de chargement png.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | Initialise une nouvelle instance de la classe `PngLoadOptions`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Obtient ou définit une valeur indiquant si [strict mode]. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Obtient ou définit une valeur indiquant si [strict mode]. |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


Initialise une nouvelle instance de la classe `PngLoadOptions`.

### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


Obtient ou définit une valeur indiquant si [strict mode].

**Returns:**
boolean - une valeur indiquant si [strict mode].
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


Obtient ou définit une valeur indiquant si [strict mode].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si [strict mode]. |


**Example: The following example shows how to read PNG file : a strict mode.**
L'exemple suivant montre comment lire un fichier PNG : en mode strict. Le mode strict permet de détecter les problèmes potentiels : images PNG, par ex. blocs de données non reconnus, fin de fichier inattendue. De tels fichiers peuvent encore être ouverts : mode par défaut (non strict) par Aspose.Imaging et par les visionneuses courantes également. Cependant, toute tentative de les ouvrir : le mode strict entraîne une exception correspondante.
``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1442\\";
String inputImage = dir + "FC5F1998104EB92469CB14070628073616BB28F9.png";
String outputImage = inputImage + ".png";

// Mode par défaut (non strict) - lecture réussie.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputImage);
try {
    image.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image.close();
}

// Mode strict - ImageLoadException : Fin de fichier inattendue.
com.aspose.imaging.Image image2 = com.aspose.imaging.Image.load(inputImage, new com.aspose.imaging.imageloadoptions.PngLoadOptions() {{
    setStrictMode(true);
    }});
                
try {
    image2.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image2.close();
}
```

