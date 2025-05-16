# Introduction-to-R-programming

Welcome! This repository will help you get started with R and RStudio for data analysis. It includes step-by-step setup instructions and example R projects to introduce basic data manipulation and visualization, using biological/environmental data examples.

## Installing R and RStudio
You need to install R (the programming language) and RStudio (an IDE for using R). Both are free. Install R first, then RStudio.

**Windows:**

*Installing program R*
  1. Go to the Comprehensive R Archive Network (https://cran.r-project.org/)
  2. Click “Download R for Windows”.
  3. Click “base” (for the base system).
  4. Finally, download the latest R installer (the link will say something like “Download R x.x.x for Windows”) and run the .exe installer
  5. Follow the setup wizard (you can accept default options)

*Installing R Studio*
  1. Go to the official RStudio (Posit) download page and download RStudio Desktop for Windows (the site usually auto-detects your OS).
  2. Run the RStudio installer and follow the prompts to install

**macOS:**
Go to CRAN and click “Download R for (Mac) OS X”. Download the latest R .pkg file for macOS and open it. Follow the installer steps to install R (defaults are fine)
dataquest.io
. On some macOS versions, you may need to drag the R app into your Applications folder
. Install RStudio Desktop for macOS by downloading the .dmg from RStudio’s download page. Open the .dmg and drag the RStudio app into Applications to install. (RStudio may automatically offer the correct download for macOS on its site

**Note:** You must install R before installing RStudio
. Once both are installed, open RStudio to begin using R. (If RStudio asks you to install any recommended packages on first launch, you can accept.)

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
