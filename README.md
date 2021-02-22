# libflac-1.3.3
FLAC stands for Free Lossless Audio Codec, an audio format similar to MP3, but lossless, meaning that audio is compressed in FLAC without any loss in quality.

I am adding this repo since I want to make a WebAssembly version and since the commonly available versions are older.

FLAC 1.3.3 (4-Augs-2019)
General:
Fix CPU detection (Janne HyvÃ¤rinen).
Switch from unsigned types to uint32_t (erikd).
CppCheck fixes (erikd).
Improve SIMD decoding of 24 bit files (lvqcl).
POWER* amnd POWER9 improvements (Anton Blanchard).
More tests.
FLAC format:
(none)
Ogg FLAC format:
(none)
flac:
When converting to WAV, use WAVEFORMATEXTENSIBLE when bits per second is not 8 or 16 (erikd).
Fix --output-prefix with input-files in sub-directories (orbea).
metaflac:
(none)
plugins:
(none)
build system:
Cmake support (Vitaliy Kirsanov, evpobr).
Visual Studio updates (Janne HyvÃ¤rinen).
Fix for MSVC when UNICODE is enabled (lvqcl).
Fix for OpenBSD/i386 (Christian Weisgerber).
documentation:
(none)
libraries:
(none).
Interface changes:
libFLAC:
(none)
libFLAC++:
(none)
