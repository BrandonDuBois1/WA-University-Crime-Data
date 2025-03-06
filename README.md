# Washington State University Crime Data

This repository contains data from the US Department of Education campus safety and security website.  It covers a variety of different crime data for college campuses nationwide.  For purposes of analysis, I pulled data for six major universities in Washington State - University of Washington, Washington State University, Western Washington University, Gonzaga University, Seattle University, and Whitman University.  

# Motivation
Crime gets a large amount of attention these days both in the media and in our personal lives.  Seattle, home to UW and Seattle University, is known as a high-crime area that gets national attention because of this.  The Logan neighborhood, surrounding Gonzaga, is also known as a high crime area.  WSU is known as a place with heavy amounts of drinking, drug use, and partying.  Whitman is in Walla Walla, and as a small school in a quaint town seems like it would be low on crime.  I wanted to compare campus safety at each of these institutions and evauluate where each is falling short.   

# Summary of Findings
I wanted to analyze this data and see what the rime trends were at various universities in Washington State.  I had assumed the University of Washington and Seattle University would suffer from the most crime given their location in Seattle.  On the other end, I assumed Whitman would have the least amount of crime since it is in quaint little Walla Walla.  It was interesting to be proven wrong.

The biggest finding that I had was that Whitman University in Walla Walla has the most crime per capita by, and by far in recent years.  In the years since 2013, Whitman has had more crime per capita than all of the other universities analyzed.  In some years (like 2016) that crime was around five times as high as the next highest university.  The other universities had far more criminal offenses committed than Whitman, but I believe the rate of crimes per-capita is a much more telling number.  This carries into Violent Incidents.  Whitman still claimed the spot of “most dangerous university” among those compared with a rate of .243 violent crimes per 1000 students.  Seattle U was close behind.  WWU consistently ranked as having the lowest number of all incidents per capita.

When it comes to disciplinary actions, one would expect the larger schools to have a higher number of reported incidents.  Wrong!  Gonzaga had a higher raw number of disciplinary actions imposed upon students, even more than the much larger universities.  Gonzaga is notoriously harsh on student drinking, and these numbers corroborate that claim.  Gonzaga had over 23,000 disciplinary actions throughout the course of this data (almost all attributed to drinking or drugs), while WSU had just under 22,000.  Whitman came in above Gonzaga on this metric for a couple of years, but Gonzaga has remained consistently high since 2000.  This equates to a rate of about 50 disciplinary actions for 1000 students at Gonzaga, while WSU (known for its drinking and parties) hovers at less than 10.  Numbers for all universities other than GU and Whitman are often below 5 per 1000 for the duration of this data.  All in all, it’s clear that Gonzaga goes to great lengths to punish students for drinking and drug use. 

Another interesting metric I studied in this file is the change in crime rates at different universities before and after the COVID-19 pandemic.  The results were interesting.  The Seattle area universities (UW and Seattle U) had similar and notable increases in crime.  Both had a significant increase in violent crime rate (UW: +103% and Seattle U: +49%).  All of the other schools had a notable decrease in crime (WSU: -22.5%, WWU: -22.3%, Whitman: -34%) while Gonzaga had a slight increase in crime of +6%.  This tracks with the general knowledge that crime increased dramatically in large cities throughout the pandemic.  However, I want to note an interesting caveat with this trend.  When looking at data visualizations. It appears that crime rates normally dropped significantly when the pandemic kicked in.  In reality, crime rates were much lower in the early 2000s and began rising across the board around 2010.  There appears to be a notable spike in all crime around 2017-2020.  Ultimately, the analysis of average per-capita violent crime rates before and after the pandemic does not tell the whole story. 

A final interesting note regards the violence again women (VAW) data.  Data was pretty steady until reported incidents of violence again women on college campuses skyrocketed in 2017.  Interestingly, 2017 was also the year that the #metoo movement gained popularity.  I hypothesize that this large increase in reports was not solely from an increase in crimes against women, but rather shows that there was a renewed focus on sexual assault and violence against women during this time.  The rate of VAW dropped significantly with the pandemic in 2020 (likely due to social distancing), but at the end of the data in 2022 showed a significant rise from 2021. 

All in all, I think this was an extremely interesting data set.  It showed us that Whitman University strangely has the most crime per capita by a sizeable margin. 
 Additionally, we can see how Gonzaga continues to issue disciplinary action to students at far higher rates than other universities.  Further, we can clearly see how crime at universities has changed over time and how reporting on violent acts against women has changed significantly with changes in the social climate.  I believe there is much more than can be gleaned from this data, and urge you to take a look through it and see which insights you can find!


## Directions on How to Run it Yourself. 
1.  **Click** on this link [here](https://github.com/BrandonDuBois1/Malloy-TSA) 
2.   **Click** on the file that ends with '.malloyNB'.
3.   **Type** the period key (" . "). 
4.   **Click** the Run All button on the top of the page. 
5. All information will be loaded and you may look at the whole analysis.


## Code

This repository contains one Malloy code file:
- [`WA_university_crime.malloynb`], this file performs the analysis on the TSA data.
- 
This repository contains 4 CSV files:
- [`arrests.csv`], contains the arrest data for all of the analyzed schools.
- [`offenses.csv`], contains data of criminal offense counts and types for each of the analyzed schools.
- [`disciplinary_actions.csv`], contains data of disciplinary actions reported from each of the analyzed schools.
- [`vaw.csv`], contains data regarding violence against women reported from each of the analyzed schools.

## Licensing 

The data files are provided by the US Department of Education via their Campus Safety and Security annual reporting.  

## Visualizations
This graph shows the arrests per-capita at each of the universities.  It is broken out by location of arrest.
![Image](https://github.com/user-attachments/assets/78bfb54a-b444-4495-9fbb-36a4371f2029)

![Image](https://github.com/user-attachments/assets/9894952c-26f4-4931-9b06-8327758be7e0)

![Image](https://github.com/user-attachments/assets/61467b4f-21b7-4bb5-9644-410567179dac)

![Image](https://github.com/user-attachments/assets/9d8ec6b1-6e2d-4d2d-b821-73f005137194)

![Image](https://github.com/user-attachments/assets/abecec88-c8cc-4276-a866-5cdce70f10ba)

![Image](https://github.com/user-attachments/assets/95f1c1fa-3ddf-4520-8c4d-ce8433b9f7d3)
