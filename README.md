<a id="readme-top"></a>

<br />
<div align="center">
  <h3 align="centre">GEOL0069 AI for Earth Observation: Week 4 </h3>
<div align="center">
  <h3 align="center"><b>Altimetry Classification: Sea Ice vs. Leads</b></h3>

  <p align="center">
    Unsupervised Machine Learning for discriminating sea ice and leads using Sentinel-2 optical imagery and Sentinel-3 altimetry data.
    <br />
    <a href="https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="#usage">View Results</a>
    ·
    <a href="https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/issues">Report Bug</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage & Results</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

This project explores the application of **Unsupervised Learning** to categorise satellite data. The core objective is to differentiate between **Sea Ice** and **Leads** (open water fractures in sea ice) using two distinct methods:
1. **Unit 1:** Structural setup and initial data exploration.
2. **Unit 2:** Implementation of K-Means and Gaussian Mixture Models (GMM) to classify Sentinel-3 altimetry echoes.

By analysing features like **Peakiness (PP)**, **Stack Standard Deviation (SSD)**, and **Sigma_0**, we can effectively cluster radar waveforms without prior labelling, then validate these clusters against official ESA classifications.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
* [![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
* [![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
* [![Rasterio](https://img.shields.io/badge/Rasterio-green?style=for-the-badge)](https://rasterio.readthedocs.io/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To run the notebooks in this repository:

### Prerequisites
You will need a Python environment with the following libraries:
```sh
