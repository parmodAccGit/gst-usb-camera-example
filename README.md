# gst-usb-camera-example
 * Gstreamer Application:
 * Gstreamer Application for single USB Camera usecases with different possible
 * outputs
 *
 * Description:
 * This application Demonstrates single USB camera usecases with below possible
 * output:
 *     --Live Camera Preview on Display
 *     --Dump the Camera YUV to a file
 *
 * Usage:
 * Live Camera Preview on Display:
 * gst-usb-camera-example -o 0 -w 640 -h 480 -f 30 -F YUY2
 * For YUV dump on device:
 * gst-usb-camera-example -o 1 -w 640 -h 480 -f 30 -F YUY2
 *
 * Help:
 * gst-usb-camera-example --help
 *
 * *******************************************************************************
 * Live Camera Preview on Display:
 *     camerasrc->capsfilter->convert->waylandsink
 * Dump the Camera YUV to a filesink:
 *     camerasrc->capsfilter->convert->filesink
 * *******************************************************************************

