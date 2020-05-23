# pyvobsub2srt

A Python script to convert vobsub subtitles into srt format using tesseract for ocr

## Usage

`./vobsub2srt ../chap1/chap1 > ../chap1/chap1.srt`

if there are ../chap1/chap1.idx and ../chap1/chap1.sub .

## Requirements

- Python3
- [OGMRip](http://ogmrip.sourceforge.net/en/index.html) for subp2png
- ImageMagick for convert images
- tesseract for ocr
