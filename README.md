## DemoProjectRepository Collaborated by 

Tools Used: SOAPUI Free Version, Groovy.
project is scripted by using Groovy for automation of GET, POST, PUT, DELETE Request

- GET: Fetches all the Data

- POST: Adds the Data

- PUT: Edits the Data by ID

- DELETE: Deletes the Data by ID

## Student API Testing Project
Here are links for REST API

- [Link for GET] (http://thetestingworldapi.com/Api/GET-api-studentsDetails)

- [Link for PUT] (http://thetestingworldapi.com/Api/PUT-api-studentsDetails-id)

- [Link for POST] (http://thetestingworldapi.com/Api/POST-api-studentsDetails)

- [Link for DELETE] (http://thetestingworldapi.com/Api/DELETE-api-studentsDetails-id)

 
## Status Code For PUT Request

- 204 for OK (but no content)

- 200 for OK with Body (Updated response)

- 400 if the supplied data was invalid

## 
### REST API example:

Endpoint	http://thetestingworldapi.com/Api/PUT-api-studentsDetails/541697

HTTP Method Type	PUT

Body	{"id":"541697","first_name":"Varun","middle_name":"David","last_name":"Dhavan","date_of_birth":"24-April-1987"}

Success Response	Success Status code: 200 OK{"id":"541697","first_name":"Varun","middle_name":"David","last_name":"Dhavan","date_of_birth":"24-April-1987"}

Note: The Student ID 541697 used in the example, has been previously created as a resource on the server. In addition to this, we will update the associated Student information in the PUT request.
