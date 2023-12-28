# Master's Thesis
# Visual Viper: A Portable Visualization Library for Streamlined Scientific Communication

## Overview

This repository contains the LaTeX source files for the Master's Thesis titled "Visual Viper: A Portable Visualization Library for Streamlined Scientific Communication". The thesis discusses the development and application of an automated Python library designed to streamline the process of creating data visualizations, specifically aimed at enhancing scientific communication in the healthcare sector.

This work was submitted for the acquisition of the \\Master's Degree in Medical Informatics by the Faculty of Medicine of the University of Porto (FMUP).

## Relevant Links

- [Master's Degree in Medical Informatics @FMUP Program](https://mim.med.up.pt/)
- [Faculty of Medicine of the University of Porto (FMUP)](https://sigarra.up.pt/fmup/pt/web_page.inicial)

## File Structure

* `main.tex`: This is the main LaTeX file that compiles all the sections and chapters of the thesis. Run LaTeX on this file to generate the final PDF document.
* `bib.bib`: This BibTeX file contains all the bibliographic entries.
* `media/`: This folder contains all images and figures used in the thesis.

## Abstract

### Background

The healthcare industry is seeing a digital revolution, resulting in an
ever-growing influx of data. This transformation creates an urgent need
for efficient and automated data visualization tools. Visual Viper (VV)
aims to meet this demand by offering an automated Python library that
streamlines the complex and often time-consuming process of creating
data visualizations for scientific communication.

### Aim

The aim of this study is to outline the development of VV, assess its
performance and adaptability, explore its modular design and development
methodologies, and establish its practical applications in healthcare
research.

### Methods

Built using Python, VV employs Vega-Lite for high-level interactive
graphics. The library is structured with modular, extensible
architecture, developed with object-oriented programming (OOP) and
test-driven development (TDD) practices. Docker containerization ensures
a consistent development environment, and GitLab version control,
aligned with Semantic Versioning, streamlines collaborative development.
Native CI/CD capabilities of GitLab further enrich the development
process. VV operates environment-agnostically and offers serverless
deployment options.

### Results

VV includes various interconnected components, each responsible for
specific tasks ranging from data retrieval to chart rendering. Four main
classes (\textquotesingle DatasetBuilder\textquotesingle,
\textquotesingle ChartNotationBuilder\textquotesingle, `ChartRenderer',
and \textquotesingle ChartDeployer\textquotesingle) encapsulate the
respective functionalities, thus aiding in code maintenance and
extension.

Evaluation metrics, captured using Monday.com and Python's time library,
showed that while VV required a longer initial setup time (2h vs. 0.5h),
it outperformed manual methods in "Time-to-Final-Chart" (2h9min vs.
14h54min) for a project involving 72 spreadsheets. Adjusted metrics
accounting for task fatigue and human intervention also favor VV,
especially for larger and ongoing projects.

VV effectively minimizes manual labor, ensures data visualization
consistency and fosters best practices in scientific communication.
Current limitations include a focus on mostly specific organizational
workflows and visualizations.

### Conclusion

VV presents a robust and customizable solution for automating data
visualization. It holds promise for significantly enhancing scientific
communication efficiency within the healthcare sector, with its modular
and scalable design paving the way for future developments.
