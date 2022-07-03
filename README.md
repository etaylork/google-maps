# Google Maps API Project

A practice project from the udemy course [Understanding Typescript](https://www.udemy.com/course/understanding-typescript). Project explains how to use third party libraries within typescript to send HTTP requests.

# Requirements

- Nodejs installed

- Google API key for Geocoding and Javascript Maps API's

# How to run application

1. Updated the GOOGLE_API_KEY variable in the `src/app.ts` file

2. Updated the script section in the `index.html` file where it says FIXME with the google API Key.

   ```html
   <script
     src="https://maps.googleapis.com/maps/api/js?key=${FIXME}&callback=initMap"
     async
     defer
   ></script>
   ```

3. Execute the following commands in the root directory of this repository.

   ```bash

   $ npm install

   $ npm start

   ```
