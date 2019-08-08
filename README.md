# instaDM-parser-master-R

R script to parse Instagram's downloadable messages.json file to pretty human readable.

Place messages.json file in same folder as parser.R

## Requirements
```
library(dplyr)
library(rjson)
library(tidyverse)
```

## Usage
```
git clone https://github.com/AdarshPawar29/instaDM-parser-master-R
cd instaDM-parser-master-R
RScript parser.R message.json
```

### How to get messages.json?
For Desktop follow this [Link](https://www.instagram.com/download/request/).

For Mobile go to Settings > Security > Download Data
