# wiremock-webinar
all examples used for the wiremock webinar

1) mvn clean install
it will download wiremock standalone library

2) docker build -twiremock-demo:latest .
it will creates a docker image for wiremock with mappings and files

3) docker run -p8080:8080 wiremock-demo:latest
it will run the docker image on port 8080

4) you'll need to import in postman the collection in /postman for examples

if you want to test the weatherstack API before, you need to create an account on http://weatherstack.com. Then you'll receive a token to add in your json requests. 

Examples will show : 

try a simple get on an pre-configured mapping
search for all existing mappings
search for all existing requests
search for all existing unmatched requests
reset requests logs
create on the fly a mapping with less priority for 404
get the 404
create a negative cases (reached limited usage of API) mapping
get reached limited usage
create scenario for hello world example
get scenario
test hello world examples
reset state of scenarios


