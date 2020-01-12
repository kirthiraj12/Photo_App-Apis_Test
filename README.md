
# Instructions to develop, build, run , test and CI postman scripts using newman and docker 




Install 

npm install -g newman
or
brew install newman

Postman: 

newman : 
https://github.com/postmanlabs/newman

docker: 

npm: 


Training set 1: 


Training set 2: 


Training set 3 

Test runner collection in postman 

Run tests in Newman 

Run tests in docker 


Newman run: 
$ newman run examples/sample-collection.json

newman run com.kk.sample.postman.api.postman_collection.json  -e environments/host-fakejson.postman_environment.json  -r html,cli  --reporter-html-export reports/kk_sample_api_test.html  --reporter-html-template reports/templates/customTemplate.hbs



# Run Postman Collections Using Docker

install docker 

docker-compose build

docker-compose up




