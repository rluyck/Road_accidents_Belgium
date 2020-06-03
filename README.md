# Analysis of road accidents in Belgium 2005-2018 (ongoing)

### Beware

-Original dataset uses "dead" i.o. "death"<br>
-Project is ongoing, some plots may not look very nice, will be corrected for final results.

### Data source

-https://statbel.fgov.be/en/open-data.<br> -License: 'Licentie open data' which is compatible with the Creative Commons Attribution 2.0 license https://creativecommons.org/licenses/by/2.0
### Objectives 

-look for patterns/major contributors to deadly accidents<br>
-where and why do most deadly accidents occur?<br>
-create model to make predictions<br>

## Current findings (project ongoing)

(Parts still in Dutch will be translated to English)


### jointplot hour and day of the week (dow)

<b>Noteworthy</b>: morning rush hour (8-9am), evening rush hour (5-6pm) and most accidents on friday.
<p align="center">
  <img src="Plots/joint_plot_dayow_hr.png" width="600" height="600">
</p>

### Accidents per hour

<b>Noteworthy</b>: morning rush hour (8-9am) and evening rush hour (5-6pm)
<p align="center">
  <img src="Plots/recorded_accidents_per_hr.png" width="800" height="450">
</p>

### Accidents per day of the week
<b>Noteworthy</b>: upward trend from monday to wednesday, thursday small drop with peak accidents on friday. Why? Do people get more tired when the week goes on? The drop on thursday due to working from home? Do people rush home on friday or exhausted from the week and therefor less concentrated? To do: plot hours for only friday.

<p align="center">
  <img src="Plots/recorded_accidents_per_dayow.png" width="800" height="450">
</p>

### Accidents per year
<b>Noteworthy</b>: downward trend.
<p align="center">
  <img src="Plots/recorded_accidents_per_year.png" width="800" height="450">
</p>

### Accidents per quarter
<b>Noteworthy</b>: second quarter peak due to holidays? Easter + start of summer holiday
<p align="center">
  <img src="Plots/recorded_accidents_per_quarter.png" width="800" height="450">
</p>

### Accidents per month
<b>Noteworthy</b>: second quarter peak due to holidays? 9th and 10th month due to bad weather conditions? To do:check for weather condition per month per municipality from 2005-2018

<p align="center">
  <img src="Plots/recorded_accidents_per_month.png" width="800" height="450">
</p>

### Road type

<p align="center">
  <img src="Plots/road_type.png" >
</p>

<b>Translation</b>: xlabels in their respective order -
regional road, provincial road or municipal road, motorway, unknown



### Area

<p align="center">
  <img src="Plots/area.png" >
</p>

<b>Translation</b>: xlabels in their respective order -
outside built-up area, inside built-up area and not available

### Collision type


<p align="center">
  <img src="Plots/collision_type.png" >
</p>

<b>Translation</b>: xlabels in their respective order - 
Lateral, Against an obstacle on the road, Chain collision (4 drivers or more), From behind (or side by side), One driver/no obstacle, Frontal impact (or when crossing), Not available, Against an obstacle on the road , With a pedestrian 


### Light condition

<p align="center">
  <img src="Plots/light_condition.png" width="800" height="450">
</p>

<b>Translation</b>: xlabels in their respective order - in broad daylight, night / lit public lighting, not available, dawn / dusk, night / no public lighting


### Change of mean values over time

-dead = number of accidents with death<br>
-deadafter30d = number of accidents causing death within 30 days<br>

<b>Beware of the different scale per plot!</b>

<p align="center">
  <img src="Plots/mort_inj_over_time.png">
</p>

### Total deaths per municipality 2005-2018
<p align="center">
  <img src="Plots/BE_mun_cropped.png" width="700" height="550" >
</p>
<b>Noteworthy</b>: Top 10

-Antwerp (199)<br>
-Gent (142)<br>
-Namur (130)<br>
-Doornik (126)<br>
-Charleroi (122)<br>
-Liege (118)<br>
-Mons (111)<br>
-Bruxelles (78)<br>
-Brugge (70)<br>
-Genk (65)<br>
### GIF
<p align="center">
  <img src="Plots/cropped_accidents_over_time.gif" width="700" height="550">
</p>














