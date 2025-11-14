---
title: ExifProperties
second_title: Aspose.Imaging for Java API Reference
description: Exif tags list
type: docs
weight: 11
url: /java/com.aspose.imaging.exif/exifproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Exif tags list
## Fields

| Field | Description |
| --- | --- |
| [ImageWidth](#ImageWidth) | The number of columns of image data, equal to the number of pixels per row. |
| [ImageLength](#ImageLength) | The number of rows of image data. |
| [BitsPerSample](#BitsPerSample) | The number of bits per image component. |
| [Compression](#Compression) | The compression scheme used for the image data. |
| [PhotometricInterpretation](#PhotometricInterpretation) | The pixel composition. |
| [ImageDescription](#ImageDescription) | A character string giving the title of the image. |
| [Make](#Make) | The manufacturer of the recording equipment. |
| [Model](#Model) | The model name or model number of the equipment. |
| [Orientation](#Orientation) | The image orientation viewed in terms of rows and columns. |
| [SamplesPerPixel](#SamplesPerPixel) | The number of components per pixel. |
| [XResolution](#XResolution) | The number of pixels per ResolutionUnit in the ImageWidth direction. |
| [YResolution](#YResolution) | The number of pixels per ResolutionUnit in the ImageLength direction. |
| [PlanarConfiguration](#PlanarConfiguration) | Indicates whether pixel components are recorded in a chunky or planar format. |
| [ResolutionUnit](#ResolutionUnit) | The unit for measuring XResolution and YResolution. |
| [TransferFunction](#TransferFunction) | A transfer function for the image, described in tabular style. |
| [Software](#Software) | This tag records the name and version of the software or firmware of the camera or image input device used to generate the image. |
| [DateTime](#DateTime) | The date and time of image creation. |
| [Artist](#Artist) | This tag records the name of the camera owner, photographer or image creator. |
| [WhitePoint](#WhitePoint) | The chromaticity of the white point of the image. |
| [PrimaryChromaticities](#PrimaryChromaticities) | The chromaticity of the three primary colors of the image. |
| [YCbCrCoefficients](#YCbCrCoefficients) | The matrix coefficients for transformation from RGB to YCbCr image data. |
| [YCbCrSubSampling](#YCbCrSubSampling) | The sampling ratio of chrominance components in relation to the luminance component. |
| [YCbCrPositioning](#YCbCrPositioning) | The position of chrominance components in relation to the luminance component. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | The reference black point value and reference white point value. |
| [Copyright](#Copyright) | Copyright information. |
| [ExposureTime](#ExposureTime) | Exposure time, given in seconds. |
| [FNumber](#FNumber) | The F number. |
| [ExposureProgram](#ExposureProgram) | The class of the program used by the camera to set exposure when the picture is taken. |
| [SpectralSensitivity](#SpectralSensitivity) | Indicates the spectral sensitivity of each channel of the camera used. |
| [PhotographicSensitivity](#PhotographicSensitivity) | Indicates the ISO Speed and ISO Latitude of the camera or input device as specified in ISO 12232. |
| [OECF](#OECF) | Indicates the Opto-Electric Conversion Function (OECF) specified in ISO 14524. |
| [ExifVersion](#ExifVersion) | The exif version. |
| [DateTimeOriginal](#DateTimeOriginal) | The date and time when the original image data was generated. |
| [DateTimeDigitized](#DateTimeDigitized) | The date time digitized. |
| [ComponentsConfiguration](#ComponentsConfiguration) | The components' configuration. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Specific to compressed data; states the compressed bits per pixel. |
| [ShutterSpeedValue](#ShutterSpeedValue) | The shutter speed value. |
| [ApertureValue](#ApertureValue) | The lens aperture value. |
| [BrightnessValue](#BrightnessValue) | The brightness value. |
| [ExposureBiasValue](#ExposureBiasValue) | The exposure bias value. |
| [MaxApertureValue](#MaxApertureValue) | The max aperture value. |
| [SubjectDistance](#SubjectDistance) | The distance to the subject, given in meters. |
| [MeteringMode](#MeteringMode) | The metering mode. |
| [LightSource](#LightSource) | The kind light source. |
| [Flash](#Flash) | Indicates the status of flash when the image was shot. |
| [FocalLength](#FocalLength) | The actual focal length of the lens, in mm. |
| [SubjectArea](#SubjectArea) | This tag indicates the location and area of the main subject in the overall scene. |
| [MakerNote](#MakerNote) | A tag for manufacturers of Exif writers to record any desired information. |
| [UserComment](#UserComment) | A tag for Exif users to write keywords or comments on the image besides those in ImageDescription, and without the character code limitations of the ImageDescription tag. |
| [SubsecTime](#SubsecTime) | A tag used to record fractions of seconds for the DateTime tag. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | A tag used to record fractions of seconds for the DateTimeOriginal tag. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | A tag used to record fractions of seconds for the DateTimeDigitized tag. |
| [FlashpixVersion](#FlashpixVersion) | The Flashpix format version supported by a FPXR file. |
| [ColorSpace](#ColorSpace) | The color space information tag (ColorSpace) is always recorded as the color space specifier. |
| [RelatedSoundFile](#RelatedSoundFile) | The related sound file. |
| [FlashEnergy](#FlashEnergy) | Indicates the strobe energy at the time the image is captured, as measured in Beam Candle Power Seconds(BCPS). |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | This tag records the camera or input device spatial frequency table and SFR values in the direction of image width, image height, and diagonal direction, as specified in ISO 12233. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Indicates the number of pixels in the image width (X) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Indicates the number of pixels in the image height (Y) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | Indicates the unit for measuring FocalPlaneXResolution and FocalPlaneYResolution. |
| [SubjectLocation](#SubjectLocation) | Indicates the location of the main subject in the scene. |
| [ExposureIndex](#ExposureIndex) | Indicates the exposure index selected on the camera or input device at the time the image is captured. |
| [SensingMethod](#SensingMethod) | Indicates the image sensor type on the camera or input device. |
| [FileSource](#FileSource) | The file source. |
| [SceneType](#SceneType) | Indicates the type of scene. |
| [CFAPattern](#CFAPattern) | Indicates the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. |
| [CustomRendered](#CustomRendered) | This tag indicates the use of special processing on image data, such as rendering geared to output. |
| [ExposureMode](#ExposureMode) | This tag indicates the exposure mode set when the image was shot. |
| [WhiteBalance](#WhiteBalance) | This tag indicates the white balance mode set when the image was shot. |
| [DigitalZoomRatio](#DigitalZoomRatio) | This tag indicates the digital zoom ratio when the image was shot. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | This tag indicates the equivalent focal length assuming a 35mm film camera, in mm. |
| [SceneCaptureType](#SceneCaptureType) | This tag indicates the type of scene that was shot. |
| [GainControl](#GainControl) | This tag indicates the degree of overall image gain adjustment. |
| [Contrast](#Contrast) | This tag indicates the direction of contrast processing applied by the camera when the image was shot. |
| [Saturation](#Saturation) | This tag indicates the direction of saturation processing applied by the camera when the image was shot. |
| [Sharpness](#Sharpness) | This tag indicates the direction of sharpness processing applied by the camera when the image was shot |
| [DeviceSettingDescription](#DeviceSettingDescription) | This tag indicates information on the picture-taking conditions of a particular camera model. |
| [SubjectDistanceRange](#SubjectDistanceRange) | This tag indicates the distance to the subject. |
| [ImageUniqueID](#ImageUniqueID) | The image unique id. |
| [GPSVersionID](#GPSVersionID) | Indicates the version of GPSInfoIFD. |
| [GPSLatitudeRef](#GPSLatitudeRef) | Indicates whether the latitude is north or south latitude. |
| [GPSLatitude](#GPSLatitude) | Indicates the latitude. |
| [GPSLongitudeRef](#GPSLongitudeRef) | Indicates whether the longitude is east or west longitude. |
| [GPSLongitude](#GPSLongitude) | Indicates the longitude. |
| [GPSAltitudeRef](#GPSAltitudeRef) | Indicates the altitude used as the reference altitude. |
| [GPSAltitude](#GPSAltitude) | Indicates the altitude based on the reference in GPSAltitudeRef. |
| [GPSTimestamp](#GPSTimestamp) | Indicates the time as UTC (Coordinated Universal Time). |
| [GPSSatellites](#GPSSatellites) | Indicates the GPS satellites used for measurements. |
| [GPSStatus](#GPSStatus) | Indicates the status of the GPS receiver when the image is recorded. |
| [GPSMeasureMode](#GPSMeasureMode) | Indicates the GPS measurement mode. |
| [GPSDOP](#GPSDOP) | Indicates the GPS DOP (data degree of precision). |
| [GPSSpeedRef](#GPSSpeedRef) | Indicates the unit used to express the GPS receiver speed of movement. |
| [GPSSpeed](#GPSSpeed) | Indicates the speed of GPS receiver movement. |
| [GPSTrackRef](#GPSTrackRef) | Indicates the reference for giving the direction of GPS receiver movement. |
| [GPSTrack](#GPSTrack) | Indicates the direction of GPS receiver movement. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | Indicates the reference for giving the direction of the image when it is captured. |
| [GPSImgDirection](#GPSImgDirection) | Indicates the direction of the image when it was captured. |
| [GPSMapDatum](#GPSMapDatum) | Indicates the geodetic survey data used by the GPS receiver. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | Indicates whether the latitude of the destination point is north or south latitude. |
| [GPSDestLatitude](#GPSDestLatitude) | Indicates the latitude of the destination point. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | Indicates whether the longitude of the destination point is east or west longitude. |
| [GPSDestLongitude](#GPSDestLongitude) | Indicates the longitude of the destination point. |
| [GPSDestBearingRef](#GPSDestBearingRef) | Indicates the reference used for giving the bearing to the destination point. |
| [GPSDestBearing](#GPSDestBearing) | Indicates the bearing to the destination point. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | Indicates the unit used to express the distance to the destination point. |
| [GPSDestDistance](#GPSDestDistance) | Indicates the distance to the destination point. |
| [GPSProcessingMethod](#GPSProcessingMethod) | A character string recording the name of the method used for location finding. |
| [GPSAreaInformation](#GPSAreaInformation) | A character string recording the name of the GPS area. |
| [GPSDateStamp](#GPSDateStamp) | A character string recording date and time information relative to UTC (Coordinated Universal Time). |
| [GPSDifferential](#GPSDifferential) | Indicates whether differential correction is applied to the GPS receiver. |
| [StripOffsets](#StripOffsets) | For each strip, the byte offset of that strip. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | The offset to the start byte (SOI) of JPEG compressed thumbnail data. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | The number of bytes of JPEG compressed thumbnail data. |
| [ExifIfdPointer](#ExifIfdPointer) | A pointer to the Exif IFD. |
| [GPSIfdPointer](#GPSIfdPointer) | The gps ifd pointer. |
| [RowsPerStrip](#RowsPerStrip) | The number of rows per strip. |
| [StripByteCounts](#StripByteCounts) | The total number of bytes in each strip. |
| [PixelXDimension](#PixelXDimension) | Information specific to compressed data. |
| [PixelYDimension](#PixelYDimension) | Information specific to compressed data. |
| [Gamma](#Gamma) | Gamma value |
| [SensitivityType](#SensitivityType) | Type of photographic sensitivity |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | Indicates standard output sensitivity of camera |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | Indicates recommended exposure index |
| [ISOSpeed](#ISOSpeed) | Information about iso speed value as defined in ISO 12232 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | This tag indicates ISO speed latitude yyy value as defined in ISO 12232 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | This tag indicates ISO speed latitude zzz value as defined in ISO 12232 |
| [CameraOwnerName](#CameraOwnerName) | Contains camera owner name |
| [BodySerialNumber](#BodySerialNumber) | Contains camera body serial number |
| [LensMake](#LensMake) | This tag records lens manufacturer |
| [LensModel](#LensModel) | This tag records lens\`s model name and model number |
| [LensSerialNumber](#LensSerialNumber) | This tag records the serial number of interchangeable lens |
| [LensSpecification](#LensSpecification) | This tag notes minimum focal length, maximum focal length, minimum F number in the minimum focal length and minimum F number in maximum focal length |
### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


The number of columns of image data, equal to the number of pixels per row.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


The number of rows of image data.

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


The number of bits per image component. In this standard each component of the image is 8 bits, so the value for this tag is 8.

### Compression {#Compression}
```
public static final int Compression
```


The compression scheme used for the image data. When a primary image is JPEG compressed, this designation is not necessary and is omitted.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


The pixel composition.

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


A character string giving the title of the image. It may be a comment such as "1988 company picnic" or the like.

### Make {#Make}
```
public static final int Make
```


The manufacturer of the recording equipment. This is the manufacturer of the DSC, scanner, video digitizer or other equipment that generated the image. When the field is left blank, it is treated as unknown.

### Model {#Model}
```
public static final int Model
```


The model name or model number of the equipment. This is the model name or number of the DSC, scanner, video digitizer or other equipment that generated the image. When the field is left blank, it is treated as unknown.

### Orientation {#Orientation}
```
public static final int Orientation
```


The image orientation viewed in terms of rows and columns.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


The number of components per pixel. Since this standard applies to RGB and YCbCr images, the value set for this tag is 3.

### XResolution {#XResolution}
```
public static final int XResolution
```


The number of pixels per ResolutionUnit in the ImageWidth direction. When the image resolution is unknown, 72 [dpi] is designated.

### YResolution {#YResolution}
```
public static final int YResolution
```


The number of pixels per ResolutionUnit in the ImageLength direction. The same value as XResolution is designated.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Indicates whether pixel components are recorded in a chunky or planar format. If this field does not exist, the TIFF default of 1 (chunky) is assumed.

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


The unit for measuring XResolution and YResolution. The same unit is used for both XResolution and YResolution. If the image resolution is unknown, 2 (inches) is designated.

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


A transfer function for the image, described in tabular style. Normally this tag is not necessary, since color space is specified in the color space information ColorSpace tag.

### Software {#Software}
```
public static final int Software
```


This tag records the name and version of the software or firmware of the camera or image input device used to generate the image. The detailed format is not specified, but it is recommended that the example shown below be followed. When the field is left blank, it is treated as unknown.

### DateTime {#DateTime}
```
public static final int DateTime
```


The date and time of image creation. In Exif standard, it is the date and time the file was changed.

### Artist {#Artist}
```
public static final int Artist
```


This tag records the name of the camera owner, photographer or image creator. The detailed format is not specified, but it is recommended that the information be written as in the example below for ease of Interoperability. When the field is left blank, it is treated as unknown. (Ex. "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James")

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


The chromaticity of the white point of the image. Normally this tag is not necessary, since color space is specified in the colorspace information ColorSpace tag.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


The chromaticity of the three primary colors of the image. Normally this tag is not necessary, since colorspace is specified in the colorspace information ColorSpace tag.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


The matrix coefficients for transformation from RGB to YCbCr image data.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


The sampling ratio of chrominance components in relation to the luminance component.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


The position of chrominance components in relation to the luminance component. This field is designated only for JPEG compressed data or uncompressed YCbCr data. The TIFF default is 1 (centered); but when Y:Cb:Cr = 4:2:2 it is recommended in this standard that 2 (co-sited) be used to record data, in order to improve the image quality when viewed on TV systems. When this field does not exist, the reader shall assume the TIFF default. In the case of Y:Cb:Cr = 4:2:0, the TIFF default (centered) is recommended. If the reader does not have the capability of supporting both kinds of YCbCrPositioning, it shall follow the TIFF default regardless of the value in this field. It is preferable that readers " be able to support both centered and co-sited positioning.

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


The reference black point value and reference white point value. No defaults are given in TIFF, but the values below are given as defaults here. The color space is declared in a color space information tag, with the default being the value that gives the optimal image characteristics Interoperability these conditions

### Copyright {#Copyright}
```
public static final int Copyright
```


Copyright information. In this standard the tag is used to indicate both the photographer and editor copyrights. It is the copyright notice of the person or organization claiming rights to the image. The Interoperability copyright statement including date and rights should be written in this field; e.g., "Copyright, John Smith, 19xx. All rights reserved." In this standard the field records both the photographer and editor copyrights, with each recorded in a separate part of the statement. When there is a clear distinction between the photographer and editor copyrights, these are to be written in the order of photographer followed by editor copyright, separated by NULL (in this case since the statement also ends with a NULL, there are two NULL codes). When only the photographer copyright is given, it is terminated by one NULL code . When only the editor copyright is given, the photographer copyright part consists of one space followed by a terminating NULL code, then the editor copyright is given. When the field is left blank, it is treated as unknown.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


Exposure time, given in seconds.

### FNumber {#FNumber}
```
public static final int FNumber
```


The F number.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


The class of the program used by the camera to set exposure when the picture is taken.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


Indicates the spectral sensitivity of each channel of the camera used.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


Indicates the ISO Speed and ISO Latitude of the camera or input device as specified in ISO 12232.

### OECF {#OECF}
```
public static final int OECF
```


Indicates the Opto-Electric Conversion Function (OECF) specified in ISO 14524.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


The exif version.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


The date and time when the original image data was generated.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


The date time digitized.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


The components' configuration.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


Specific to compressed data; states the compressed bits per pixel.

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


The shutter speed value.

### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


The lens aperture value.

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


The brightness value.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


The exposure bias value.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


The max aperture value.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


The distance to the subject, given in meters.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


The metering mode.

### LightSource {#LightSource}
```
public static final int LightSource
```


The kind light source.

### Flash {#Flash}
```
public static final int Flash
```


Indicates the status of flash when the image was shot.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


The actual focal length of the lens, in mm.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


This tag indicates the location and area of the main subject in the overall scene.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


A tag for manufacturers of Exif writers to record any desired information. The contents are up to the manufacturer, but this tag should not be used for any other than its intended purpose.

### UserComment {#UserComment}
```
public static final int UserComment
```


A tag for Exif users to write keywords or comments on the image besides those in ImageDescription, and without the character code limitations of the ImageDescription tag.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


A tag used to record fractions of seconds for the DateTime tag.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


A tag used to record fractions of seconds for the DateTimeOriginal tag.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


A tag used to record fractions of seconds for the DateTimeDigitized tag.

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


The Flashpix format version supported by a FPXR file.

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


The color space information tag (ColorSpace) is always recorded as the color space specifier.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


The related sound file.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


Indicates the strobe energy at the time the image is captured, as measured in Beam Candle Power Seconds(BCPS).

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


This tag records the camera or input device spatial frequency table and SFR values in the direction of image width, image height, and diagonal direction, as specified in ISO 12233.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


Indicates the number of pixels in the image width (X) direction per FocalPlaneResolutionUnit on the camera focal plane.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


Indicates the number of pixels in the image height (Y) direction per FocalPlaneResolutionUnit on the camera focal plane.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Indicates the unit for measuring FocalPlaneXResolution and FocalPlaneYResolution. This value is the same as the ResolutionUnit.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Indicates the location of the main subject in the scene. The value of this tag represents the pixel at the center of the main subject relative to the left edge, prior to rotation processing as per the Rotation tag.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


Indicates the exposure index selected on the camera or input device at the time the image is captured.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


Indicates the image sensor type on the camera or input device.

### FileSource {#FileSource}
```
public static final int FileSource
```


The file source.

### SceneType {#SceneType}
```
public static final int SceneType
```


Indicates the type of scene. If a DSC recorded the image, this tag value shall always be set to 1, indicating that the image was directly photographed.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Indicates the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. It does not apply to all sensing methods.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


This tag indicates the use of special processing on image data, such as rendering geared to output. When special processing is performed, the reader is expected to disable or minimize any further processing.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


This tag indicates the exposure mode set when the image was shot. In auto-bracketing mode, the camera shoots a series of frames of the same scene at different exposure settings.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


This tag indicates the white balance mode set when the image was shot.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


This tag indicates the digital zoom ratio when the image was shot. If the numerator of the recorded value is 0, this indicates that digital zoom was not used.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


This tag indicates the equivalent focal length assuming a 35mm film camera, in mm. A value of 0 means the focal length is unknown. Note that this tag differs from the FocalLength tag.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


This tag indicates the type of scene that was shot. It can also be used to record the mode in which the image was shot.

### GainControl {#GainControl}
```
public static final int GainControl
```


This tag indicates the degree of overall image gain adjustment.

### Contrast {#Contrast}
```
public static final int Contrast
```


This tag indicates the direction of contrast processing applied by the camera when the image was shot.

### Saturation {#Saturation}
```
public static final int Saturation
```


This tag indicates the direction of saturation processing applied by the camera when the image was shot.

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


This tag indicates the direction of sharpness processing applied by the camera when the image was shot

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


This tag indicates information on the picture-taking conditions of a particular camera model. The tag is used only to indicate the picture-taking conditions in the reader.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


This tag indicates the distance to the subject.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


The image unique id.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


Indicates the version of GPSInfoIFD.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


Indicates whether the latitude is north or south latitude.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Indicates the latitude. The latitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If latitude is expressed as degrees, minutes and seconds, a typical format would be dd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be dd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


Indicates whether the longitude is east or west longitude.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


Indicates the longitude. The longitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If longitude is expressed as degrees, minutes and seconds, a typical format would be ddd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be ddd/1,mmmm/100,0/1.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


Indicates the altitude used as the reference altitude. If the reference is sea level and the altitude is above sea level, 0 is given. If the altitude is below sea level, a value of 1 is given and the altitude is indicated as an absolute value in the GPSAltitude tag.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


Indicates the altitude based on the reference in GPSAltitudeRef. Altitude is expressed as one RATIONAL value. The reference unit is meters.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


Indicates the time as UTC (Coordinated Universal Time). TimeStamp is expressed as three RATIONAL values giving the hour, minute, and second.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


Indicates the GPS satellites used for measurements. This tag can be used to describe the number of satellites, their ID number, angle of elevation, azimuth, SNR and other information in ASCII notation. The format is not specified. If the GPS receiver is incapable of taking measurements, value of the tag shall be set to NULL.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


Indicates the status of the GPS receiver when the image is recorded.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


Indicates the GPS measurement mode. - 2- or 3-dimensional.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


Indicates the GPS DOP (data degree of precision). An HDOP value is written during two-dimensional measurement, and PDOP during three-dimensional measurement.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


Indicates the unit used to express the GPS receiver speed of movement. 'K' 'M' and 'N' represents kilometers per hour, miles per hour, and knots.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


Indicates the speed of GPS receiver movement.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


Indicates the reference for giving the direction of GPS receiver movement. 'T' denotes true direction and 'M' is magnetic direction.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


Indicates the direction of GPS receiver movement. The range of values is from 0.00 to 359.99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


Indicates the reference for giving the direction of the image when it is captured. 'T' denotes true direction and 'M' is magnetic direction.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


Indicates the direction of the image when it was captured. The range of values is from 0.00 to 359.99.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


Indicates the geodetic survey data used by the GPS receiver.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


Indicates whether the latitude of the destination point is north or south latitude. The ASCII value 'N' indicates north latitude, and 'S' is south latitude.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


Indicates the latitude of the destination point. The latitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If latitude is expressed as degrees, minutes and seconds, a typical format would be dd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be dd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


Indicates whether the longitude of the destination point is east or west longitude. ASCII 'E' indicates east longitude, and 'W' is west longitude.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


Indicates the longitude of the destination point. The longitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If longitude is expressed as degrees, minutes and seconds, a typical format would be ddd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be ddd/1,mmmm/100,0/1.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


Indicates the reference used for giving the bearing to the destination point. 'T' denotes true direction and 'M' is magnetic direction.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


Indicates the bearing to the destination point. The range of values is from 0.00 to 359.99.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


Indicates the unit used to express the distance to the destination point. 'K', 'M' and 'N' represent kilometers, miles and knots.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


Indicates the distance to the destination point.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


A character string recording the name of the method used for location finding. The first byte indicates the character code used, and this is followed by the name of the method.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


A character string recording the name of the GPS area. The first byte indicates the character code used, and this is followed by the name of the GPS area.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


A character string recording date and time information relative to UTC (Coordinated Universal Time). The format is YYYY:MM:DD.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


Indicates whether differential correction is applied to the GPS receiver.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


For each strip, the byte offset of that strip. It is recommended that this be selected so the number of strip bytes does not exceed 64 Kbytes. Aux tag.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


The offset to the start byte (SOI) of JPEG compressed thumbnail data. This is not used for primary image JPEG data.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


The number of bytes of JPEG compressed thumbnail data. This is not used for primary image JPEG data. JPEG thumbnails are not divided but are recorded as a continuous JPEG bitstream from SOI to EOI. Appn and COM markers should not be recorded. Compressed thumbnails must be recorded in no more than 64 Kbytes, including all other data to be recorded in APP1.

### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


A pointer to the Exif IFD. Interoperability, Exif IFD has the same structure as that of the IFD specified in TIFF. ordinarily, however, it does not contain image data as in the case of TIFF.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


The gps ifd pointer.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


The number of rows per strip. This is the number of rows in the image of one strip when an image is divided into strips.

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


The total number of bytes in each strip.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


Information specific to compressed data. When a compressed file is recorded, the valid width of the meaningful image shall be recorded in this tag, whether there is padding data or a restart marker.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


Information specific to compressed data. When a compressed file is recorded, the valid height of the meaningful image shall be recorded in this tag

### Gamma {#Gamma}
```
public static final int Gamma
```


Gamma value

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


Type of photographic sensitivity

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


Indicates standard output sensitivity of camera

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


Indicates recommended exposure index

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


Information about iso speed value as defined in ISO 12232

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


This tag indicates ISO speed latitude yyy value as defined in ISO 12232

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


This tag indicates ISO speed latitude zzz value as defined in ISO 12232

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


Contains camera owner name

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


Contains camera body serial number

### LensMake {#LensMake}
```
public static final int LensMake
```


This tag records lens manufacturer

### LensModel {#LensModel}
```
public static final int LensModel
```


This tag records lens\`s model name and model number

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


This tag records the serial number of interchangeable lens

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


This tag notes minimum focal length, maximum focal length, minimum F number in the minimum focal length and minimum F number in maximum focal length

