# sproFinder

sproFinder is a an application that finds coffee shops nearby you. Using Google Maps, sproFinder will search for the nearest coffee shops based on a user-given address.

## Installation

Run ```npm i``` to download the required dependencies

## Approach

Utilizing Map Box, I plan to utilize a coffee tag to search for nearby coffee shops at convert the search to geocoordinates that can place markers down in areas nearby a given address. Possibly, I would like to use a premade google maps featured here: https://www.google.com/maps/d/u/0/viewer?mid=1M7VXYjEpJaxGUBaPl9dqrd-P6gM&ll=19.459788526805003%2C7.610340000000008&z=2 (taken from reddit.com/r/coffee) to have a pre-selected group of coffee shops curated by users on reddit.

## Proof of API connection
https://api.mapbox.com/v4/mapbox.mapbox-streets-v8/2/0/1.mvt?access_token=[accesstokenhere]

![image](https://user-images.githubusercontent.com/110140349/189812703-0ba9e6ec-c2d9-46c4-944e-ffb015350fb4.png)


## ERD
![image](https://user-images.githubusercontent.com/110140349/189814158-5925ade4-e0b3-4e78-bbde-6bd0ad4cd924.png)

## REST Chart

|method      | action         | description          |
|------------|----------------|----------------------|
|get         |                |                      |      
