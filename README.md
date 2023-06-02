# P05_Communicate_Data_Findings
This is the final project to complete the Data Analyst Nanodegree at Udacity.

## Project Overview
This [project](Part_1_Exploratory_Dataviz.ipynb) comprises two parts. In the first one, 
with the help of **Exploratory Data Visualization**, I better understood the data I was
working with. Meanwhile, the second focused on **Explanatory Data Visualization** that 
I used to communicate my analysis findings through a slide deck. To access the slides, 
download the [file](Part_2_Explanatory_Dataviz.slides.html) and open it in a web browser.

### Data set

This data set contains information on a bike-sharing system in the San Francisco Bay Area. 
It includes the duration, the start, and the end of the trips, as well as information 
about the users of the system.


### Summary of Findings
The exploration brought light to the usage dynamic of the service along the week 
and along the day. There is a significant variation when we compare the periods of the week. 
Weekdays are usually busier and are characterized by two peaks of usage, which represent the 
home-work-home routine. Weekends have just one peak that is almost a plateau in the late 
morning and in the afternoon. Besides, they present longer trips and younger people using 
the service. In this analysis, I limited to user age at 90 years old and the duration of 
the trips at 50 minutes. Interestingly, there is a weak correlation between these two 
numeric variables. 

In this process, I came across the huge gender gap existing among the users of the service. 
Interested in this fact, I made further investigations trying to understand the behavior 
of this feature when compared with the other variables of interest. I ended up concluding that
trips made by Male individuals are shorter than those made by the other genders in all days 
of the week. The same tendency is verified in an hourly basis. In addition, it seems that the 
gender distribution is quite constant on weekdays. On the other hand, I noticed that, on weekends, 
for a period of time the gender gap decreases. As stated in the analysis, a possible reason 
for the gender gap is that womem feel unsafer to cycle.


### Key Insights for Presentation
The presentation will focus on the usage dynamics along the week and along the day, considering 
the different genders included in the data set, as well as the duration. I won't include other 
features analyzed in the exploratory analysis. 

First, I introduce the overall gender distribution. Following that, I present the duration distribution. 
Afterwards, I look at the variation on the number of trips in each time of the day considering the 
difference between weekends and weekdays.

Next, I compare with point plots the duration of the trips along the week and along the day 
for each gender. And finally, I present the usage dynamics along the day on Thursdays and
on Saturdays, taking into account each gender.

## Libraries required
* NumPy
* pandas
* Matplotlib
* Seaborn

## Author
* Affonso Ciekalski Soares Campos

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.
 
