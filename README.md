# [Partido Libertario Mx Social Networks Analysis](#Table-Of-Contents)
Here I made an analysis for Partido Libertario Mx which is similar to a Libertarian Party, this analysis belongs to february 2021 data, the purpose is to analyse if their social networks are growing or not, what provoked the improvement, and where is the audience from.

You can start by reading the results or go directly to the [table of contents](#Table-Of-Contents).

# [Results](#Table-Of-Contents)
The results are written below but if you want to see the report in tableau click there [Facebook](https://public.tableau.com/views/facebookfebPlib/Story1?:language=es&:display_count=y&:origin=viz_share_link) and [Twitter](https://public.tableau.com/views/FebPlib/Story1?:language=es&:display_count=y&publish=yes&:origin=viz_share_link).
  

## [Facebook Report February 2021](#Table-Of-Contents)

First I start by concentratring the results cards and the statistical description of the KPIs for the social network on this case we incresed almost every aspect compared to january, january when I analysed it, it was towards to be a low results month, here we can see that we passed that bad month. Starting with the 'alcance' that means scope or reach, we incresed the number of people that watches our content by 375% compared to the past month. 

Another important KPI are the 'Comentarios' that means comments, the results is crazy above 1200% but this responds to an event we hosted, on libertarian parties around latin america. Here we can also conclude these kind of events improve our results by a lot and give us a lot of visibility so the objective will be to replicate these kind of events.

On the description side I will just say a few things so I avoid making this project boring to read for you, we can see a big difference between the median and the mean, that is because the distribution of the people a publication reach is biased to the right, what I mean is that 75% of our publications are lower than 651 of people reached, even though there are some publications that can be considered outliers, like the event on 8th February that reached 77k.

![fbdesc](https://user-images.githubusercontent.com/58957744/116261033-dd715300-a73c-11eb-9c03-010214d786b3.png)

Here we can take a quick glance of the cities that follow us, the countries and the audience demography. We know now the cities we can start to invite affiliates to events of the party to start the register in that county, for example start with Mexico City, our best city where we can start to host bigger events presential as soon as it is possible. 

What we can conclude here is that we must increase our content directed to women the proportion of females compared to males is ridiculous, knowing a bit about this movement they have great women personalities of liberalism and libertarianism so an objective will be to share about them and try to attract more women to the party.

![fb](https://user-images.githubusercontent.com/58957744/116261041-dea28000-a73c-11eb-9be2-04b6e1198cd2.png)

See the 2 spikes the first one belongs to the event with othe libertarian parties, and the second one responds to a publication of marxist flags on the government building. Once I made an analysis of the entire publications ever, the most 'viral' for us are about criticising the actual government, our proposals, anti-socialism and eventual scandals of the actual government.

![fb2](https://user-images.githubusercontent.com/58957744/116261029-dcd8bc80-a73c-11eb-8d8c-2f828f117d79.png)


## [Twitter Report February 2021](#Table-Of-Contents)

We can see a clear increase in any KPI compared to january but when we know the overall panorama we know january was low and even if february was better, february is still a low month we can know that by looking at the max impressions that is about 55k, that is low from our best tweets ever, those are at least above 100k. 

The distribution of tweets and impressions is similar to facebook's with the difference that what is considered here a low tweet impressions Q1 = 953 on facebook the similar KPI with that number is above Q3. On a past analysis I did for them it was clear how twitter is better than facebook for them, but here we can see another frame on how that is true.

![twitdesc](https://user-images.githubusercontent.com/58957744/116267923-7191e900-a742-11eb-9315-a181bf357c31.png)

We have some spikes through the month, at least 8, I labeled the most important, we can click the data point to see the tweets that belong to that day, as I said our most 'viral' content is about criticising the actual government, the event of libertarian parties, anti-socialism and eventual scandals like the one of the Osito Bimbo (Bimbo's bear).

![twit](https://user-images.githubusercontent.com/58957744/116261034-de09e980-a73c-11eb-9349-192960bd33c0.png)

This month as in the overall analysis is congruent, the best hours are around 5 p.m. as we can see the biggest bar, on thing that this chart means without putting it in is that there are no publications between 8 and 10 a.m., we have to analyse that, historicly our best ours are 6 p.m. and above, but we have to ask ourselves if we are actually looking to not tweet at that hour or if not there is an error.

![twit2](https://user-images.githubusercontent.com/58957744/116261037-de09e980-a73c-11eb-8f03-c6201888a6af.png)

That is all, I wanted to not get too deep in thought, just some simple and relevant points of the reports.

# Table Of Contents

* [Resume](#Partido-Libertario-Mx-Social-Networks-Analysis)
* [Results](#Results)
  *  [Twitter Report February 2021](#Twitter-Report-February-2021)
  *  [Facebook Report February 2021](#Facebook-Report-February-2021)
* [Tools And Libraries](#Tools-And-Libraries)
* [Data Wrangling](#Data-Wrangling)


# [Tools And Libraries](#Table-Of-Contents)
  * Python 3.7
  * Pandas 1.1.5
  * Numpy 1.19.5
  * Datetime
  * Excel
  * Tableau

# [Data Wrangling](#Table-Of-Contents)
The wrangling was done altogether (twitter and facebook) in a jupyter notebook via google colab, to see the entire document and more in detail comments I added [click](https://github.com/JorgePablol/Data-Analysis-Libertarian-with-Tableau/blob/main/Libertarian_cleaning_github_version.ipynb) if the document don't open reload or download and open it with Google Colab. 

## The wrangling can be divided in 4 simple steps:

### 1. Importing Libraries

![wran1](https://user-images.githubusercontent.com/58957744/116272528-98521e80-a746-11eb-8df7-9b106963825e.png)

### 2. Dropping useless features

![wran2](https://user-images.githubusercontent.com/58957744/116274265-1d8a0300-a748-11eb-87d4-87907f0ca433.png)

### 3. Creating interesting features like weekday name, hour feature.

![wran3](https://user-images.githubusercontent.com/58957744/116274269-1e229980-a748-11eb-9098-2cda8792575d.png)

### 4. Executing the function scripts.

![wran4](https://user-images.githubusercontent.com/58957744/116274272-1e229980-a748-11eb-85c6-c72e27b18236.png)

