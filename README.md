# Regulating the Taxicab Market in the Smartphone Era

###### December 2015

For traditional taxi drivers and companies, ridesourcing services like Lyft and Uber represent unfair competition, exempt from regulation of the taxicab market. Historically, regulation has however been prompted by drivers and companies themselves. 

In this project, I go back to the source of the current regulation in New York City, and investigate whether new technologies have weakened the old rationale. To do so, I attempt to infer the characteristics of both user populations.

I find a growing divergence between users of Uber and taxis over time. Ridesourcing applications have given access of taxi services to a more diverse population, as they claim.

The fact that Lyft, Uber and co. have been able to expand the market without the help of old regulatory crutches confirms that new technology and business models has rendered old regulation is obsolete, and that a new framework is needed.

## I. The Old Rationale for Regulation

The current regulation of the cab industry in North America actually [dates back to the late 1930s][Frankena & Pautler], when the Great Depression provoked an influx of unemployed people in the market as drivers. As taxi fares, quality, occupancy and revenue crumbled, suppliers exerced heavy pressure to regulate entry.

The inherent instability of this market stems from the impossible synchronization between supply (available cabs) and demand.
The market failures that it caused justified a regulatory framework, until the smartphone arrived.

| Market failure | Regulatory response | Smartphone impact |
|:--------------:|:-------------------:|:-----------------:|
| Prices stick to an arbitrary high level, irrespective of consumer preferences on waiting time | Price setting & Entry regulation | Instant geolocalization of supply & demand, algorithmic fare setting |
| Consumer has no information on the driver, and has no simultaneous offers to choose from | Background checks & [Medallion bond][Cairnes] | Rating of drivers and passengers reducing information assymmetry |
| Sparse offer and demand at night or in the periphery prevents social benefits | Mandatory service & Cross-subsisdy | Certainty of supply & demand enabling night and periphery service |

The theoretical transformation of smartphone-based services collides however with the plain fact that Uber was born in Paris, and that ridesourcing services thrive in well established taxicab markets. Are they "merely" improving the experience of existing taxi riders in worldwide capitals, or are they expanding it by solving its market failures?

## II. Who rides Uber & NYC cabs?
### A. Sources & Method

In the Summer of 2015, [Five-Thirty-Eight filed a FOIL request][538] for trip records of rides from ridesourcing companies, including Uber. Combined with the open data of the Taxi and Limousine Commission, it warrants a unique comparison between traditional cabs and Uber, over two periods - April-Setpember 2014, and January-June 2015.

To compare the users of Uber and taxicabs, I proceed as such:
  * I select only trips starting between 6:30 and 9:30 on weekdays, assuming that they start around users' homes
  * I extract from the Census information on the neighborhood in which a user's home is located
  * Combining the fact that users from Uber and taxicabs are not located in the same neighborhoods, and that neighborhoods have different characteristics, I infer a probable distribution of those users in terms of age, income, and education
  
My estimates are thus based on a subset of total users, fluctuating over time between 8.5% and 11.5%. The sample consists in 1.8 millions Uber trips (9.5% of all Uber trips), and 16.5 millions taxi trips (9.3%).

![alt-text](https://github.com/amapsa/Uber_market/blob/master/Figures/ratio_ink.jpg)

Of course, those samples of Uber and taxicabs users are biased: people using the services early in the morning are not representative of the larger population, and power users may be skewing the result (1 person taking 1000 rides from the same neighborhood will be counted as 1000 persons). But I assume those biases to be similar for Uber and taxicabs, so the *difference* between the two population should remain instructive.

### B. Results

The results paint a picture of two increasingly different user populations. In April 2014, there is virtually no difference between the users of Uber and taxicabs in terms of education, age, or income. But as months go by and Uber expands, its population diverges from the taxicabs population, both in educaiton and in income (though not in age).

![alt-text](https://github.com/amapsa/Uber_market/blob/master/Figures/diff.jpg)

As the taxicab users did not really not change between April 2014 and May 2015, this divergence is due to the change in Uber's user population, not only in terms of residency, but also in terms of income and education. Uber has been able to reach less educated and rich people, compared to taxicabs (though not compared to the whole population).

| Date       | Uber > Bachelor | Taxicabs > Bachelor| Gap |
|:----------:|:---------------:|:------------------:|:---:|
| April 2014 | 67.6%           | 69.6%              | 2   |
| May 2015   | 60.4%           | 68.1%              | 7.7 |

This fact implies that the higher share of Uber trips started outside of Manhattan (from 20% to 30%) have not been solely to get customers identical to those in Manhattan, but who tend to move in the gentrifying parts of Brooklyn. This is probably one impact of the introduction of UberPool.

## III. A new framework

Uber's ability to service a portion of the population up to now excluded from the taxicab market, without being substantially cheaper, suggests that old market failures which supported the regulation of the taxicab market have no impact on the business of those new unregulated ridesourcing services.

As the foundations of the old regulatory framework crumble, it is time to do away with them.

This does not imply that ridesourcing services are having purely positive effects: their impact on congestion is [unclear][congestion], their relationships with drivers asks for some reflexion on the nature of work, and the [drop in taxi medallion prices][medallion] may disrupt drivers' lives. It means however that we need [new tools][Sundararajan], suited for today's challenges.

For decades, many predicted that the development of phone booking would weaken the rationale behind entry and prices regulation. Cellphone booking services did not, in the end, change the status quo. But their smartphone-based followers have brought the foreseen consequences to their fullest magnitude. An update of the regulation is long overdue.

[Frankena & Pautler]: https://www.ftc.gov/sites/default/files/documents/reports/economic-analysis-taxicab-regulation/233832.pdf
[Cairnes]: https://www.sciencedirect.com/science/article/pii/0047272794014957
[538]: https://github.com/fivethirtyeight/uber-tlc-foil-response
[congestion]: http://www.pnas.org/content/111/37/13290.abstract
[medallion]: https://www.nytimes.com/2015/01/08/upshot/new-york-city-taxi-medallion-prices-keep-falling-now-down-about-25-percent.html
[Sundararajan]: http://chicagounbound.uchicago.edu/cgi/viewcontent.cgi?article=1039&context=uclrev_online
