# WineLabels
## Synopsis
pass

## Problem and Solution
Product decision in the wine market heavily depends on non-rational consumer decision. Wine is a non standardized product with a wide spread in both quality and price that is normally not known by the client. Especially, when the consumer has no experience with a specific vineyard, the choice to buy a bottle depends on those aspects that are immediately obvious to the client winch is the price and the wine label.

There are several known classes of wine labels such as “minimal” or “prestigious”. However, these classifications rely on non-parameterized human decisions from a design point of view. Thus, the aim of my project is to do a classification of wine labels by machine learning and furthermore to test whether the already described  label classes really reflect a meaningful structure.
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/labels.png)

Being able to classify labels automatically is very useful for large web-shops as this reduces human efforts a lot and results in an improved user experience.   

## Use case
The algorithm will be applied in the back-end system of a web-shop and has no direct user exposure.

## Data
The data set is built by crawling websites such as vicampo.de, wirwinzer.de, winestro.com, euvino.eu, weine.de and storing the bottle images.
In a second step, we select only promising images, i.e. images that show a single bottle. Afterwords, we reduce the images to the labels only.
To train the data, we then have to classify some labels manually.


## Approach
CNN architecture


## Defined style classes
### Prestigous
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/p1.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/p2.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/p3.png)
\
Style features: Usage of large crests, golden colours, serife fonts \
Similar to: Classic, Vintage

### Classic
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/c1.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/c2.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/c3.png)
\
Style features: Usage of crests, golden colours, serife fonts \
Similar to: Prestigous, young classic

### Young Classic
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/yc1.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/yc2.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/yc3.png)
\
Style features:   \
Similar to:  

### Text
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/t1.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/t2.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/t3.png)
\
Style features:   \
Similar to:  

### Minimal
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/m1.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/m2.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/m3.png)
\
Style features:   \
Similar to:  
### Hand drawn
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/h1.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/h2.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/h3.png)
\
Style features: Usage of crests, golden colours, serife fonts \
Similar to: Vintage

### Vintage
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/v1.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/v2.png)
![alt text](https://raw.githubusercontent.com/toeb83/WineLabels/master/md_img/v3.png)
\
Style features: Usage of crests, golden colours, serife fonts \
Similar to: Vintage
