---
title: TiffTags
second_title: Aspose.Imaging for .NET API Referansı
description: tiff etiketi enum.
type: docs
weight: 7740
url: /tr/aspose.imaging.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

tiff etiketi enum.

```csharp
public enum TiffTags
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| SubFileType | `254` | Alt dosya veri tanımlayıcısı. |
| OsubfileType | `255` | [TIFF rev. 5.0] Alt dosyadaki veri türü. |
| ImageWidth | `256` | Piksel cinsinden görüntü genişliği. |
| ImageLength | `257` | Piksel cinsinden resim yüksekliği. |
| BitsPerSample | `258` | Kanal başına bit (örnek). |
| Compression | `259` | Veri sıkıştırma tekniği. |
| Photometric | `262` | Fotometrik yorumlama. |
| Thresholding | `263` | [TIFF rev. 5.0] Verilerde kullanılan eşik. |
| CellWidth | `264` | [TIFF rev. 5.0] Titreşim matrisi genişliği. |
| CellLength | `265` | [TIFF rev. 5.0] Titreşim matrisi yüksekliği. |
| FillOrder | `266` | Bir bayt içinde veri sırası. |
| DocumentName | `269` | Görüntü için tutulan belgenin adı. |
| ImageDescription | `270` | Resim hakkında bilgi. |
| Make | `271` | Tarayıcı üreticisi adı. |
| Model | `272` | Tarayıcı model adı/numarası. |
| StripOffsets | `273` | Veri şeritlerine ofsetler. |
| Orientation | `274` | [TIFF rev. 5.0] Görüntü yönü. |
| SamplesPerPixel | `277` | Piksel başına örnek. |
| RowsPerStrip | `278` | Veri şeridi başına satır sayısı. |
| StripByteCounts | `279` | Şeritler için bayt sayısı. |
| MinSampleValue | `280` | [TIFF rev. 5.0] Minimum örnek değeri. |
| MaxSampleValue | `281` | [TIFF rev. 5.0] Maksimum örnek değeri. |
| Xresolution | `282` | x. cinsinden piksel/çözünürlük |
| Yresolution | `283` | Y. cinsinden piksel/çözünürlük |
| PlanarConfig | `284` | Depolama organizasyonu. |
| PageName | `285` | Sayfa adı resmi şuradan. |
| Xposition | `286` | Resmin X sayfa ofseti lhs. |
| Yposition | `287` | Y resminin sayfa ofseti lhs. |
| FreeOffsets | `288` | [TIFF rev. 5.0] Serbest bloğa bayt ofseti. |
| FreeByteCounts | `289` | [TIFF rev. 5.0] Serbest blokların boyutları. |
| GrayResponseUnit | `290` | [TIFF rev. 6.0] Gri tonlama eğrisi doğruluğu. |
| GrayResponseCurve | `291` | [TIFF rev. 6.0] Gri tonlamalı yanıt eğrisi. |
| T4Options | `292` | TIFF 6.0 GROUP3OPTIONS için özel ad takma adı. CCITT Grup 3 faks kodlaması için seçenekler. 32 bayrak biti. |
| T6Options | `293` | CCITT Grup 4 faks kodlaması için seçenekler. 32 bayrak biti. GROUP4OPTIONS için TIFF 6.0 özel ad takma adı. |
| ResolutionUnit | `296` | Çözünürlük birimleri. |
| PageNumber | `297` | Çok sayfalı sayfa numaraları. |
| ColorResponseUnit | `300` | [TIFF rev. 6.0] Renk eğrisi doğruluğu. |
| TransferFunction | `301` | Kolorimetri bilgisi. |
| Software | `305` | Ad ve sürüm. |
| DateTime | `306` | Oluşturma tarihi ve saati. |
| Artist | `315` | Resmin yaratıcısı. |
| HostComputer | `316` | Oluşturulan makine. |
| Predictor | `317` | LZW ile tahmin şeması. |
| WhitePoint | `318` | Görüntü beyaz nokta. |
| PrimaryChromaticities | `319` | Birincil renklilikler. |
| ColorMap | `320` | Palet görüntüsü için RGB haritası. |
| HalftoneHints | `321` | Vurgu + gölge bilgisi. |
| TileWidth | `322` | Piksel cinsinden döşeme genişliği. |
| TileLength | `323` | Piksel cinsinden döşeme yüksekliği. |
| TileOffsets | `324` | Veri döşemelerine ofsetler. |
| TileByteCounts | `325` | Döşemeler için bayt sayısı. |
| BadFaxLines | `326` | Yanlış piksel sayısına sahip çizgiler. |
| CleanFaxData | `327` | Yeniden oluşturulmuş satır bilgisi. |
| ConsecutiveBadFaxLines | `328` | Maksimum ardışık hatalı satır. |
| SubIfd | `330` | Alt görüntü tanımlayıcıları. |
| InkSet | `332` | Mürekkepler ayrı görüntüde. |
| InkNames | `333` | ASCII mürekkep adları. |
| NumberOfInks | `334` | Mürekkep sayısı. |
| DotRange | `336` | %0 ve %100 nokta kodları. |
| TargetPrinter | `337` | Ayırma hedefi. |
| ExtraSamples | `338` | Ekstra numuneler hakkında bilgi. |
| SampleFormat | `339` | Veri örneği biçimi. |
| SminSampleValue | `340` | Değişken MinSampleValue. |
| SmaxSampleValue | `341` | Değişken MaxSampleValue. |
| TransferRange | `342` | Değişken TransferRange |
| ClipPath | `343` | Klip Yolu. Adobe TIFF technote 2. tarafından TIFF rev 6.0 sonrası tanıtıldı |
| Xclippathunits | `344` | XClipPathBirimleri. Adobe TIFF technote 2. tarafından TIFF rev 6.0 sonrası tanıtıldı |
| Yclippathunits | `345` | YClipPathBirimleri. Adobe TIFF technote 2. tarafından TIFF rev 6.0 sonrası tanıtıldı |
| Indexed | `346` | Dizine eklendi. Adobe TIFF Technote 3. tarafından TIFF rev 6.0 sonrası tanıtıldı |
| JpegTables | `347` | JPEG tablo akışı. TIFF rev 6.0. sonrası tanıtıldı |
| OpiProxy | `351` | OPI Proxy'si. Adobe TIFF technote tarafından TIFF rev 6.0 sonrası tanıtıldı. |
| JpegProc | `512` | [gözden geçirilmiş bir TIFF içinde JPEG şemasını belirten Teknik Not #2 tarafından geçersiz kılınmıştır] JPEG işleme algoritması. |
| JpegInerchangeFormat | `513` | [gözden geçirilmiş bir TIFF içinde JPEG şemasını belirten Teknik Not #2 tarafından geçersiz kılınmıştır] SOI işaretçisine işaretçi. |
| JpegInterchangeFormatLength | `514` | [gözden geçirilmiş bir TIFF içinde JPEG şemasını belirten Teknik Not #2 tarafından geçersiz kılınmıştır] JFIF akış uzunluğu |
| JpegRestartInterval | `515` | [gözden geçirilmiş bir TIFF içinde JPEG şemasını belirten Teknik Not #2 tarafından geçersiz kılınmıştır] Aralık uzunluğunu yeniden başlatın. |
| JpegLosslessPredictors | `517` | [gözden geçirilmiş bir TIFF içinde JPEG şemasını belirten Teknik Not #2 tarafından geçersiz kılınmıştır] Kayıpsız proc tahmincisi. |
| JpegPointTransform | `518` | [gözden geçirilmiş bir TIFF içinde JPEG şemasını belirten Teknik Not #2 tarafından geçersiz kılınmıştır] Kayıpsız nokta dönüşümü. |
| JpegQTables | `519` | [gözden geçirilmiş bir TIFF içinde JPEG şemasını belirten Teknik Not #2 tarafından geçersiz kılınmıştır] Q matris ofsetleri. |
| JpegDCtables | `520` | [gözden geçirilmiş bir TIFF içinde JPEG şemasını belirten Teknik Not #2 tarafından geçersiz kılınmıştır] DCT tablosu ofsetleri. |
| JpegACtables | `521` | [gözden geçirilmiş bir TIFF içinde JPEG şemasını belirten Teknik Not #2 tarafından geçersiz kılınmıştır] AC katsayısı ofsetleri. |
| YcbcrCoefficients | `529` | RGB -&gt; YCbCr dönüşümü. |
| YcbcrSubSampling | `530` | YCbCr alt örnekleme faktörleri. |
| YcbcrPositioning | `531` | Alt örnek konumlandırma. |
| ReferenceBlackWhite | `532` | Kolorimetri bilgisi. |
| XmlPacket | `700` | XML paketi. Adobe XMP Spesifikasyonu tarafından TIFF rev 6.0 sonrası tanıtıldı, Ocak 2004. |
| OpiImageid | `32781` | OPI Görüntü Kimliği. Adobe TIFF technote tarafından TIFF rev 6.0 sonrası tanıtıldı. |
| Refpts | `32953` | Görüntü referans noktaları. Island Graphics'e kayıtlı özel etiket. |
| Copyright | `33432` | Telif hakkı dizesi. Bu etiket TIFF rev. 6,0 w/ bilinmeyen sahiplik. |
| PhotoshopResources | `34377` | Photoshop görüntü kaynakları. |
| IccProfile | `34675` | Yerleşik ICC cihaz profili |
| ExifIfdPointer | `34665` | Exif IFD'sine yönelik bir işaretçi. |
| XPTitle | `40091` | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi. XPTitle Windows Gezgini tarafından yoksayılır.ImageDescription etiket var. |
| XPComment | `40092` | Windows Gezgini tarafından kullanılan görüntüye yorum yapın. |
| XPAuthor | `40093` | Windows Gezgini tarafından kullanılan Resim Yazarı. XPAuthor Windows Gezgini tarafından yoksayılır.Artist etiket var. |
| XPKeywords | `40094` | Windows Gezgini tarafından kullanılan Resim Anahtar Kelimeleri. |
| XPSubject | `40095` | Windows Gezgini tarafından kullanılan konu resmi. |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
