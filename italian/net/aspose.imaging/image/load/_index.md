---
title: Load
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Carica una nuova immagine dal file specificato.
type: docs
weight: 20
url: /it/net/aspose.imaging/image/load/
---
## Load(string, LoadOptions) {#load_3}

Carica una nuova immagine dal file specificato.

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file da cui caricare l'immagine. |
| loadOptions | LoadOptions | Le opzioni di carico. |

### Valore di ritorno

L'immagine caricata.

### Guarda anche

* class [LoadOptions](../../loadoptions)
* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

---

## Load(string) {#load_2}

Carica una nuova immagine dal file specificato.

```csharp
public static Image Load(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file da cui caricare l'immagine. |

### Valore di ritorno

L'immagine caricata.

### Esempi

Questo esempio mostra il caricamento di un file immagine esistente in un'istanza di Aspose.Imaging.Image utilizzando il percorso del file specificato

```csharp
[C#]

//Crea un'istanza di immagine e inizializzala con un file di immagine esistente dalla posizione del disco
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
{
    //eseguo un po' di elaborazione delle immagini
}
```

### Guarda anche

* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Carica una nuova immagine dal flusso specificato.

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare l'immagine. |
| loadOptions | LoadOptions | Le opzioni di carico. |

### Valore di ritorno

L'immagine caricata.

### Guarda anche

* class [LoadOptions](../../loadoptions)
* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

---

## Load(Stream) {#load}

Carica una nuova immagine dal flusso specificato.

```csharp
public static Image Load(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare l'immagine. |

### Valore di ritorno

L'immagine caricata.

### Esempi

Questo esempio mostra l'uso degli oggetti System.IO.Stream per caricare un file immagine esistente

```csharp
[C#]

//Crea un'istanza di FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.bmp", System.IO.FileMode.Open))
{
    //Crea un'istanza della classe Image e carica un file esistente tramite l'oggetto FileStream chiamando il metodo Load
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(stream))
    {
        //eseguo un po' di elaborazione delle immagini.
    }
}
```

### Guarda anche

* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
