Firstly I set the arrays of constants for the location & corresponding data, to the useState Hook set to empty objects and strings.
The URL for the API (from OpenWeather) contains the output value for the location the user would enter in the input at the top.

I set a 'SearchLocation function for the event in which a location is searched the the 'Enter' key is pressed, so the corresponsding response data from the API would be set as the Data. I imported Axios for the HTTP requests. I assingned the function to the onKeyPress function pointer. I also assigned the input value to change & assigned it to the onChange function pointer.

Then for the different data points, I inputed between the <p> tags, the dynamic objects for which the correspondging values from the API calls would be rendered, e.g data.name...

I chose a simple background & theme.