# Quantifying Peer Review Informativeness: An Unsupervised, Linguistic Features-Based Approach

## Overview

Peer reviews play a crucial role in upholding the quality and rigor of academic research. This project, titled **Quantifying Peer Review Informativeness: An Unsupervised, Linguistic Features-Based Approach**, introduces a novel method to measure the informativeness of peer reviews by analyzing linguistic features at the sentence level. By employing an unsupervised approach, our method provides a composite score to gauge the quality and informativeness of peer reviews, which could contribute significantly to the peer-review process across disciplines.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Visualizations](#visualizations)
- [Contributing](#contributing)
- [Contact](#contact)

## Introduction

In the academic world, the quality of peer reviews impacts the validity, relevance, and impact of research work. However, the informativeness of reviews can vary greatly, making it essential to quantify their quality reliably. Our approach leverages **linguistic features and unsupervised learning** to measure informativeness based on correlations between features and informativeness scores. This metric can help journals, institutions, and researchers better assess and improve the peer review process.

## Methodology

1. **Dataset**: Our analysis uses a dataset comprising research papers and their corresponding peer reviews.
2. **Linguistic Feature Extraction**: We extract various linguistic features from each sentence within the peer reviews.
3. **Modeling Techniques**:
   - **Principal Component Analysis (PCA)**: Used to identify the most significant components that relate to informativeness.
   - **Auto-Encoders**: Deployed to capture nonlinear relationships in the data, highlighting meaningful patterns in review quality.
4. **Composite Score Calculation**: Based on our findings, we compute a composite informativeness score by integrating the top-scoring components, specifically:
   - **2nd Principal Component**
   - **Auto-Encoder Output**
   - **1st Principal Component**
5. **Evaluation**: Visualizations, including heatmaps and scatter plots, are used to illustrate and validate the relationship between linguistic features and informativeness.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Quantifying-Peer-Review-Informativeness-An-Unsupervised-Linguistic-Features-Based-Approach
   cd quantifying-peer-review-informativeness
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Data:
  The entire data for ICLR papers and reviews can be found in the zip file "ICLR_2022.zip". Extract this folder before running the analysis files.
2. Analysis and Visualizations:
  The analysis and visualizations can be found on the colab notebooks and can be re-created using the ICLR 2022 research paper and corresponding review data.

## Results

Our analysis found that the 2nd Principal Component, Auto-Encoder Output, and 1st Principal Component provide significant indicators of review informativeness. The composite score, generated from these elements, showed a robust relationship with hypothesized informativeness levels, supporting the use of these components in a composite metric for review quality.

## Visualizations

We provide various visualizations to help users explore the data and understand the model’s outputs. Key visualizations include:
1. Heatmaps: Display correlations between linguistic features and informativeness.
2. Scatter Plots: Illustrate the clustering of reviews based on informativeness scores.

## Contributing
We welcome contributions to enhance this project! To contribute:

1. Fork the repository.
2. Create a new branch (feature/YourFeature).
3. Commit your changes.
4. Push to the branch.
5. Open a pull request.

## Contact
For questions or further discussion, please contact the corresponding authors:

1. Prabhat Kumar Bharti: prabhat1921cs32@iitp.ac.in
2. Asif Ekbal: asif@iitp.ac.in

Or reach out to other contributors:

1. Vijay Harkare: vijay.harkare2020@gmail.com
2. Aditya Shah: adityashah841@gmail.com
3. Mayank Agarwal: mayank265@iitp.ac.in

