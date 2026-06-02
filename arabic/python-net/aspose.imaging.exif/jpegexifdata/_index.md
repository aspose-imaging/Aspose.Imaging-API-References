---
title: "فئة JpegExifData"
type: docs
weight: 40
url: /ar/python-net/aspose.imaging.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.JpegExifData

**Inheritance:** IImageMetadataFormat, ExifData

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | يُهيئ مثيلاً جديداً من الفئة [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/). |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | يُهيئ مثيلاً جديداً من الفئة [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) باستخدام بيانات من المصفوفة. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | يُهيئ مثيلاً جديداً من الفئة [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) باستخدام بيانات من المصفوفة. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_4) | يُهيئ مثيلاً جديداً من الفئة [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) باستخدام بيانات من المصفوفة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | الحد الأقصى لحجم مقطع EXIF بالبايت المسموح به. |
| aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن قيمة الفتحة. |
| artist | string | r/w | يحصل أو يضبط الفنان. |
| bits_per_sample | int[] | r/w | يحصل أو يضبط عدد البتات لكل عينة. |
| body_serial_number | string | r/w | يحصل أو يعيّن رقم تسلسل جسم الكاميرا. |
| brightness_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | يحصل أو يعيّن قيمة السطوع. |
| camera_owner_name | string | r/w | يحصل أو يعيّن اسم مالك الكاميرا |
| cfa_pattern | System.Byte | r/w | يحصل أو يعيّن نمط CFA. |
| color_space | [ExifColorSpace](/imaging/python-net/aspose.imaging.exif.enums/exifcolorspace/) | r/w | يحصل أو يعيّن مساحة اللون. |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | يحصل أو يعيّن العلامات التي تنتمي إلى القسم المشترك. ينطبق هذا فقط على صور JPEG، وفي تنسيق TIFF يتم استخدام tiffOptions بدلاً من ذلك. |
| components_configuration | System.Byte | r/w | يحصل أو يعيّن تكوين المكونات. |
| compressed_bits_per_pixel | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن عدد البتات المضغوطة لكل بكسل. |
| ضغط | int | r/w | يحصل أو يضبط الضغط. |
| contrast | [ExifContrast](/imaging/python-net/aspose.imaging.exif.enums/exifcontrast/) | r/w | يحصل أو يعيّن التباين. |
| حقوق النشر | string | r/w | يحصل أو يضبط حقوق النشر. |
| custom_rendered | [ExifCustomRendered](/imaging/python-net/aspose.imaging.exif.enums/exifcustomrendered/) | r/w | يحصل أو يعيّن العرض المخصص. |
| date_time | string | r/w | يحصل أو يضبط التاريخ والوقت. |
| date_time_digitized | string | r/w | يحصل أو يعيّن تاريخ ووقت الرقمنة. |
| date_time_original | string | r/w | يحصل أو يعيّن تاريخ ووقت الأصل. |
| device_setting_description | System.Byte | r/w | يحصل أو يعيّن وصف إعدادات الجهاز |
| digital_zoom_ratio | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن نسبة التكبير الرقمي. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | الحصول أو تعيين العلامات التي تنتمي إلى قسم EXIF فقط. |
| exif_version | System.Byte | r/w | الحصول أو تعيين نسخة EXIF. |
| exposure_bias_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | الحصول أو تعيين قيمة انحياز التعرض. |
| exposure_index | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين مؤشر التعرض. |
| exposure_mode | [ExifExposureMode](/imaging/python-net/aspose.imaging.exif.enums/exifexposuremode/) | r/w | الحصول أو تعيين وضع التعرض. |
| exposure_program | [ExifExposureProgram](/imaging/python-net/aspose.imaging.exif.enums/exifexposureprogram/) | r/w | الحصول أو تعيين برنامج التعرض. |
| exposure_time | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين زمن التعرض. |
| f_number | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين رقم F. |
| file_source | [ExifFileSource](/imaging/python-net/aspose.imaging.exif.enums/exiffilesource/) | r/w | الحصول أو تعيين نوع مصدر الملف. |
| flash | [ExifFlash](/imaging/python-net/aspose.imaging.exif.enums/exifflash/) | r/w | الحصول أو تعيين الفلاش. |
| flash_energy | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين طاقة الفلاش. |
| flashpix_version | System.Byte | r/w | الحصول أو تعيين نسخة flash pix. |
| focal_length | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين البعد البؤري. |
| focal_length_in_35_mm_film | int | r/w | الحصول أو تعيين البعد البؤري في فيلم 35 مم. |
| focal_plane_resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | الحصول أو تعيين وحدة دقة المستوى البؤري. |
| focal_plane_x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين دقة المستوى البؤري X. |
| focal_plane_y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين دقة المستوى البؤري Y. |
| gain_control | [ExifGainControl](/imaging/python-net/aspose.imaging.exif.enums/exifgaincontrol/) | r/w | الحصول أو تعيين درجة تعديل الكسب الكلي للصورة. |
| gamma | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين قيمة جاما. |
| gps_altitude | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | الحصول أو تعيين ارتفاع GPS. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/imaging/python-net/aspose.imaging.exif.enums/exifgpsaltituderef/) | r/w | الحصول أو تعيين ارتفاع GPS المستخدم كارتفاع مرجعي. |
| gps_area_information | System.Byte | r/w | يحصل أو يعيّن معلومات منطقة GPS. |
| gps_date_stamp | string | r/w | يحصل أو يعيّن سلسلة الأحرف الخاصة بـ GPS التي تسجل معلومات التاريخ والوقت بالنسبة إلى UTC (التوقيت العالمي المنسق). |
| gps_dest_bearing | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن اتجاه GPS إلى نقطة الوجهة. |
| gps_dest_bearing_ref | string | r/w | يحصل أو يعيّن المرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة. |
| gps_dest_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن مسافة GPS إلى نقطة الوجهة. |
| gps_dest_distance_ref | string | r/w | يحصل أو يعيّن وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. |
| gps_dest_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن خط عرض GPS لنقطة الوجهة. |
| gps_dest_latitude_ref | string | r/w | يحصل أو يعيّن قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا. |
| gps_dest_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن خط طول GPS لنقطة الوجهة. |
| gps_dest_longitude_ref | string | r/w | يحصل أو يعيّن قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا. |
| gps_differential | int | r/w | يحصل أو يعيّن قيمة GPS التي تشير إلى ما إذا كان تصحيح الفرق مطبقًا على مستقبل GPS. |
| gps_img_direction | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن اتجاه GPS للصورة عند التقاطها. |
| gps_img_direction_ref | string | r/w | يحصل أو يعيّن المرجع GPS لتحديد اتجاه الصورة عند التقاطها. |
| gps_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن خط عرض GPS. |
| gps_latitude_ref | string | r/w | يحصل أو يعيّن ما إذا كان خط عرض GPS شماليًا أم جنوبيًا. |
| gps_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن خط طول GPS. |
| gps_longitude_ref | string | r/w | يحصل أو يضبط ما إذا كان خط طول GPS شرقًا أم غربًا. |
| gps_map_datum | string | r/w | يحصل أو يضبط بيانات المسح الجيوديسي لـ GPS المستخدمة بواسطة مستقبل GPS. |
| gps_measure_mode | string | r/w | يحصل أو يضبط وضع قياس GPS. |
| gps_processing_method | System.Byte | r/w | يحصل أو يضبط سلسلة الأحرف الخاصة بـ GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع. |
| gps_satellites | string | r/w | يحصل أو يضبط أقمار GPS المستخدمة للقياسات. |
| gps_speed | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط سرعة حركة مستقبل GPS. |
| gps_speed_ref | string | r/w | يحصل أو يضبط الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS. |
| gps_status | string | r/w | يحصل أو يضبط حالة مستقبل GPS عند تسجيل الصورة. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | يحصل أو يضبط العلامات التي تنتمي إلى قسم GPS فقط. |
| gps_timestamp | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط وقت GPS كـ UTC (التوقيت العالمي المنسق). |
| gps_track | string | r/w | يحصل أو يضبط اتجاه حركة مستقبل GPS. |
| gps_track_ref | string | r/w | يحصل أو يضبط المرجع لتحديد اتجاه حركة مستقبل GPS. |
| gps_version_id | System.Byte | r/w | يحصل أو يضبط معرف نسخة GPS. |
| gpsdop | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط قيمة DOP لـ GPS (درجة دقة البيانات). |
| image_description | string | r/w | يحصل أو يضبط وصف الصورة. |
| image_length | int | r/w | يحصل أو يضبط طول الصورة. |
| image_unique_id | string | r/w | يحصل أو يضبط المعرف الفريد للصورة. |
| image_width | int | r/w | يحصل أو يضبط عرض الصورة. |
| is_big_endian | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تدفق بيانات EXIF المُنشأ من big endian. |
| iso_speed | int | r/w | يحصل أو يعيّن سرعة ISO |
| iso_speed_latitude_yyy | int | r/w | يحصل أو يعيّن قيمة إحداثيات سرعة ISO yyy لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| iso_speed_latitude_zzz | int | r/w | يحصل أو يعيّن قيمة إحداثيات سرعة ISO zzz لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| iso_speed_value | int | r/w | يحصل أو يعيّن قيمة سرعة iso. |
| lens_make | string | r/w | يحصل أو يعيّن صانع العدسة. |
| lens_model | string | r/w | يحصل أو يعيّن نموذج العدسة. |
| lens_serial_number | string | r/w | يحصل أو يعيّن الرقم التسلسلي للعدسة. |
| lens_specification | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن مواصفات العدسة |
| light_source | [ExifLightSource](/imaging/python-net/aspose.imaging.exif.enums/exiflightsource/) | r/w | يحصل أو يعيّن مصدر الضوء. |
| make | string | r/w | يحصل أو يعيّن الشركة المصنعة لمعدات التسجيل. |
| maker_note_data | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r | يحصل على بيانات ملاحظة الصانع. |
| maker_note_raw_data | System.Byte | r/w | يحصل أو يعيّن البيانات الخام لملاحظة الصانع. |
| maker_notes | [MakerNote[]](/imaging/python-net/aspose.imaging.exif/makernote/) | r | يحصل على ملاحظات الصانع. |
| max_aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن قيمة الفتحة القصوى. |
| metering_mode | [ExifMeteringMode](/imaging/python-net/aspose.imaging.exif.enums/exifmeteringmode/) | r/w | الحصول أو تعيين وضع القياس. |
| model | string | r/w | يحصل أو يضبط النموذج. |
| oecf | System.Byte | r/w | الحصول أو تعيين وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524. |
| orientation | [ExifOrientation](/imaging/python-net/aspose.imaging.exif.enums/exiforientation/) | r/w | الحصول أو تعيين الاتجاه. |
| photographic_sensitivity | int | r/w | الحصول أو تعيين الحساسية الفوتوغرافية. |
| photometric_interpretation | int | r/w | يحصل أو يضبط التفسير الضوئي. |
| pixel_x_dimension | int | r/w | الحصول أو تعيين بُعد البكسل x. |
| pixel_y_dimension | int | r/w | الحصول أو تعيين بُعد البكسل y. |
| planar_configuration | int | r/w | يحصل أو يضبط تكوين المستوى. |
| primary_chromaticities | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط تشبع الألوان للثلاث ألوان الأساسية في الصورة. |
| properties | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | الحصول أو تعيين جميع علامات EXIF (بما في ذلك العلامات الشائعة وعلامات GPS). |
| recommended_exposure_index | int | r/w | الحصول أو تعيين مؤشر التعرض الموصى به. |
| reference_black_white | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط المرجعية للون الأسود والأبيض. |
| related_sound_file | string | r/w | الحصول أو تعيين ملف الصوت المرتبط. |
| resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | يحصل أو يضبط وحدة الدقة. |
| samples_per_pixel | int | r/w | يحصل أو يضبط العينات لكل بكسل. |
| saturation | [ExifSaturation](/imaging/python-net/aspose.imaging.exif.enums/exifsaturation/) | r/w | الحصول أو تعيين التشبع. |
| scene_capture_type | [ExifSceneCaptureType](/imaging/python-net/aspose.imaging.exif.enums/exifscenecapturetype/) | r/w | الحصول أو تعيين نوع التقاط المشهد. |
| scene_type | System.Byte | r/w | الحصول أو تعيين نوع المشهد. |
| sensing_method | [ExifSensingMethod](/imaging/python-net/aspose.imaging.exif.enums/exifsensingmethod/) | r/w | الحصول أو تعيين طريقة الاستشعار. |
| sensitivity_type | int | r/w | الحصول أو تعيين نوع الحساسية. |
| sharpness | int | r/w | الحصول أو تعيين الحدة. |
| shutter_speed_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | الحصول أو تعيين قيمة سرعة الغالق. |
| البرمجيات | string | r/w | يحصل أو يعيّن البرنامج. |
| استجابة_التردد_المكاني | System.Byte | r/w | يحصل أو يضبط استجابة التردد المكاني. |
| حساسية_طيفية | string | r/w | يحصل أو يضبط الحساسية الطيفية. |
| حساسية_الإخراج_القياسي | int | r/w | يحصل أو يضبط حساسية الإخراج القياسي |
| منطقة_الموضوع | int[] | r/w | يحصل أو يضبط منطقة الموضوع. |
| subject_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط مسافة الموضوع. |
| subject_distance_range | [ExifSubjectDistanceRange](/imaging/python-net/aspose.imaging.exif.enums/exifsubjectdistancerange/) | r/w | يحصل أو يضبط نطاق مسافة الموضوع. |
| موقع_الموضوع | int[] | r/w | يحصل أو يضبط موقع الموضوع. |
| وقت_الجزء_الثانوي | string | r/w | يحصل أو يضبط أجزاء الثواني للوسم DateTime. |
| وقت_الجزء_الثانوي_المرقم | string | r/w | يحصل أو يضبط أجزاء الثواني للوسم DateTimeDigitized. |
| وقت_الجزء_الثانوي_الأصلي | string | r/w | يحصل أو يضبط أجزاء الثواني للوسم DateTimeOriginal. |
| thumbnail | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r/w | يحصل أو يضبط صورة المصغرة. |
| transfer_function | int[] | r/w | يحصل أو يعيّن دالة النقل. |
| تعليق_المستخدم | string | r/w | يحصل أو يضبط تعليق المستخدم. |
| white_balance | [ExifWhiteBalance](/imaging/python-net/aspose.imaging.exif.enums/exifwhitebalance/) | r/w | يحصل أو يضبط توازن اللون الأبيض. |
| white_point | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط اللونية لنقطة اللون الأبيض في الصورة. |
| x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط دقة x. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يعيّن معاملات المصفوفة للتحويل من بيانات الصورة RGB إلى YCbCr. |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/imaging/python-net/aspose.imaging.exif.enums/exifycbcrpositioning/) | r/w | يحصل أو يعيّن موضع مكونات التشبع اللوني بالنسبة إلى مكون الإضاءة. |
| y_cb_cr_sub_sampling | int[] | r/w | يحصل أو يعيّن نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة إلى مكون الإضاءة. |
| y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط دقة y. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_tag_value(key)](#get_tag_value_key_1) | يحصل على قيمة العلامة. |
| [load_from_bytes(binary_data)](#load_from_bytes_binary_data_2) | ينشئ مثيلاً جديداً من الفئة [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) عن طريق تحميله من مصفوفة البايت. |
| [remove_tag(tag)](#remove_tag_tag_3) | إزالة العلامة من الحاوية |
| [remove_tag(tag_id)](#remove_tag_tag_id_4) | إزالة العلامة من الحاوية |
| [remove_tag_id(tag_id)](#remove_tag_id_tag_id_5) | إزالة العلامة من الحاوية |
| [serialize_exif_data()](#serialize_exif_data__6) | يسلسل بيانات EXIF. يكتب قيم العلامات ومحتوياتها. أكثر علامة حجم تأثيرًا هي محتويات علامة الصورة المصغرة. |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

يُهيئ مثيلاً جديداً من الفئة [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/).

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

يُهيئ مثيلاً جديداً من الفئة [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) باستخدام بيانات من المصفوفة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | العلامات الشائعة. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | علامات EXIF. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | علامات GPS. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

يُهيئ مثيلاً جديداً من الفئة [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) باستخدام بيانات من المصفوفة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | مصفوفة من علامات EXIF مع العلامات الشائعة وعلامات GPS. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_4}


```
 JpegExifData(exifdata) 
```

يُهيئ مثيلاً جديداً من الفئة [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) باستخدام بيانات من المصفوفة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| exifdata | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | مصفوفة من علامات EXIF مع العلامات الشائعة وعلامات GPS. |

### Method: get_tag_value(key) {#get_tag_value_key_1}


```
 get_tag_value(key) 
```

يحصل على قيمة العلامة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | مفتاح العلامة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | نوع TiffDataType |


### Method: load_from_bytes(binary_data)  [static] {#load_from_bytes_binary_data_2}


```
 load_from_bytes(binary_data) 
```

ينشئ مثيلاً جديداً من الفئة [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) عن طريق تحميله من مصفوفة البايت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| binary_data | System.Byte | البيانات الثنائية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | مثيل ExifData المحمّل. |


### Method: remove_tag(tag) {#remove_tag_tag_3}


```
 remove_tag(tag) 
```

إزالة العلامة من الحاوية

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tag | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | العلامة المراد إزالتها |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_4}


```
 remove_tag(tag_id) 
```

إزالة العلامة من الحاوية

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tag_id | int | معرف العلامة المراد إزالته. |

### Method: remove_tag_id(tag_id) {#remove_tag_id_tag_id_5}


```
 remove_tag_id(tag_id) 
```

إزالة العلامة من الحاوية

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tag_id | int | معرف العلامة المراد إزالته. |

### Method: serialize_exif_data() {#serialize_exif_data__6}


```
 serialize_exif_data() 
```

يسلسل بيانات EXIF. يكتب قيم العلامات ومحتوياتها. أكثر علامة حجم تأثيرًا هي محتويات علامة الصورة المصغرة.

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Byte | بيانات EXIF المتسلسلة. |


