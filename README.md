# FFXIX_Server_Search_Application
This is a Server Application which accepts a GET search route and accepts a query parameter for a search by keyword. A POST search route that accepts a POST body with the id  for the user to make a selection upon returned search results. And a GET route utalizing  the file based database to return past search results to the user. The keyword is used to perform a search on the custom node module  utalizing the FFXIV API's search. This custom node module  accepts a user's command line arguments, and performs a search upon the FFXIV  database based on the keyword or term. This then returns  the search results for the user to make a selection and recieve further details for the selected item. 
## This application utalizing:
Node.js, Express 

Node plugins & dependencies: nodemon, cors, express, yargs, and superagent
