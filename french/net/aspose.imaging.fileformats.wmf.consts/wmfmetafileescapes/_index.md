---
title: WmfMetafileEscapes
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lénumération MetafileEscapes spécifie les fonctionnalités du pilote dimprimante qui peuvent ne pas être directement accessibles via les enregistrements WMF définis dans lénumération RecordType section 2.1.1.1.
type: docs
weight: 8230
url: /fr/net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
## WmfMetafileEscapes enumeration

L'énumération MetafileEscapes spécifie les fonctionnalités du pilote d'imprimante qui peuvent ne pas être directement accessibles via les enregistrements WMF définis dans l'énumération RecordType (section 2.1.1.1).

```csharp
public enum WmfMetafileEscapes
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Newframe | `1` | Informe le pilote d'imprimante que l'application a fini d'écrire sur une page. |
| Abortdoc | `2` | Arrête le traitement du document en cours. |
| Nextband | `3` | Informe le pilote d'imprimante que l'application a fini d'écrire sur une bande. |
| Setcolortable | `4` | Définit les valeurs de la table des couleurs. |
| Getcolortable | `5` | Obtient les valeurs de la table des couleurs. |
| Flushout | `6` | Provoque le vidage de toutes les sorties en attente vers le périphérique de sortie. |
| Draftmode | `7` | Indique que le pilote d'imprimante DEVRAIT n'imprimer que du texte et aucun graphique. |
| Queryescsupport | `8` | Interroge un pilote d'imprimante pour déterminer si une fonction d'échappement spécifique est prise en charge sur le périphérique de sortie qu'il pilote. |
| Setabortproc | `9` | Définit la fonction définie par l'application qui permet d'annuler un travail d'impression pendant l'impression. |
| Startdoc | `10` | Informe le pilote d'imprimante qu'un nouveau travail d'impression démarre. |
| Enddoc | `11` | Informe le pilote d'imprimante que le travail d'impression en cours se termine. |
| Getphyspagesize | `12` | Récupère la taille de page physique actuellement sélectionnée sur un périphérique de sortie. |
| Getprintingoffset | `13` | Récupère le décalage du coin supérieur gauche de la page physique où l'impression ou le dessin réel commence. |
| Getscalingfactor | `14` | Récupère les facteurs d'échelle pour l'axe des x et l'axe des y d'une imprimante. |
| MetaEscapeEnhancedMetafile | `15` | Utilisé pour intégrer un métafichier au format de métafichier amélioré (EMF) dans un métafichier WMF. |
| Setpenwidth | `16` | Définit la largeur d'un stylo en pixels. |
| Setcopycount | `17` | Définit le nombre de copies. |
| Setpapersource | `18` | Définit la source, telle qu'un bac à papier particulier ou un bac sur une imprimante, pour les formulaires de sortie. |
| Passthrough | `19` | Cet enregistrement passe par des données arbitraires. |
| Gettechnology | `20` | Obtient des informations concernant la technologie graphique prise en charge sur un appareil. |
| Setlinecap | `21` | Spécifie le mode de dessin au trait à utiliser dans la sortie vers un périphérique. |
| Setlinejoin | `22` | Spécifie le mode de jointure de ligne à utiliser dans la sortie vers un périphérique. |
| Setmiterlimit | `23` | Définit la limite de longueur des jointures mitre à utiliser dans la sortie vers un appareil. |
| Bandinfo | `24` | Récupère ou spécifie les paramètres concernant les bandes sur un appareil, tels que le nombre de bandes. |
| Drawpatternrect | `25` | Dessine un rectangle avec un motif défini. |
| Getvectorpensize | `26` | Récupère la taille physique du stylet actuellement définie sur un appareil. |
| Getvectorbrushsize | `27` | Récupère la taille physique du pinceau actuellement définie sur un appareil. |
| Enableduplex | `28` | Active ou désactive l'impression recto-verso (duplex) sur un périphérique. |
| Getsetpaperbins | `29` | Récupère ou spécifie la source des formulaires de sortie sur un appareil. |
| Getsetprintorient | `30` | Récupère ou spécifie l'orientation du papier sur un périphérique. |
| Enumpaperbins | `31` | Récupère les informations concernant les sources des différents formulaires sur un périphérique de sortie. |
| Setdibscaling | `32` | Spécifie la mise à l'échelle des bitmaps indépendants du périphérique (DIB). |
| Epsprinting | `33` | Indique le début et la fin d'une section PostScript encapsulé (EPS). |
| Enumpapermetrics | `34` | Interroge un pilote d'imprimante sur les dimensions du papier et d'autres données de formulaire. |
| Getsetpapermetrics | `35` | Récupère ou spécifie les dimensions du papier et d'autres données de formulaire sur un périphérique de sortie. |
| PostscriptData | `37` | Envoie des données PostScript arbitraires à un périphérique de sortie. |
| PostscriptIgnore | `38` | Indique à un périphérique de sortie d'ignorer les données PostScript. |
| Getdeviceunits | `42` | Obtient les unités de périphérique actuellement configurées sur un périphérique de sortie. |
| Getextendedtextmetrics | `256` | Obtient les métriques de texte étendu actuellement configurées sur un périphérique de sortie . |
| Getpairkerntable | `258` | Obtient la table de crénage des polices actuellement définie sur un périphérique de sortie. |
| Exttextout | `512` | Dessine le texte en utilisant la police, la couleur d'arrière-plan et la couleur du texte actuellement sélectionnées. |
| Getfacename | `513` | Obtient le nom de la police actuellement configuré sur un appareil. |
| Downloadface | `514` | Définit le nom de la police sur un appareil. |
| MetafileDriver | `2049` | Interroge un pilote d'imprimante sur la prise en charge des métafichiers sur un périphérique de sortie . |
| Querydibsupport | `3073` | Interroge le pilote d'imprimante sur sa prise en charge des DIB sur un périphérique de sortie. |
| BeginPath | `4096` | Ouvre un chemin. |
| ClipToPath | `4097` | Définit une zone de découpage délimitée par un chemin. L'entrée DOIT être une quantité 16-bit qui définit l'action à entreprendre. |
| EndPath | `4098` | Termine un chemin. |
| OpenChannel | `4110` | Identique à STARTDOC spécifié avec un document NULL et un nom de fichier output , des données en mode brut et un type de zéro. |
| Downloadheader | `4111` | Demande au pilote d'imprimante de télécharger des ensembles de procédures PostScript. |
| CloseChannel | `4112` | Identique à ENDDOC. Voir OPEN_CHANNEL. |
| PostscriptPassthrough | `4115` | Envoie des données arbitraires directement à un pilote d'imprimante, qui est censé traiter ces données uniquement en mode PostScript.PostscriptIdentify . |
| EncapsulatedPostscript | `4116` | Envoie des données arbitraires directement au pilote d'imprimante. |
| PostscriptIdentify | `4117` | Définit le pilote d'imprimante en mode PostScript ou GDI. |
| PostscriptInjection | `4118` | Insère un bloc de données brutes dans un flux PostScript. L'input DOIT être une quantité de 32 bits spécifiant le nombre d'octets à injecter, une quantité de 16 bits spécifiant le point d'injection et une quantité de 16 bits spécifiant le numéro de page, suivie de les octets à injecter. |
| Checkjpegformat | `4119` | Vérifie si l'imprimante prend en charge une image JPEG. |
| Checkpngformat | `4120` | Vérifie si l'imprimante prend en charge une image PNG. |
| GetPsFeaturesetting | `4121` | Obtient des informations sur un paramètre de fonctionnalité spécifié pour un pilote d'imprimante PostScript . |
| MxdcEscape | `4122` | Permet aux applications d'écrire des documents dans un fichier ou sur une imprimante au format XML Paper Specification (XPS). |
| Spclpassthrough2 | `4568` | Permet aux applications d'inclure des procédures privées et d'autres données arbitraires dans les documents. |

### Voir également

* espace de noms [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
