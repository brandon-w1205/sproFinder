# sproFinder

sproFinder is a an application that finds coffee shops nearby you. Using Google Maps, sproFinder will search for the nearest coffee shops based on a user-given address.

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
|GET         | /user          | shows user information  | 
|POST        | /user/new      | creates a new user   |
|PUT         | /user/:id      | edits specific user  |
|DESTROY     | /user/:id      | Deletes user         |

|method      | action         | description          |
|------------|----------------|----------------------|
|GET         | /location      | shows map            | 
|POST        | /location/new  | uploads a new map    |
|PUT         | /location/:id  | edits location       |
|DESTROY     | /location/:id  | Deletes map          |

|method      | action         | description          |
|------------|----------------|----------------------|
|GET         | /reviews       | shows reviews        | 
|POST        | /reviews/new   | uploads a new review |
|PUT         | /reviews/:id   | edits a review       |
|DESTROY     | /reviews/:id   | Deletes a user review| 

## Wireframe
![image](https://user-images.githubusercontent.com/110140349/189816680-da321c11-b97d-4e90-89fb-313310f4b399.png)

![image](https://user-images.githubusercontent.com/110140349/189817139-2470d88d-6e6d-4e03-ae46-0c94b73045a0.png)

![image](https://user-images.githubusercontent.com/110140349/189817457-71fb9931-039d-4a33-b804-24d5a2669dac.png)

## MVP
* Have a fully functioning HTML and Javascript with controllers
* Have models set up
* Successfully integrate the API
* Have a working map that searches for coffee shops by address given
* Allow user to have account for address saving and review saving
* Allow user to view reviews by them
* Allow user to edit reviews and location of map
* Allow user to change account info or delete

## Stretch Goals
* Proper CSS Styling
* Implement curated coffee map from Reddit Google Map
