# PSPbeam Credits

PSPbeam is an independently maintained continuation and modification of PSPdisp. The repository contains inherited PSPdisp code, original PSPbeam contributions, and third-party components. Each remains subject to its applicable license.

## PSPdisp

PSPbeam is based on PSPdisp by **Jochen Schleu** (2008–2015).

The original PSPdisp code remains subject to its original **BSD 3-Clause** license. PSPbeam does not claim ownership of that inherited code or change its license.

Original PSPdisp website: https://www.jjs.at/software/pspdisp.html

## Original PSPbeam contributions

The following files are designated as original PSPbeam contributions and are covered by `PSPBEAM-CONTRIBUTIONS-LICENSE.md`, to the extent the PSPbeam Project holds or controls the relevant rights:

- `audio_adpcm.c` and `audio_adpcm.h`
- `audio_ring.c` and `audio_ring.h`
- `jpeg_dimensions.c` and `jpeg_dimensions.h`
- `screenshot.c` and `screenshot.h`
- `screenshot_pixels.c` and `screenshot_pixels.h`
- `video_avi.c` and `video_avi.h`
- `video_capture.c` and `video_capture.h`
- `loopback_audio_utils.h`

## Third-party components

The following components were identified in a repository audit. Retain their actual license files and notices, and verify the precise version and license in the distributed source tree.

| Component | Repository location reported by the audit | License reported by the audit |
|---|---|---|
| intraFont | `Source/psp/source/library/intraFont.*` | CC BY-SA 3.0 |
| libusb-win32 | `Source/*/LibUsb.pas` | LGPL 2.1 or later |
| Microsoft SideShow sample | `Source/sideshow/source/BitmapDriverSample/` | Microsoft Public License (Ms-PL) |
| SpeexDSP | `Source/app/source/loopback/third_party/speexdsp/` | BSD 2-Clause |
| PSPLink USBHostFS | `Source/psp/source/usbhostfs/` | BSD 3-Clause |
| Danzeff | `Source/psp/source/library/danzeff.*` | BSD; consult the component's included notice for exact terms |

The table summarizes repository audit findings. The actual license text and notices distributed with each component control.

## Distribution

When publishing PSPbeam, include the applicable license texts and notices for PSPdisp and all third-party components. Do not describe the entire repository as being under the PSPbeam contributions license.
