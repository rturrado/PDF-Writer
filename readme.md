# PDF-Writer
Fork of [galkahana/PDF-Writer](https://github.com/galkahana/PDF-Writer), a C++ library for creating, parsing an manipulating PDF files and streams.

This fork:
- Added `PDFHUMMUS_BUILD_TESTS` option to avoid building PDFWriterTestPlayground unless requested.
- Fixed cmake_minimum_required deprecation warning when adding PDF-Writer to another project.
- Added check for CMake policy CMP0128.
