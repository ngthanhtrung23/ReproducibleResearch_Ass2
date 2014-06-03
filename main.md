# Relation of Severe Weather Events on Public Health and Economy

## Synopsis
It was found that severe weather events indeed had a huge impact on society in recent years. More than 150,000 people have been injured or killed, and the total economic damage have exceeded 476 billion US dollars. Floods were found to have cost most significant economy damage, which attributed to more than 150 billions US dollars of property damage. Tornados were found to have made most number of death and injuries, with almost 97,000 injuries or fatalities in recent years.

## Data Processing

```r
download.file("https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2FStormData.csv.bz2", dest="storm.bz2")
```

```
## Error: unsupported URL scheme
```

```r
storm_data <- read.table(
  bzfile("storm.bz2", open = "r"),
  header = TRUE,
  sep = ",")
```

```
## Warning: cannot open bzip2-ed file 'storm.bz2', probable reason 'No such
## file or directory'
```

```
## Error: cannot open the connection
```
