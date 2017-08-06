#Fail Log Module 4
**Installation**
Installed R and R Studio onto my PC

**Exercise 1**
installed  gelphi
use gelphi
having trouble installing my charts
reading annotations
will return


**Exercise 2** 
$ ls
$zip -r equityfiles.zip equityfolder
downloaded folder from file manager 
set input to colonial newspaper database


**Exercise 3**
Opened R studio
made new directory
used
install.packages("mallet")
library("mallet")
install.packages('RCurl')
library(RCurl)
used 
x <- getURL("https://raw.githubusercontent.com/shawngraham/exercise/gh-pages/CND.csv", .opts = list(ssl.verifypeer = FALSE))

really cool to see how barplot(counts, main="Cities", xlab="Number of Articles") gets the graphs out

years <- table(documents$Year)
barplot(years, main="Publication Year", xlab="Year", ylab="Number of Articles")

mallet.instances <- mallet.import(documents$Article_ID, documents$Text, "en.txt", token.regexp = "\\p{L}[\\p{L}\\p{P}]+\\p{L}")

mallet.instances <- mallet.import(documents$Article_ID, documents$Text, "en.txt", token.regexp = "\\p{L}[\\p{L}\\p{P}]+\\p{L}")
**Error in mallet.import(documents$Article_ID, documents$Text, "en.txt",  : 
  could not find function "mallet.import"** not sure why trouble shooted and looked in slack / annotations 

set the number of desired topics
num.topics <- 20
topic.model <- MalletLDA(num.topics) --leads to mallet error 


**Exercise 4**
downloaded overview
imported the csv from module 2

**Exercise 6** 
downloaded voyant
inputted URL https://raw.githubusercontent.com/shawngraham/exercise/gh-pages/CND.csv .
http://voyant-tools.org/?corpus=colonial-newspapers&stopList=stop.en.taporware.txt went here
tried using the rezoviz 
**Exercise 7**
Receieved Error using RAW
looking to slack and annotations for assistance 

**Exercise 8** 
Grabbed  Gatineau Valley Historical Society

**Exercise 9**
 install igraph; 
- read.csv("texasnodes.csv", header=T, as.is=T)
examine data
head(nodes)

head(links)
nrow(nodes); length(unique(nodes$id))
nrow(links); nrow(unique(links[,c("source", "target")]))

stuck not getting my chart up
Error in graph_from_data_frame(d = links, vertices = nodes, directed = T) : 
  could not find function "graph_from_data_frame"
seeing this moving back steps now

**Exercise 10**
Tutorial
Installed QGIS
Downloaded the country data on the gensus.gov page.  
added the vector of tl\_2016/_us/_country 
right clicked and opened attribute table
downloaded the =national railway line map from North America Supplement
added the vector of the rail roads
 got the  county population estimates 
 aligned color to value range

Using Historic Maps with QGIS
downloaded the SR_50M.tiff zip
inserted the SR_50M.tif in raster layer
blended the layers
imported the raster image of the Rumsey JPG
raster into Georeferencer 
not getting the image that is shown on the instructions 
redid the plugin for Georeferencer 
added points via Georeferencer
got this error when i tried to transform
gdal_translate -of GTiff -gcp 6038.85 4361.39 -81.1615 26.2249 -gcp 3879.19 4543.69 -98.3433 27.5813 -gcp 3738.95 4066.89 -97.8911 30.7464 -gcp 4959.02 1486.52 -87.0395 47.25 -gcp 1032.37 2384.04 -122.533 42.0502 -gcp 2308.53 2678.54 -114.847 40.2416 
Failed to compute GCP transform. Transform is not solvable.




