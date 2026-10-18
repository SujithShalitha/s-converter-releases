# Supported formats

| Kind | Opens | Saves as |
|---|---|---|
| Images | JPG, PNG, WebP, AVIF, TIFF, GIF, BMP, SVG, HEIC/HEIF (iPhone), camera RAW: CR2, NEF, ARW, DNG, RAF, ORF, RW2 | JPG, PNG, WebP, AVIF, TIFF, GIF, PDF |
| Video | MP4, MKV, AVI, MOV, WMV, FLV, WebM, MPEG, M4V, 3GP, TS, VOB, MTS, M2TS, OGV | MP4, MKV, AVI, MOV, WebM, GIF, WMV, FLV, MPEG, 3GP, TS |
| Audio | MP3, WAV, FLAC, AAC, OGG, WMA, M4A, AIFF, Opus, AMR, AC3, and the sound from any video | MP3, WAV, FLAC, AAC, OGG, M4A, Opus, AIFF, WMA, AC3, AMR |
| Documents | DOCX, DOC, ODT, RTF, TXT, Markdown, HTML, EPUB, PPTX, PPT, ODP, XLSX, XLS, ODS, CSV | PDF, DOCX, HTML, TXT, ODT, RTF, Markdown, XLSX |
| PDF | PDF | JPG pages, and every [PDF tool](pdf-tools.md) |
| Archives | ZIP, 7Z, RAR, TAR, TGZ, GZ, BZ2, XZ, ISO, CAB | ZIP, 7Z, RAR (needs WinRAR), TAR.GZ |

## Notes

- **Documents** are converted by S Converter's own engine: no Microsoft Office or LibreOffice needed. Word to PDF keeps headings, lists, tables, pictures and links; PowerPoint to PDF keeps each slide's layout.
- **Video** uses your graphics card when it can (NVIDIA NVENC, Intel Quick Sync, AMD AMF).
- **HEIC and RAW** photos are read directly; you don't need extra Windows codecs.
- **Compress** keeps each image's own format; HEIC and RAW become JPG, and BMP becomes PNG.

Related: [Convert files](convert.md)

[← All topics](README.md)
