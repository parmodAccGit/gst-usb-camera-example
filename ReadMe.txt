# Copyright (c) 2025 Qualcomm Innovation Center, Inc.  All Rights Reserved.
# SPDX-License-Identifier: BSD-3-Clause-Clear
 
#Need to set SDKTARGETSYSROOT, MACHINE  and GST_APP_NAME environment variables.
 
#export SDKTARGETSYSROOT=<path to installation directory of platfom SDK>/tmp/sysroots
#Example: export SDKTARGETSYSROOT=/local/mnt/workspace/Platform_eSDK_plus_QIM/tmp/sysroots
 
#eport MACHINE=<Chipset machine name>
#Example: export MACHINE=qcs615-adp-air
 
#export GST_APP_NAME=<App file name>
#Example: export GST_APP_NAME=gst-usb-camera-app

 * Gstreamer Application:
 * Gstreamer Application for single USB Camera usecases with different possible
 * outputs
 *
 * Description:
 * This application Demonstrates single USB camera usecases with below possible
 * output:
 *     --Live Camera Preview on Display
 *
 * Usage:
 * Live Camera Preview on Display:
 * gst-usb-camera-app 0 -w 640 -h 480 -f 30 -F YUY2
 *
 * Help:
 * gst-usb-camera-app --help
