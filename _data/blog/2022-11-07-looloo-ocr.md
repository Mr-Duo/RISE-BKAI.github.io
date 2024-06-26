---
template: BlogPost
path: /blog/looloo-ocr-2022
date: 2022-11-07T07:08:53.137Z
title: Transformer-based Optical Character Recognition (OCR) for Thai-English documents
thumbnail: "/assets/blogs/ocr.jpg"
metaDescription:
---

A majority of Thai-English documents exist in a physical paper format, making digitization and information retrieval considerably challenging.
Current Thai-English Optical Character Recognition (OCR) systems are still limited in accessibility and lack evaluation on various downstream real-world scenarios.
They have a high character error rate measure of performance. To improve the current state of Thai-English OCR systems, we propose a transformer-based OCR (TrOCR) pretrained on a large synthetic image dataset generated from a collection of Thai and English corpora.

We show that our model can be fine-tuned for various downstream image modality tasks, including printed and handwritten text-line images. Our fine-tuned model achieved character error rates (CER) of 0.73%, 1.32%, and 3.14% on scanned, camera-captured, and handwritten recognition respectively. The accuracy of our OCR system which measures the number of correct predictions to the total number of predictions is at 94.10%, 93.82%, and 86.74% respectively. The model can also be fine-tuned on a smaller dataset while still preserving the CER. We believe that our model and evaluation provide the next milestone developments for the current state of the Thai-English OCRs.

This work is lead by Atirut Boribalburephan, Peeranat Buabang, and Shinawatra. If you are interested, see our [blog on Looloo's website](https://loolootech.com/ocr/).
