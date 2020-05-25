# Scene It
![Image description](assets/Scene-It.png)
## Contents
- [What It Is](#What-It-Is)
- [What I Used](#What-I-Used)
- [Challenges and Solutions](#Challenges-and-Solutions)
- [Minimum Viable Product](#Minimum-Viable-Product)
- [Stretch Goals](#Stretch-Goals)
- [Screenshots](#Screenshots)
- [Code Examples](#Code-Examples)
## What It Is
Using the OMDb API, Scene It allows a user to search for any movie in the API and save that movie to their personal
watchlist via local storage in the browser. The user is able to switch back and forth between their watchlist and the movie search page. 

I used Axios and Promise Objects to make requests to the OMBb API, and render functions with template literals and Bootstrap to format the JSON data coming back from the API.
## What I Used
- JavaScript
- jQuery
- Axios
- Bootstrap
- HTML/CSS
## Challenges and Solutions
- Challenge #1: Requesting and Handling Data from an API <br />
This project was my first experience requesting data from an API, handling the response, and formatting the response data in a way that is useful and aesthetically pleasing to the user. I learned how to pass requests for specific data based off a user's seach to the API; this taught me how to read, comprehend, and implement API documentation. As a result of making requests this way I also had to learn about asynchronous JavaScript and Promises. I used the Axios library to make `.get` requests to the API, and used `.then` to handle the Promise Object that was returned from the request. 

- Challenge #2: Formatting and Rendering Data to the DOM <br />
The Promise Object from the `.then` method is passed to a render function. The render function uses template literals with inline Bootstrap to style the data. The necessary data for each movie, such as the movie image, title, year of release, and plot are accessed and saved using embedded expressions. The formatted data is then appended to the DOM using jQuery, i.e. `$('.movies-container').html(movieHTML);`.

- Challenge #3: Saving Data To and Loading Data From Local Storafe <br />
An additional challenge with this project was learning how to use local storage and understanding how to work with JSON data. I learned about methods such as `JSON.parse` and `JSON.stringify` to convert JSON data into a JavaScript Object and vice versa. I also learned to use local storage methods such as `localStorage.getItem()` and `localStorage.setItem()` to save the users' watchlist data to their browser. 
## Minimum Viable Product
## Stretch Goals
## Screenshots
## Code Examples
