---
title: "PngLoadOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni di caricamento png."
type: docs
weight: 18
url: /it/java/com.aspose.imaging.imageloadoptions/pngloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

Le opzioni di caricamento png.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | Inizializza una nuova istanza della classe `PngLoadOptions`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Ottiene o imposta un valore che indica se [strict mode]. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Ottiene o imposta un valore che indica se [strict mode]. |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


Inizializza una nuova istanza della classe `PngLoadOptions`.

### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


Ottiene o imposta un valore che indica se [strict mode].

**Returns:**
boolean - un valore che indica se [strict mode].
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


Ottiene o imposta un valore che indica se [strict mode].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se [strict mode]. |


**Example: The following example shows how to read PNG file : a strict mode.**
Il seguente esempio mostra come leggere un file PNG : [strict mode]. La modalità strict consente di trovare potenziali problemi : immagini PNG, ad esempio blocchi di dati non riconosciuti, fine file inaspettata. Tali file possono comunque essere aperti : modalità predefinita (non-strict) da Aspose.Imaging e anche dai visualizzatori comuni. Tuttavia, qualsiasi tentativo di aprirli : la modalità strict genera un'eccezione corrispondente.
``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1442\\";
String inputImage = dir + "FC5F1998104EB92469CB14070628073616BB28F9.png";
String outputImage = inputImage + ".png";

// Modalità predefinita (non-strict) - lettura riuscita.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputImage);
try {
    image.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image.close();
}

// Modalità strict - ImageLoadException : Fine file inaspettata.
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

