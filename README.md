# CNN based star tracker for high-precision spacecraft navigation

This repository contains the research paper, data, presentations, reviews, and reference papers for the proposal of using Convolutional Neural Networks (CNN) in the star tracker sensor of a spacecraft. The star tracker is a critical component for spacecraft attitude determination and navigation.

## Table of Contents

- [Introduction](#introduction)
- [Repository Structure](#repository-structure)
- [Code](#code)
- [Data](#data)
- [Papers](#papers)
- [Reports](#reports)

## Introduction

The goal of this research paper is to explore the idea of leveraging CNN for star tracking in spacecraft systems. Star trackers are optical devices used to determine the spacecraft's attitude by identifying and tracking celestial objects mainly stars. Traditional star trackers utilize algorithms and techniques based on image processing and pattern recognition to perform this task. However, CNNs have shown significant potential in various computer vision tasks making them a promising alternative for star tracking applications.

This repository serves as a comprehensive resource for the research conducted, providing access to relevant data, presentations, reviews, and reference papers.

## Repository Structure

```bash
├── code/
│   └── [Models that implemented for every work and script that was used to collect simulated data]
├── data/
│   └── [Simulated subset of data used for training and testing the CNN model]
├── papers/
│   └── [Reference papers for the research]
├── reports/
│   └── [Reports that was generated for the project]
```
## Code

The `code` folder contains the implementation of the models. It consists of 3 folder, and each folder has the implementation and saved model for every week. It also has 1 extra folder that contains the code for data generation which was used to collect the simulated images through the Stellarium program.

## Data

The `data` folder contains the subset of dataset used for training and testing the CNN model. It includes labeled star images and corresponding attitude information. The data files are organized and formatted appropriately for the CNN training process.

## Papers

The `papers` folder contains a collection of reference papers that have been researched and consulted throughout the course of the study. These papers contribute to the theoretical background, related work, and state-of-the-art techniques in the field of star tracking, attitude determination, and navigation for spacecraft systems.

## Reports
The `reports` folder within this repository contains the reports generated throughout the project including the research proposal and the final research report. The research proposal document outlines the initial plan, objectives, and methodology of the research project. On the other hand, the final research report document presents the complete findings, analysis, and conclusions of the research project.

**Author:**
- [Farid Guliyev](mailto:farid.guliyev@gwmail.gwu.edu)



