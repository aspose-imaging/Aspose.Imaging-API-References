---
title: "aspose.imaging.fileformats.bmp"
type: docs
weight: 140
url: /sv/python-net/aspose.imaging.fileformats.bmp/
---


Modulen hanterar Bmp‑filformatbehandling.

## **Classes**
| **Klass** | **Description** |
| :- | :- |
| [BitmapCoreHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcoreheader/) | Dimensioner och färgformat för DIB.<br/>            Headernamn BITMAPCOREHEADER även känt som OS21XBITMAPHEADER. |
| [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | Specificerar BITMAPINFOHEADER. <br/>                OS-stöd: Windows NT, 3.1x eller senare.<br/>                Funktioner: Lägger till 16 bpp och 32 bpp format. Lägger till RLE-komprimering. |
| [BitmapV4Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/) | BitmapV4Header-strukturen är bitmapinformationens headerfil. Det är en utökad version av BITMAPINFOHEADER-strukturen.<br/>            <br/>BitmapV4Header-strukturen är utökad för att tillåta en JPEG- eller PNG-bild att skickas som källbild till StretchDIBits.<br/> |
| [BitmapV5Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/) | BitmapV5Header-strukturen är bitmapinformationens headerfil. Det är en utökad version av BITMAPINFOHEADER-strukturen.<br/>            <br/>Om bV5Height är negativt, vilket indikerar en top‑down DIB, måste bV5Compression vara antingen BI_RGB eller BI_BITFIELDS. Top‑down DIBs kan inte komprimeras.<br/>            Det oberoende färghanteringsgränssnittet (ICM) 2.0 tillåter International Color Consortium (ICC) färgprofiler att länkas eller bäddas in i DIBs (DIBs). <br/>            Se Använda strukturer för mer information. När en DIB laddas in i minnet bör profildata (om den finns) följa färgtabellen, <br/>            och bV5ProfileData ska ange offseten för profildata från början av BITMAPV5HEADER-strukturen. <br/>            Värdet som lagras i bV5ProfileData kommer att skilja sig från värdet som returneras av sizeof-operatorn för BITMAPV5HEADER-argumentet, <br/>            eftersom bV5ProfileData är offseten i byte från början av BITMAPV5HEADER-strukturen till början av profildata. <br/>            (Bitmap-bitar följer inte färgtabellen i minnet). Applikationer bör ändra bV5ProfileData-medlemmen efter att DIB har laddats in i minnet.<br/>            För packade DIBs bör profildata följa bitmap-bitarna på liknande sätt som filformatet. <br/>            bV5ProfileData-medlemmen bör fortfarande ge offseten för profildata från början av BITMAPV5HEADER.<br/>            Applikationer bör endast komma åt profildata när bV5Size är lika med storleken på BITMAPV5HEADER och bV5CSType är PROFILE_EMBEDDED eller PROFILE_LINKED.<br/> |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) | Du kan enkelt hantera Bitmap (BMP) och Device Independent Bitmap<br/>            (DIB)-filer, vilket underlättar effektiv manipulation och bearbetning av raster<br/>            bilder. Genom att utföra olika operationer på bilder förenklar detta API<br/>            arbetsflödet och erbjuder utvecklare ett pålitligt verktyg för att arbeta med BMP och<br/>            DIB-format i sina mjukvaruapplikationer. |
| [Os22XBitmapHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/) | En OS/2 2.x OS22XBITMAPHEADER även känd som BITMAPCOREHEADER2. |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Specificerar olika bitmap-komprimeringsmetoder. |
