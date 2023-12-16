---
title: "Fuelathons Addendum: Research Notes"
date: 2023-07-03
tags: ["engineering", "supermileage", "ubc"]
draft: false
---

**Let's look at a brief and very incomplete history of fuelathons!**  I wanted to make a more detailed piece about fuelathons in general as a companion post to my reflection on the [SAE Supermileage competition](/posts/sae-supermileage). Unfortunately, there wasn't a lot of historical record keeping over time, leaving a patchy network of details along the way. I wanted to share some of what I could find. (which is by no means exhaustive!)

## Fuelathons

Beyond the aforementioned SAE Supermileage competition, the premier competition for engineering students is the [Shell Eco-Marathon](https://www.shellecomarathon.com/), taking place in various locales including the Americas, Europe, and Asia. Throughout the years, there have also been independent competitions held by various entities in places like [Québec](https://www.fsg.ulaval.ca/faculte/evenements/4389), [Niagara](https://www.niagarafallsreview.ca/news/gss-goes-the-distance-in-dsbn-s-supermileage-challenge/article_92959c68-4da6-5b04-8c4a-91b459c34a13.html), [Minnesota](https://www.mteea.net/index.php/competitions/supermileage), and [Japan](http://www.fc-design.jp/monodukuri/entry/2006/scch_2006.htm). Additionally, there are teams who have taken it upon themselves to create suitable conditions for world record attempts[^1].

### Shell Eco-Marathon

Shell has a long history of supporting investigations into improving fuel efficiency, spanning as far back as 1939[^2]. The modern incarnation of the Shell Eco-Marathon began in Europe in 1985 in France[^3]. Shell has made a number of short videos showcasing the legacy and history of the competition, many of which are hosted unlisted. You can see what they have to say in [2012](https://www.youtube.com/watch?v=2ImSHgBn2kA) and more recently in [2020](https://www.youtube.com/watch?v=vuErQbe3_qI), which so happens to feature the 8870 mpg record from La Joliverie MicroJoule. I believe there are some discrepancies in the reported number here for the record caused by the various unit conversions from mpg(US), mpg(imp), and L/km, but neat to have that as part of the official record displayed by Shell.

You can find some more information from their current [about page](https://www.shellecomarathon.com/about.html) (whose link I expect to break at any point since Shell loves to redesign the Shell Eco-Marathon website).

### SAE Supermileage

The SAE Supermileage competition ran from 1980 to 2022, spanning 43 competitions. From 1984 to 1996, two separate competitions hosted in Michigan and on the west coast coexisted, before merging in 1997. Since hosted at the Eaton Marshall Proving Grounds, the competition was a hallmark for fuelathon competitions, predating even the Shell Eco-Marathon.

## World Records

One of the interesting side histories of the fuelathons is the world records for the different fuel classes. As far as I could find, there were five records of note. First is for the gasoline category, where MicroJoule captured back in 2003. They bested this record is consecutive years, but it was difficult to pinpoint the exact progression of this record.

For the electric vehicle category, there are two main classes with the fuel cell and battery categories. ETH Zürich built the "most efficient vehicle" in Pac-car II in 2005 under the fuel cell category. This would eventually be bested by Duke Electric Vehicles' Maxwell car in 2018. The battery category was won by TU Munich in 2016, but were also bested by Duke Electric Vehicles' Eta car in 2019.

See the table below for more details.

{{<table "table table-post">}}
| Team | Year | Class | Fuel Efficiency |
|:---|:---:|:---|---:|
| [La Joliverie MicroJoule](https://www.instagram.com/microjoule_lajoliverie/) | 2003 | Gasoline |  [8924 mpg (3794 km/L)](https://web.archive.org/web/20060621232355/http://la-joliverie.com/index.php?id=91) |
| ETH Zürich PAC-Car II | 2005 | Fuel Cell | [12600 mpge (5357 km/L)](https://en.wikipedia.org/wiki/Pac-car_II) |
| TU Munich eli-14 | 2016 | Battery | [765 mi/kWh (1232 km/kWh)](https://web.archive.org/web/20180116063854/http://tufast-eco.de/en/guinness-world-record-2/) |
| [Duke Electric Vehicles](http://www.duke-ev.org/) Maxwell | 2018 | Fuel Cell | [14573 mpge (6196 km/L)](https://www.guinnessworldrecords.com/world-records/most-fuel-efficient-vehicle) |
| [Duke Electric Vehicles](http://www.duke-ev.org/) Eta | 2019 | Battery | [797 mi/kWh (1283 km/kWh)](https://pratt.duke.edu/about/news/duke-student-team-wins-second-guinness-world-record-vehicle-efficiency) |
{{</table>}}

It may be a long time before we see another record set in any of these categories, however. A key success to such high efficiencies are low rolling resistance tires. There is only one class of tires that are truly competitive, the Michelin "blacks" or "radials," which were last available for sale in 2016. As the finite supply of these tires continues to dwindle, and the rubber degrades[^1], these records may stay out of reach for a long time to come.

## Building the Most Efficient Vehicles

While the general aspects of building highly efficient vehicles can be straightforward, there are some very useful resources. I'll point to two in particular that I think provide a lot of very useful information and approach the problem in a more rigorous fashion.

The first is the book on designing PAC-Car II: [The World's Most Fuel Efficient Vehicle: The Design and Development of PAC-Car II](https://www.paccar.ethz.ch/book/) [^4].

The second is an IEEE VPPC paper from Duke University: [A Study of Energy Losses in the World's Most Fuel Efficient Vehicle](https://www.pgrady.net/assets/pdf/VPPC2019.pdf) [^5].

There's also plenty of useful information to be gleaned from technical reports from various teams that may be floating around the internet.

## Some Notable Team

I'm using the word "notable" somewhat loosely here, but below are a few supermileage / ecocar teams that have websites. There's a strong bias towards North American and Canadian teams here (due to my background), but they often have some interesting details on the construction of their vehicles and team history. Check them out!

{{<table "table table-post">}}
| School | Team |
|:---|:---|
| Duke University | [Duke Electric Vehicles](http://www.duke-ev.org/) |
| Technische Universität München | [TUfast Eco Team](https://tufast-eco.de/) |
| Northern Illinois University | [NIU Supermileage](https://www.niusupermileage.com/) |
| University of British Columbia | [UBC Supermileage](https://www.supermileage.ca/) |
| Université Laval | [Alérion Supermileage](https://alerion-supermileage.com/) |
| University of Ottawa | [UO Supermileage](https://uosupermileage.ca/) |
| Toronto Metropolitan University | [Ryerson Supermileage](http://www.ryersonsupermileage.com/) |
| University of Alberta | [UofA EcoCar](https://www.ualberta-ecocar.ca/) |
{{</table>}}

## Conclusion

By no means is this an exhaustive exploration of fuelathons, but I figure it would be a good starting point for anyone interested in the history of such competitions. [Let me know](mailto:contact@kevinta.dev) if anything is wrong or if you found this interesting!

[^1]: Miranda Volborth. "[Duke Student Team Wins Second Guinness World Record for Vehicle Efficiency](https://pratt.duke.edu/about/news/duke-students-break-guinness-world-record-fuel-efficiency)," Duke University, 2019.
[^2]: W. S. Affleck and G. B. Toft. "[Mileage Marathons](https://link.springer.com/chapter/10.1007/978-1-349-03418-5_12),"  Fuel Economy of the Gasoline Engine: Fuel, Lubricant and Other Effects, 1977.
[^3]: "[History of Shell Eco-marathon](https://web.archive.org/web/20120218180157/https://www.shell.com/home/content/ecomarathon/about/history)," Shell, 2009.
[^4]: J.J. Santin, C.H. Onder, J. Bernard, D. Isler, P. Kobler, F. Kolb, N. Weidmann, and L. Guzzella. "[The World's Most Fuel Efficient Vehicle: The Design and Development of PAC-Car II](https://www.paccar.ethz.ch/book/)," ETH Zurich, 2007.
[^5]: Patrick Grady, Gerry Chen, Shomik Verma, Aniruddh Marellapudi, and Nico Hotz. "[A Study of Energy Losses in the World's Most Fuel Efficient Vehicle](https://ieeexplore.ieee.org/document/8952212)," IEEE Conference on Vehicle Power and Propulsion (VPPC), 2019.
