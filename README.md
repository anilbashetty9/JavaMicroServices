# JavaMicroServices
Microservices Java project

## Build Application
mvn clean package

## Run the jar file
java -jar target/demo-thorntail.jar

## Test results

### Header:
{
  "Content-type": "application/json"
}

### Request:
{
  "name": "Anil",
  "message": "Anil"
}

### Response:
{
  "name": "Anil",
  "message": "Hello, 'Anil' from student-VirtualBox/25911@student-VirtualBox",
  "date": "09-06-2019"
}
