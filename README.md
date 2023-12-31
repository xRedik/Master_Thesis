# CNN based star tracker for high-precision spacecraft navigation

## Table of Contents

- [Introduction](#introduction)
- [Repository Structure](#repository-structure)
- [Code](#code)
- [Dataset](#dataset)
- [Papers](#papers)
- [Reports](#reports)

## Introduction

The goal of this research paper is to explore the idea of leveraging CNN for star tracking in spacecraft systems. Star trackers are optical devices used to determine the spacecraft's attitude by identifying and tracking celestial objects mainly stars. Traditional star trackers utilize algorithms and techniques based on image processing and pattern recognition to perform this task. However, CNNs have shown significant potential in various computer vision tasks making them a promising alternative for star tracking applications.

This repository serves as a comprehensive resource for the research conducted, providing access to relevant dataset, reference papers and codes that was used to train the model.

## Repository Structure

```bash
├── code/
│   └── [Models that implemented for every work and script that was used to collect simulated data]
├── dataset/
│   └── [Simulated subset of dataset used for training and testing the CNN model]
├── papers/
│   └── [Reference papers for the research]
├── reports/
│   └── [Reports that was generated for the project]
```
## Code

The `code` folder contains the implementation of the models. It consists of 2 folder. The model folder consists of the model that was used to create and train the model. The dataset script generator consists of the script that was usec to generate input images, and corresping positions for the input image (target).

## Dataset

The `dataset` folder contains the subset of dataset used for training and testing the CNN model. It includes labeled star images and corresponding attitude information. The data files are organized and formatted appropriately for the CNN training process.

## Papers

The `papers` folder contains a collection of reference papers that have been researched and consulted throughout the course of the study. These papers contribute to the theoretical background, related work, and state-of-the-art techniques in the field of star tracking, attitude determination, and navigation for spacecraft systems.

## Reports
The `reports` folder within this repository contains the reports generated throughout the project including the research proposal and the final research report. The research proposal document outlines the initial plan, objectives, and methodology of the research project. On the other hand, the final research report document presents the complete findings, analysis, and conclusions of the research project.

**Author:**
- [Farid Guliyev](mailto:farid.guliyev@gwmail.gwu.edu)



