# Exploration-and-Explanatory-PISA-Data
This project is communicate data finding which the problems provided by Udacity. I completed this project as part of Udacity Nanodegree Program in Data Analyst (https://www.udacity.com/course/data-analyst-nanodegree--nd002). 

### Project Overview
Performance flights can be measure with number of Ontime, Delay, Cancelled, and Diverted Flights. This project want to analyze what the performance of flights in US at 2006 until 2007. The data can be found in http://stat-computing.org/dataexpo/2009/the-data.html

#### Library
To run this project, you need import library:
1. pandas
2. numpy 
3. matplotlib.pyplot 
4. seaborn

*to save into html slide, use file output_toggle.tpl, run this code in terminal:
***ipython nbconvert slide_deck.ipynb --to slides --template output_toggle.tpl  --post serve***

### Part of this project:
1. Wrangling:
https://github.com/RyMey/Exploration-and-Explanatory-Flight-Data/blob/master/wrangling.ipynb
 
2. Exploratory:
https://github.com/RyMey/Exploration-and-Explanatory-Flight-Data/blob/master/exploration.ipynb
 
3. Explanatory:
https://github.com/RyMey/Exploration-and-Explanatory-Flight-Data/blob/master/slide_deck.slides.html

### Summary
In three years, <b>the worst performance was delayed</b> by a total of <i>~ 3 million flights</i>, and then canceled with <i>4 hundred flights</i>, and diverted with <i>50 thousand flights</i>. From <i>21,604,865 total flights</i> in three years, the delay has a proportion of <i>13%</i>, canceled has <i>1.94%</i>, and diverted has <i>0.23%</i>. But from all bad performance schedule flights, the proportion of delay is <i>86.4%</i>, Cancelled <i>12.1%</i>, and diverted 1.5%. <b> The most delayed Origin is PUB (Pueblo) </b>, PIR (Pierre), ADK (Adak Island). <b>The most Ontime is HVN (new Haven)</b>, GLH (Greenville, MS), and MKC (kansas City Donwtown). In three years, <b>the most cancelled Origin is TEX (Telluride)</b>, ALO (Waterloo), HKY (Hickory Regional). <b>The most not cancelled is PIR (Pierre)</b>, HVN (new Haven), and PUB (Pueblo). <b>The most diverted Origin is ADK (Adak Island)</b>, HLN (helena,Montana) , SIT (Sitka, Alaska). <b>The most not diverted is SMX (Santa Maria)</b>, VLD (Valdoka), BQK (Brunswick). The departure and arrival correlations are very hight, so the highest option is when one of other Delay so the other will also be delayed. If the flights has departure delay, so the highest possible is flights arrival will be delayed. But some flights doesn't Delay in departure have delay in arrival.The most reason of Cancelled flights in each year is carrier. In <b>some month like Desember, and Februari, many flights was cancelled because of Weather</b>. So it may can be consideration from customer if they want to buy some ticket in that month. <b>From the trends, delayed and cancelled is decrase but flights diverted is increase over year.</b>
