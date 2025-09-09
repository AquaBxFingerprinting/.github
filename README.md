# FingerprintSimilarity

**Objective**
This repository collection focuses on developing methods to measure the distances between web browser fingerprints.

**Purpose**
The primary aim is to cluster individuals based on fingerprint similarity, grouping those with the closest profiles.

**Future Work**
The next phase involves identifying optimized web browser configurations for each cluster to enhance anonymization and reduce fingerprint uniqueness.

## [fingerprint-extract](https://gitlab.inria.fr/diverse/fingerprintsimilarity/fingerprint-extract)
This application extracts the fingerprint of your browser based on the work of [https://github.com/HuygheMaxime/fp-rainbow/](https://github.com/HuygheMaxime/fp-rainbow/).

## [fingerprint-feature-model](https://gitlab.inria.fr/diverse/fingerprintsimilarity/fingerprint-feature-model)

This repository contains tools for processing and manipulating feature models represented as trees. The tools allow you to merge multiple feature trees, convert them into different formats, and generate random configurations for testing and validation.

## [fingerprint-experiment](https://gitlab.inria.fr/diverse/fingerprintsimilarity/fingerprint-experiment)
This project analyzes different distances (Hamming and Euclidean) and uses machine learning models for clustering analysis.

## [fingerprint-automated-extract](https://gitlab.inria.fr/diverse/fingerprintsimilarity/fingerprint-automated-extract )

This script performs fingerprint extraction on a computer by launching a browser with various configurations using Puppeteer and Bun. It navigates to a specified URL to collect fingerprint data and saves the data in JSON format.
