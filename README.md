
## Welcome to the workshop

For this session you will need 

Postman 
Newman 
Docker 
Any UI editor ( IntelliJ, VSCode etc) 

## Application Installation 
- Install Newman

npm install -g newman
or
brew install newman

- Install Postman 

https://www.getpostman.com/downloads/

- Install newman 
https://github.com/postmanlabs/newman

- Install docker: 

## Training 

Training set 1:  Manual API testing 

Training set 2: Automated API Testing 

Training set 3: 

  Test runner collection in postman 

  Run tests in Newman 
  
# Run test in newman   

Go to your source folder 

Type the following command
newman run com.kk.sample.postman.api.postman_collection.json  -e environments/host-fakejson.postman_environment.json  -r html,cli  --reporter-html-export reports/kk_sample_api_test.html  --reporter-html-template reports/templates/customTemplate.hbs

# Run the tests in Jenkins 

# Run the tests in Docker 

dockerfile 

Running The Collection in docker 

To run this collection from the command line, assuming you have Docker running on your flavour of OS, type the following:
docker-compose build

docker-compose up
This should pull the node image and install all the components you need, before running through the checks.

Following the collection run, you will still have the restful_booker_checks container created, if you wish to removed this, you can use the following command:

docker-compose rm -f



