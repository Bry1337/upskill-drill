## Objective
- Write a simple iOS/Android mobile app. There is no time limit to complete this test however your speed, quality, and creativity will be greatly considered in the assessment. 
- The app will have 2 views: The Splash Screen, the Home Screen.

## Splash Screen
- The Splash Screen should display an `image` or `progress bar` for 2 sec before displaying the Home Screen.

## Home Screen
- Clicking back button should close the app.
- The Home Screen should display 2 buttons at the bottom of the screen which will be for List View and  Google Map View.
  - By List View, which means a view with a list.
- The List View should display the list of airports fetched by calling: https://raw.githubusercontent.com/mwgg/Airports/master/airports.json
- The Google Map View should display the airports.
- Clicking on an item on the list should ask you (in a popup) to: 
  - look for the airport in google
  - Save this airport to favorite.
- By clicking on "Look for" + airportName + " in google" should open google and search for this airport.
- By clicking on "Save this airport  to favorite" should save this airport locally. When launching the app and reloading the list, the saved item in the list should have a different background colour.
- The pin in the Google Map should have a different colour as well.
- Clicking on a saved item should display the popup with 2 options:
  - Look for the airport in google
  - Remove this airport from favorite.
- Only 1 item can be saved. An error message will be displayed.

## Submission
- You should fork this repository and send a `Pull Request` 
- PR `Title` should be in this format `{Name}, [Android,iOS]`
