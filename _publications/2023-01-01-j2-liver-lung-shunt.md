---
title: "Quantification of liver-lung shunt fraction on 3D SPECT/CT images for selective internal radiation therapy of liver cancer using CNN-based segmentations and non-rigid registration"
collection: publications
category: manuscripts
permalink: /publication/2023-j2-liver-lung-shunt
excerpt: 'Automatic quantification of liver-lung shunt fraction in SPECT/CT images using 3D nn-UNet and non-rigid registration for selective internal radiation therapy planning.'
date: 2023-01-01
venue: 'Computer Methods and Programs in Biomedicine'
paperurl: 'https://doi.org/10.1016/j.cmpb.2023.107453'
citation: 'Manh Ha Luu, Hong Son Mai, Xuan Loc Pham, <b>Le Quoc Anh</b>, Quoc Khanh Le, Theo Van Walsum, Ngoc Ha Le, Daniel Franklin, Vu Ha Le, Adriaan Moelker, et al. &quot;Quantification of liver-Lung shunt fraction on 3D SPECT/CT images for selective internal radiation therapy of liver cancer using CNN-based segmentations and non-rigid registration.&quot; <i>Computer Methods and Programs in Biomedicine</i>, 233:107453, 2023.'
---

This paper presents a pipeline for (semi)automatic quantification of liver-lung shunt fraction (LSF) in non-contrast-enhanced CT (nCECT) images. We utilize the Elastix registration technique to deform the liver in the CECT image to the shape of that liver in the nCECT image, then apply a 3D nn-UNet model to segment the deformed liver in CECT. This integrated approach enables reliable liver segmentation and LSF quantification for selective internal radiation therapy (SIRT) planning.
