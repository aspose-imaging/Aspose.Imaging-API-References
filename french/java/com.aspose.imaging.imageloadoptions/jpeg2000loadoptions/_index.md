---
title: "Jpeg2000LoadOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Options de chargement JPEG2000"
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.imageloadoptions/jpeg2000loadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

Options de chargement JPEG2000
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | Initialise une nouvelle instance de la classe `Jpeg2000LoadOptions`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | Obtient le temps de décodage maximal en secondes (cette option peut être utilisée sur des machines très lentes ou à faible mémoire pour éviter le blocage du processus sur des images très volumineuses - résolution supérieure à 5500x6500 pixels). |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | Définit le temps de décodage maximal en secondes (cette option peut être utilisée sur des machines très lentes ou à faible mémoire pour éviter le blocage du processus sur des images très volumineuses - résolution supérieure à 5500x6500 pixels). |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | Obtient le temps de décodage maximal pour la tuile. |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | Définit le temps de décodage maximal pour la tuile. |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


Initialise une nouvelle instance de la classe `Jpeg2000LoadOptions`.

### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


Obtient le temps de décodage maximal en secondes (cette option peut être utilisée sur des machines très lentes ou à faible mémoire pour éviter le blocage du processus sur des images très volumineuses - résolution supérieure à 5500x6500 pixels).

**Returns:**
int - Le temps de décodage maximal.
### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


Définit le temps de décodage maximal en secondes (cette option peut être utilisée sur des machines très lentes ou à faible mémoire pour éviter le blocage du processus sur des images très volumineuses - résolution supérieure à 5500x6500 pixels).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le temps de décodage maximal. |

### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


Obtient le temps de décodage maximal pour la tuile.

Valeur : Le temps de décodage maximal pour la tuile.

**Returns:**
int - le temps de décodage maximal pour la tuile.
### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


Définit le temps de décodage maximal pour la tuile.

Valeur : Le temps de décodage maximal pour la tuile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le temps de décodage maximal pour la tuile. |

