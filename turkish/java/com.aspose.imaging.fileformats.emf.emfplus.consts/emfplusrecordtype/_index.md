---
title: "EmfPlusRecordType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "RecordType sayımı, EMF meta dosyalarında kullanılan kayıt türlerini tanımlar."
type: docs
weight: 45
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRecordType extends System.Enum
```

RecordType sayımı, EMF+ meta dosyalarında kullanılan kayıt türlerini tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EmfPlusHeader](#EmfPlusHeader) | Bu kayıt, meta dosyada EMF+ verisinin başlangıcını belirtir. |
| [EmfPlusEndOfFile](#EmfPlusEndOfFile) | Bu kayıt, meta dosyada EMF+ verisinin sonunu belirtir. |
| [EmfPlusComment](#EmfPlusComment) | Bu kayıt, keyfi özel verileri belirtir. |
| [EmfPlusGetDC](#EmfPlusGetDC) | Bu kayıt, meta dosyada karşılaşılan sonraki EMF kayıtlarının İŞLENMESİ gerektiğini belirtir. |
| [EmfPlusMultiFormatStart](#EmfPlusMultiFormatStart) | Bu kayıt ayrılmıştır ve KULLANILMAMASI GEREKİR. |
| [EmfPlusMultiFormatSection](#EmfPlusMultiFormatSection) | Bu kayıt ayrılmıştır ve KULLANILMAMASI GEREKİR. |
| [EmfPlusMultiFormatEnd](#EmfPlusMultiFormatEnd) | Bu kayıt ayrılmıştır ve KULLANILMAMASI GEREKİR. |
| [EmfPlusObject](#EmfPlusObject) | Bu kayıt, grafik işlemlerinde kullanılmak üzere bir nesneyi belirtir. |
| [EmfPlusClear](#EmfPlusClear) | Bu kayıt, çıktı `coordinate space`'i temizler ve belirtilen bir arka plan rengi ve şeffaflıkla başlatır. |
| [EmfPlusFillRects](#EmfPlusFillRects) | Bu kayıt, belirtilen bir fırça kullanarak bir dizi dikdörtgenin içini nasıl dolduracağını tanımlar. |
| [EmfPlusDrawRects](#EmfPlusDrawRects) | Bu kayıt, bir dizi dikdörtgen çizerken kalem darbelerini tanımlar. |
| [EmfPlusFillPolygon](#EmfPlusFillPolygon) | Bu kayıt, belirtilen bir fırça kullanarak bir çokgenin içini doldurmak için verileri tanımlar. |
| [EmfPlusDrawLines](#EmfPlusDrawLines) | Bu kayıt, bir dizi bağlı çizgi çizerken kalem darbelerini tanımlar. |
| [EmfPlusFillEllipse](#EmfPlusFillEllipse) | Bu kayıt, belirtilen bir fırça kullanarak bir elipsin içini nasıl dolduracağını tanımlar. |
| [EmfPlusDrawEllipse](#EmfPlusDrawEllipse) | Bu kayıt, bir elips çizerken kalem darbelerini tanımlar. |
| [EmfPlusFillPie](#EmfPlusFillPie) | Bu kayıt, belirtilen bir fırça kullanarak bir elipsin iç bölümünün bir kesitini nasıl dolduracağını tanımlar. |
| [EmfPlusDrawPie](#EmfPlusDrawPie) | Bu kayıt, bir elipsin bir kesitini çizmeye yönelik kalem darbelerini tanımlar. |
| [EmfPlusDrawArc](#EmfPlusDrawArc) | Kayıt, bir elipsin bir yayını çizmeye yönelik kalem darbelerini tanımlar. |
| [EmfPlusFillRegion](#EmfPlusFillRegion) | Bu kayıt, belirtilen bir fırça kullanarak bir bölgenin içini nasıl dolduracağını tanımlar. |
| [EmfPlusFillPath](#EmfPlusFillPath) | Kayıt, bir grafik yolunda tanımlanan şekillerin içlerini belirtilen bir fırça ile nasıl dolduracağını tanımlar. |
| [EmfPlusDrawPath](#EmfPlusDrawPath) | Kayıt, bir grafik yolundaki şekilleri çizmek için kalem darbelerini tanımlar. |
| [EmfPlusFillClosedCurve](#EmfPlusFillClosedCurve) | Bu kayıt, belirtilen bir fırça kullanarak kapalı bir kardinal spline'ın içini nasıl dolduracağını tanımlar. |
| [EmfPlusDrawClosedCurve](#EmfPlusDrawClosedCurve) | Bu kayıt, kapalı bir kardinal spline'ı çizmeye yönelik kalemi ve darbeleri tanımlar. |
| [EmfPlusDrawCurve](#EmfPlusDrawCurve) | Bu kayıt, bir kardinal spline'ı çizmeye yönelik kalem darbelerini tanımlar. |
| [EmfPlusDrawBeziers](#EmfPlusDrawBeziers) | Bu kayıt, bir Bezier spline'ı çizmeye yönelik kalem darbelerini tanımlar. |
| [EmfPlusDrawImage](#EmfPlusDrawImage) | Bu kayıt, ölçeklendirilmiş bir [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) nesnesini (bölüm 2.2.1.4) tanımlar. |
| [EmfPlusDrawImagePoints](#EmfPlusDrawImagePoints) | Bu kayıt, bir paralelkenar içinde ölçeklendirilmiş bir EmfPlusImage nesnesini tanımlar. |
| [EmfPlusDrawString](#EmfPlusDrawString) | Bu kayıt, bir yazı tipi, bir yerleşim dikdörtgeni ve bir biçime dayalı bir metin dizesini tanımlar. |
| [EmfPlusSetRenderingOrigin](#EmfPlusSetRenderingOrigin) | Bu kayıt, oluşturmanın başlangıç noktasını belirtilen yatay ve dikey koordinatlara tanımlar. |
| [EmfPlusSetAntiAliasMode](#EmfPlusSetAntiAliasMode) | Bu kayıt, metin anti-aliasing'inin etkinleştirilip devre dışı bırakılacağını tanımlar. |
| [EmfPlusSetTextRenderingHint](#EmfPlusSetTextRenderingHint) | Bu kayıt, metin oluşturmak için kullanılan süreci tanımlar. |
| [EmfPlusSetTextContrast](#EmfPlusSetTextContrast) | Bu kayıt, belirtilen metin gama değerine göre metin kontrastını ayarlar. |
| [EmfPlusSetInterpolationMode](#EmfPlusSetInterpolationMode) | Bu kayıt, bir nesnenin ara değerleme modunu belirtilen görüntü filtreleme türüne göre tanımlar. |
| [EmfPlusSetPixelOffsetMode](#EmfPlusSetPixelOffsetMode) | Bu kayıt, piksel merkezleme değerine göre piksel offset modunu tanımlar. |
| [EmfPlusSetCompositingMode](#EmfPlusSetCompositingMode) | Bu kayıt, kaynak renklerin arka plan renkleriyle nasıl birleştirileceğini belirten alfa karıştırma durumuna göre birleştirme modunu tanımlar. |
| [EmfPlusSetCompositingQuality](#EmfPlusSetCompositingQuality) | Bu kayıt, birden fazla nesneden birleşik görüntüler oluşturmak için istenen kalite seviyesini tanımlayan birleştirme kalitesini tanımlar. |
| [EmfPlusSave](#EmfPlusSave) | Bu kayıt, belirtilen bir dizinle tanımlanan grafik durumunu kaydedilmiş grafik durumları yığınına kaydeder. |
| [EmfPlusRestore](#EmfPlusRestore) | Bu kayıt, belirtilen bir dizinle tanımlanan grafik durumunu kaydedilmiş grafik durumları yığından geri yükler. |
| [EmfPlusBeginContainer](#EmfPlusBeginContainer) | Bu kayıt, yeni bir grafik durum kapsayıcısı açar ve onun için bir dönüşüm belirtir. |
| [EmfPlusBeginContainerNoParams](#EmfPlusBeginContainerNoParams) | Bu kayıt, yeni bir grafik durum kapsayıcısı açar. |
| [EmfPlusEndContainer](#EmfPlusEndContainer) | Bu kayıt, daha önce bir başlat konteyner işlemiyle açılmış bir grafik durumu konteynerini kapatır. |
| [EmfPlusSetWorldTransform](#EmfPlusSetWorldTransform) | Bu kayıt, belirtilen dönüşüm matrisine göre playback device\_context içindeki mevcut dünya uzayı dönüşümünü tanımlar. |
| [EmfPlusResetWorldTransform](#EmfPlusResetWorldTransform) | Bu kayıt, mevcut dünya uzayı dönüşümünü kimlik matrisine sıfırlar. |
| [EmfPlusMultiplyWorldTransform](#EmfPlusMultiplyWorldTransform) | Bu kayıt, mevcut dünya uzayını belirtilen bir dönüşüm matrisiyle çarpar. |
| [EmfPlusTranslateWorldTransform](#EmfPlusTranslateWorldTransform) | Bu kayıt, belirtilen yatay ve dikey mesafelere göre mevcut dünya uzayına bir çeviri dönüşümü uygular. |
| [EmfPlusScaleWorldTransform](#EmfPlusScaleWorldTransform) | Bu kayıt, belirtilen yatay ve dikey ölçek faktörlerine göre mevcut dünya uzayına bir ölçekleme dönüşümü uygular. |
| [EmfPlusRotateWorldTransform](#EmfPlusRotateWorldTransform) | Bu kayıt, mevcut dünya uzayını belirtilen bir açıyla döndürür. |
| [EmfPlusSetPageTransform](#EmfPlusSetPageTransform) | Bu kayıt, mevcut dünya uzayı dönüşümü için ek ölçek faktörlerini belirtir. |
| [EmfPlusResetClip](#EmfPlusResetClip) | Bu kayıt, dünya uzayı için mevcut kırpma bölgesini sonsuza sıfırlar. |
| [EmfPlusSetClipRect](#EmfPlusSetClipRect) | Bu kayıt, mevcut kırpma bölgesini bir dikdörtgenle birleştirir. |
| [EmfPlusSetClipPath](#EmfPlusSetClipPath) | Bu kayıt, mevcut kırpma bölgesini bir grafik yoluyla birleştirir. |
| [EmfPlusSetClipRegion](#EmfPlusSetClipRegion) | Bu kayıt, mevcut kırpma bölgesini başka bir grafik bölgesiyle birleştirir. |
| [EmfPlusOffsetClip](#EmfPlusOffsetClip) | Bu kayıt, dünya uzayının mevcut kırpma bölgesine bir çeviri dönüşümü uygular. |
| [EmfPlusDrawDriverString](#EmfPlusDrawDriverString) | Bu kayıt, karakter konumlarıyla metin çıktısını belirtir. |
| [EmfPlusStrokeFillPath](#EmfPlusStrokeFillPath) | Bu kayıt, bir yoldaki açık tüm şekilleri kapatır, yolun dış hattını geçerli kalemle çizer ve içini geçerli fırça ile doldurur. |
| [EmfPlusSerializableObject](#EmfPlusSerializableObject) | Bu kayıt, bir veri tamponuna serileştirilmiş bir görüntü efektleri parametre bloğunu tanımlar. |
| [EmfPlusSetTSGraphics](#EmfPlusSetTSGraphics) | Bu kayıt, bir terminal sunucusu için grafik cihaz bağlamının durumunu belirtir. |
| [EmfPlusSetTSClip](#EmfPlusSetTSClip) | Bu kayıt, bir terminal sunucusu için grafik cihaz bağlamındaki kırpma alanlarını belirtir. |
### EmfPlusHeader {#EmfPlusHeader}
```
public static final short EmfPlusHeader
```


Bu kayıt, metafilde EMF+ verisinin başlangıcını belirtir. Bu, [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) kaydından sonraki ilk EMF kaydına GİRDİRİLMELİDİR ([MS-EMF] bölüm 2.3.4.2 kaydı).

### EmfPlusEndOfFile {#EmfPlusEndOfFile}
```
public static final short EmfPlusEndOfFile
```


Bu kayıt, meta dosyada EMF+ verisinin sonunu belirtir.

### EmfPlusComment {#EmfPlusComment}
```
public static final short EmfPlusComment
```


Bu kayıt, keyfi özel verileri belirtir.

### EmfPlusGetDC {#EmfPlusGetDC}
```
public static final short EmfPlusGetDC
```


Bu kayıt, metafilde karşılaşılan sonraki EMF kayıtlarının İŞLENMESİ GEREKİLDİĞİNİ belirtir. Bir sonraki EMF+ kaydıyla karşılaşıldığında EMF kayıtlarının işlenmesi durur.

### EmfPlusMultiFormatStart {#EmfPlusMultiFormatStart}
```
public static final short EmfPlusMultiFormatStart
```


Bu kayıt ayrılmıştır ve KULLANILMAMASI GEREKİR.

### EmfPlusMultiFormatSection {#EmfPlusMultiFormatSection}
```
public static final short EmfPlusMultiFormatSection
```


Bu kayıt ayrılmıştır ve KULLANILMAMASI GEREKİR.

### EmfPlusMultiFormatEnd {#EmfPlusMultiFormatEnd}
```
public static final short EmfPlusMultiFormatEnd
```


Bu kayıt ayrılmıştır ve KULLANILMAMASI GEREKİR.

### EmfPlusObject {#EmfPlusObject}
```
public static final short EmfPlusObject
```


Bu kayıt, grafik işlemlerinde kullanılmak üzere bir nesneyi belirtir.

### EmfPlusClear {#EmfPlusClear}
```
public static final short EmfPlusClear
```


Bu kayıt, çıktı `coordinate space`'i temizler ve belirtilen bir arka plan rengi ve şeffaflıkla başlatır.

### EmfPlusFillRects {#EmfPlusFillRects}
```
public static final short EmfPlusFillRects
```


Bu kayıt, belirtilen bir fırça kullanarak bir dizi dikdörtgenin içini nasıl dolduracağını tanımlar.

### EmfPlusDrawRects {#EmfPlusDrawRects}
```
public static final short EmfPlusDrawRects
```


Bu kayıt, bir dizi dikdörtgen çizerken kalem darbelerini tanımlar.

### EmfPlusFillPolygon {#EmfPlusFillPolygon}
```
public static final short EmfPlusFillPolygon
```


Bu kayıt, belirtilen bir fırça kullanarak bir çokgenin içini doldurmak için verileri tanımlar.

### EmfPlusDrawLines {#EmfPlusDrawLines}
```
public static final short EmfPlusDrawLines
```


Bu kayıt, bir dizi bağlı çizgi çizerken kalem darbelerini tanımlar.

### EmfPlusFillEllipse {#EmfPlusFillEllipse}
```
public static final short EmfPlusFillEllipse
```


Bu kayıt, belirtilen bir fırça kullanarak bir elipsin içini nasıl dolduracağını tanımlar.

### EmfPlusDrawEllipse {#EmfPlusDrawEllipse}
```
public static final short EmfPlusDrawEllipse
```


Bu kayıt, bir elips çizerken kalem darbelerini tanımlar.

### EmfPlusFillPie {#EmfPlusFillPie}
```
public static final short EmfPlusFillPie
```


Bu kayıt, belirtilen bir fırça kullanarak bir elipsin iç bölümünün bir kesitini nasıl dolduracağını tanımlar.

### EmfPlusDrawPie {#EmfPlusDrawPie}
```
public static final short EmfPlusDrawPie
```


Bu kayıt, bir elipsin bir kesitini çizmeye yönelik kalem darbelerini tanımlar.

### EmfPlusDrawArc {#EmfPlusDrawArc}
```
public static final short EmfPlusDrawArc
```


Kayıt, bir elipsin bir yayını çizmeye yönelik kalem darbelerini tanımlar.

### EmfPlusFillRegion {#EmfPlusFillRegion}
```
public static final short EmfPlusFillRegion
```


Bu kayıt, belirtilen bir fırça kullanarak bir bölgenin içini nasıl dolduracağını tanımlar.

### EmfPlusFillPath {#EmfPlusFillPath}
```
public static final short EmfPlusFillPath
```


Kayıt, bir grafik yolunda tanımlanan şekillerin iç kısımlarının belirtilen bir fırça ile nasıl doldurulacağını tanımlar. Bir yol, rastgele bir çizgi, eğri ve şekil dizisini tanımlayan bir nesnedir.

### EmfPlusDrawPath {#EmfPlusDrawPath}
```
public static final short EmfPlusDrawPath
```


Kayıt, bir grafik yolundaki şekilleri çizmeye yönelik kalem darbelerini tanımlar. Bir yol, rastgele bir çizgi, eğri ve şekil dizisini tanımlayan bir nesnedir.

### EmfPlusFillClosedCurve {#EmfPlusFillClosedCurve}
```
public static final short EmfPlusFillClosedCurve
```


Bu kayıt, belirtilen bir fırça kullanarak kapalı bir kardinal spline'ın içini nasıl dolduracağını tanımlar.

### EmfPlusDrawClosedCurve {#EmfPlusDrawClosedCurve}
```
public static final short EmfPlusDrawClosedCurve
```


Bu kayıt, kapalı bir kardinal spline'ı çizmeye yönelik kalemi ve darbeleri tanımlar.

### EmfPlusDrawCurve {#EmfPlusDrawCurve}
```
public static final short EmfPlusDrawCurve
```


Bu kayıt, bir kardinal spline'ı çizmeye yönelik kalem darbelerini tanımlar.

### EmfPlusDrawBeziers {#EmfPlusDrawBeziers}
```
public static final short EmfPlusDrawBeziers
```


Bu kayıt, bir Bezier spline'ı çizmeye yönelik kalem darbelerini tanımlar.

### EmfPlusDrawImage {#EmfPlusDrawImage}
```
public static final short EmfPlusDrawImage
```


Bu kayıt, ölçeklendirilmiş bir [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) nesnesini tanımlar (bölüm 2.2.1.4). Bir görüntü, bitmap ya da metafile verisinden oluşabilir.

### EmfPlusDrawImagePoints {#EmfPlusDrawImagePoints}
```
public static final short EmfPlusDrawImagePoints
```


Bu kayıt, bir paralelkenar içinde ölçeklendirilmiş bir EmfPlusImage nesnesini tanımlar. Bir görüntü, bitmap ya da metafile verisinden oluşabilir.

### EmfPlusDrawString {#EmfPlusDrawString}
```
public static final short EmfPlusDrawString
```


Bu kayıt, bir yazı tipi, bir yerleşim dikdörtgeni ve bir biçime dayalı bir metin dizesini tanımlar.

### EmfPlusSetRenderingOrigin {#EmfPlusSetRenderingOrigin}
```
public static final short EmfPlusSetRenderingOrigin
```


Bu kayıt, renderlamanın başlangıç noktasını belirtilen yatay ve dikey koordinatlara tanımlar. Bu, tarama fırçaları ve piksel başına 8 ve 16 bit dithering desenleri için geçerlidir.

### EmfPlusSetAntiAliasMode {#EmfPlusSetAntiAliasMode}
```
public static final short EmfPlusSetAntiAliasMode
```


Bu kayıt, metin anti-aliasing'in etkinleştirilip etkinleştirilmeyeceğini tanımlar. Metin anti-aliasing, karakter gliflerinin çizgi ve kenarlarının bir çıktı yüzeyine çizildiğinde daha pürüzsüz görünmesini sağlayan bir yöntemdir.

### EmfPlusSetTextRenderingHint {#EmfPlusSetTextRenderingHint}
```
public static final short EmfPlusSetTextRenderingHint
```


Bu kayıt, metin oluşturmak için kullanılan süreci tanımlar.

### EmfPlusSetTextContrast {#EmfPlusSetTextContrast}
```
public static final short EmfPlusSetTextContrast
```


Bu kayıt, belirtilen metin gama değerine göre metin kontrastını ayarlar.

### EmfPlusSetInterpolationMode {#EmfPlusSetInterpolationMode}
```
public static final short EmfPlusSetInterpolationMode
```


Bu kayıt, bir nesnenin ara değerleme modunu belirtilen görüntü filtreleme türüne göre tanımlar. Ara değerleme modu, ölçeklemenin (genişletme ve küçültme) nasıl gerçekleştirileceğini etkiler.

### EmfPlusSetPixelOffsetMode {#EmfPlusSetPixelOffsetMode}
```
public static final short EmfPlusSetPixelOffsetMode
```


Bu kayıt, piksel merkezleme değerine göre piksel offset modunu tanımlar.

### EmfPlusSetCompositingMode {#EmfPlusSetCompositingMode}
```
public static final short EmfPlusSetCompositingMode
```


Bu kayıt, kaynak renklerin arka plan renkleriyle nasıl birleştirileceğini belirten alfa karıştırma durumuna göre birleştirme modunu tanımlar.

### EmfPlusSetCompositingQuality {#EmfPlusSetCompositingQuality}
```
public static final short EmfPlusSetCompositingQuality
```


Bu kayıt, birden fazla nesneden birleşik görüntüler oluşturmak için istenen kalite seviyesini tanımlayan birleştirme kalitesini tanımlar.

### EmfPlusSave {#EmfPlusSave}
```
public static final short EmfPlusSave
```


Bu kayıt, belirtilen bir indeksle tanımlanan grafik durumunu, kaydedilmiş grafik durumları yığınına kaydeder. Her yığın indeksi belirli bir kaydedilmiş durumla ilişkilidir ve indeks, durumu geri yüklemek için bir [EmfPlusRestore](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) kaydı (bölüm 2.3.7.4) tarafından kullanılır.

### EmfPlusRestore {#EmfPlusRestore}
```
public static final short EmfPlusRestore
```


Bu kayıt, belirtilen bir indeksle tanımlanan grafik durumunu, kaydedilmiş grafik durumları yığından geri yükler. Her yığın indeksi belirli bir kaydedilmiş durumla ilişkilidir ve indeks, durumu kaydetmek için bir [EmfPlusSave](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave) kaydı (bölüm 2.3.7.5) tarafından tanımlanır.

### EmfPlusBeginContainer {#EmfPlusBeginContainer}
```
public static final short EmfPlusBeginContainer
```


Bu kayıt, yeni bir grafik durum kapsayıcısı açar ve ona bir dönüşüm tanımlar. Grafik kapsayıcıları, grafik durumunun öğelerini korumak için kullanılır.

### EmfPlusBeginContainerNoParams {#EmfPlusBeginContainerNoParams}
```
public static final short EmfPlusBeginContainerNoParams
```


Bu kayıt, yeni bir grafik durum kapsayıcısı açar.

### EmfPlusEndContainer {#EmfPlusEndContainer}
```
public static final short EmfPlusEndContainer
```


Bu kayıt, daha önce bir başlat konteyner işlemiyle açılmış bir grafik durumu konteynerini kapatır.

### EmfPlusSetWorldTransform {#EmfPlusSetWorldTransform}
```
public static final short EmfPlusSetWorldTransform
```


Bu kayıt, belirtilen dönüşüm matrisine göre playback device\_context içindeki mevcut dünya uzayı dönüşümünü tanımlar.

### EmfPlusResetWorldTransform {#EmfPlusResetWorldTransform}
```
public static final short EmfPlusResetWorldTransform
```


Bu kayıt, mevcut dünya uzayı dönüşümünü kimlik matrisine sıfırlar.

### EmfPlusMultiplyWorldTransform {#EmfPlusMultiplyWorldTransform}
```
public static final short EmfPlusMultiplyWorldTransform
```


Bu kayıt, mevcut dünya uzayını belirtilen bir dönüşüm matrisiyle çarpar.

### EmfPlusTranslateWorldTransform {#EmfPlusTranslateWorldTransform}
```
public static final short EmfPlusTranslateWorldTransform
```


Bu kayıt, belirtilen yatay ve dikey mesafelere göre mevcut dünya uzayına bir çeviri dönüşümü uygular.

### EmfPlusScaleWorldTransform {#EmfPlusScaleWorldTransform}
```
public static final short EmfPlusScaleWorldTransform
```


Bu kayıt, belirtilen yatay ve dikey ölçek faktörlerine göre mevcut dünya uzayına bir ölçekleme dönüşümü uygular.

### EmfPlusRotateWorldTransform {#EmfPlusRotateWorldTransform}
```
public static final short EmfPlusRotateWorldTransform
```


Bu kayıt, mevcut dünya uzayını belirtilen bir açıyla döndürür.

### EmfPlusSetPageTransform {#EmfPlusSetPageTransform}
```
public static final short EmfPlusSetPageTransform
```


Bu kayıt, mevcut dünya uzayı dönüşümü için ek ölçek faktörlerini belirtir.

### EmfPlusResetClip {#EmfPlusResetClip}
```
public static final short EmfPlusResetClip
```


Bu kayıt, dünya uzayı için mevcut kırpma bölgesini sonsuza sıfırlar.

### EmfPlusSetClipRect {#EmfPlusSetClipRect}
```
public static final short EmfPlusSetClipRect
```


Bu kayıt, mevcut kırpma bölgesini bir dikdörtgenle birleştirir.

### EmfPlusSetClipPath {#EmfPlusSetClipPath}
```
public static final short EmfPlusSetClipPath
```


Bu kayıt, mevcut kırpma bölgesini bir grafik yoluyla birleştirir.

### EmfPlusSetClipRegion {#EmfPlusSetClipRegion}
```
public static final short EmfPlusSetClipRegion
```


Bu kayıt, mevcut kırpma bölgesini başka bir grafik bölgesiyle birleştirir.

### EmfPlusOffsetClip {#EmfPlusOffsetClip}
```
public static final short EmfPlusOffsetClip
```


Bu kayıt, dünya uzayının mevcut kırpma bölgesine bir çeviri dönüşümü uygular.

### EmfPlusDrawDriverString {#EmfPlusDrawDriverString}
```
public static final short EmfPlusDrawDriverString
```


Bu kayıt, karakter konumlarıyla metin çıktısını belirtir.

### EmfPlusStrokeFillPath {#EmfPlusStrokeFillPath}
```
public static final short EmfPlusStrokeFillPath
```


Bu kayıt, bir yoldaki açık tüm şekilleri kapatır, yolun dış hattını geçerli kalemle çizer ve içini geçerli fırça ile doldurur.

### EmfPlusSerializableObject {#EmfPlusSerializableObject}
```
public static final short EmfPlusSerializableObject
```


Bu kayıt, bir veri tamponuna serileştirilmiş bir görüntü efektleri parametre bloğunu tanımlar.

### EmfPlusSetTSGraphics {#EmfPlusSetTSGraphics}
```
public static final short EmfPlusSetTSGraphics
```


Bu kayıt, bir terminal sunucusu için grafik cihaz bağlamının durumunu belirtir.

### EmfPlusSetTSClip {#EmfPlusSetTSClip}
```
public static final short EmfPlusSetTSClip
```


Bu kayıt, bir terminal sunucusu için grafik cihaz bağlamındaki kırpma alanlarını belirtir.

