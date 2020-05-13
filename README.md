# Exploration dataset road accidents in Belgium 2005-2018

Source: https://statbel.fgov.be/en/open-data

This data is made available under the 'Licentie open data' which is compatible with the Creative Commons Attribution 2.0 license https://creativecommons.org/licenses/by/2.0

## Current findings (project ongoing)

### 1. Accidents per hour

<b>Noteworthy</b>: morning rush hour (8-9am) and evening rush hour (5-6pm)
<p align="center">
  <img src="Plots/recorded_accidents_per_hr.png">
</p>

### 2. Accidents per day of the week
<b>Noteworthy</b>: upward trend from monday to wednesday, thursday small drop with peak accidents on friday. Why? Do people get more tired when the week goes on? The drop on thursday due to working from home? Do people rush home on friday or exhausted from the week and therefor less concentrated? 
<br><b>To do list +=</b> plot hours for only friday.
<p align="center">
  <img src="Plots/recorded_accidents_per_dayow.png">
</p>

### 3. Accidents per year
<b>Noteworthy</b>: downward trend.
<p align="center">
  <img src="Plots/recorded_accidents_per_year.png">
</p>

### 4. Accidents per quarter
<b>Noteworthy</b>: second quarter peak due to holidays? Easter + start of summer holiday
<p align="center">
  <img src="Plots/recorded_accidents_per_quarter.png">
</p>

### 5. Accidents per month
<b>Noteworthy</b>: second quarter peak due to holidays? 9th and 10th month due to bad weather conditions? 
<br><b>To do list +=</b> check for weather condition per month per municipality from 2005-2018

<p align="center">
  <img src="Plots/recorded_accidents_per_month.png">
</p>

### 6. Change of mean values of time

-dead = number of accidents with dead<br>
-deadafter30d = number of accidents dead within 30 days<br>
-mortallyinjured = number of accidents with mortally injured<br>
-severlyinjured = number of accidents with severely injured<br>
-slightlyinjured = number of accidents with slightly injured<br>

<b>Beware of the different scale per plot!</b>

<p align="center">
  <img src="Plots/mean_accidents_mort_inj_over_time.png">
</p>

### 7. Total deaths per municipality 2005-2018
<b>Noteworthy</b>: Top 10

-Antwerp 199<br>
-Gent 142<br>
-Namur 130<br>
-Doornik 126<br>
-Charleroi 122<br>
-Liege 118<br>
-Mons 111<br>
-Bruxelles 78<br>
-Brugge 70<br>
-Genk 65<br>
<br><b>To do list +=</b> why? Amount of inhabitants/munic. contribution
<br><b>To do list +=</b> why? Amount of people traveling there for work.
<br><b>To do list +=</b> barplot top 10 per year

<p align="center">
  <img src="Plots/BE_mun.png">
</p>


### Changing deaths per municipality (gif)
<p align="center">
  <img src="Plots/gif/accidents_over_time.gif">
</p>














