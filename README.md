# Office 365  - Hack Productivity 3
## Inspiration
I observed that lot of QA, Dev, and teams were struggling while testing rest API calls. They make rest api call from one tool and document on another tool. How cool it would be if we make rest call, test rest call and document those request/response payloads from single tool.  

## What it does
ExcelPost is capable of making REST calls from Excel spreadsheet. It also helps to document those request and response payloads

## How I built it
I have built it using HTML, CSS, JQuery, Microsoft apis

## Challenges I ran into
I was alone working on this hack. I did not have clear idea and direction till the last moment.Everything was new to me. 

## Accomplishments that I'm proud of
Finally I alone made it and developed Microsoft add in.I learned and implemented.

## What I learned
* HTML
* CSS
* JQuery

## What's next for ExcelPost
I am going to add some more methods and functionality. Would also work on promoting this add in

## Testing instructions:

Please use below provided data for Testing:

Sample data 1:

* Enter Rest Endpoint.
* Select "Get" method.
* Hit "Send" button and check response payload in.

* Rest Endpoint - https://reqres.in/api/users?page=2
* Method - GET

* Response Payload -
{
    "page": 2,
    "per_page": 3,
    "total": 12,
    "total_pages": 4,
    "data": [
        {
            "id": 4,
            "first_name": "Eve",
            "last_name": "Holt",
            "avatar": "https://s3.amazonaws.com/uifaces/faces/twitter/marcoramires/128.jpg"
        },
        {
            "id": 5,
            "first_name": "Charles",
            "last_name": "Morris",
            "avatar": "https://s3.amazonaws.com/uifaces/faces/twitter/stephenmoon/128.jpg"
        },
        {
            "id": 6,
            "first_name": "Tracey",
            "last_name": "Ramos",
            "avatar": "https://s3.amazonaws.com/uifaces/faces/twitter/bigmancho/128.jpg"
        }
    ]
}

Sample data 2:

* Enter Rest Endpoint.
* Select "Post" method.
* Enter request payload.
* Hit "Send" button and check response payload.

* Rest Endpoint - https://reqres.in/api/users
* Method - POST
* Request payload - 
{
    "name": "morpheus",
    "job": "leader"
}

* Response payload -
{
    "name": "morpheus",
    "job": "leader",
    "id": "263",
    "createdAt": "2017-12-19T14:28:21.400Z"
}
