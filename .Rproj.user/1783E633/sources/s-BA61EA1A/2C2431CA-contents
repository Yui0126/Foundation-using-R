
# I do not know if this is the best color choice

install_from_swirl("R Programming")
library(swirl)
swirl()
Yui
for(i in 1:10)
  print(i)
class(i)
x <- c("a","b","c","d")
for (i in 1:4) {
  print(x[i])
  
}

for (i in seq_along(x)) {
  print(x[1])
  
}

for (letter in x) {
  print(letter)
}

for (b in 1:6) {
  print(b^2)
}


for (j in 5) {
  print(j**3)
}
library(swirl)
swirl()
Yui

pollutantmean("specdata", "sulfate", 1:10)

getwd()
setwd("C:/Users/ynaru/Desktop/R coursera/Data Science Foundations using R/Foundation using R/specdata")
load("specdata")


link.address.for.specdata.zip <- "https://d396qusza40orc.cloudfront.net/rprog%2Fdata%2Fspecdata.zip"

download.file(link.address.for.specdata.zip, "specdata20May2021.zip",
              method = "wininet", quiet = FALSE, mode = "wb",
              cacheOK = TRUE,extra = getOption("download.file.extra"),headers = NULL)

unzip("specdata20May2021.zip")

filenames <- list.files("specdata", full.names = TRUE)
filenames[2]
specdata <- read.csv(filenames[3])
tail(specdata)
mean(specdata$sulfate, na.rm = T)

pollutantmean <- 