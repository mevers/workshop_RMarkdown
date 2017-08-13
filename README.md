# workshop_RMarkdown

This GitHub repository contains slides and additional material for the RMarkdown workshop held at the Research School of Population Health (RSPH) of the Australian National University in August 2017.

## How to copy the material
Create a local copy by cloning the repository.
```
git clone https://github.com/mevers/workshop_RMarkdown
```

Further instructions are given in the [slides](slides.html). RMarkdown templates to create sample Word and PDF output files are given in subfolder [templates](templates).

To reproduce examples from the slides and templates, the following R packages should be installed: `dplyr`, `DT`, `ggplot2`, `hrbrthemes`, `knitr`, `pander`, `plotly`, `rmarkdown`, `scatterD3`, `xtable`. Sourcing the following R gist automatically checks and installs any missing R packages:
```
source("https://gist.github.com/mevers/ac8eccfe45b0638a8b9a258664c91741/raw/install_workshop_libs.R")
```

Sample text can be found in file [sample_text.txt](sample_text.txt), or can be downloaded within R as a gist:
```
download.file(
  "https://gist.github.com/mevers/f4b149520f32cfda538a43c31428d7c5/raw/sample_text.txt",
  "sample_text.txt");
```

## Questions and issues

If you have any RMarkdown-related questions/issues please open a new GitHub issue. This will allow others to benefit from further discussions and potential solutions.   
