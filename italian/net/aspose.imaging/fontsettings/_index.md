---
title: FontSettings
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Impostazioni generali dei caratteri del renderer dei formati vettoriali di imaging.
type: docs
weight: 9340
url: /it/net/aspose.imaging/fontsettings/
---
## FontSettings class

Impostazioni generali dei caratteri del renderer dei formati vettoriali di imaging.

```csharp
public static class FontSettings
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [DefaultFontName](../../aspose.imaging/fontsettings/defaultfontname) { get; set; } | Ottiene o imposta il nome predefinito del carattere. |
| static [GetSystemAlternativeFont](../../aspose.imaging/fontsettings/getsystemalternativefont) { get; set; } | Ottiene o imposta un valore che indica se [ottieni font alternativo]. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [GetDefaultFontsFolders](../../aspose.imaging/fontsettings/getdefaultfontsfolders)() | Ottiene le cartelle dei caratteri predefinite. |
| static [GetFontsFolders](../../aspose.imaging/fontsettings/getfontsfolders)() | Ottiene una copia dell'array che contiene l'elenco delle cartelle in cui Aspose.Words cerca i caratteri TrueType. |
| static [Reset](../../aspose.imaging/fontsettings/reset)() | Reimposta la cartella dei caratteri e il nome del carattere predefinito sui valori predefiniti di sistema. |
| static [SetFontsFolder](../../aspose.imaging/fontsettings/setfontsfolder)(string) | Questa è una scorciatoia per[`SetFontsFolders`](./setfontsfolders) per impostare una sola directory dei font. Non ci sono controlli effettuati sulla cartella dei font. |
| static [SetFontsFolders](../../aspose.imaging/fontsettings/setfontsfolders)(string[], bool) | Imposta le cartelle da cui vengono caricati i font TrueType e cancella tutti i font caricati. Non ci sono controlli eseguiti sulle cartelle dei font. |
| static [UpdateFonts](../../aspose.imaging/fontsettings/updatefonts)() | Aggiorna la cache dei caratteri per i file PSD che contengono livelli di testo. Questo metodo garantisce che i caratteri dalla cartella fontsFolder using method FontSettings.SetFontsFolder(fontsFolder) o dopo il ripristino dei caratteri usando FontSettings.Reset() verranno presi in considerazione durante l'elaborazione dei file PSD. Utilizzare questo metodo ogni volta che FontSettings.SetFontsFolder(fontsFolder) o FontSettings.Reset() richiamano immagini PSD. Senza chiamare questo metodo non vi è alcuna garanzia che i caratteri verranno aggiornati. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
