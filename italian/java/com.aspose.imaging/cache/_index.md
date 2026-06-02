---
title: "Cache"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Contiene le impostazioni della cache."
type: docs
weight: 15
url: /it/java/com.aspose.imaging/cache/
---
**Inheritance:**
java.lang.Object
```
public final class Cache
```

Contiene le impostazioni della cache.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Ottiene un valore che indica se la riallocazione dovrebbe essere esatta o no. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Imposta un valore che indica se la riallocazione dovrebbe essere esatta o no. |
| [getCacheFolder()](#getCacheFolder--) | Ottiene la cartella della cache. |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Imposta la cartella della cache. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Ottiene il conteggio dei byte allocati in memoria. |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Ottiene il conteggio dei byte allocati su disco. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Ottiene la memoria massima disponibile per la cache in memoria. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Imposta la memoria massima disponibile per la cache in memoria. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Ottiene lo spazio su disco massimo disponibile per la cache. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Imposta lo spazio su disco massimo disponibile per la cache. |
| [getCacheType()](#getCacheType--) | Ottiene o imposta lo schema della cache utilizzato. |
| [setCacheType(int value)](#setCacheType-int-) | Imposta lo schema della cache utilizzato. |
| [setDefaults()](#setDefaults--) | Imposta le impostazioni `Cache` ai valori predefiniti. |

## Example: This example demonstrates how to use com.aspose.imaging.Cache

``` java
// Per impostazione predefinita la cartella della cache è impostata sulla directory temporanea locale dell'utente.
// È possibile specificare anche un'altra cartella della cache rispetto a quella predefinita come segue:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// La modalità automatica è flessibile ed efficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Il valore predefinito è 0, il che significa che non c'è limite superiore
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Non è consigliabile modificare la proprietà seguente poiché potrebbe influire notevolmente sulle prestazioni
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// In qualsiasi momento è possibile verificare quanti byte sono attualmente allocati per la memoria o il disco
// cache esaminando le proprietà seguenti
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Esegui un'elaborazione di immagini come segue
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Dopo aver eseguito il codice sopra, verranno allocati 40000 byte in memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Le proprietà di allocazione possono essere usate per verificare se tutti gli oggetti Aspose.Imaging sono stati correttamente eliminati.
// Nel caso in cui ti sia dimenticato di chiamare dispose su qualche oggetto, i valori della cache saranno diversi da 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getExactReallocateOnly() {#getExactReallocateOnly--}
```
public static boolean getExactReallocateOnly()
```


Restituisce un valore che indica se la riallocazione deve essere esatta o meno. Se la riallocazione non è esatta, le prestazioni dovrebbero essere superiori.

**Returns:**
boolean - `true` se la riallocazione è esatta; altrimenti, `false`.

La riallocazione esatta effettuerà la riallocazione di memoria aggiuntiva solo fino al limite superiore specificato. Quando si passa il limite superiore per la memoria in RAM durante la riallocazione, i dati nella cache verranno copiati su disco, se possibile. Quando si passa il limite superiore per la memoria su disco durante la riallocazione, viene sollevata l'eccezione appropriata. Le prestazioni dovrebbero essere superiori se questa opzione è disattivata, poiché non verrà eseguita alcuna copia aggiuntiva, se possibile; tuttavia ciò potrebbe anche portare a superare i limiti superiori specificati per la memoria o il disco.
### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Imposta un valore che indica se la riallocazione deve essere esatta o meno. Se la riallocazione non è esatta, le prestazioni dovrebbero essere superiori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | `true` se la riallocazione è esatta; altrimenti, `false`. |

La riallocazione esatta effettuerà la riallocazione di memoria aggiuntiva solo fino al limite superiore specificato. Quando si passa il limite superiore per la memoria in RAM durante la riallocazione, i dati nella cache verranno copiati su disco, se possibile. Quando si passa il limite superiore per la memoria su disco durante la riallocazione, viene sollevata l'eccezione appropriata. Le prestazioni dovrebbero essere superiori se questa opzione è disattivata, poiché non verrà eseguita alcuna copia aggiuntiva, se possibile; tuttavia ciò potrebbe anche portare a superare i limiti superiori specificati per la memoria o il disco. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Per impostazione predefinita la cartella della cache è impostata sulla directory temporanea locale dell'utente.
// È possibile specificare anche un'altra cartella della cache rispetto a quella predefinita come segue:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// La modalità automatica è flessibile ed efficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Il valore predefinito è 0, il che significa che non c'è limite superiore
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Non è consigliabile modificare la proprietà seguente poiché potrebbe influire notevolmente sulle prestazioni
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// In qualsiasi momento è possibile verificare quanti byte sono attualmente allocati per la memoria o il disco
// cache esaminando le proprietà seguenti
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Esegui un'elaborazione di immagini come segue
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Dopo aver eseguito il codice sopra, verranno allocati 40000 byte in memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Le proprietà di allocazione possono essere usate per verificare se tutti gli oggetti Aspose.Imaging sono stati correttamente eliminati.
// Nel caso in cui ti sia dimenticato di chiamare dispose su qualche oggetto, i valori della cache saranno diversi da 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Ottiene la cartella della cache.

**Returns:**
java.lang.String - La cartella della cache.
### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


Imposta la cartella della cache.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | La cartella della cache. |

### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Ottiene il conteggio dei byte allocati in memoria.

**Returns:**
long - Il conteggio dei byte allocati in memoria.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Per impostazione predefinita la cartella della cache è impostata sulla directory temporanea locale dell'utente.
// È possibile specificare anche un'altra cartella della cache rispetto a quella predefinita come segue:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// La modalità automatica è flessibile ed efficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Il valore predefinito è 0, il che significa che non c'è limite superiore
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Non è consigliabile modificare la proprietà seguente poiché potrebbe influire notevolmente sulle prestazioni
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// In qualsiasi momento è possibile verificare quanti byte sono attualmente allocati per la memoria o il disco
// cache esaminando le proprietà seguenti
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Esegui un'elaborazione di immagini come segue
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Dopo aver eseguito il codice sopra, verranno allocati 40000 byte in memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Le proprietà di allocazione possono essere usate per verificare se tutti gli oggetti Aspose.Imaging sono stati correttamente eliminati.
// Nel caso in cui ti sia dimenticato di chiamare dispose su qualche oggetto, i valori della cache saranno diversi da 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Ottiene il conteggio dei byte allocati su disco.

**Returns:**
long - Il conteggio dei byte allocati su disco.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Per impostazione predefinita la cartella della cache è impostata sulla directory temporanea locale dell'utente.
// È possibile specificare anche un'altra cartella della cache rispetto a quella predefinita come segue:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// La modalità automatica è flessibile ed efficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Il valore predefinito è 0, il che significa che non c'è limite superiore
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Non è consigliabile modificare la proprietà seguente poiché potrebbe influire notevolmente sulle prestazioni
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// In qualsiasi momento è possibile verificare quanti byte sono attualmente allocati per la memoria o il disco
// cache esaminando le proprietà seguenti
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Esegui un'elaborazione di immagini come segue
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Dopo aver eseguito il codice sopra, verranno allocati 40000 byte in memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Le proprietà di allocazione possono essere usate per verificare se tutti gli oggetti Aspose.Imaging sono stati correttamente eliminati.
// Nel caso in cui ti sia dimenticato di chiamare dispose su qualche oggetto, i valori della cache saranno diversi da 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Restituisce la memoria massima disponibile per la cache in memoria. Il valore specificato è il conteggio dei megabyte.

**Returns:**
int - La memoria massima per la cache.

Un valore di 0 consumerà tutta la memoria disponibile e funge da nessun limite superiore.
### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Imposta la memoria massima disponibile per la cache in memoria. Il valore specificato è il conteggio dei megabyte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | La memoria massima per la cache. |

Un valore di 0 consumerà tutta la memoria disponibile e funge da nessun limite superiore. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Per impostazione predefinita la cartella della cache è impostata sulla directory temporanea locale dell'utente.
// È possibile specificare anche un'altra cartella della cache rispetto a quella predefinita come segue:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// La modalità automatica è flessibile ed efficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Il valore predefinito è 0, il che significa che non c'è limite superiore
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Non è consigliabile modificare la proprietà seguente poiché potrebbe influire notevolmente sulle prestazioni
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// In qualsiasi momento è possibile verificare quanti byte sono attualmente allocati per la memoria o il disco
// cache esaminando le proprietà seguenti
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Esegui un'elaborazione di immagini come segue
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Dopo aver eseguito il codice sopra, verranno allocati 40000 byte in memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Le proprietà di allocazione possono essere usate per verificare se tutti gli oggetti Aspose.Imaging sono stati correttamente eliminati.
// Nel caso in cui ti sia dimenticato di chiamare dispose su qualche oggetto, i valori della cache saranno diversi da 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Ottiene lo spazio su disco massimo disponibile per la cache. Il valore specificato è il conteggio dei megabyte.

**Returns:**
int - Lo spazio su disco massimo disponibile per la cache.

Un valore di 0 consumerà tutta la memoria disponibile e funge da nessun limite superiore.
### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Imposta lo spazio su disco massimo disponibile per la cache. Il valore specificato è il conteggio dei megabyte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Lo spazio su disco massimo disponibile per la cache. |

Un valore di 0 consumerà tutta la memoria disponibile e funge da nessun limite superiore. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Per impostazione predefinita la cartella della cache è impostata sulla directory temporanea locale dell'utente.
// È possibile specificare anche un'altra cartella della cache rispetto a quella predefinita come segue:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// La modalità automatica è flessibile ed efficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Il valore predefinito è 0, il che significa che non c'è limite superiore
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Non è consigliabile modificare la proprietà seguente poiché potrebbe influire notevolmente sulle prestazioni
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// In qualsiasi momento è possibile verificare quanti byte sono attualmente allocati per la memoria o il disco
// cache esaminando le proprietà seguenti
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Esegui un'elaborazione di immagini come segue
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Dopo aver eseguito il codice sopra, verranno allocati 40000 byte in memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Le proprietà di allocazione possono essere usate per verificare se tutti gli oggetti Aspose.Imaging sono stati correttamente eliminati.
// Nel caso in cui ti sia dimenticato di chiamare dispose su qualche oggetto, i valori della cache saranno diversi da 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Ottiene o imposta lo schema della cache utilizzato.

**Returns:**
int - Lo schema di cache utilizzato.
### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Imposta lo schema della cache utilizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Lo schema di cache utilizzato. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Per impostazione predefinita la cartella della cache è impostata sulla directory temporanea locale dell'utente.
// È possibile specificare anche un'altra cartella della cache rispetto a quella predefinita come segue:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// La modalità automatica è flessibile ed efficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Il valore predefinito è 0, il che significa che non c'è limite superiore
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Non è consigliabile modificare la proprietà seguente poiché potrebbe influire notevolmente sulle prestazioni
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// In qualsiasi momento è possibile verificare quanti byte sono attualmente allocati per la memoria o il disco
// cache esaminando le proprietà seguenti
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Esegui un'elaborazione di immagini come segue
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Dopo aver eseguito il codice sopra, verranno allocati 40000 byte in memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Le proprietà di allocazione possono essere usate per verificare se tutti gli oggetti Aspose.Imaging sono stati correttamente eliminati.
// Nel caso in cui ti sia dimenticato di chiamare dispose su qualche oggetto, i valori della cache saranno diversi da 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Imposta le impostazioni `Cache` ai valori predefiniti.

