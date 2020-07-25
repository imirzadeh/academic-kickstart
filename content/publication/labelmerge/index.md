---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "LabelMerger: Learning Activities
in Uncontrolled Environments"
subtitle: ""
summary: "Scalable Algorithm for improving aggregated noisy-labels in data collection process."
authors: [Seyed Iman Mirzadeh, Jessica C. Ardo, Ramin Fallahzadeh, Bryan Minor, Lorraine Evangelista, Diane Cook, Hassan Ghasemzadeh]
tags: []
categories: []
date: 2019-11-10T18:57:02-08:00
lastmod: 2019-11-10T18:57:02-08:00
featured: true
draft: false
publication_types: ["1"]
url_pdf: https://www.imirzadeh.me/dl/TransAI_2019_paper_16%20%282%29.pdf
abstract: "While inferring human activities from sensors embedded in mobile devices using machine learning algorithms has been studied, current research relies primarily on sensor data that are collected in controlled settings and/or with healthy individuals. Currently, there exists a gap in research about how to design activity recognition models based on sensor data collected with chronically ill individuals and in free-living environments. In this paper, we focus on a situation where free-living activity data are collected continuously, activity vocabulary (i.e., class labels) are not known as a priori, and sensor data are annotated by end-users through an active learning process. By analyzing sensor data collected in a clinical study involving patients with cardiovascular disease, we demonstrate significant challenges that arise while inferring physical activities in uncontrolled environments. In particular, we observe that activity labels that are distinct in syntax can refer to semantically-identical behaviors, resulting in a sparse label space. To construct a meaningful label space, we propose LabelMerger, a framework for restructuring the label space created through active learning in uncontrolled environments in preparation for training activity recognition models. LabelMerger combines semantic meaning of activity labels with physical attributes of the activities (i.e., domain knowledge) to generate a flexible and meaningful representation of the labels.Specifically, our approach merges labels using both word embedding techniques from the natural language processing and activity intensity from physical activity research. We show that the new representation of the sensor data obtained by LabelMerger results in more accurate activity recognition models compare to the case where original label space is used to learn recognition models."

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
