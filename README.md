# To Do API
<!-- 
Create
Read
Update
Delete -->

(Endpoints)
(GET? POST? PUT/PATCH? DELETE?)
(Need to define the request and response)

#APIs

## Get all the items

GET `/api/items/`

[
    {
        "id": 1,
        "item": "get some eggs",
        "completed": true
    },
    {
        "id": 2,
        "item": "get some beer",
        "completed": false
    },
]

## Create a new item

POST

{
    "item": "the name of the thing we're including"
}

## Delete an item

DELETE

## Update an item (completing a task, renaming etc.)

PATCH