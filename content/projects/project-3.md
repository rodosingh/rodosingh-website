---
title: "Table-Tennis shot classification using OpenPose"
date: 2019-05-12T12:14:34+06:00
image: "images/portfolio/item-3.png"
author: "Aditya Kumar Singh"
project_url : "https://themefisher.com/"
categories: ["illustration"]
description: "This is meta description."
draft: false
---

#### Project Overview

To classify whether the shot played in the given video is backhand or forehand.

Using `OpenPose` pose estimation technique in `OpenCV` library, I estimated the keypoints of body using `heatMap` technique for each frame and collected them for all frames which serves as the data of one sample. And then those serves as the data for classification.
