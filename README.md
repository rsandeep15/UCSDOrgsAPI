# UCSD Students Orgs API 
A Node.js Script to get all student organizations at UCSD

GET /update
- Returns a live list of active student organizations at UCSD as a JSON array. 
Live Demo: http://52.38.85.90/update

GET /details/:orgId
- Returns the org name and the details of the organization as a JSON object, given an orgId.
Live Demo: http://52.38.85.90/details/6589

Simply run `node app.js` and navigate to endpoint on your browser for local testing. 
App runs on port 3000 by default.
