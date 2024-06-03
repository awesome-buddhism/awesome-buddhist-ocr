# Awesome Buddhist OCR

<!-- A curated list of awesome resources related to Optical Character Recognition (OCR) for Buddhist texts. This includes tools, libraries, datasets, research papers, and more that facilitate the digital reading and processing of Buddhist scriptures and documents. -->

## Introduction

Briefly explain the purpose of this list and what OCR for Buddhist texts entails. You may also include why this particular area is important or of interest to you and the community.

## Contents

- [Tools](#tools)
- [Libraries](#libraries)
- [Datasets](#datasets)
- [Research Papers](#research-papers)
- [Websites](#websites)

## Tools

<!-- List of tools that are useful for OCR processing of Buddhist texts with description and links to the tool. -->

- [Google Vision API](https://cloud.google.com/vision/docs/drag-and-drop) - Google Vision API is the currently the best performing OCR Model for the Tibetan Buddhist text images, which is available via google cloud console and is a paid service.
- [Namsel OCR](https://github.com/thubtenrigzin/namsel-ocr) - Namsel OCR is a model trained on Machine printed Tibetan text images, which is an open-source project.
- [Monlam-BDRC OCR](https://huggingface.co/BDRC/Woodblock/blob/main/Woodblock.onnx) - This OCR model made in collaboration between Monlam and BDRC, which is trained on woodblock printed images and is Easter2 model architecture.

## Libraries

<!-- Include libraries that support the development of OCR applications specifically tailored for Buddhist scriptures. -->

- [Openpecha-toolkit](https://github.com/OpenPecha/Toolkit) - Openpecha-toolkit is a python package which converts the Google OCR and Google Books output data into Openpecha format, which in turn can be converted into .txt, .docs, .epub and .hfml formats.
## Datasets

<!-- Mention any datasets that are particularly useful for training OCR models on Buddhist texts. -->
### OCR Line image and Transcriptions
- Lhasa Kanjur - 160K line images and transcripts
- Derge Tenjur - 676K line images and transcripts
- Lithang Kanjur - 25 GB line images and transcripts
- Norbuketaka - 2M line images and transcripts
- Google Books - 700K line images and transcripts

### Line Segmentation data
- Monlam AI annotated - 9k page images
- HTR project annotated - 10k page images
- Google books - 20k page images (line segmentation from Google Books OCR output)
- Transkribus annotated - 2 works line segmentated using Transkribus

### Laout Analysis data
- Monlam AI annotated - 9k page images

## Research Papers

<!-- Reference research papers that focus on OCR technology as it applies to Buddhist texts or similar scripts. -->

- [TrOCR](https://arxiv.org/pdf/2109.10282) - TrOCR is OCR model architecture based on transformer model.
- [Easter2](https://arxiv.org/pdf/2205.14879) - Easter2 is OCR model based on the Convlutional Neural 

## Websites

<!-- Include any websites that provide resources, forums, or articles on Buddhist OCR. -->

- [Openpecha-OCR](https://staging-tools.openpecha.org/ocr/) - to OCR BDRC images using Google Vision API use this website.
- [Monlam AI OCR](https://monlam.ai/model/ocr) - OCR Tibetan text images use this website of Monlam AI OCR.

---

