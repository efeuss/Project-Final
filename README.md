# Project-Final

## Project Firefly
Attempting to find any weather correlations with the predicted or actual peak firefly mating dates. Using exploratory data analysis to determine what weather patterns to focus on.

Using climate data from NOAA obtained from the climate data online search (https://www.ncdc.noaa.gov/cdo-web/search) centered around the weather center in Morristown, TN. Includues other related cities, all about 1.5 miles north, northeast, or northwest from the Elkmont area of the Great Smoky Mountain National Park where the synchronous fireflies put on their annual mating lightshow.

**References for these notes**
- Great Smoky Mountain National Park (GSMNP) spans Tennessee and North Carolina
- Elkmont is a campground/area within GSMNP where the firefly display is most concentrated

## Firefly Mating Data
I compiled this data myself, from a mix of National Park Service (NPS) data regarding firefly lottery viewing dates and a paper studying predicting mating dates that shows peak mating dates. Between these two pieces of data, I have firefly dates from 1993 - 2005 & 2014 - 2023. The event in 2020 was canceled due to COVID-19, but a surmised date range was calculated based on virtual events surrounding the annual show.

The imported data is START and END dates. This is based off the dates the NPS provided. This was related to the above paper by considering GOOD to be the START and PEAK + 1 day to be the END. "Good displays occur when at least 50% of males have emerged." [1] So I chose PEAK + 1 day to match with NPS END dates because I assume the lightshow will still be desirable to watch as the peak tapers out.

(Because peak nights can span 2 - 5 days depending on weather conditions, only the final night of maximum male display was recorded for this study (this date was referred to as “peak display”) [1] but I wanted to try to align this a bit with the extended windows of NPS dates offered to guests).

## Research Questions
1. How much snowfall was there November 1998 - April 1999 that might have caused the short 1999 season?
    - Let's compare vs. snowfall November 2002 - April 2003 to look at longest season
    - Will compare by each month and then total "winter season"<br><br>
2. Our latest "start date" is June 11th in 1993. Let's look at spring rainfall and see if this causes an impact
    - Let's compare vs. spring rainfall in 2003, our earliest date at May 28th
    - We may also want to consider water equivalent of snowfalls in March<br><br>
3. Current firefly peak date estimations use degree days, which is a comparsion of the measurement vs. the average set point for that location. Degree Day base starting March 1 is 45F. How many days in April were above 45F for each year? Does this correlate at all with START date?<br><br>
4. The short season of 1999 and the long season of 2003:
    - What was the rainfall in May & June these years?
    - What was the daily average temperature?
    - Anything to explain the difference in length?<br><br>
5. I'm interested in our latest END dates, at June 22 1997 (also let's look at June 20, 1993) - could weather in June be related to this? Degree Day base for June is 50F, or let's also consider daily or monthly rainfall.

## Works Cited
[1] Lynn F. Faust, Paul A. Weston, Degree-Day Prediction of Adult Emergence of Photinus carolinus (Coleoptera: Lampyridae), Environmental Entomology, Volume 38, Issue 5, 1 October 2009, Pages 1505–1512, https://doi.org/10.1603/022.038.0519

[2] Degree Days https://www.eia.gov/energyexplained/units-and-calculators/degree-days.php



