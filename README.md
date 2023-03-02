# azure_rest_api

This page holds a short experient to see how a RESTful API would be built using Azure functions and .NET

The endpoint is here: 

GET https://azuretestfunctionrestapi.azurewebsites.net/api/tasks - list all tasks (must post a task, to get something back)

GET https://azuretestfunctionrestapi.azurewebsites.net/api/task/{{task ID}} - list a tasks (must post a task, to get something back)

POST  https://azuretestfunctionrestapi.azurewebsites.net/api/task - create a task
    body-> { taskDescription: "Testtask"}
    
PUT https://azuretestfunctionrestapi.azurewebsites.net/api/task/{{task ID}} - update a task
    body-> { isCompleted: true}    
    


