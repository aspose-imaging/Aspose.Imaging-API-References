---
title: WmfMetafileEscapes
second_title: Aspose.Imaging for .NET API Referansı
description: MetafileEscapes Numaralandırması RecordType Numaralandırmasında bölüm 2.1.1.1 tanımlanan WMF kayıtları aracılığıyla doğrudan erişilebilir olmayabilecek yazıcı sürücüsü işlevselliğini belirtir.
type: docs
weight: 8230
url: /tr/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
## WmfMetafileEscapes enumeration

MetafileEscapes Numaralandırması, RecordType Numaralandırmasında (bölüm 2.1.1.1) tanımlanan WMF kayıtları aracılığıyla doğrudan erişilebilir olmayabilecek yazıcı sürücüsü işlevselliğini belirtir.

```csharp
public enum WmfMetafileEscapes
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Newframe | `1` | Uygulamanın bir sayfaya yazmayı bitirdiğini yazıcı sürücüsüne bildirir. |
| Abortdoc | `2` | Geçerli belgeyi işlemeyi durdurur. |
| Nextband | `3` | Uygulamanın bir banda yazmayı bitirdiğini yazıcı sürücüsüne bildirir. |
| Setcolortable | `4` | Renk tablosu değerlerini ayarlar. |
| Getcolortable | `5` | Renk tablosu değerlerini alır. |
| Flushout | `6` | Bekleyen tüm çıktıların çıktı aygıtına boşaltılmasına neden olur. |
| Draftmode | `7` | Yazıcı sürücüsünün yalnızca metin yazdırması ve grafik içermemesi gerektiğini belirtir. |
| Queryescsupport | `8` | Belirli bir kaçış function 'nin sürdüğü çıkış aygıtında desteklenip desteklenmediğini belirlemek için bir yazıcı sürücüsünü sorgular. |
| Setabortproc | `9` | Bir yazdırma işinin yazdırma sırasında iptal edilmesini sağlayan uygulama tanımlı işlevi ayarlar . |
| Startdoc | `10` | Yazıcı sürücüsüne yeni bir yazdırma işinin başladığını bildirir. |
| Enddoc | `11` | Yazıcı sürücüsüne geçerli yazdırma işinin sona erdiğini bildirir. |
| Getphyspagesize | `12` | Bir çıktı aygıtında seçili olan fiziksel sayfa boyutunu alır. |
| Getprintingoffset | `13` | Asıl yazdırma veya çizimin başladığı fiziksel sayfanın sol üst köşesinden ofseti alır. |
| Getscalingfactor | `14` | Bir yazıcının x ekseni ve y ekseni için ölçeklendirme faktörlerini alır. |
| MetaEscapeEnhancedMetafile | `15` | Gelişmiş bir meta dosya biçimini (EMF) bir WMF meta dosyasına gömmek için kullanılır. |
| Setpenwidth | `16` | Bir kalemin genişliğini piksel olarak ayarlar. |
| Setcopycount | `17` | Kopya sayısını ayarlar. |
| Setpapersource | `18` | Yazıcıdaki belirli bir kağıt tepsisi veya sele gibi kaynağı, çıktı formları için ayarlar. |
| Passthrough | `19` | Bu kayıt rastgele verilerden geçer. |
| Gettechnology | `20` | a aygıtında desteklenen grafik teknolojisiyle ilgili bilgileri alır. |
| Setlinecap | `21` | Bir aygıta çıkışta kullanılacak çizgi çizme modunu belirtir. |
| Setlinejoin | `22` | Bir aygıta çıkışta kullanılacak hat birleştirme modunu belirtir. |
| Setmiterlimit | `23` | Bir aygıta çıkışta kullanılacak gönye bağlantılarının uzunluğu sınırını ayarlar. |
| Bandinfo | `24` | Bantların sayısı gibi bir aygıttaki bantlamayla ilgili ayarları alır veya belirtir. |
| Drawpatternrect | `25` | Tanımlı bir desene sahip bir dikdörtgen çizer. |
| Getvectorpensize | `26` | Bir aygıtta halihazırda tanımlanmış olan fiziksel kalem boyutunu alır. |
| Getvectorbrushsize | `27` | Bir aygıtta şu anda tanımlanmış olan fiziksel fırça boyutunu alır. |
| Enableduplex | `28` | Bir aygıtta çift taraflı (dupleks) yazdırmayı etkinleştirir veya devre dışı bırakır. |
| Getsetpaperbins | `29` | Bir aygıttaki çıktı formlarının kaynağını alır veya belirtir. |
| Getsetprintorient | `30` | Bir aygıttaki kağıt yönünü alır veya belirtir. |
| Enumpaperbins | `31` | an çıktı aygıtındaki farklı formların kaynaklarıyla ilgili bilgileri alır. |
| Setdibscaling | `32` | Aygıttan bağımsız bit eşlemlerin (DIB'ler) ölçeklenmesini belirtir. |
| Epsprinting | `33` | Kapsüllenmiş PostScript (EPS) bölümünün başlangıcını ve sonunu gösterir. |
| Enumpapermetrics | `34` | Kağıt boyutları ve diğer form verileri için bir yazıcı sürücüsü sorgular. |
| Getsetpapermetrics | `35` | Bir çıktı aygıtında kağıt boyutları ve diğer form verilerini alır veya belirtir. |
| PostscriptData | `37` | Bir çıktı aygıtına rastgele PostScript verileri gönderir. |
| PostscriptIgnore | `38` | Çıkış aygıtına PostScript verilerini yoksaymasını bildirir. |
| Getdeviceunits | `42` | Bir çıkış aygıtında şu anda yapılandırılmış aygıt birimlerini alır. |
| Getextendedtextmetrics | `256` | Şu anda bir output cihazında yapılandırılmış genişletilmiş metin metriklerini alır. |
| Getpairkerntable | `258` | Bir çıktı aygıtında halihazırda tanımlanmış olan yazı tipi karakter aralığı tablosunu alır. |
| Exttextout | `512` | Seçili olan yazı tipini, arka plan rengini ve metin rengini kullanarak metin çizer. |
| Getfacename | `513` | Bir aygıtta şu anda yapılandırılmış olan yazı tipi yüz adını alır. |
| Downloadface | `514` | Bir aygıttaki yazı tipi yüz adını ayarlar. |
| MetafileDriver | `2049` | Bir output aygıtındaki meta dosyaları desteği hakkında bir yazıcı sürücüsünü sorgular. |
| Querydibsupport | `3073` | Yazıcı sürücüsünü bir çıktı aygıtındaki DIB desteği hakkında sorgular. |
| BeginPath | `4096` | Bir yol açar. |
| ClipToPath | `4097` | Bir yolla sınırlanan bir klip bölgesi tanımlar. Giriş, yapılacak eylemi tanımlayan 16 bit bir miktar OLMALIDIR. |
| EndPath | `4098` | Bir yolu sonlandırır. |
| OpenChannel | `4110` | BOŞ belge ve output dosya adı, ham moddaki veriler ve bir sıfır türü ile belirtilen STARTDOC ile aynı. |
| Downloadheader | `4111` | Yazıcı sürücüsüne PostScript prosedür setlerini indirmesi talimatını verir. |
| CloseChannel | `4112` | ENDDOC ile aynı. OPEN_CHANNEL. 'ye bakın |
| PostscriptPassthrough | `4115` | Rastgele verileri doğrudan, bu verileri yalnızca PostScript modundayken işlemesi beklenen yazıcı sürücüsüne gönderir.PostscriptIdentify . |
| EncapsulatedPostscript | `4116` | İsteğe bağlı verileri doğrudan yazıcı sürücüsüne gönderir. |
| PostscriptIdentify | `4117` | Yazıcı sürücüsünü PostScript veya GDI moduna ayarlar. |
| PostscriptInjection | `4118` | PostScript akışına bir ham veri bloğu ekler. input , enjekte edilecek bayt sayısını belirten 32 bitlik bir miktar, enjeksiyon noktasını belirten 16 bitlik bir miktar ve sayfa numarasını belirten 16 bitlik bir nicelik ve ardından enjekte edilecek baytlar olmalıdır. |
| Checkjpegformat | `4119` | Yazıcının bir JPEG görüntüsünü destekleyip desteklemediğini kontrol eder. |
| Checkpngformat | `4120` | Yazıcının PNG görüntüsünü destekleyip desteklemediğini kontrol eder. |
| GetPsFeaturesetting | `4121` | PostScript yazıcı sürücüsü için belirtilen özellik ayarı hakkında bilgi alır. |
| MxdcEscape | `4122` | Uygulamaların belgeleri bir dosyaya veya bir yazıcıya XML Paper Belirtim (XPS) biçiminde yazmasına olanak tanır. |
| Spclpassthrough2 | `4568` | Uygulamaların özel prosedürleri ve diğer keyfi verileri belgelere dahil etmesini sağlar. |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
