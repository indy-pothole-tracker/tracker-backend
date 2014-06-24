API Documentation
=================

Create/Update a pothole (POST)

request url: http://localhost:8080/api/ReportPothole?api_key=##########

Example Requst Body:
{
"latitude":100.25233412,
"longitude":78.251234123,
"severity":6
}

Example Response:
"Success"
"Failure"
"Wrong API key"

Get All Potholes (GET)

request url: http://localhost:8080/api/GetAllPotholes?api_key=##########

Example Response: 
[{"severity": "6", "creator": "None", "createdate": "2014-06-24 17:50:32.331000", "number_of_reports": "1", "longitude": "78.251234123", "latitude": "20.125123"}, {"severity": "5", "creator": "test@example.com", "createdate": "2014-06-24 17:44:08.476000", "number_of_reports": "2", "longitude": "51.1623", "latitude": "12.1623341234"}, {"severity": "4", "creator": "test@example.com", "createdate": "2014-06-24 15:52:26.907000", "number_of_reports": "3", "longitude": "12.123456", "latitude": "12.123456"}, {"severity": "7", "creator": "None", "createdate": "2014-06-24 15:54:57.794000", "number_of_reports": "2", "longitude": "78.251234123", "latitude": "100.25233412"}]
