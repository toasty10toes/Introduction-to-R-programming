# Introduction-to-R-programming

Welcome! This repository will help you get started with R and RStudio for data analysis. It includes step-by-step setup instructions and example R projects to introduce basic data manipulation and visualization, using biological/environmental data examples.

## Installing R

The following instructions to download R and RStudio are only applicable if you are using a personal laptop.
If you are using a government laptop, please contact IT to download R and RStudio if it is not already installed. 

You need to install R — the programming language — and RStudio — an integrated development environment for using R. Both are free. Install R first, then RStudio.
Follow the directions for whatever operating system you are working under. 

As a quick note, an 

**Windows:**

  1. Go to the Comprehensive R Archive Network (https://cran.r-project.org/).
  2. Click “Download R for Windows”.
  3. Click “base” (for the base system).
  4. Finally, download the latest R installer (the link will say something like “Download R x.x.x for Windows”) and run the .exe installer.
  5. Follow the setup instructions (you can accept default options).

**macOS:**

  1. Go to Comprehensive R Archive Network (https://cran.r-project.org/).
  2. Click “Download R for (Mac) OS X”. 
  3. Download the latest R .pkg file for macOS and open it.
  4. Follow the installer steps to install R (defaults are fine)
     On some macOS versions, you may need to drag the R app into your Applications folder

## Installing R Studio
   1. Go to the official RStudio webpage (http://posit.co/downloads/).
   2. Hit the 'Download RStudio' button (the webpage usually detects your operating system). 
   3. Run the RStudio installer and follow the prompts to install.

**Note:** You must install R before installing RStudio
Once both R and RStudio are installed, open RStudio to begin using R. (If RStudio asks you to install any recommended packages on first launch, you can accept.)

## Downloading this Repository (Without Git)
To get the materials in this repository onto your computer without using Git:
  1. Navigate to the repository’s page on GitHub in your web browser.
  2. Click the green “Code” button at the top of the file list.
  3. In the dropdown, choose “Download ZIP”
  4. Save the ZIP file to your computer, then unzip it (extract all files). This will create a folder containing the repository files.

You can now open the example R project files in RStudio!

## Getting Started with R: Example Projects
This repository includes two example files to practice basic R skills. Open these in RStudio and step through the code and comments:
example1.R – Demonstrates reading a CSV file into R, then basic data manipulation with dplyr: filtering rows, adding a new column, renaming columns, and selecting/subsetting data.
example2.R – Demonstrates basic plotting with ggplot2: creating a scatter plot (with categories colored by species) and a histogram for exploratory data visualization.
Each example uses a real-world inspired dataset (environmental or biological) and is heavily commented for clarity. Make sure to install the necessary packages (like dplyr, ggplot2) by running install.packages("tidyverse") or individually (install.packages("dplyr"), install.packages("ggplot2")) if you haven’t already, so that you can use these libraries in R. Below you can find the content of the example files with explanations:
