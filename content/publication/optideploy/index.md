---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Optimal Policy for Deployment of Machine Learning Models
on Energy-Bounded Systems"
subtitle: ""
summary: "This paper studies the problem of deploying machine learning models using optimization theory."
authors: [Seyed Iman Mirzadeh, Hassan Ghasemzadeh]
tags: []
categories: []
date: 2019-11-10T18:57:14-08:00
lastmod: 2019-11-10T18:57:14-08:00
featured: true
draft: false
abstract: "With the recent advances in both machine learning and embedded systems research, the demand to deploy these computational models on edge devices has increased substantially. Without deploying computational models on edge devices, frequent transmission of sensor data to the cloud results in rapid battery depletion because energy consumption due to wireless data transmission is significantly higher than that of on-the-device data processing. This rapid power dissipation leads to a considerable reduction in battery lifetime of the system, therefore jeopardizing real-world utility of smart devices. 

A major challenge that obstructs the deployment of machine learning models on edge devices is the power limitations of these systems. It is well-established that for difficult machine learning tasks, models with higher performance often require more computation power and thus are not power-efficient choices for deployment on edge devices. However, trade-offs between performance and power consumption are not well studied. While numerous methods (e.g., model compression) have been developed to obtain an optimal model, these methods focus on improving the efficiency of a “single” model.

In an entirely new direction, we introduce an effective method to find a combination of “multiple” models that are optimal in terms of power-efficiency and performance by solving an optimization problem in which both performance and power consumption are taken into account. The general goal of our optimization problem is to find an optimal distribution of model allocations that maximize expected performance subject to a given power budget. Experimental results demonstrate that on the ImageNet dataset, we can achieve a 20% energy reduction with only a 0.3% accuracy drop compared to Squeeze-and-Excitation Networks. Compared to a pruned convolutional neural network for human activity recognition task, while consuming 1.7% less energy, our proposed policy achieves 1.3% higher accuracy."

url_pdf: https://www.imirzadeh.me/dl/AAAI_optimal_deploy.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Center"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
