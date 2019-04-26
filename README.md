# Analysis of eBay Roman coins
There are a lot of coins sold on eBay. But what are the most popular. I would have said Gordian III antoninianus, but turns out it is Hadrian denarius.

![queen](https://raw.githubusercontent.com/matteoferla/Roman-coins-on-eBay/master/queen.jpg)

## Textmining
I textmined the titles for emperor and denomination.

### Emperors
Luckly, [someone make a nice table of emperors](https://github.com/zonination/emperors). Constantine the great is also known as Constantine I or Constantine Senior.

### Denominations
Denominations came from wikipedia. Plus a few that wiki seems to not know, such as aurelianus (a post-Aurelian reform XXI antoninianus) and minims. Unfortunately, I did not want to waste time with Latin/English plurals. 1 as, 2 asses. 1 quadrans, 2 quadrantes.

One thing I could do, that I haven't is classify by gold, silver and bronze... but antoniniani are tricky.

### Quality
Obviously, quality of coins varies from slugs to EF. All listings are EF+ and photophopped to the max. So I did not text mine for quality.          
I am mighty tempted to do a Hugh transform on circles in figures, de-prospective them, pump the contrast and measure the difference from Gaussian noise. The reason I'd like to do that is because a deskewed and contrasted image is the first, hardest and most crucial step in making a machine learning for coin classifier.

### fakes
And there are the fake sellers.
Unfortunately, seller data is not given by a normal search. Otherwise I'd have crosschecked with [the list of fake sellers](http://www.forumancientcoins.com/board/index.php?topic=18502.0).

### Plots
Did I hear you say, "I want violin plots, waffle charts and choropleth maps?".

![boxplot emperors](https://raw.githubusercontent.com/matteoferla/Roman-coins-on-eBay/master/boxplot%20emperors.png)

Edit: y-axis is price in USD.


![coin per emperors](https://raw.githubusercontent.com/matteoferla/Roman-coins-on-eBay/master/coin%20per%20emperors.png)

NB. Some emperors, such as Philip I and Constantine go by alternative names.

![coins per denomination](https://raw.githubusercontent.com/matteoferla/Roman-coins-on-eBay/master/coins%20per%20denomination.png)


![denomination over time](https://raw.githubusercontent.com/matteoferla/Roman-coins-on-eBay/master/denomination%20over%20time.png)

Edit: typo in title... should read by denomination


![seller location](https://raw.githubusercontent.com/matteoferla/Roman-coins-on-eBay/master/seller%20location.png)


![euro](https://raw.githubusercontent.com/matteoferla/Roman-coins-on-eBay/master/euro%20sellers.png)

NB. A permit is required to export Roman coins from Italy

