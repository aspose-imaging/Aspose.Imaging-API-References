---
title: SplitStreamContainer
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Représente le conteneur de flux divisé qui contient le flux et fournit des routines de traitement de flux.
type: docs
weight: 11120
url: /fr/net/aspose.imaging/splitstreamcontainer/
---
## SplitStreamContainer class

Représente le conteneur de flux divisé qui contient le flux et fournit des routines de traitement de flux.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer#constructor_1)(Stream) | Initialise une nouvelle instance du[`SplitStreamContainer`](../splitstreamcontainer) classe. |
| [SplitStreamContainer](splitstreamcontainer#constructor_2)(Stream, bool) | Initialise une nouvelle instance du[`SplitStreamContainer`](../splitstreamcontainer) classe. |
| [SplitStreamContainer](splitstreamcontainer#constructor)(StreamContainer, bool) | Initialise une nouvelle instance du[`SplitStreamContainer`](../splitstreamcontainer) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [CanRead](../../aspose.imaging/splitstreamcontainer/canread) { get; } | Obtient une valeur indiquant si le flux prend en charge la lecture. |
| override [CanSeek](../../aspose.imaging/splitstreamcontainer/canseek) { get; } | Obtient une valeur indiquant si le flux prend en charge la recherche. |
| override [CanWrite](../../aspose.imaging/splitstreamcontainer/canwrite) { get; } | Obtient une valeur indiquant si le flux prend en charge l'écriture. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Obtient une valeur indiquant si ce flux est supprimé à la fermeture. |
| override [Length](../../aspose.imaging/splitstreamcontainer/length) { get; set; } | Obtient ou définit la longueur du flux en octets. Cette valeur est inférieure à laLength par la position de départ du flux transmise dans le constructeur StreamContainer. |
| override [Position](../../aspose.imaging/splitstreamcontainer/position) { get; set; } | Obtient ou définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux transmise dans le constructeur StreamContainer. |
| override [Stream](../../aspose.imaging/splitstreamcontainer/stream) { get; } | Obtient le flux de données. |
| [SyncRoot](../../aspose.imaging/splitstreamcontainer/syncroot) { get; } | Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |
| override [Flush](../../aspose.imaging/splitstreamcontainer/flush)() | Efface tous les tampons pour ce flux et provoque l'écriture de toutes les données mises en tampon sur le périphérique sous-jacent. |
| [Insert](../../aspose.imaging/splitstreamcontainer/insert)(int, StreamContainer, bool) | Insère le conteneur de flux dans la position spécifiée. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read)(byte[]) | Lit les octets pour remplir le tampon d'octets spécifié. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read_1)(byte[], int, int) | Lit une séquence d'octets du flux actuel et avance la position dans le flux du nombre d'octets lus. |
| override [ReadByte](../../aspose.imaging/splitstreamcontainer/readbyte)() | Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si à la fin du flux. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Enregistre (copie) les données du flux dans le flux spécifié. Utilise la taille de tampon par défaut[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) et streamer[`Length`](../streamcontainer/length) valeur. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Enregistre (copie) les données du flux dans le flux spécifié. Utilise la taille de tampon par défaut[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) et streamer[`Length`](../streamcontainer/length) valeur. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Enregistre (copie) toutes les données du flux dans le flux spécifié. Utilise le flux[`Length`](../streamcontainer/length) valeur. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Enregistre (copie) les données du flux dans le flux spécifié. Utilise le flux[`Length`](../streamcontainer/length) valeur. |
| override [Save](../../aspose.imaging/splitstreamcontainer/save#save_2)(Stream, int, long) | Enregistre (copie) les données du flux dans le flux spécifié. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Enregistre (copie) les données du flux dans le flux spécifié. |
| override [Seek](../../aspose.imaging/splitstreamcontainer/seek)(long, SeekOrigin) | Définit la position dans le flux actuel. |
| override [SeekBegin](../../aspose.imaging/splitstreamcontainer/seekbegin)() | Définit la position du flux au début du flux. Cette valeur représente le décalage par rapport à la position de départ du flux transmise dans le constructeur StreamContainer. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes)() | Convertit les données du flux enByte tableau. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes_1)(long, long) | Convertit les données du flux enByte tableau. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write)(byte[]) | Écrit tous les octets spécifiés dans le flux. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write_1)(byte[], int, int) | Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits. |
| override [WriteByte](../../aspose.imaging/splitstreamcontainer/writebyte)(byte) | Écrit un octet à la position actuelle dans le flux et avance la position dans le flux d'un octet. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | Copie les données contenues dans un autre[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | Copie les données contenues dans un autre[`StreamContainer`](../streamcontainer) . |

### Voir également

* class [StreamContainer](../streamcontainer)
* espace de noms [Aspose.Imaging](../../aspose.imaging)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
