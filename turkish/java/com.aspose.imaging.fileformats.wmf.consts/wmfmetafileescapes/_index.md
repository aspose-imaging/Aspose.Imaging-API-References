---
title: "WmfMetafileEscapes"
second_title: "Aspose.Imaging for Java API Referansı"
description: "MetafileEscapes Sıralaması, yazıcı sürücüsü işlevselliğini belirtir ve bu işlevsellik, RecordType Sıralaması bölüm 2.1.1.1'de tanımlanan WMF kayıtları aracılığıyla doğrudan erişilemeyebilir."
type: docs
weight: 24
url: /tr/java/com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfMetafileEscapes extends System.Enum
```

MetafileEscapes Sıralaması, RecordType Sıralamasında (bölüm 2.1.1.1) tanımlanan WMF kayıtları aracılığıyla doğrudan erişilemeyebilecek yazıcı sürücü işlevselliğini belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Newframe](#Newframe) | Uygulamanın bir sayfaya yazmayı tamamladığını yazıcı sürücüsüne bildirir. |
| [Abortdoc](#Abortdoc) | Mevcut belgenin işlenmesini durdurur. |
| [Nextband](#Nextband) | Uygulamanın bir banda yazmayı tamamladığını yazıcı sürücüsüne bildirir. |
| [Setcolortable](#Setcolortable) | Renk tablosu değerlerini ayarlar. |
| [Getcolortable](#Getcolortable) | Renk tablosu değerlerini alır. |
| [Flushout](#Flushout) | Bekleyen tüm çıktının çıkış cihazına boşaltılmasını sağlar. |
| [Draftmode](#Draftmode) | Yazıcı sürücüsünün yalnızca metin yazdırması gerektiğini ve grafik yazdırmamasını gösterir. |
| [Queryescsupport](#Queryescsupport) | Bir yazıcı sürücüsüne, sürücünün yönettiği çıkış cihazında belirli bir kaçış işlevinin desteklenip desteklenmediğini belirlemek için sorgu gönderir. |
| [Setabortproc](#Setabortproc) | Yazdırma sırasında bir baskı işinin iptal edilmesini sağlayan, uygulama tarafından tanımlanan işlevi ayarlar. |
| [Startdoc](#Startdoc) | Yeni bir baskı işinin başladığını yazıcı sürücüsüne bildirir. |
| [Enddoc](#Enddoc) | Mevcut baskı işinin sona erdiğini yazıcı sürücüsüne bildirir. |
| [Getphyspagesize](#Getphyspagesize) | Çıkış cihazında şu anda seçili olan fiziksel sayfa boyutunu alır. |
| [Getprintingoffset](#Getprintingoffset) | Gerçek baskı veya çizimin başladığı fiziksel sayfanın sol üst köşesinden ofseti alır. |
| [Getscalingfactor](#Getscalingfactor) | Yazıcının x ekseni ve y ekseni için ölçekleme faktörlerini alır. |
| [MetaEscapeEnhancedMetafile](#MetaEscapeEnhancedMetafile) | Bir WMF metafilesi içinde geliştirilmiş metafile formatı (EMF) metafilesi gömmek için kullanılır. |
| [Setpenwidth](#Setpenwidth) | Kalemin piksel cinsinden genişliğini ayarlar. |
| [Setcopycount](#Setcopycount) | Kopya sayısını ayarlar. |
| [Setpapersource](#Setpapersource) | Çıktı formları için, bir yazıcıdaki belirli bir kağıt tepsisi veya kutu gibi kaynağı ayarlar. |
| [Passthrough](#Passthrough) | Bu kayıt rastgele verileri geçirir. |
| [Gettechnology](#Gettechnology) | Bir cihazda desteklenen grafik teknolojisiyle ilgili bilgileri alır. |
| [Setlinecap](#Setlinecap) | Bir cihaza çıktıda kullanılacak çizgi çizme modunu belirtir. |
| [Setlinejoin](#Setlinejoin) | Bir cihaza çıktıda kullanılacak çizgi birleştirme modunu belirtir. |
| [Setmiterlimit](#Setmiterlimit) | Bir cihaza çıktıda kullanılacak köşe birleşimlerinin uzunluk sınırını ayarlar. |
| [Bandinfo](#Bandinfo) | Bir cihazdaki bantlama ile ilgili ayarları, örneğin bant sayısını, alır veya belirtir. |
| [Drawpatternrect](#Drawpatternrect) | Tanımlı bir desenle bir dikdörtgen çizer. |
| [Getvectorpensize](#Getvectorpensize) | Bir cihazda şu anda tanımlı fiziksel kalem boyutunu alır. |
| [Getvectorbrushsize](#Getvectorbrushsize) | Bir cihazda şu anda tanımlı fiziksel fırça boyutunu alır. |
| [Enableduplex](#Enableduplex) | Bir cihazda çift taraflı (duplex) baskıyı etkinleştirir veya devre dışı bırakır. |
| [Getsetpaperbins](#Getsetpaperbins) | Bir cihazdaki çıktı formlarının kaynağını alır veya belirtir. |
| [Getsetprintorient](#Getsetprintorient) | Bir cihazdaki kağıt yönlendirmesini alır veya belirtir. |
| [Enumpaperbins](#Enumpaperbins) | Bir çıktı cihazındaki farklı formların kaynaklarıyla ilgili bilgileri alır. |
| [Setdibscaling](#Setdibscaling) | Cihaz bağımsız bitmap'lerin (DIB'ler) ölçeklendirmesini belirtir. |
| [Epsprinting](#Epsprinting) | Kapsüllenmiş PostScript (EPS) bölümünün başlangıç ve bitişini gösterir. |
| [Enumpapermetrics](#Enumpapermetrics) | Bir yazıcı sürücüsünden kağıt boyutları ve diğer form verilerini sorgular. |
| [Getsetpapermetrics](#Getsetpapermetrics) | Bir çıktı cihazındaki kağıt boyutlarını ve diğer form verilerini alır veya belirtir. |
| [PostscriptData](#PostscriptData) | İsteğe bağlı PostScript verilerini bir çıktı cihazına gönderir. |
| [PostscriptIgnore](#PostscriptIgnore) | Bir çıktı cihazına PostScript verilerini yok saymasını bildirir. |
| [Getdeviceunits](#Getdeviceunits) | Bir çıktı cihazında şu anda yapılandırılmış cihaz birimlerini alır. |
| [Getextendedtextmetrics](#Getextendedtextmetrics) | Bir çıktı cihazında şu anda yapılandırılmış genişletilmiş metin ölçümlerini alır. |
| [Getpairkerntable](#Getpairkerntable) | Bir çıktı cihazında şu anda tanımlı yazı tipi çekirdek tablosunu alır. |
| [Exttextout](#Exttextout) | Şu anda seçili yazı tipini, arka plan rengini ve metin rengini kullanarak metin çizer. |
| [Getfacename](#Getfacename) | Bir cihazda şu anda yapılandırılmış yazı tipi yüz adını alır. |
| [Downloadface](#Downloadface) | Bir cihazda yazı tipi yüz adını ayarlar. |
| [MetafileDriver](#MetafileDriver) | Bir çıktı cihazında metafile desteği hakkında bir yazıcı sürücüsünü sorgular. |
| [Querydibsupport](#Querydibsupport) | Bir çıktı cihazında DIB desteği hakkında yazıcı sürücüsünü sorgular. |
| [BeginPath](#BeginPath) | Bir yolu açar. |
| [ClipToPath](#ClipToPath) | Bir yol tarafından sınırlanan bir kırpma bölgesi tanımlar. |
| [EndPath](#EndPath) | Bir yolu sonlandırır. |
| [OpenChannel](#OpenChannel) | NULL belge ve çıktı dosya adıyla belirtilen STARTDOC ile aynı, veri ham modda ve tür sıfır. |
| [Downloadheader](#Downloadheader) | Yazıcı sürücüsüne PostScript prosedür setlerini indirmesi talimatını verir. |
| [CloseChannel](#CloseChannel) | ENDDOC ile aynı. |
| [PostscriptPassthrough](#PostscriptPassthrough) | Keyfi veriyi doğrudan bir yazıcı sürücüsüne gönderir; bu sürücünün veriyi yalnızca PostScript modunda işlemesi beklenir. |
| [EncapsulatedPostscript](#EncapsulatedPostscript) | Keyfi veriyi doğrudan yazıcı sürücüsüne gönderir. |
| [PostscriptIdentify](#PostscriptIdentify) | Yazıcı sürücüsünü PostScript ya da GDI moduna ayarlar. |
| [PostscriptInjection](#PostscriptInjection) | Ham veriden bir bloğu PostScript akışına ekler. |
| [Checkjpegformat](#Checkjpegformat) | Yazıcının JPEG görüntüsünü destekleyip desteklemediğini kontrol eder. |
| [Checkpngformat](#Checkpngformat) | Yazıcının PNG görüntüsünü destekleyip desteklemediğini kontrol eder. |
| [GetPsFeaturesetting](#GetPsFeaturesetting) | PostScript yazıcı sürücüsü için belirtilen özellik ayarı hakkında bilgi alır. |
| [MxdcEscape](#MxdcEscape) | Uygulamaların belgeleri bir dosyaya ya da bir yazıcıya XML Paper Specification (XPS) formatında yazmasını sağlar. |
| [Spclpassthrough2](#Spclpassthrough2) | Uygulamaların belgelere özel prosedürler ve diğer keyfi verileri eklemesini sağlar. |
### Newframe {#Newframe}
```
public static final int Newframe
```


Uygulamanın bir sayfaya yazmayı tamamladığını yazıcı sürücüsüne bildirir.

### Abortdoc {#Abortdoc}
```
public static final int Abortdoc
```


Mevcut belgenin işlenmesini durdurur.

### Nextband {#Nextband}
```
public static final int Nextband
```


Uygulamanın bir banda yazmayı tamamladığını yazıcı sürücüsüne bildirir.

### Setcolortable {#Setcolortable}
```
public static final int Setcolortable
```


Renk tablosu değerlerini ayarlar.

### Getcolortable {#Getcolortable}
```
public static final int Getcolortable
```


Renk tablosu değerlerini alır.

### Flushout {#Flushout}
```
public static final int Flushout
```


Bekleyen tüm çıktının çıkış cihazına boşaltılmasını sağlar.

### Draftmode {#Draftmode}
```
public static final int Draftmode
```


Yazıcı sürücüsünün yalnızca metin yazdırması gerektiğini ve grafik yazdırmamasını gösterir.

### Queryescsupport {#Queryescsupport}
```
public static final int Queryescsupport
```


Bir yazıcı sürücüsüne, sürücünün yönettiği çıkış cihazında belirli bir kaçış işlevinin desteklenip desteklenmediğini belirlemek için sorgu gönderir.

### Setabortproc {#Setabortproc}
```
public static final int Setabortproc
```


Yazdırma sırasında bir baskı işinin iptal edilmesini sağlayan, uygulama tarafından tanımlanan işlevi ayarlar.

### Startdoc {#Startdoc}
```
public static final int Startdoc
```


Yeni bir baskı işinin başladığını yazıcı sürücüsüne bildirir.

### Enddoc {#Enddoc}
```
public static final int Enddoc
```


Mevcut baskı işinin sona erdiğini yazıcı sürücüsüne bildirir.

### Getphyspagesize {#Getphyspagesize}
```
public static final int Getphyspagesize
```


Çıkış cihazında şu anda seçili olan fiziksel sayfa boyutunu alır.

### Getprintingoffset {#Getprintingoffset}
```
public static final int Getprintingoffset
```


Gerçek baskı veya çizimin başladığı fiziksel sayfanın sol üst köşesinden ofseti alır.

### Getscalingfactor {#Getscalingfactor}
```
public static final int Getscalingfactor
```


Yazıcının x ekseni ve y ekseni için ölçekleme faktörlerini alır.

### MetaEscapeEnhancedMetafile {#MetaEscapeEnhancedMetafile}
```
public static final int MetaEscapeEnhancedMetafile
```


Bir WMF metafilesi içinde geliştirilmiş metafile formatı (EMF) metafilesi gömmek için kullanılır.

### Setpenwidth {#Setpenwidth}
```
public static final int Setpenwidth
```


Kalemin piksel cinsinden genişliğini ayarlar.

### Setcopycount {#Setcopycount}
```
public static final int Setcopycount
```


Kopya sayısını ayarlar.

### Setpapersource {#Setpapersource}
```
public static final int Setpapersource
```


Çıktı formları için, bir yazıcıdaki belirli bir kağıt tepsisi veya kutu gibi kaynağı ayarlar.

### Passthrough {#Passthrough}
```
public static final int Passthrough
```


Bu kayıt rastgele verileri geçirir.

### Gettechnology {#Gettechnology}
```
public static final int Gettechnology
```


Bir cihazda desteklenen grafik teknolojisiyle ilgili bilgileri alır.

### Setlinecap {#Setlinecap}
```
public static final int Setlinecap
```


Bir cihaza çıktıda kullanılacak çizgi çizme modunu belirtir.

### Setlinejoin {#Setlinejoin}
```
public static final int Setlinejoin
```


Bir cihaza çıktıda kullanılacak çizgi birleştirme modunu belirtir.

### Setmiterlimit {#Setmiterlimit}
```
public static final int Setmiterlimit
```


Bir cihaza çıktıda kullanılacak köşe birleşimlerinin uzunluk sınırını ayarlar.

### Bandinfo {#Bandinfo}
```
public static final int Bandinfo
```


Bir cihazdaki bantlama ile ilgili ayarları, örneğin bant sayısını, alır veya belirtir.

### Drawpatternrect {#Drawpatternrect}
```
public static final int Drawpatternrect
```


Tanımlı bir desenle bir dikdörtgen çizer.

### Getvectorpensize {#Getvectorpensize}
```
public static final int Getvectorpensize
```


Bir cihazda şu anda tanımlı fiziksel kalem boyutunu alır.

### Getvectorbrushsize {#Getvectorbrushsize}
```
public static final int Getvectorbrushsize
```


Bir cihazda şu anda tanımlı fiziksel fırça boyutunu alır.

### Enableduplex {#Enableduplex}
```
public static final int Enableduplex
```


Bir cihazda çift taraflı (duplex) baskıyı etkinleştirir veya devre dışı bırakır.

### Getsetpaperbins {#Getsetpaperbins}
```
public static final int Getsetpaperbins
```


Bir cihazdaki çıktı formlarının kaynağını alır veya belirtir.

### Getsetprintorient {#Getsetprintorient}
```
public static final int Getsetprintorient
```


Bir cihazdaki kağıt yönlendirmesini alır veya belirtir.

### Enumpaperbins {#Enumpaperbins}
```
public static final int Enumpaperbins
```


Bir çıktı cihazındaki farklı formların kaynaklarıyla ilgili bilgileri alır.

### Setdibscaling {#Setdibscaling}
```
public static final int Setdibscaling
```


Cihaz bağımsız bitmap'lerin (DIB'ler) ölçeklendirmesini belirtir.

### Epsprinting {#Epsprinting}
```
public static final int Epsprinting
```


Kapsüllenmiş PostScript (EPS) bölümünün başlangıç ve bitişini gösterir.

### Enumpapermetrics {#Enumpapermetrics}
```
public static final int Enumpapermetrics
```


Bir yazıcı sürücüsünden kağıt boyutları ve diğer form verilerini sorgular.

### Getsetpapermetrics {#Getsetpapermetrics}
```
public static final int Getsetpapermetrics
```


Bir çıktı cihazındaki kağıt boyutlarını ve diğer form verilerini alır veya belirtir.

### PostscriptData {#PostscriptData}
```
public static final int PostscriptData
```


İsteğe bağlı PostScript verilerini bir çıktı cihazına gönderir.

### PostscriptIgnore {#PostscriptIgnore}
```
public static final int PostscriptIgnore
```


Bir çıktı cihazına PostScript verilerini yok saymasını bildirir.

### Getdeviceunits {#Getdeviceunits}
```
public static final int Getdeviceunits
```


Bir çıktı cihazında şu anda yapılandırılmış cihaz birimlerini alır.

### Getextendedtextmetrics {#Getextendedtextmetrics}
```
public static final int Getextendedtextmetrics
```


Bir çıktı cihazında şu anda yapılandırılmış genişletilmiş metin ölçümlerini alır.

### Getpairkerntable {#Getpairkerntable}
```
public static final int Getpairkerntable
```


Bir çıktı cihazında şu anda tanımlı yazı tipi çekirdek tablosunu alır.

### Exttextout {#Exttextout}
```
public static final int Exttextout
```


Şu anda seçili yazı tipini, arka plan rengini ve metin rengini kullanarak metin çizer.

### Getfacename {#Getfacename}
```
public static final int Getfacename
```


Bir cihazda şu anda yapılandırılmış yazı tipi yüz adını alır.

### Downloadface {#Downloadface}
```
public static final int Downloadface
```


Bir cihazda yazı tipi yüz adını ayarlar.

### MetafileDriver {#MetafileDriver}
```
public static final int MetafileDriver
```


Bir çıktı cihazında metafile desteği hakkında bir yazıcı sürücüsünü sorgular.

### Querydibsupport {#Querydibsupport}
```
public static final int Querydibsupport
```


Bir çıktı cihazında DIB desteği hakkında yazıcı sürücüsünü sorgular.

### BeginPath {#BeginPath}
```
public static final int BeginPath
```


Bir yolu açar.

### ClipToPath {#ClipToPath}
```
public static final int ClipToPath
```


Bir yol tarafından sınırlanan bir kırpma bölgesi tanımlar. Giriş, yapılacak eylemi tanımlayan 16 bitlik bir miktar OLMAK ZORUNDADIR.

### EndPath {#EndPath}
```
public static final int EndPath
```


Bir yolu sonlandırır.

### OpenChannel {#OpenChannel}
```
public static final int OpenChannel
```


NULL belge ve çıktı dosya adıyla belirtilen STARTDOC ile aynı, veri ham modda ve tür sıfır.

### Downloadheader {#Downloadheader}
```
public static final int Downloadheader
```


Yazıcı sürücüsüne PostScript prosedür setlerini indirmesi talimatını verir.

### CloseChannel {#CloseChannel}
```
public static final int CloseChannel
```


ENDDOC ile aynı. OPEN\_CHANNEL bakınız.

### PostscriptPassthrough {#PostscriptPassthrough}
```
public static final int PostscriptPassthrough
```


Keyfi veriyi doğrudan bir yazıcı sürücüsüne gönderir; bu sürücünün veriyi yalnızca PostScript modunda işlemesi beklenir. [PostscriptIdentify](../../com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes\#PostscriptIdentify).

### EncapsulatedPostscript {#EncapsulatedPostscript}
```
public static final int EncapsulatedPostscript
```


Keyfi veriyi doğrudan yazıcı sürücüsüne gönderir.

### PostscriptIdentify {#PostscriptIdentify}
```
public static final int PostscriptIdentify
```


Yazıcı sürücüsünü PostScript ya da GDI moduna ayarlar.

### PostscriptInjection {#PostscriptInjection}
```
public static final int PostscriptInjection
```


Ham veriden bir bloğu PostScript akışına ekler. Giriş, enjekte edilecek bayt sayısını belirten 32 bitlik bir miktar, enjeksiyon noktasını belirten 16 bitlik bir miktar ve sayfa numarasını belirten 16 bitlik bir miktar OLMAK ZORUNDADIR; ardından enjekte edilecek baytlar gelir.

### Checkjpegformat {#Checkjpegformat}
```
public static final int Checkjpegformat
```


Yazıcının JPEG görüntüsünü destekleyip desteklemediğini kontrol eder.

### Checkpngformat {#Checkpngformat}
```
public static final int Checkpngformat
```


Yazıcının PNG görüntüsünü destekleyip desteklemediğini kontrol eder.

### GetPsFeaturesetting {#GetPsFeaturesetting}
```
public static final int GetPsFeaturesetting
```


PostScript yazıcı sürücüsü için belirtilen özellik ayarı hakkında bilgi alır.

### MxdcEscape {#MxdcEscape}
```
public static final int MxdcEscape
```


Uygulamaların belgeleri bir dosyaya ya da bir yazıcıya XML Paper Specification (XPS) formatında yazmasını sağlar.

### Spclpassthrough2 {#Spclpassthrough2}
```
public static final int Spclpassthrough2
```


Uygulamaların belgelere özel prosedürler ve diğer keyfi verileri eklemesini sağlar.

