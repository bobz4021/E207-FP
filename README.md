# E207-FP: Online Time Warping

## Project Overview

This project aims to explore the effectiveness of various time warping algorithms applied to audio processing, specifically focusing on the use of chroma features for alignment and comparison of audio recordings. The primary dataset for this study is the Mazuika Dataset.

## Team Structure

- **Team A:**
- **Team B:**

## Objectives and Tasks

### Initial Setup

- Select 2 train audio recordings from the Mazuika Dataset.
- Both subteams are tasked with reading the MATCH paper to understand the foundational concepts and methodologies.

### Implementation Phase

- **Team A:** Focus on getting the MATCH algorithm up and running. This involves understanding and applying the algorithm specifically with chroma features.
  
- **Both Teams:** Acquire the FlexDTW implementation from the appropriate repository. The goal here is for both teams to implement an online time warping algorithm that can process audio data in real-time or near-real-time.

### Experimentation and Comparison

- **Team B:** Compare the Dynamic Time Warping (DTW) algorithm when utilizing chroma features for audio alignment.
  
- **Both Teams:** Explore the Online FlexDTW with chroma features. This involves understanding how chroma features can be integrated with the FlexDTW algorithm for better performance in audio alignment tasks.

- **Team A:** Specifically compare the MATCH algorithm's performance when chroma features are utilized. This requires a deep dive into how the MATCH algorithm can be optimized or adjusted for chroma features.

- **Both Teams:** Investigate the effect of window size on the algorithms' performances. This involves experimenting with a range of window sizes to determine their impact on the accuracy and efficiency of the time warping processes.

### Results Replication and Analysis

- **Team B:** Replicate results using the Mazurika Dataset, with Professor Tsai providing the necessary code. This task is crucial for validating the experiments and ensuring that the findings are reliable and reproducible.

  - Focus on DTW with chroma features, comparing it against other methodologies to highlight its strengths and weaknesses.

## Expected Outcomes

The project aims to compare various time warping algorithms, particularly focusing on:
- The use of chroma features in DTW and FlexDTW implementations.
- The performance and applicability of the MATCH algorithm with chroma features.
- The impact of window size on the algorithms' effectiveness.

By conducting these comparisons and analyses, the project seeks to contribute to the understanding of how time warping algorithms can be optimized for audio processing tasks, particularly in the context of online or real-time applications.
