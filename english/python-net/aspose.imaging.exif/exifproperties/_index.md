---
title: ExifProperties Enumeration
type: docs
weight: 190
url: /python-net/aspose.imaging.exif/exifproperties/
---

Exif tags list

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.ExifProperties

## **Members**
| **Member name** | **Description** |
| :- | :- |
| APERTURE_VALUE | The lens aperture value. |
| ARTIST | This tag records the name of the camera owner, photographer or image creator. The detailed format is not specified, but it is recommended that the information be written as in the example below for ease of Interoperability. When the field is left blank, it is treated as unknown. Ex.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | The number of bits per image component. In this standard each component of the image is 8 bits, so the value for this tag is 8. |
| BODY_SERIAL_NUMBER | Contains camera body serial number |
| BRIGHTNESS_VALUE | The brightness value. |
| CAMERA_OWNER_NAME | Contains camera owner name |
| CFA_PATTERN | Indicates the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. It does not apply to all sensing methods. |
| COLOR_SPACE | The color space information tag (ColorSpace) is always recorded as the color space specifier. |
| COMPONENTS_CONFIGURATION | The components configuration. |
| COMPRESSED_BITS_PER_PIXEL | Specific to compressed data; states the compressed bits per pixel. |
| COMPRESSION | The compression scheme used for the image data. When a primary image is JPEG compressed, this designation is not necessary and is omitted. |
| CONTRAST | This tag indicates the direction of contrast processing applied by the camera when the image was shot. |
| COPYRIGHT | Copyright information. In this standard the tag is used to<br/>                indicate both the photographer and editor copyrights. It is<br/>                the copyright notice of the person or organization claiming<br/>                rights to the image. The Interoperability copyright<br/>                statement including date and rights should be written in this<br/>                field; e.g., "Copyright, John Smith, 19xx. All rights<br/>                reserved.". In this standard the field records both the<br/>                photographer and editor copyrights, with each recorded in a<br/>                separate part of the statement. When there is a clear distinction<br/>                between the photographer and editor copyrights, these are to be<br/>                written in the order of photographer followed by editor copyright,<br/>                separated by NULL (in this case since the statement also ends with<br/>                a NULL, there are two NULL codes). When only the photographer<br/>                copyright is given, it is terminated by one NULL code . When only<br/>                the editor copyright is given, the photographer copyright part<br/>                consists of one space followed by a terminating NULL code, then<br/>                the editor copyright is given. When the field is left blank, it is<br/>                treated as unknown. |
| CUSTOM_RENDERED | This tag indicates the use of special processing on image data, such as rendering geared to output. When special processing is performed, the reader is expected to disable or minimize any further processing. |
| DATE_TIME | The date and time of image creation. In Exif standard, it is the date and time the file was changed. |
| DATE_TIME_DIGITIZED | The date time digitized. |
| DATE_TIME_ORIGINAL | The date and time when the original image data was generated. |
| DEVICE_SETTING_DESCRIPTION | This tag indicates information on the picture-taking conditions of a particular camera model. The tag is used only to indicate the picture-taking conditions in the reader. |
| DIGITAL_ZOOM_RATIO | This tag indicates the digital zoom ratio when the image was shot. If the numerator of the recorded value is 0, this indicates that digital zoom was not used. |
| EXIF_IFD_POINTER | A pointer to the Exif IFD. Interoperability, Exif IFD has the same structure as that of the IFD specified in TIFF. ordinarily, however, it does not contain image data as in the case of TIFF. |
| EXIF_VERSION | The exif version. |
| EXPOSURE_BIAS_VALUE | The exposure bias value. |
| EXPOSURE_INDEX | Indicates the exposure index selected on the camera or input device at the time the image is captured. |
| EXPOSURE_MODE | This tag indicates the exposure mode set when the image was shot. In auto-bracketing mode, the camera shoots a series of frames of the same scene at different exposure settings. |
| EXPOSURE_PROGRAM | The class of the program used by the camera to set exposure when the picture is taken. |
| EXPOSURE_TIME | Exposure time, given in seconds. |
| FILE_SOURCE | The file source. |
| FLASH | Indicates the status of flash when the image was shot. |
| FLASHPIX_VERSION | The Flashpix format version supported by a FPXR file. |
| FLASH_ENERGY | Indicates the strobe energy at the time the image is captured, as measured in Beam Candle Power Seconds(BCPS). |
| FOCAL_LENGTH | The actual focal length of the lens, in mm. |
| FOCAL_LENGTH_IN_35_MM_FILM | This tag indicates the equivalent focal length assuming a 35mm film camera, in mm. A value of 0 means the focal length is unknown. Note that this tag differs from the FocalLength tag. |
| FOCAL_PLANE_RESOLUTION_UNIT | Indicates the unit for measuring FocalPlaneXResolution and FocalPlaneYResolution. This value is the same as the ResolutionUnit. |
| FOCAL_PLANE_X_RESOLUTION | Indicates the number of pixels in the image width (X) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| FOCAL_PLANE_Y_RESOLUTION | Indicates the number of pixels in the image height (Y) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| F_NUMBER | The F number. |
| GAIN_CONTROL | This tag indicates the degree of overall image gain adjustment. |
| GAMMA | Gamma value |
| GPSDOP | Indicates the GPS DOP (data degree of precision). An HDOP value is written during two-dimensional measurement,<br/>                and PDOP during three-dimensional measurement. |
| GPS_ALTITUDE | Indicates the altitude based on the reference in GPSAltitudeRef. Altitude is expressed as one RATIONAL value.<br/>                The reference unit is meters. |
| GPS_ALTITUDE_REF | Indicates the altitude used as the reference altitude. If the reference is sea level and the altitude is above sea level,<br/>                0 is given. If the altitude is below sea level, a value of 1 is given and the altitude is indicated as an absolute value in<br/>                the GPSAltitude tag. |
| GPS_AREA_INFORMATION | A character string recording the name of the GPS area. The first byte indicates<br/>                the character code used, and this is followed by the name of the GPS area. |
| GPS_DATE_STAMP | A character string recording date and time information relative to UTC<br/>                (Coordinated Universal Time). The format is YYYY:MM:DD. |
| GPS_DEST_BEARING | Indicates the bearing to the destination point. The range of values is from 0.00 to 359.99. |
| GPS_DEST_BEARING_REF | Indicates the reference used for giving the bearing to the destination point. 'T' denotes true direction and 'M' is<br/>                magnetic direction. |
| GPS_DEST_DISTANCE | Indicates the distance to the destination point. |
| GPS_DEST_DISTANCE_REF | Indicates the unit used to express the distance to the destination point. 'K', 'M' and 'N' represent kilometers, miles<br/>                and knots. |
| GPS_DEST_LATITUDE | Indicates the latitude of the destination point. The latitude is expressed as three RATIONAL values giving the<br/>                degrees, minutes, and seconds, respectively. If latitude is expressed as degrees, minutes and seconds, a typical<br/>                format would be dd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are<br/>                given up to two decimal places, the format would be dd/1,mmmm/100,0/1. |
| GPS_DEST_LATITUDE_REF | Indicates whether the latitude of the destination point is north or south latitude. The ASCII value 'N' indicates north<br/>                latitude, and 'S' is south latitude. |
| GPS_DEST_LONGITUDE | Indicates the longitude of the destination point. The longitude is expressed as three RATIONAL values giving the<br/>                degrees, minutes, and seconds, respectively. If longitude is expressed as degrees, minutes and seconds, a typical<br/>                format would be ddd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are<br/>                given up to two decimal places, the format would be ddd/1,mmmm/100,0/1. |
| GPS_DEST_LONGITUDE_REF | Indicates whether the longitude of the destination point is east or west longitude. ASCII 'E' indicates east longitude,<br/>                and 'W' is west longitude. |
| GPS_DIFFERENTIAL | Indicates whether differential correction is applied to the GPS receiver. |
| GPS_IFD_POINTER | The gps ifd pointer. |
| GPS_IMG_DIRECTION | Indicates the direction of the image when it was captured. The range of values is from 0.00 to 359.99. |
| GPS_IMG_DIRECTION_REF | Indicates the reference for giving the direction of the image when it is captured. 'T' denotes true direction and 'M' is<br/>                magnetic direction. |
| GPS_LATITUDE | Indicates the latitude. The latitude is expressed as three RATIONAL values giving the degrees, minutes, and<br/>                seconds, respectively. If latitude is expressed as degrees, minutes and seconds, a typical format would be<br/>                dd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two<br/>                decimal places, the format would be dd/1,mmmm/100,0/1. |
| GPS_LATITUDE_REF | Indicates whether the latitude is north or south latitude. |
| GPS_LONGITUDE | Indicates the longitude. The longitude is expressed as three RATIONAL values giving the degrees, minutes, and<br/>                seconds, respectively. If longitude is expressed as degrees, minutes and seconds, a typical format would be<br/>                ddd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two<br/>                decimal places, the format would be ddd/1,mmmm/100,0/1. |
| GPS_LONGITUDE_REF | Indicates whether the longitude is east or west longitude. |
| GPS_MAP_DATUM | Indicates the geodetic survey data used by the GPS receiver. |
| GPS_MEASURE_MODE | Indicates the GPS measurement mode. - 2- or 3- dimensional. |
| GPS_PROCESSING_METHOD | A character string recording the name of the method used for location finding.<br/>                The first byte indicates the character code used, and this is followed by the name<br/>                of the method. |
| GPS_SATELLITES | Indicates the GPS satellites used for measurements. This tag can be used to describe the number of satellites,<br/>                their ID number, angle of elevation, azimuth, SNR and other information in ASCII notation. The format is not<br/>                specified. If the GPS receiver is incapable of taking measurements, value of the tag shall be set to NULL. |
| GPS_SPEED | Indicates the speed of GPS receiver movement. |
| GPS_SPEED_REF | Indicates the unit used to express the GPS receiver speed of movement. 'K' 'M' and 'N' represents kilometers per<br/>                hour, miles per hour, and knots. |
| GPS_STATUS | Indicates the status of the GPS receiver when the image is recorded. |
| GPS_TIMESTAMP | Indicates the time as UTC (Coordinated Universal Time). TimeStamp is expressed as three RATIONAL values<br/>                giving the hour, minute, and second. |
| GPS_TRACK | Indicates the direction of GPS receiver movement. The range of values is from 0.00 to 359.99. |
| GPS_TRACK_REF | Indicates the reference for giving the direction of GPS receiver movement. 'T' denotes true direction and 'M' is<br/>                magnetic direction. |
| GPS_VERSION_ID | Indicates the version of GPSInfoIFD. |
| IMAGE_DESCRIPTION | A character string giving the title of the image. It may be a comment such as "1988 company picnic" or the like. |
| IMAGE_LENGTH | The number of rows of image data. |
| IMAGE_UNIQUE_ID | The image unique id. |
| IMAGE_WIDTH | The number of columns of image data, equal to the number of pixels per row. |
| ISO_SPEED | Information about iso speed value as defined in ISO 12232 |
| ISO_SPEED_LATITUDE_YYY | This tag indicates ISO speed latitude yyy value as defined in ISO 12232 |
| ISO_SPEED_LATITUDE_ZZZ | This tag indicates ISO speed latitude zzz value as defined in ISO 12232 |
| JPEG_INTERCHANGE_FORMAT | The offset to the start byte (SOI) of JPEG compressed thumbnail data. This is not used for primary image JPEG data. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | The number of bytes of JPEG compressed thumbnail data. This is not used for primary image JPEG data. JPEG thumbnails are not divided but are recorded as a continuous JPEG bitstream from SOI to EOI. Appn and COM markers should not be recorded. Compressed thumbnails must be recorded in no more than 64 Kbytes, including all other data to be recorded in APP1. |
| LENS_MAKE | This tag records lens manufacturer |
| LENS_MODEL | This tag records lens`s model name and model number |
| LENS_SERIAL_NUMBER | This tag records the serial number of interchangable lens |
| LENS_SPECIFICATION | This tag notes minimum focal length, maximum focal length, minimum F number in the minimum focal length and minimum F number in maximum focal length |
| LIGHT_SOURCE | The kind light source. |
| MAKE | The manufacturer of the recording equipment. This is the manufacturer of the DSC, scanner, video digitizer or other equipment that generated the image. When the field is left blank, it is treated as unknown. |
| MAKER_NOTE | A tag for manufacturers of Exif writers to record any desired information. The contents are up to the manufacturer, but this tag should not be used for any other than its intended purpose. |
| MAX_APERTURE_VALUE | The max aperture value. |
| METERING_MODE | The metering mode. |
| MODEL | The model name or model number of the equipment. This is the model name or number of the DSC, scanner, video digitizer or other equipment that generated the image. When the field is left blank, it is treated as unknown. |
| OECF | Indicates the Opto-Electric Conversion Function (OECF) specified in ISO 14524. |
| ORIENTATION | The image orientation viewed in terms of rows and columns. |
| PHOTOGRAPHIC_SENSITIVITY | Indicates the ISO Speed and ISO Latitude of the camera or input device as specified in ISO 12232. |
| PHOTOMETRIC_INTERPRETATION | The pixel composition. |
| PIXEL_X_DIMENSION | Information specific to compressed data. When a compressed file is recorded, the valid width of the meaningful image shall be recorded in this tag, whether or not there is padding data or a restart marker. |
| PIXEL_Y_DIMENSION | Information specific to compressed data. When a compressed file is recorded, the valid height of the meaningful image shall be recorded in this tag |
| PLANAR_CONFIGURATION | Indicates whether pixel components are recorded in a chunky or planar format. If this field does not exist, the TIFF default of 1 (chunky) is assumed. |
| PRIMARY_CHROMATICITIES | The chromaticity of the three primary colors of the image. Normally this tag is not necessary, since colorspace is specified in the colorspace information ColorSpace tag. |
| RECOMMENDED_EXPOSURE_INDEX | Indicates recommended exposure index |
| REFERENCE_BLACK_WHITE | The reference black point value and reference white point<br/>                value. No defaults are given in TIFF, but the values below are given as defaults here.<br/>                The color space is declared<br/>                in a color space information tag, with the default<br/>                being the value that gives the optimal image characteristics<br/>                Interoperability these conditions |
| RELATED_SOUND_FILE | The related sound file. |
| RESOLUTION_UNIT | The unit for measuring XResolution and YResolution. The same unit is used for both XResolution and YResolution. If the image resolution is unknown, 2 (inches) is designated. |
| ROWS_PER_STRIP | The number of rows per strip. This is the number of rows in the image of one strip when an image is divided into strips. |
| SAMPLES_PER_PIXEL | The number of components per pixel. Since this standard applies to RGB and YCbCr images, the value set for this tag is 3. |
| SATURATION | This tag indicates the direction of saturation processing applied by the camera when the image was shot. |
| SCENE_CAPTURE_TYPE | This tag indicates the type of scene that was shot. It can also be used to record the mode in which the image was shot. |
| SCENE_TYPE | Indicates the type of scene. If a DSC recorded the image, this tag value shall always be set to 1, indicating that the image was directly photographed. |
| SENSING_METHOD | Indicates the image sensor type on the camera or input device. |
| SENSITIVITY_TYPE | Type of photographic sensitivity |
| SHARPNESS | This tag indicates the direction of sharpness processing applied by the camera when the image was shot |
| SHUTTER_SPEED_VALUE | The shutter speed value. |
| SOFTWARE | This tag records the name and version of the software or firmware of the camera or image input device used to generate the image. The detailed format is not specified, but it is recommended that the example shown below be followed. When the field is left blank, it is treated as unknown. |
| SPATIAL_FREQUENCY_RESPONSE | This tag records the camera or input device spatial frequency table and SFR values in the direction of image width, image height, and diagonal direction, as specified in ISO 12233. |
| SPECTRAL_SENSITIVITY | Indicates the spectral sensitivity of each channel of the camera used. |
| STANDARD_OUTPUT_SENSITIVITY | Indicates standard output sensitivity of camera |
| STRIP_BYTE_COUNTS | The total number of bytes in each strip. |
| STRIP_OFFSETS | For each strip, the byte offset of that strip. It is recommended that this be selected so the number of strip bytes does not exceed 64 Kbytes.<br/>                Aux tag. |
| SUBJECT_AREA | This tag indicates the location and area of the main subject in the overall scene. |
| SUBJECT_DISTANCE | The distance to the subject, given in meters. |
| SUBJECT_DISTANCE_RANGE | This tag indicates the distance to the subject. |
| SUBJECT_LOCATION | Indicates the location of the main subject in the scene. The value of this tag represents the pixel at the center of the main subject relative to the left edge, prior to rotation processing as per the Rotation tag. |
| SUBSEC_TIME | A tag used to record fractions of seconds for the DateTime tag. |
| SUBSEC_TIME_DIGITIZED | A tag used to record fractions of seconds for the DateTimeDigitized tag. |
| SUBSEC_TIME_ORIGINAL | A tag used to record fractions of seconds for the DateTimeOriginal tag. |
| TRANSFER_FUNCTION | A transfer function for the image, described in tabular style. Normally this tag is not necessary, since color space is specified in the color space information ColorSpace tag. |
| USER_COMMENT | A tag for Exif users to write keywords or comments on the image besides those in ImageDescription, and without the character code limitations of the ImageDescription tag. |
| WHITE_BALANCE | This tag indicates the white balance mode set when the image was shot. |
| WHITE_POINT | The chromaticity of the white point of the image. Normally this tag is not necessary, since color space is specified in the colorspace information ColorSpace tag. |
| X_RESOLUTION | The number of pixels per ResolutionUnit in the ImageWidth direction. When the image resolution is unknown, 72 [dpi] is designated. |
| Y_CB_CR_COEFFICIENTS | The matrix coefficients for transformation from RGB to YCbCr image data. |
| Y_CB_CR_POSITIONING | The position of chrominance components in relation to the<br/>                luminance component. This field is designated only for<br/>                JPEG compressed data or uncompressed YCbCr data. The TIFF<br/>                default is 1 (centered); but when Y:Cb:Cr = 4:2:2 it is<br/>                recommended in this standard that 2 (co-sited) be used to<br/>                record data, in order to improve the image quality when viewed<br/>                on TV systems. When this field does not exist, the reader shall<br/>                assume the TIFF default. In the case of Y:Cb:Cr = 4:2:0, the<br/>                TIFF default (centered) is recommended. If the reader<br/>                does not have the capability of supporting both kinds of<br/>                YCbCrPositioning, it shall follow the TIFF default regardless<br/>                of the value in this field. It is preferable that readers "<br/>                be able to support both centered and co-sited positioning. |
| Y_CB_CR_SUB_SAMPLING | The sampling ratio of chrominance components in relation to the luminance component. |
| Y_RESOLUTION | The number of pixels per ResolutionUnit in the ImageLength direction. The same value as XResolution is designated. |
