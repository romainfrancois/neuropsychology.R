# neuropsychology
An R Toolbox for Psychologists, Neuropsychologists and Neuroscientists

|Name|neuropsychology|
|----------------|---|
|Status|![](https://img.shields.io/badge/status-stable-brightgreen.svg)|
|Latest Version|![](https://img.shields.io/badge/version-0.1-brightgreen.svg)|
|Authors|Dominique Makowski|

---
## Installation

Open R and paste the following commands:

```
install.packages("devtools")
library("devtools")
install_github("neuropsychology/neuropsychology.R", dependencies=TRUE)
```

Once the package is installed, load the package each time you open a new R session by using the following command:

```
library(neuropsychology)
```

---
## Feature Examples

### Use a data set
```
df <- personality
```

Available datasets are:
- personality

See the description of each datasets by typing "?nameofthedataset" (ex: "?personality") in the console.

### Quickly get a corelation table with significance stars
```
cortable(personality)
```
This function will automatically select the numeric columns of your dataframe and show a correlation table with significance stars.
You can adjust the p value by applying different corrections or change the type of correlation type (Spearman's or Pearson's). Run "?cortable" for documentation.

---
## Citation

Run the following commands to see the proper citation entry in APA6 or Bibtex format:
```
library(neuropsychology)
citation("neuropsychology")
```
