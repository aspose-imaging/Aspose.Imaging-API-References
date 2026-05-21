---
title: "Cache"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Contient les paramètres du cache."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging/cache/
---
**Inheritance:**
java.lang.Object
```
public final class Cache
```

Contient les paramètres du cache.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Obtient une valeur indiquant si la réallocation doit être exacte ou non. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Définit une valeur indiquant si la réallocation doit être exacte ou non. |
| [getCacheFolder()](#getCacheFolder--) | Obtient le dossier de cache. |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Définit le dossier de cache. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Obtient le nombre d'octets alloués en mémoire. |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Obtient le nombre d'octets alloués sur le disque. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Obtient la mémoire maximale disponible pour le cache en mémoire. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Définit la mémoire maximale disponible pour le cache en mémoire. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Obtient l'espace disque maximal disponible pour le cache. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Définit l'espace disque maximal disponible pour le cache. |
| [getCacheType()](#getCacheType--) | Obtient ou définit le schéma de cache utilisé. |
| [setCacheType(int value)](#setCacheType-int-) | Définit le schéma de cache utilisé. |
| [setDefaults()](#setDefaults--) | Définit les paramètres du `Cache` aux valeurs par défaut. |

## Example: This example demonstrates how to use com.aspose.imaging.Cache

``` java
// Par défaut, le dossier de cache est défini sur le répertoire temporaire local de l'utilisateur.
// Vous pouvez également spécifier un autre dossier de cache que le défaut comme suit :
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Le mode automatique est flexible et efficace
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// La valeur par défaut est 0, ce qui signifie qu'il n'y a pas de limite supérieure
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Il n'est pas recommandé de modifier la propriété suivante car cela peut fortement affecter les performances
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// À tout moment, vous pouvez vérifier combien d'octets sont actuellement alloués pour la mémoire ou le disque
// le cache en examinant les propriétés suivantes
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Effectuez un traitement d'image comme ci‑dessous
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

    // Après l'exécution du code ci‑dessus, 40000 octets seront alloués en mémoire.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Les propriétés d'allocation peuvent être utilisées pour vérifier si tous les objets Aspose.Imaging ont été correctement libérés.
// Dans le cas où vous auriez oublié d'appeler dispose sur un objet, les valeurs du cache seront différentes de 0.
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


Obtient une valeur indiquant si la réallocation doit être exacte ou non. Si la réallocation n'est pas exacte, les performances devraient être supérieures.

**Returns:**
booléen - `true` si la réallocation est exacte ; sinon, `false`.

La réallocation exacte effectuera la réallocation de mémoire supplémentaire uniquement jusqu'à la limite supérieure spécifiée. Lors du passage de la limite supérieure pour la mémoire en cours lors de la réallocation, les données mises en cache seront copiées sur le disque si possible. Lors du passage de la limite supérieure pour la mémoire disque lors de la réallocation, l'exception appropriée est levée. Les performances devraient être supérieures si cette option est désactivée, car aucune copie supplémentaire ne sera effectuée si possible, cependant cela peut également conduire à dépasser les limites supérieures spécifiées pour la mémoire ou le disque.
### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Définit une valeur indiquant si la réallocation doit être exacte ou non. Si la réallocation n'est pas exacte, les performances devraient être supérieures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | `true` si la réallocation est exacte ; sinon, `false`. |

La réallocation exacte effectuera la réallocation de mémoire supplémentaire uniquement jusqu'à la limite supérieure spécifiée. Lors du passage de la limite supérieure pour la mémoire en cours lors de la réallocation, les données mises en cache seront copiées sur le disque si possible. Lors du passage de la limite supérieure pour la mémoire disque lors de la réallocation, l'exception appropriée est levée. Les performances devraient être supérieures si cette option est désactivée, car aucune copie supplémentaire ne sera effectuée si possible, cependant cela peut également conduire à dépasser les limites supérieures spécifiées pour la mémoire ou le disque. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Par défaut, le dossier de cache est défini sur le répertoire temporaire local de l'utilisateur.
// Vous pouvez également spécifier un autre dossier de cache que le défaut comme suit :
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Le mode automatique est flexible et efficace
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// La valeur par défaut est 0, ce qui signifie qu'il n'y a pas de limite supérieure
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Il n'est pas recommandé de modifier la propriété suivante car cela peut fortement affecter les performances
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// À tout moment, vous pouvez vérifier combien d'octets sont actuellement alloués pour la mémoire ou le disque
// le cache en examinant les propriétés suivantes
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Effectuez un traitement d'image comme ci‑dessous
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

    // Après l'exécution du code ci‑dessus, 40000 octets seront alloués en mémoire.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Les propriétés d'allocation peuvent être utilisées pour vérifier si tous les objets Aspose.Imaging ont été correctement libérés.
// Dans le cas où vous auriez oublié d'appeler dispose sur un objet, les valeurs du cache seront différentes de 0.
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


Obtient le dossier de cache.

**Returns:**
java.lang.String - Le dossier du cache.
### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


Définit le dossier de cache.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le dossier du cache. |

### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Obtient le nombre d'octets alloués en mémoire.

**Returns:**
long - Le nombre d'octets alloués en mémoire.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Par défaut, le dossier de cache est défini sur le répertoire temporaire local de l'utilisateur.
// Vous pouvez également spécifier un autre dossier de cache que le défaut comme suit :
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Le mode automatique est flexible et efficace
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// La valeur par défaut est 0, ce qui signifie qu'il n'y a pas de limite supérieure
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Il n'est pas recommandé de modifier la propriété suivante car cela peut fortement affecter les performances
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// À tout moment, vous pouvez vérifier combien d'octets sont actuellement alloués pour la mémoire ou le disque
// le cache en examinant les propriétés suivantes
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Effectuez un traitement d'image comme ci‑dessous
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

    // Après l'exécution du code ci‑dessus, 40000 octets seront alloués en mémoire.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Les propriétés d'allocation peuvent être utilisées pour vérifier si tous les objets Aspose.Imaging ont été correctement libérés.
// Dans le cas où vous auriez oublié d'appeler dispose sur un objet, les valeurs du cache seront différentes de 0.
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


Obtient le nombre d'octets alloués sur le disque.

**Returns:**
long - Le nombre d'octets alloués sur le disque.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Par défaut, le dossier de cache est défini sur le répertoire temporaire local de l'utilisateur.
// Vous pouvez également spécifier un autre dossier de cache que le défaut comme suit :
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Le mode automatique est flexible et efficace
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// La valeur par défaut est 0, ce qui signifie qu'il n'y a pas de limite supérieure
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Il n'est pas recommandé de modifier la propriété suivante car cela peut fortement affecter les performances
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// À tout moment, vous pouvez vérifier combien d'octets sont actuellement alloués pour la mémoire ou le disque
// le cache en examinant les propriétés suivantes
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Effectuez un traitement d'image comme ci‑dessous
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

    // Après l'exécution du code ci‑dessus, 40000 octets seront alloués en mémoire.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Les propriétés d'allocation peuvent être utilisées pour vérifier si tous les objets Aspose.Imaging ont été correctement libérés.
// Dans le cas où vous auriez oublié d'appeler dispose sur un objet, les valeurs du cache seront différentes de 0.
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


Obtient la mémoire maximale disponible pour le cache en mémoire. La valeur spécifiée est le nombre de mégaoctets.

**Returns:**
int - La mémoire maximale pour le cache.

Une valeur de 0 consommera toute la mémoire disponible et constitue une absence de limite supérieure.
### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Définit la mémoire maximale disponible pour le cache en mémoire. La valeur spécifiée est le nombre de mégaoctets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La mémoire maximale pour le cache. |

Une valeur de 0 consommera toute la mémoire disponible et constitue une absence de limite supérieure. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Par défaut, le dossier de cache est défini sur le répertoire temporaire local de l'utilisateur.
// Vous pouvez également spécifier un autre dossier de cache que le défaut comme suit :
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Le mode automatique est flexible et efficace
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// La valeur par défaut est 0, ce qui signifie qu'il n'y a pas de limite supérieure
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Il n'est pas recommandé de modifier la propriété suivante car cela peut fortement affecter les performances
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// À tout moment, vous pouvez vérifier combien d'octets sont actuellement alloués pour la mémoire ou le disque
// le cache en examinant les propriétés suivantes
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Effectuez un traitement d'image comme ci‑dessous
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

    // Après l'exécution du code ci‑dessus, 40000 octets seront alloués en mémoire.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Les propriétés d'allocation peuvent être utilisées pour vérifier si tous les objets Aspose.Imaging ont été correctement libérés.
// Dans le cas où vous auriez oublié d'appeler dispose sur un objet, les valeurs du cache seront différentes de 0.
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


Obtient l'espace disque maximal disponible pour le cache. La valeur spécifiée correspond au nombre de mégaoctets.

**Returns:**
int - L'espace disque maximal disponible pour le cache.

Une valeur de 0 consommera toute la mémoire disponible et constitue une absence de limite supérieure.
### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Définit l'espace disque maximal disponible pour le cache. La valeur spécifiée correspond au nombre de mégaoctets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L'espace disque maximal disponible pour le cache. |

Une valeur de 0 consommera toute la mémoire disponible et constitue une absence de limite supérieure. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Par défaut, le dossier de cache est défini sur le répertoire temporaire local de l'utilisateur.
// Vous pouvez également spécifier un autre dossier de cache que le défaut comme suit :
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Le mode automatique est flexible et efficace
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// La valeur par défaut est 0, ce qui signifie qu'il n'y a pas de limite supérieure
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Il n'est pas recommandé de modifier la propriété suivante car cela peut fortement affecter les performances
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// À tout moment, vous pouvez vérifier combien d'octets sont actuellement alloués pour la mémoire ou le disque
// le cache en examinant les propriétés suivantes
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Effectuez un traitement d'image comme ci‑dessous
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

    // Après l'exécution du code ci‑dessus, 40000 octets seront alloués en mémoire.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Les propriétés d'allocation peuvent être utilisées pour vérifier si tous les objets Aspose.Imaging ont été correctement libérés.
// Dans le cas où vous auriez oublié d'appeler dispose sur un objet, les valeurs du cache seront différentes de 0.
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


Obtient ou définit le schéma de cache utilisé.

**Returns:**
int - Le schéma de cache utilisé.
### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Définit le schéma de cache utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le schéma de cache utilisé. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Par défaut, le dossier de cache est défini sur le répertoire temporaire local de l'utilisateur.
// Vous pouvez également spécifier un autre dossier de cache que le défaut comme suit :
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Le mode automatique est flexible et efficace
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// La valeur par défaut est 0, ce qui signifie qu'il n'y a pas de limite supérieure
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Il n'est pas recommandé de modifier la propriété suivante car cela peut fortement affecter les performances
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// À tout moment, vous pouvez vérifier combien d'octets sont actuellement alloués pour la mémoire ou le disque
// le cache en examinant les propriétés suivantes
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Effectuez un traitement d'image comme ci‑dessous
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

    // Après l'exécution du code ci‑dessus, 40000 octets seront alloués en mémoire.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Les propriétés d'allocation peuvent être utilisées pour vérifier si tous les objets Aspose.Imaging ont été correctement libérés.
// Dans le cas où vous auriez oublié d'appeler dispose sur un objet, les valeurs du cache seront différentes de 0.
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


Définit les paramètres du `Cache` aux valeurs par défaut.

