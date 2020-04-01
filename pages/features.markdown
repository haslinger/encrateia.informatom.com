---
layout: post
title: Features
permalink: /features/
---

The app can hold data for several activities simulaneously.
But you could also split the activities in public activities, that you do
share with Strava and private ones, that should be kept seperately.

(For this you currently connect to the same account twice, but you don't import
the activities in the second account. You just upload them via the application's
documents directory on your mobile device.)

## 1. Features on Athlete Level

* list of activities
* import Activities back a certain number of days (can be in- and decremented in
7 day steps)
* power (plot): Only available, if you have tracked activities with a Stryd
  powermeter.
* power per heart rate (plot)
* stride ratio (plot): Length of your steps over vertical oscillation
* power ratio (plot): (Power minus form power) over power in percent.
  Answers the question: Which percentage of your energy and power goes into
  lateral movement.
* speed over heart rate (plot)

* The plots above display a linear weighted gliding average of the last 30 days.

## 2. Features on Activity Level

* numeric and textual metadata
  * on the overview view
    * time created
    * moving time
    * distance
    * average pace
    * max pace
    * total calories
    * total ascent
    * total descent
    * climb
    * average heart rate
    * max heart rate
    * average steps per minute
    * max steps per minute
    * total training effect* heart rate (plot)
  * on the metadata view
    * title
    * timestamp
    * last event
    * total strides
    * average running cadence
    * maximum running cadence
    * average temperature
    * maximum temperature
    * average vertical oscillation
    * total fractional cycles
    * total timer time
    * strava id
    * garmin id
    * activity type
    * sport
    * sub sport
    * event timer
    * trigger
    * number of laps
    * number of sessions
    * average fractional cadence
    * maximum fractional cadence
    * start position
    * north east corner of bounding rectangle
    * south west corner of bounding rectangle
    * average speed
    * maximum speed
* power (plot)
* power duration diagram (the time axes has logarithmic scale)
* speed over heart rate (plot)
* form power (plot)
* vertical oscillation (plot)
* cadence (plot)
* power over heart rate (plot)
* ground time (plot)
* power ratio (plot, s.a.)
* stride ratio (plot)
* leg spring stiffness (plot)
* list of laps (if laps have been recorded)
  * number
  * heart rate
  * pace
  * power
  * distance
  * ascent

## 3. Features on Lap Level

* numeric and textual metadata
  (as provided by the .fit-file, no plausibility checks)
  * on the overview view
    * start time
    * distance
    * average pace
    * max pace
    * total calories
    * total ascent
    * total descent
    * climb
    * average heart rate
    * max heart rate
    * average steps per minute
    * max steps per minute
    * total strides
  * on the metadata view
    * Lap number
    * timestamp
    * event
    * sport
    * sub sport
    * event type
    * event group
    * avg vertical oscillation
    * total elapsed time
    * total timer time
    * average stance time
    * average stance time percent
    * lap trigger
    * average temperature
    * maximum temperature
    * average fractional cadence
    * maximum fractional cadence
    * total fractional cycle
    * start position
    * end position
    * intensity
    * average speed
    * maximum speed
* heart rate (plot)
* power (plot)
* power duration diagram (the time axes has logarithmic scale)
* ground time (plot)
* leg spring stiffness (plot)
* form power (plot)
* vertical oscillation (plot)
* cadence (plot)
