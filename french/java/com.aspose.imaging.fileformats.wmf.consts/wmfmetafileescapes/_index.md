---
title: "WmfMetafileEscapes"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération MetafileEscapes spécifie la fonctionnalité du pilote d'imprimante qui pourrait ne pas être directement accessible via les enregistrements WMF définis dans la section 2.1.1.1 de l'énumération RecordType."
type: docs
weight: 24
url: /fr/java/com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfMetafileEscapes extends System.Enum
```

L'énumération MetafileEscapes spécifie la fonctionnalité du pilote d'imprimante qui pourrait ne pas être directement accessible via les enregistrements WMF définis dans l'énumération RecordType (section 2.1.1.1).
## Champs

| Champ | Description |
| --- | --- |
| [Newframe](#Newframe) | Informe le pilote d'imprimante que l'application a fini d'écrire sur une page. |
| [Abortdoc](#Abortdoc) | Arrête le traitement du document actuel. |
| [Nextband](#Nextband) | Informe le pilote d'imprimante que l'application a fini d'écrire sur une bande. |
| [Setcolortable](#Setcolortable) | Définit les valeurs de la table de couleurs. |
| [Getcolortable](#Getcolortable) | Obtient les valeurs de la table de couleurs. |
| [Flushout](#Flushout) | Force l'évacuation de toute sortie en attente vers le dispositif de sortie. |
| [Draftmode](#Draftmode) | Indique que le pilote d'imprimante DOIT n'imprimer que du texte, et aucune image. |
| [Queryescsupport](#Queryescsupport) | Interroge le pilote d'imprimante pour déterminer si une fonction d'échappement spécifique est prise en charge sur le dispositif de sortie qu'il pilote. |
| [Setabortproc](#Setabortproc) | Définit la fonction définie par l'application qui permet d'annuler un travail d'impression pendant l'impression. |
| [Startdoc](#Startdoc) | Informe le pilote d'imprimante qu'un nouveau travail d'impression démarre. |
| [Enddoc](#Enddoc) | Informe le pilote d'imprimante que le travail d'impression en cours se termine. |
| [Getphyspagesize](#Getphyspagesize) | Récupère la taille physique de la page actuellement sélectionnée sur un dispositif de sortie. |
| [Getprintingoffset](#Getprintingoffset) | Récupère le décalage depuis le coin supérieur gauche de la page physique où l'impression ou le dessin réel commence. |
| [Getscalingfactor](#Getscalingfactor) | Récupère les facteurs d'échelle pour l'axe x et l'axe y d'une imprimante. |
| [MetaEscapeEnhancedMetafile](#MetaEscapeEnhancedMetafile) | Utilisé pour incorporer un métafichier au format amélioré (EMF) dans un métafichier WMF. |
| [Setpenwidth](#Setpenwidth) | Définit la largeur d'un crayon en pixels. |
| [Setcopycount](#Setcopycount) | Définit le nombre de copies. |
| [Setpapersource](#Setpapersource) | Définit la source, comme un bac à papier particulier ou un tiroir d'imprimante, pour les formulaires de sortie. |
| [Passthrough](#Passthrough) | Cet enregistrement transmet des données arbitraires. |
| [Gettechnology](#Gettechnology) | Obtient des informations concernant la technologie graphique prise en charge sur un dispositif. |
| [Setlinecap](#Setlinecap) | Spécifie le mode de tracé de ligne à utiliser lors de la sortie vers un dispositif. |
| [Setlinejoin](#Setlinejoin) | Spécifie le mode de jointure de ligne à utiliser lors de la sortie vers un dispositif. |
| [Setmiterlimit](#Setmiterlimit) | Définit la limite de la longueur des jointures en onglet à utiliser lors de la sortie vers un dispositif. |
| [Bandinfo](#Bandinfo) | Récupère ou spécifie les paramètres concernant le banding sur un appareil, tels que le nombre de bandes. |
| [Drawpatternrect](#Drawpatternrect) | Dessine un rectangle avec un motif défini. |
| [Getvectorpensize](#Getvectorpensize) | Récupère la taille physique du stylet actuellement définie sur un appareil. |
| [Getvectorbrushsize](#Getvectorbrushsize) | Récupère la taille physique du pinceau actuellement définie sur un appareil. |
| [Enableduplex](#Enableduplex) | Active ou désactive l'impression recto verso (duplex) sur un appareil. |
| [Getsetpaperbins](#Getsetpaperbins) | Récupère ou spécifie la source des formulaires de sortie sur un appareil. |
| [Getsetprintorient](#Getsetprintorient) | Récupère ou spécifie l'orientation du papier sur un appareil. |
| [Enumpaperbins](#Enumpaperbins) | Récupère les informations concernant les sources de différents formulaires sur un dispositif de sortie. |
| [Setdibscaling](#Setdibscaling) | Spécifie le redimensionnement des bitmaps indépendants du dispositif (DIBs). |
| [Epsprinting](#Epsprinting) | Indique le début et la fin d'une section PostScript encapsulé (EPS). |
| [Enumpapermetrics](#Enumpapermetrics) | Interroge le pilote d'imprimante pour les dimensions du papier et d'autres données de formulaires. |
| [Getsetpapermetrics](#Getsetpapermetrics) | Récupère ou spécifie les dimensions du papier et d'autres données de formulaires sur un dispositif de sortie. |
| [PostscriptData](#PostscriptData) | Envoie des données PostScript arbitraires à un dispositif de sortie. |
| [PostscriptIgnore](#PostscriptIgnore) | Notifie un dispositif de sortie d'ignorer les données PostScript. |
| [Getdeviceunits](#Getdeviceunits) | Obtient les unités du dispositif actuellement configurées sur un dispositif de sortie. |
| [Getextendedtextmetrics](#Getextendedtextmetrics) | Obtient les métriques de texte étendues actuellement configurées sur un dispositif de sortie. |
| [Getpairkerntable](#Getpairkerntable) | Obtient la table de crénage des polices actuellement définie sur un dispositif de sortie. |
| [Exttextout](#Exttextout) | Dessine du texte en utilisant la police actuellement sélectionnée, la couleur d'arrière-plan et la couleur du texte. |
| [Getfacename](#Getfacename) | Obtient le nom de la police actuellement configuré sur un appareil. |
| [Downloadface](#Downloadface) | Définit le nom de la police sur un appareil. |
| [MetafileDriver](#MetafileDriver) | Interroge le pilote d'imprimante concernant la prise en charge des métafichiers sur un dispositif de sortie. |
| [Querydibsupport](#Querydibsupport) | Interroge le pilote d'imprimante concernant sa prise en charge des DIBs sur un dispositif de sortie. |
| [BeginPath](#BeginPath) | Ouvre un chemin. |
| [ClipToPath](#ClipToPath) | Définit une région de découpe délimitée par un chemin. |
| [EndPath](#EndPath) | Termine un chemin. |
| [OpenChannel](#OpenChannel) | Identique à STARTDOC spécifié avec un document NULL et un nom de fichier de sortie, des données en mode brut, et un type de zéro. |
| [Downloadheader](#Downloadheader) | Indique au pilote d'imprimante de télécharger des ensembles de procédures PostScript. |
| [CloseChannel](#CloseChannel) | Identique à ENDDOC. |
| [PostscriptPassthrough](#PostscriptPassthrough) | Envoie des données arbitraires directement au pilote d'imprimante, qui doit traiter ces données uniquement en mode PostScript. |
| [EncapsulatedPostscript](#EncapsulatedPostscript) | Envoie des données arbitraires directement au pilote d'imprimante. |
| [PostscriptIdentify](#PostscriptIdentify) | Configure le pilote d'imprimante en mode PostScript ou GDI. |
| [PostscriptInjection](#PostscriptInjection) | Insère un bloc de données brutes dans un flux PostScript. |
| [Checkjpegformat](#Checkjpegformat) | Vérifie si l'imprimante prend en charge une image JPEG. |
| [Checkpngformat](#Checkpngformat) | Vérifie si l'imprimante prend en charge une image PNG. |
| [GetPsFeaturesetting](#GetPsFeaturesetting) | Obtient des informations sur un paramètre de fonctionnalité spécifié pour un pilote d'imprimante PostScript. |
| [MxdcEscape](#MxdcEscape) | Permet aux applications d'écrire des documents dans un fichier ou vers une imprimante au format XML Paper Specification (XPS). |
| [Spclpassthrough2](#Spclpassthrough2) | Permet aux applications d'inclure des procédures privées et d'autres données arbitraires dans les documents. |
### Newframe {#Newframe}
```
public static final int Newframe
```


Informe le pilote d'imprimante que l'application a fini d'écrire sur une page.

### Abortdoc {#Abortdoc}
```
public static final int Abortdoc
```


Arrête le traitement du document actuel.

### Nextband {#Nextband}
```
public static final int Nextband
```


Informe le pilote d'imprimante que l'application a fini d'écrire sur une bande.

### Setcolortable {#Setcolortable}
```
public static final int Setcolortable
```


Définit les valeurs de la table de couleurs.

### Getcolortable {#Getcolortable}
```
public static final int Getcolortable
```


Obtient les valeurs de la table de couleurs.

### Flushout {#Flushout}
```
public static final int Flushout
```


Force l'évacuation de toute sortie en attente vers le dispositif de sortie.

### Draftmode {#Draftmode}
```
public static final int Draftmode
```


Indique que le pilote d'imprimante DOIT n'imprimer que du texte, et aucune image.

### Queryescsupport {#Queryescsupport}
```
public static final int Queryescsupport
```


Interroge le pilote d'imprimante pour déterminer si une fonction d'échappement spécifique est prise en charge sur le dispositif de sortie qu'il pilote.

### Setabortproc {#Setabortproc}
```
public static final int Setabortproc
```


Définit la fonction définie par l'application qui permet d'annuler un travail d'impression pendant l'impression.

### Startdoc {#Startdoc}
```
public static final int Startdoc
```


Informe le pilote d'imprimante qu'un nouveau travail d'impression démarre.

### Enddoc {#Enddoc}
```
public static final int Enddoc
```


Informe le pilote d'imprimante que le travail d'impression en cours se termine.

### Getphyspagesize {#Getphyspagesize}
```
public static final int Getphyspagesize
```


Récupère la taille physique de la page actuellement sélectionnée sur un dispositif de sortie.

### Getprintingoffset {#Getprintingoffset}
```
public static final int Getprintingoffset
```


Récupère le décalage depuis le coin supérieur gauche de la page physique où l'impression ou le dessin réel commence.

### Getscalingfactor {#Getscalingfactor}
```
public static final int Getscalingfactor
```


Récupère les facteurs d'échelle pour l'axe x et l'axe y d'une imprimante.

### MetaEscapeEnhancedMetafile {#MetaEscapeEnhancedMetafile}
```
public static final int MetaEscapeEnhancedMetafile
```


Utilisé pour incorporer un métafichier au format amélioré (EMF) dans un métafichier WMF.

### Setpenwidth {#Setpenwidth}
```
public static final int Setpenwidth
```


Définit la largeur d'un crayon en pixels.

### Setcopycount {#Setcopycount}
```
public static final int Setcopycount
```


Définit le nombre de copies.

### Setpapersource {#Setpapersource}
```
public static final int Setpapersource
```


Définit la source, comme un bac à papier particulier ou un tiroir d'imprimante, pour les formulaires de sortie.

### Passthrough {#Passthrough}
```
public static final int Passthrough
```


Cet enregistrement transmet des données arbitraires.

### Gettechnology {#Gettechnology}
```
public static final int Gettechnology
```


Obtient des informations concernant la technologie graphique prise en charge sur un dispositif.

### Setlinecap {#Setlinecap}
```
public static final int Setlinecap
```


Spécifie le mode de tracé de ligne à utiliser lors de la sortie vers un dispositif.

### Setlinejoin {#Setlinejoin}
```
public static final int Setlinejoin
```


Spécifie le mode de jointure de ligne à utiliser lors de la sortie vers un dispositif.

### Setmiterlimit {#Setmiterlimit}
```
public static final int Setmiterlimit
```


Définit la limite de la longueur des jointures en onglet à utiliser lors de la sortie vers un dispositif.

### Bandinfo {#Bandinfo}
```
public static final int Bandinfo
```


Récupère ou spécifie les paramètres concernant le banding sur un appareil, tels que le nombre de bandes.

### Drawpatternrect {#Drawpatternrect}
```
public static final int Drawpatternrect
```


Dessine un rectangle avec un motif défini.

### Getvectorpensize {#Getvectorpensize}
```
public static final int Getvectorpensize
```


Récupère la taille physique du stylet actuellement définie sur un appareil.

### Getvectorbrushsize {#Getvectorbrushsize}
```
public static final int Getvectorbrushsize
```


Récupère la taille physique du pinceau actuellement définie sur un appareil.

### Enableduplex {#Enableduplex}
```
public static final int Enableduplex
```


Active ou désactive l'impression recto verso (duplex) sur un appareil.

### Getsetpaperbins {#Getsetpaperbins}
```
public static final int Getsetpaperbins
```


Récupère ou spécifie la source des formulaires de sortie sur un appareil.

### Getsetprintorient {#Getsetprintorient}
```
public static final int Getsetprintorient
```


Récupère ou spécifie l'orientation du papier sur un appareil.

### Enumpaperbins {#Enumpaperbins}
```
public static final int Enumpaperbins
```


Récupère les informations concernant les sources de différents formulaires sur un dispositif de sortie.

### Setdibscaling {#Setdibscaling}
```
public static final int Setdibscaling
```


Spécifie le redimensionnement des bitmaps indépendants du dispositif (DIBs).

### Epsprinting {#Epsprinting}
```
public static final int Epsprinting
```


Indique le début et la fin d'une section PostScript encapsulé (EPS).

### Enumpapermetrics {#Enumpapermetrics}
```
public static final int Enumpapermetrics
```


Interroge le pilote d'imprimante pour les dimensions du papier et d'autres données de formulaires.

### Getsetpapermetrics {#Getsetpapermetrics}
```
public static final int Getsetpapermetrics
```


Récupère ou spécifie les dimensions du papier et d'autres données de formulaires sur un dispositif de sortie.

### PostscriptData {#PostscriptData}
```
public static final int PostscriptData
```


Envoie des données PostScript arbitraires à un dispositif de sortie.

### PostscriptIgnore {#PostscriptIgnore}
```
public static final int PostscriptIgnore
```


Notifie un dispositif de sortie d'ignorer les données PostScript.

### Getdeviceunits {#Getdeviceunits}
```
public static final int Getdeviceunits
```


Obtient les unités du dispositif actuellement configurées sur un dispositif de sortie.

### Getextendedtextmetrics {#Getextendedtextmetrics}
```
public static final int Getextendedtextmetrics
```


Obtient les métriques de texte étendues actuellement configurées sur un dispositif de sortie.

### Getpairkerntable {#Getpairkerntable}
```
public static final int Getpairkerntable
```


Obtient la table de crénage des polices actuellement définie sur un dispositif de sortie.

### Exttextout {#Exttextout}
```
public static final int Exttextout
```


Dessine du texte en utilisant la police actuellement sélectionnée, la couleur d'arrière-plan et la couleur du texte.

### Getfacename {#Getfacename}
```
public static final int Getfacename
```


Obtient le nom de la police actuellement configuré sur un appareil.

### Downloadface {#Downloadface}
```
public static final int Downloadface
```


Définit le nom de la police sur un appareil.

### MetafileDriver {#MetafileDriver}
```
public static final int MetafileDriver
```


Interroge le pilote d'imprimante concernant la prise en charge des métafichiers sur un dispositif de sortie.

### Querydibsupport {#Querydibsupport}
```
public static final int Querydibsupport
```


Interroge le pilote d'imprimante concernant sa prise en charge des DIBs sur un dispositif de sortie.

### BeginPath {#BeginPath}
```
public static final int BeginPath
```


Ouvre un chemin.

### ClipToPath {#ClipToPath}
```
public static final int ClipToPath
```


Définit une région de découpage délimitée par un chemin. L'entrée DOIT être une quantité de 16 bits qui définit l'action à effectuer.

### EndPath {#EndPath}
```
public static final int EndPath
```


Termine un chemin.

### OpenChannel {#OpenChannel}
```
public static final int OpenChannel
```


Identique à STARTDOC spécifié avec un document NULL et un nom de fichier de sortie, des données en mode brut, et un type de zéro.

### Downloadheader {#Downloadheader}
```
public static final int Downloadheader
```


Indique au pilote d'imprimante de télécharger des ensembles de procédures PostScript.

### CloseChannel {#CloseChannel}
```
public static final int CloseChannel
```


Identique à ENDDOC. Voir OPEN\_CHANNEL.

### PostscriptPassthrough {#PostscriptPassthrough}
```
public static final int PostscriptPassthrough
```


Envoie des données arbitraires directement au pilote d'imprimante, qui doit traiter ces données uniquement en mode PostScript. [PostscriptIdentify](../../com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes\#PostscriptIdentify).

### EncapsulatedPostscript {#EncapsulatedPostscript}
```
public static final int EncapsulatedPostscript
```


Envoie des données arbitraires directement au pilote d'imprimante.

### PostscriptIdentify {#PostscriptIdentify}
```
public static final int PostscriptIdentify
```


Configure le pilote d'imprimante en mode PostScript ou GDI.

### PostscriptInjection {#PostscriptInjection}
```
public static final int PostscriptInjection
```


Insère un bloc de données brutes dans un flux PostScript. L'entrée DOIT être une quantité de 32 bits spécifiant le nombre d'octets à injecter, une quantité de 16 bits spécifiant le point d'injection, et une quantité de 16 bits spécifiant le numéro de page, suivies des octets à injecter.

### Checkjpegformat {#Checkjpegformat}
```
public static final int Checkjpegformat
```


Vérifie si l'imprimante prend en charge une image JPEG.

### Checkpngformat {#Checkpngformat}
```
public static final int Checkpngformat
```


Vérifie si l'imprimante prend en charge une image PNG.

### GetPsFeaturesetting {#GetPsFeaturesetting}
```
public static final int GetPsFeaturesetting
```


Obtient des informations sur un paramètre de fonctionnalité spécifié pour un pilote d'imprimante PostScript.

### MxdcEscape {#MxdcEscape}
```
public static final int MxdcEscape
```


Permet aux applications d'écrire des documents dans un fichier ou vers une imprimante au format XML Paper Specification (XPS).

### Spclpassthrough2 {#Spclpassthrough2}
```
public static final int Spclpassthrough2
```


Permet aux applications d'inclure des procédures privées et d'autres données arbitraires dans les documents.

