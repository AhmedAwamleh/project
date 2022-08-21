# project
https://trello.com/c/ztaX6iY7/19-read-articles-frontend
https://trello.com/c/q4DUW96Z/5-use-services-frontend
https://trello.com/c/Tzv72hYR/2-add-article-frontend


my work was about this things as forntend

## my work was about frontend and some backend first thing 
### 1-add article about the city
### 2-create a component to collect  user input form with a submit button that takes data for the article
### write a function to handle the article addition that sends a `post` request with the data as body to `(/blog)`
### see services around the area so that i can better plant for my trip (car rental, airBnB, Tour Guide)
### add buttons to show the services available in the area `car` `place` `guide`
### when the user clicks the button, send a `get` request to the `(/service)`  with a query according to the button `(type=car)` `(type=place)` `(type=guide)` to query the services data from the DB
### update the component state with received data
### create a `component` for each service type (`carRental`, `placeRental`, `tourGuide`)  and the send the data to each component accordingly  
### add a `route outlet` with paths (`'/car`, `/rental`, `/guide`) to render the components 
### add articles about the city so that i can better prepare for my trip
### (after landing page)add a link in the navbar to route `(/blog)` that leads to `Blog` component
### when the component loads use `(componentDidMount)` to invoke a function that sends a  `get` request to the server at `(/blog)` to query article data from Database
### update the state with articles data
### map the data to render an element for each article
###add a button that takes the user to the map page that renders the city that was mentioned in the article, the button path should contain the city name as query

