---
title: "ApngOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'API per la creazione del formato di file immagine Animated PNG Animated Portable Network Graphics è uno strumento dinamico per gli sviluppatori che desiderano generare immagini animate accattivanti."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.imageoptions/apngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.PngOptions](../../com.aspose.imaging.imageoptions/pngoptions)
```
public class ApngOptions extends PngOptions
```

L'API per la creazione del formato di file immagine Animated PNG (Animated Portable Network Graphics) è uno strumento dinamico per gli sviluppatori che desiderano generare immagini animate accattivanti. Con opzioni personalizzabili come la durata dei fotogrammi e il numero di volte in cui ripetere, questa API consente di perfezionare i contenuti animati secondo esigenze specifiche. Che si tratti di creare grafiche web coinvolgenti o visuali interattive, è possibile sfruttare questa API per incorporare senza soluzione di continuità immagini APNG con un controllo preciso sui parametri di animazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ApngOptions()](#ApngOptions--) | Inizializza una nuova istanza della classe [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions). |
| [ApngOptions(ApngOptions apngOptions)](#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-) | Inizializza una nuova istanza della classe `ApngOptions`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNumPlays()](#getNumPlays--) | Restituisce il numero di volte in cui ripetere l'animazione. |
| [setNumPlays(int value)](#setNumPlays-int-) | Imposta il numero di volte in cui ripetere l'animazione. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Restituisce la durata predefinita del fotogramma. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Imposta la durata predefinita del fotogramma. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Esporta in animazione APNG con cicli di animazione illimitati come impostazione predefinita
    image.save("Animation1.webp.png", new ApngOptions());
    // Configurazione dei cicli di animazione
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // Configurazione della durata predefinita del fotogramma
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngOptions() {#ApngOptions--}
```
public ApngOptions()
```


Inizializza una nuova istanza della classe [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions).

### ApngOptions(ApngOptions apngOptions) {#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-}
```
public ApngOptions(ApngOptions apngOptions)
```


Inizializza una nuova istanza della classe `ApngOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| apngOptions | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | Le opzioni PNG. |

### getNumPlays() {#getNumPlays--}
```
public final int getNumPlays()
```


Restituisce il numero di volte per ripetere l'animazione. 0 indica un ciclo infinito.

**Returns:**
int

**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Esporta in animazione APNG con cicli di animazione illimitati come impostazione predefinita
    image.save("Animation1.webp.png", new ApngOptions());
    // Configurazione dei cicli di animazione
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### setNumPlays(int value) {#setNumPlays-int-}
```
public final void setNumPlays(int value)
```


Imposta il numero di volte per ripetere l'animazione. 0 indica un ciclo infinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Esporta in animazione APNG con cicli di animazione illimitati come impostazione predefinita
    image.save("Animation1.webp.png", new ApngOptions());
    // Configurazione dei cicli di animazione
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public final long getDefaultFrameTime()
```


Restituisce la durata predefinita del fotogramma.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public final void setDefaultFrameTime(long value)
```


Imposta la durata predefinita del fotogramma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

