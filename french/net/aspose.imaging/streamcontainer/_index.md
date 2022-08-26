---
title: StreamContainer
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Représente le conteneur de flux qui contient le flux et fournit des routines de traitement de flux.
type: docs
weight: 11130
url: /fr/net/aspose.imaging/streamcontainer/
---
## StreamContainer class

Représente le conteneur de flux qui contient le flux et fournit des routines de traitement de flux.

```csharp
public class StreamContainer : DisposableObject
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [StreamContainer](streamcontainer#constructor)(Stream) | Initialise une nouvelle instance du[`StreamContainer`](../streamcontainer) classe. |
| [StreamContainer](streamcontainer#constructor_1)(Stream, bool) | Initialise une nouvelle instance du[`StreamContainer`](../streamcontainer) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | Obtient une valeur indiquant si le flux prend en charge la lecture. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | Obtient une valeur indiquant si le flux prend en charge la recherche. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | Obtient une valeur indiquant si le flux prend en charge l'écriture. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Obtient une valeur indiquant si ce flux est supprimé à la fermeture. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | Obtient ou définit la longueur du flux en octets. Cette valeur est inférieure à laLength par la position de départ du flux transmise dans le constructeur StreamContainer. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | Obtient ou définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux transmise dans le constructeur StreamContainer. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | Obtient le flux de données. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | Efface tous les tampons pour ce flux et provoque l'écriture de toutes les données mises en tampon sur le périphérique sous-jacent. |
| virtual [Read](../../aspose.imaging/streamcontainer/read#read)(byte[]) | Lit les octets pour remplir le tampon d'octets spécifié. |
| virtual [Read](../../aspose.imaging/streamcontainer/read#read_1)(byte[], int, int) | Lit une séquence d'octets du flux actuel et avance la position dans le flux du nombre d'octets lus. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si à la fin du flux. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save)(Stream) | Enregistre (copie) les données du flux dans le flux spécifié. Utilise la taille de tampon par défaut[`ReadWriteBytesCount`](./readwritebytescount) et streamer[`Length`](./length) valeur. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_3)(string) | Enregistre (copie) les données du flux dans le flux spécifié. Utilise la taille de tampon par défaut[`ReadWriteBytesCount`](./readwritebytescount) et streamer[`Length`](./length) valeur. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_1)(Stream, int) | Enregistre (copie) toutes les données du flux dans le flux spécifié. Utilise le flux[`Length`](./length) valeur. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_4)(string, int) | Enregistre (copie) les données du flux dans le flux spécifié. Utilise le flux[`Length`](./length) valeur. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_2)(Stream, int, long) | Enregistre (copie) les données du flux dans le flux spécifié. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_5)(string, int, long) | Enregistre (copie) les données du flux dans le flux spécifié. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | Définit la position dans le flux actuel. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | Définit la position du flux au début du flux. Cette valeur représente le décalage par rapport à la position de départ du flux transmise dans le constructeur StreamContainer. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes#tobytes)() | Convertit les données du flux enByte tableau. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes#tobytes_1)(long, long) | Convertit les données du flux enByte tableau. |
| virtual [Write](../../aspose.imaging/streamcontainer/write#write)(byte[]) | Écrit tous les octets spécifiés dans le flux. |
| virtual [Write](../../aspose.imaging/streamcontainer/write#write_1)(byte[], int, int) | Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | Écrit un octet à la position actuelle dans le flux et avance la position dans le flux d'un octet. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto#writeto)(StreamContainer) | Copie les données contenues dans un autre[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto#writeto_1)(StreamContainer, long) | Copie les données contenues dans un autre[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/streamcontainer/op_explicit) | Effectue une conversion explicite à partir[`StreamContainer`](../streamcontainer) àStream . |

## Des champs

| Nom | La description |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.imaging/streamcontainer/readwritebytescount) | Spécifie le nombre d'octets de lecture et d'écriture lors de la lecture séquentielle. |

### Voir également

* class [DisposableObject](../disposableobject)
* espace de noms [Aspose.Imaging](../../aspose.imaging)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
