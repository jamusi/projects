# SONR


## Introduction

Tired of not knowing where the beer guy is at the music festival? WE KNOW.


## Description

### what it does

We track the position of nearby devices using
[Cisco Meraki wireless access points](https://meraki.cisco.com/products/wireless) 📡.
By associating your device with our platform (in this hackaton, WIFI MAC address <-> PixelsCamp user),
we are able to locate each device in the venue and offer a rich experience:
* the user can add friends and subscribe additional POIs (example: beer-selling dudes).
* the user can explore the venue map and locate friends and services (not only static POIs, also relevant moving devices such as BEEEEEER 🍺).


### audience

On large events it gets hard to track your friends and services (such as beer-hose backpack dudes).
We provide a simple way for users to register, add friends and look for services (such as beer).
There is also extremely interesting info the organization can obtain:
* the path the user took 🚶,
* how long he spent in each part of the venue,
* estimate very crowded places (heat map),
* serve targeted advertisements 💰.💰.


### tech stack

* We make use of the Cisco Meraki infrastructure in the booths hall (and have been helping out in its setup and calibration).
* Simple [node.js](https://nodejs.org/) HTTP server which is the Cisco endpoint target,
receiving the Meraki payloads. This server also exposes the payload outward so we can
easily consume it (or a subset of it).
* The client application is a web app using (so far):
  * [leaflet](http://leafletjs.com/) for rendering the map
  * plain old javascript, HTML, CSS


## Team

 * José Pedro Dias https://pixels.camp/JosePedroDias
 * João Nabais     https://pixels.camp/jlnabais
 * Vítor Teixeira  https://pixels.camp/vitor-teixeira
 * Bruno Tavares   https://pixels.camp/anmo


## Code repository

https://github.com/JosePedroDias/sonr