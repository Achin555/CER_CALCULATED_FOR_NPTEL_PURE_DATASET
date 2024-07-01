# Assignment 2: Implementation of NPTEL Pure Set on State-of-the-Art Algorithm

## Overview

This assignment involves implementing the `nptel-pure-set.tar.gz` dataset using a state-of-the-art speech recognition algorithm and calculating the resulting Character Error Rate (CER). The objective is to assess the performance of advanced speech recognition models on real-world audio data from the NPTEL Pure dataset.

## Dataset

The `nptel-pure-set.tar.gz` dataset includes audio files, original transcriptions, corrected transcriptions, and metadata organized as follows:
- `/content/nptel_pure_set/nptel-pure/wav`: Contains audio files.
- `/content/nptel_pure_set/nptel-pure/original_txt`: Contains original transcriptions.
- `/content/nptel_pure_set/nptel-pure/corrected_txt`: Contains corrected transcriptions.
- `/content/nptel_pure_set/nptel-pure/metadata`: Contains metadata.

## Procedure

1. **Preprocessing**: Extract and preprocess the dataset to prepare audio files for transcription.
2. **Transcription**: Utilize a state-of-the-art speech recognition model for transcription.
3. **Error Calculation**: Compute the Character Error Rate (CER) by comparing model transcriptions with corrected transcriptions.
4. **Evaluation**: Assess the performance of the speech recognition model using the CER metric.

## Notes

- One audio file was unable to be transcribed due to corruption:
  - `/content/nptel_pure_set/nptel-pure/wav/0000a7be825f70cbe4c49acf9a8b7804d05a8a4701a2b42a343a694e.wav`
