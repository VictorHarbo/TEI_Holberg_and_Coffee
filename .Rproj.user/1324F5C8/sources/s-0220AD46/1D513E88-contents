# Fooling around with XML
library(tei2r)

dl <- buildDocList(directory = "/Users/vhol/Documents/Holbergskaffe/forfatterskab", stopwordsFile = "", indexFile = "",
             import = TRUE, normalize = TRUE)
texts <- importTexts(dl, normalize = TRUE)

Barsel <- parseTEI("/Users/vhol/Documents/Holbergskaffe/forfatterskab/Barselstuen.xml", node = "text")
Barsel

Abra <- parseTEI("/Users/vhol/Documents/Holbergskaffe/forfatterskab/Abracadabra.xml", node = "text")
Abra

AdVir1 <- parseTEI("/Users/vhol/Documents/Holbergskaffe/forfatterskab/AdVir1.xml", node = "text")
AdVir1


target <- c("caffee", "caffe", "cafe", "café", "caffée", "coffee")
kaffe_antal <- filter(tekster_tidy, word %in% target)
