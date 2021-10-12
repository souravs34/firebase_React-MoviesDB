# react-firebase-MoviesDB


| Rest API | GraphQL API |
| --- | --- |
| Multiple Endpoints (Get/users,POST/product) | One Endpoint Only (POST/graphql) |
| (JSON) Data is Exchanged | (JSON) Data is Exchanged |
| Any server-side Language,any Frontend Framework | Any server-side Language,any Frontend Framework |
| Stateless | Stateless |
| POST/user {name:'Max'} | POST/graphql {query:'query'} |


### JSON :-  Specific format for exchanging data.

###  JSON to Javascript object: 
              
                response.json()
 
### Javascript to JSON:

                JSON.stringify(<variable>);
                
### Try Catch Block

            Catch Block only runs if there is data.movies is undefined and does not check for the error status code.
            So we check here error status code by response.ok and then throw error hence running catch block too.

### Firebase: 
                Service offered by google consisting of many products and services.
