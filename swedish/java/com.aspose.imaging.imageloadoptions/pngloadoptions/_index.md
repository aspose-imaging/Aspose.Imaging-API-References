---
title: "PngLoadOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "PNG-inläsningsalternativen."
type: docs
weight: 18
url: /sv/java/com.aspose.imaging.imageloadoptions/pngloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

PNG-inläsningsalternativen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | Initierar en ny instans av klassen `PngLoadOptions`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Hämtar eller anger ett värde som indikerar om [strict mode]. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Hämtar eller anger ett värde som indikerar om [strict mode]. |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


Initierar en ny instans av klassen `PngLoadOptions`.

### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


Hämtar eller anger ett värde som indikerar om [strict mode].

**Returns:**
boolean - ett värde som indikerar om [strict mode].
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


Hämtar eller anger ett värde som indikerar om [strict mode].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om [strict mode]. |


**Example: The following example shows how to read PNG file : a strict mode.**
Följande exempel visar hur man läser PNG‑fil : strict mode. strict mode möjliggör att hitta potentiella problem : PNG‑bilder, t.ex. oidentifierade datablock, oväntat filslut. Sådana filer kan fortfarande öppnas : default (non‑strict) läge av Aspose.Imaging och av vanliga visare också. Däremot orsakar alla försök att öppna dem : strict mode ett motsvarande undantag.
``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1442\\";
String inputImage = dir + "FC5F1998104EB92469CB14070628073616BB28F9.png";
String outputImage = inputImage + ".png";

// Standardläge (non‑strict) - lyckad läsning.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputImage);
try {
    image.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image.close();
}

// Strict mode - ImageLoadException : Oväntat filslut.
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

