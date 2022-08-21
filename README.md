## project
https://trello.com/c/ztaX6iY7/19-read-articles-frontend
https://trello.com/c/q4DUW96Z/5-use-services-frontend
https://trello.com/c/Tzv72hYR/2-add-article-frontend


my work was about this things as forntend

 my work was about frontend and some backend first thing 
# add article about the city
2-create a component to collect  user input form with a submit button that takes data for the article
3-write a function to handle the article addition that sends a `post` request with the data as body to `(/blog)`
4-see services around the area so that i can better plant for my trip (car rental, airBnB, Tour Guide)
5-add buttons to show the services available in the area `car` `place` `guide`
6-when the user clicks the button, send a `get` request to the `(/service)`  with a query according to the button `(type=car)` `(type=place)` `(type=guide)` to query the services data from the DB
7-update the component state with received data
8-create a `component` for each service type (`carRental`, `placeRental`, `tourGuide`)  and the send the data to each component accordingly  
9-add a `route outlet` with paths (`'/car`, `/rental`, `/guide`) to render the components 
10-add articles about the city so that i can better prepare for my trip
11-(after landing page)add a link in the navbar to route `(/blog)` that leads to `Blog` component
12-when the component loads use `(componentDidMount)` to invoke a function that sends a  `get` request to the server at `(/blog)` to query article data from Database
13-update the state with articles data
14-map the data to render an element for each article
15-add a button that takes the user to the map page that renders the city that was mentioned in the article, the button path should contain the city name as query

