# Analysis of road accidents in Belgium 2005-2018 

### Data source

-https://statbel.fgov.be/en/open-data.<br> -License: 'Licentie open data' which is compatible with the Creative Commons Attribution 2.0 license https://creativecommons.org/licenses/by/2.0
### Objectives 

-look for patterns/major contributors to deadly accidents<br>
-where and why do most deadly accidents occur?<br>
-visualize map per municipality using geopandas<br>
-model to make predictions<br>

## Current findings (project ongoing)

## Overview

* [Dynamic GIF with deathly accidents per year](#GIF-per-year)
* [Hour vs. day of the week](#Hour-vs.-day-of-the-week)
* [Accidents per hour](#Accidents-per-hour)
* [Accidents per day of the week](#Accidents-per-day-of-the-week)
* [Accidents per year](#Accidents-per-year)
* [Accidents per quarter](#Accidents-per-quarter)
* [Accidents per month](#Accidents-per-month)
* [Accidents per road type](#Accidents-per-road-type)
* [Accidents per area](#Accidents-per-area)
* [Accidents per collision type](#Accidents-per-collision-type)
* [Accidents per light condition](#Accidents-per-light-condition)
* [Mean deaths per year](#Mean-deaths-per-year)
* [Total deaths per municipality from 2005-2018](#Total-deaths-per-municipality-from-2005-2018)


## Dynamic GIF with deathly accidents per year

<p align="center">
  <img src="Plots/accidents_over_time.gif" width="700" height="550">
</p>

## Hour vs. day of the week 

<b>Noteworthy</b>: morning rush hour (8-9am), evening rush hour (5-6pm) and most accidents on friday.
<p align="center">
  <img src="Plots/joint_plot_dayow_hr.png" width="600" height="600">
</p>

## Accidents per hour

<b>Noteworthy</b>: morning rush hour (8-9am) and evening rush hour (5-6pm)
<p align="center">
  <img src="Plots/recorded_accidents_per_hr.png" width="800" height="450">
</p>

## Accidents per day of the week
<b>Noteworthy</b>: upward trend from monday to wednesday, thursday small drop with peak accidents on friday. Why? Do people get more tired when the week goes on? The drop on thursday due to working from home? Do people rush home on friday or exhausted from the week and therefor less concentrated? To do: plot hours for only friday.

<p align="center">
  <img src="Plots/recorded_accidents_per_dayow.png" width="800" height="450">
</p>

## Accidents per year
<b>Noteworthy</b>: downward trend.
<p align="center">
  <img src="Plots/recorded_accidents_per_year.png" width="800" height="450">
</p>

## Accidents per quarter
<b>Noteworthy</b>: second quarter peak due to holidays? Easter + start of summer holiday
<p align="center">
  <img src="Plots/recorded_accidents_per_quarter.png" width="800" height="450">
</p>

## Accidents per month
<b>Noteworthy</b>: second quarter peak due to holidays? 9th and 10th month due to bad weather conditions? To do:check for weather condition per month per municipality from 2005-2018

<p align="center">
  <img src="Plots/recorded_accidents_per_month.png" width="800" height="450">
</p>

## Accidents per road type

<p align="center">
  <img src="Plots/road_type.png" >
</p>

<b>Translation</b>: xlabels<br>

1=regional road<br>
2=provincial road or municipal road<br>
3=motorway<br>

## Accidents per area

<p align="center">
  <img src="Plots/area.png" >
</p>

<b>Translation</b>: xlabels<br>
1 = outside built-up area (buiten de bebouwde kom)<br>
2 = inside built-up area (binnen de bebouwde kom)<br>
3 = not available<br>

## Accidents per collision type


<p align="center">
  <img src="Plots/collision_type.png" >
</p>

<b>Translation</b>: xlabels<br>
1=Lateral<br>
2=Against an obstacle on the road<br>
3=Chain collision (4 drivers or more)<br>
4=From behind (or side by side)<br>
5=One driver/no obstacle<br>
6=Frontal impact (or when crossing)<br>
7=Against an obstacle on the road<br> 
8=With a pedestrian<br>


## Accidents per light condition

<p align="center">
  <img src="Plots/light_condition.png" width="800" height="450">
</p>

<b>Translation</b>: xlabels<br>
1 = broad daylight<br>
2= lit public lighting<br>
3= not available<br>
4= dawn / dusk<br>
5= night / no public lighting<br>


## Mean deaths per year

-From all the accidens occuring, these graph represents the ratio of fatalities.<br>

<b>Beware of the different scale per plot</b>

<p align="center">
  <img src="Plots/mort_inj_over_time.png">
</p>

## Total deaths per municipality from 2005-2018

<p align="center">
  <img src="Plots/BE_mun.png" width="700" height="550" >
</p>

<b>Top 10</b>:

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















