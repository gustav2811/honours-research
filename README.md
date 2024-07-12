# honours-research
This is the home of the modelling for the honours research project, by Cara and Melina, in 2024.

# Health Scheme Claims Increase Modelling Project

## Overview

This project is focused on modelling claims increases for a health scheme using R and RStudio. The aim is to provide insights and predictive models that can help in understanding and forecasting the increase in health scheme claims.

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Installation](#installation)
3. [Setting Up the Repository](#setting-up-the-repository)
4. [Project Structure](#project-structure)
5. [Usage](#usage)
6. [Contributing](#contributing)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed [R](https://cran.r-project.org/mirrors.html) (version 4.0 or later).
- You have installed [RStudio](https://www.rstudio.com/products/rstudio/download/) (any version).
- You have installed [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
- You have a GitHub account.

## Installation

### R and RStudio

1. **Download and Install R**:
   - Visit the [CRAN mirror](https://cran.r-project.org/mirrors.html).
   - Choose your operating system (Windows, macOS, or Linux).
   - Follow the instructions to download and install R.

2. **Download and Install RStudio**:
   - Visit the [RStudio download page](https://www.rstudio.com/products/rstudio/download/).
   - Download the installer for your operating system.
   - Follow the instructions to install RStudio.

### Git

1. **Download and Install Git**:
   - Visit the [Git website](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
   - Choose your operating system and follow the instructions to download and install Git.

2. **Set Up Git**:
   - Open a terminal or command prompt.
   - Configure your Git username: `git config --global user.name "Your Name"`
   - Configure your Git email: `git config --global user.email "your.email@example.com"`

## Setting Up the Repository

1. **Fork the Repository**:
   - Go to the GitHub page of the project.
   - Click on the `Fork` button at the top right of the page to create a copy of the repository under your GitHub account.

2. **Clone the Repository**:
   - Open RStudio.
   - Click on `File` > `New Project` > `Version Control` > `Git`.
   - Enter the URL of the forked repository from your GitHub account.
   - Choose a local directory to save the repository.
   - Click on `Create Project`.

3. **Install Required Packages**:
   - Open the `R` console in RStudio.
   - Run the following commands to install necessary packages:
     ```R
     install.packages(c("dplyr", "ggplot2", "caret", "randomForest"))
     ```

## Project Structure

- `data/`: Contains raw and processed data files.
- `scripts/`: Contains R scripts for data processing, modelling, and analysis.
- `reports/`: Contains generated reports and visualizations.
- `README.md`: This file.
- `DESCRIPTION`: Metadata about the project.
- `R/`: Contains custom R functions used in the project.

## Usage

1. **Data Preparation**:
   - Place raw data files in the `data/raw/` directory.
   - Use scripts in the `scripts/` directory to preprocess the data.

2. **Modelling**:
   - Use the provided R scripts to build and evaluate models.
   - Adjust parameters and models as necessary to improve performance.

3. **Reporting**:
   - Generate reports using the scripts in the `reports/` directory.
   - Visualize the results using `ggplot2` or other visualization tools.

## Contributing

To contribute to this project, please follow these steps:

1. **Fork the Repository**: Click the `Fork` button on the top right of the repository page.

2. **Clone Your Fork**:
   ```bash
   git clone https://github.com/your-username/your-forked-repo.git
   ```

3. **Create a Branch**:
   ```bash
   git checkout -b feature-branch
   ```

4. **Make Changes**: Make your changes in the new branch.

5. **Commit Changes**:
   ```bash
   git add .
   git commit -m 'Description of changes'
   ```

6. **Push Changes**:
   ```bash
   git push origin feature-branch
   ```

7. **Create a Pull Request**: Go to the original repository on GitHub and create a pull request from your fork.

---

By following these instructions, you should be able to set up and use the project locally. If you encounter any issues, please refer to the documentation or open an issue on the GitHub repository. Happy coding!
