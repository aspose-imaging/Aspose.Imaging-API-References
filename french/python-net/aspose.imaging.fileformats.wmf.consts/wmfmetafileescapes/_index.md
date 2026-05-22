---
title: "Énumération WmfMetafileEscapes"
type: docs
weight: 150
url: /fr/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---

L'énumération MetafileEscapes spécifie les fonctionnalités du pilote d'imprimante qui pourraient ne pas être<br/>                directement accessibles via les enregistrements WMF définis dans l'énumération RecordType (section 2.1.1.1).

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfMetafileEscapes

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| ABORTDOC | Arrête le traitement du document actuel. |
| BANDINFO | Récupère ou spécifie les paramètres concernant le banding sur un dispositif, comme le<br/>                nombre de bandes. |
| BEGIN_PATH | Ouvre un chemin. |
| CHECKJPEGFORMAT | Vérifie si l'imprimante prend en charge une image JPEG. |
| CHECKPNGFORMAT | Vérifie si l'imprimante prend en charge une image PNG. |
| CLIP_TO_PATH | Définit une région de découpe délimitée par un chemin. L'entrée DOIT être une quantité de 16 bits<br/>                qui définit l'action à entreprendre. |
| CLOSE_CHANNEL | Le même que ENDDOC. Voir OPEN_CHANNEL. |
| DOWNLOADFACE | Définit le nom de la police sur un appareil. |
| DOWNLOADHEADER | Instruit le pilote d'imprimante de télécharger des ensembles de procédures PostScript. |
| DRAFTMODE | Indique que le pilote d'imprimante DOIT imprimer uniquement du texte, et aucune image. |
| DRAWPATTERNRECT | Dessine un rectangle avec un motif défini. |
| ENABLEDUPLEX | Active ou désactive l'impression recto verso (duplex) sur un appareil. |
| ENCAPSULATED_POSTSCRIPT | Envoie des données arbitraires directement au pilote d'imprimante. |
| ENDDOC | Informe le pilote d'imprimante que la tâche d'impression en cours se termine. |
| END_PATH | Termine un chemin. |
| ENUMPAPERBINS | Récupère les informations concernant les sources de différents formulaires sur un<br/>                dispositif de sortie. |
| ENUMPAPERMETRICS | Interroge le pilote d'imprimante pour les dimensions du papier et d'autres données de formulaires. |
| EPSPRINTING | Indique le début et la fin d'une section PostScript encapsulé (EPS). |
| EXTTEXTOUT | Dessine du texte en utilisant la police actuellement sélectionnée, la couleur d'arrière-plan et la couleur du texte. |
| FLUSHOUT | Force le vidage de toute sortie en attente vers le périphérique de sortie. |
| GETCOLORTABLE | Obtient les valeurs de la table de couleurs. |
| GETDEVICEUNITS | Obtient les unités du dispositif actuellement configurées sur un périphérique de sortie. |
| GETEXTENDEDTEXTMETRICS | Obtient les métriques de texte étendues actuellement configurées sur une sortie<br/>                dispositif. |
| GETFACENAME | Obtient le nom de la police actuellement configuré sur un dispositif. |
| GETPAIRKERNTABLE | Obtient la table de crénage de police actuellement définie sur un périphérique de sortie. |
| GETPHYSPAGESIZE | Récupère la taille physique de la page actuellement sélectionnée sur un périphérique de sortie. |
| GETPRINTINGOFFSET | Récupère le décalage depuis le coin supérieur gauche de la page physique<br/>                où commence réellement l'impression ou le dessin. |
| GETSCALINGFACTOR | Récupère les facteurs d'échelle pour l'axe x et l'axe y d'une imprimante. |
| GETSETPAPERBINS | Récupère ou spécifie la source des formulaires de sortie sur un dispositif. |
| GETSETPAPERMETRICS | Récupère ou spécifie les dimensions du papier et d'autres données de formulaires sur un<br/>                périphérique de sortie. |
| GETSETPRINTORIENT | Récupère ou spécifie l'orientation du papier sur un dispositif. |
| GETTECHNOLOGY | Obtient des informations concernant la technologie graphique prise en charge sur un<br/>                appareil. |
| GETVECTORBRUSHSIZE | Récupère la taille physique du pinceau actuellement définie sur un appareil. |
| GETVECTORPENSIZE | Récupère la taille physique du stylo actuellement définie sur un appareil. |
| GET_PS_FEATURESETTING | Obtient des informations sur un paramètre de fonctionnalité spécifié pour un PostScript<br/>                pilote d'imprimante. |
| METAFILE_DRIVER | Interroge un pilote d'imprimante concernant la prise en charge des métafichiers sur un périphérique de sortie<br/>                périphérique. |
| META_ESCAPE_ENHANCED_METAFILE | Utilisé pour incorporer un métafichier au format amélioré (EMF)<br/>                métafichier dans un métafichier WMF. |
| MXDC_ESCAPE | Permet aux applications d'écrire des documents dans un fichier ou vers une imprimante au format XML Paper<br/>                Specification (XPS). |
| NEWFRAME | Informe le pilote d'imprimante que l'application a terminé l'écriture d'une page. |
| NEXTBAND | Informe le pilote d'imprimante que l'application a terminé l'écriture d'une bande. |
| OPEN_CHANNEL | Identique à STARTDOC spécifié avec un document NULL et une sortie<br/>                nom de fichier, données en mode brut, et un type de zéro. |
| PASSTHROUGH | Cet enregistrement transmet des données arbitraires. |
| POSTSCRIPT_DATA | Envoie des données PostScript arbitraires à un périphérique de sortie. |
| POSTSCRIPT_IDENTIFY | Définit le pilote d'imprimante sur le mode PostScript ou GDI. |
| POSTSCRIPT_IGNORE | Informe un dispositif de sortie d'ignorer les données PostScript. |
| POSTSCRIPT_INJECTION | Insère un bloc de données brutes dans un flux PostScript. L'entrée<br/>                DOIT être une quantité de 32 bits spécifiant le nombre d'octets à injecter, une quantité de 16 bits<br/>                spécifiant le point d'injection, et une quantité de 16 bits spécifiant le numéro de page, suivi de<br/>                les octets à injecter. |
| POSTSCRIPT_PASSTHROUGH | Envoie des données arbitraires directement à un pilote d'imprimante, qui est<br/>                censé traiter ces données uniquement en mode PostScript. [WmfMetafileEscapes.POSTSCRIPT_IDENTIFY](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/). |
| QUERYDIBSUPPORT | Interroge le pilote d'imprimante sur sa prise en charge des DIB sur un dispositif de sortie. |
| QUERYESCSUPPORT | Interroge un pilote d'imprimante pour déterminer si une fonction d'échappement spécifique<br/>                est prise en charge sur le dispositif de sortie qu'il pilote. |
| SETABORTPROC | Définit la fonction définie par l'application qui permet d'annuler un travail d'impression<br/>                pendant l'impression. |
| SETCOLORTABLE | Définit les valeurs de la table de couleurs. |
| SETCOPYCOUNT | Définit le nombre de copies. |
| SETDIBSCALING | Spécifie le redimensionnement des bitmaps indépendants du dispositif (DIB). |
| SETLINECAP | Spécifie le mode de tracé de ligne à utiliser lors de la sortie vers un dispositif. |
| SETLINEJOIN | Spécifie le mode de jointure de ligne à utiliser lors de la sortie vers un dispositif. |
| SETMITERLIMIT | Définit la limite de la longueur des jointures en onglet à utiliser lors de la sortie vers un dispositif. |
| SETPAPERSOURCE | Définit la source, comme un bac à papier ou un tiroir particulier sur une imprimante, pour<br/>                les formulaires de sortie. |
| SETPENWIDTH | Définit la largeur d’un crayon en pixels. |
| SPCLPASSTHROUGH2 | Permet aux applications d’inclure des procédures privées et d’autres données arbitraires<br/>                dans les documents. |
| STARTDOC | Notifie le pilote d’imprimante qu’une nouvelle tâche d’impression démarre. |
