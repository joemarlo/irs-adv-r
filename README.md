# Advanced R class - IRS

This is an empty repo to initialize an R project. Please follow the directions below to set up your project. The `/deck` folder contains the slides and `/live-code` the scripts created during the class -- which will be updated as we go along.

## Setup
In order to get the most out of class you have to be working in this project. There are three ways to get this project on your computer.

Choose __one of these methods__:

1. Posit Cloud
2. Posit Workbench
3. Local Rstudio

### Posit Cloud

1. Create a free account on [posit.cloud](https://posit.cloud/) then login.
2. Click `New Project` in the top right.
3. Click `New project from Git Repository`
4. Paste in `https://github.com/joemarlo/irs-adv-r.git` and click `OK`

Moments later an RStudio GUI should appear with the content in the file system. In the top right, choose R 4.2.3 from the drop-down.

### Posit Workbench

If your organization has [Posit Workbench](https://posit.co/products/enterprise/workbench/), you may use this.

1. Sign in to your Workbench.
2. Click `New Session` near the top.
3. Select `Rstudio Pro` then `Start Session`
4. Select `File` then `New Project...`
5. Select `Version Control` then `Git`
6. Paste in `https://github.com/joemarlo/irs-adv-r.git`, ensure you are using R 4.2.1, and click `Create Project`

### Local Rstudio

This assumes you have [R and Rstudio](https://posit.co/download/rstudio-desktop/) along with  [`git` installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

1. Open Rstudio.
2. Select `File` then `New Project...`
3. Select `Version Control` then `Git`
4. Paste in `https://github.com/joemarlo/irs-adv-r.git`, ensure you are using R 4.2.1, and Click `Create Project`

If you're comfortable using command line, you may also clone the repo directly:

```sh
git clone https://github.com/joemarlo/irs-adv-r.git
```

After any of these methods you should have a new RStudio project called irs-adv-r. You can see this in the top right of RStudio (the name in the image may be different).

## Dependencies

The project requires a number of R packages. These packages can be downloaded and installed via:

```r
renv::restore()
```
