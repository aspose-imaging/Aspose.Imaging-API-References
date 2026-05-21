---
title: "PngLoadOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die PNG-Ladeoptionen."
type: docs
weight: 18
url: /de/java/com.aspose.imaging.imageloadoptions/pngloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

Die PNG-Ladeoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | Initialisiert eine neue Instanz der `PngLoadOptions`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Liest oder setzt einen Wert, der angibt, ob [strict mode] aktiv ist. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Liest oder setzt einen Wert, der angibt, ob [strict mode] aktiv ist. |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


Initialisiert eine neue Instanz der `PngLoadOptions`-Klasse.

### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


Liest oder setzt einen Wert, der angibt, ob [strict mode] aktiv ist.

**Returns:**
boolean – ein Wert, der angibt, ob [strict mode] aktiv ist.
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [strict mode] aktiv ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob [strict mode] aktiv ist. |


**Example: The following example shows how to read PNG file : a strict mode.**
Das folgende Beispiel zeigt, wie man eine PNG‑Datei liest : im strict mode. Der strict mode ermöglicht das Auffinden potenzieller Probleme : PNG‑Bilder, z. B. nicht erkannte Datenblöcke, unerwartetes Dateiende. Solche Dateien können weiterhin : im Standard‑ (non‑strict)‑Modus von Aspose.Imaging und von gängigen Betrachtern geöffnet werden. Versuche jedoch, sie : im strict mode zu öffnen, führen zu einer entsprechenden Ausnahme.
``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1442\\";
String inputImage = dir + "FC5F1998104EB92469CB14070628073616BB28F9.png";
String outputImage = inputImage + ".png";

// Standardmodus (non‑strict) – erfolgreich gelesen.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputImage);
try {
    image.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image.close();
}

// Strict mode – ImageLoadException : Unerwartetes Dateiende.
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

