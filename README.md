# Vita Group - Inventory Page Coding Challenge

Thanks for taking the time to do our front-end / full-stack coding test. The challenge has two parts:

1) a [task](#task) to create a basic flight results front-end site to show flight prices

2) some [follow-up questions](./FOLLOW-UP.md)

### This challnege is time boxed to 2 hours maximum.

----

You will be graded based on the following have been met:

* Your implementation works as described in the [task](#task).

* Your solutions coding design.

----

## Prerequisites/Environment Setup

This task will be using algolia as it's data source, you can find all infomration on how to use this tool by viewing the following page.
https://www.algolia.com/doc/api-client/getting-started/install/javascript/?client=javascript

Hint: You should be looking at the search functionality to retrieve data.


### Algolia API Key - d73141476465356695bf0ffb76c8107c
### Algolia Application ID - TBKK2F7Z8O

### Indices
- locations
- rooms

## Task

The task is to create an inventory page which displays every available room per location using algolia as it's data source.

### Criteria:

- All rooms should be grouped by location.
- Each section should have the location id as a the heading followed by the location address.
- Each room should be displayed as a card.
- Each room card should hold the following information.
  - Room Number
  - Room Type
  - Number of Beds
  - View
  - Price (With corresponding currency)
- Only available rooms should be displayed.
  
## Design

As this is a functional task there is only 1 design requirement, for the reviewer to be able to clearly view the page and it's content at the viewport widths:
- 380px
- 1280px

## Examples 

Example implementation: 

(This is an advanced example, please do not feel it necessary to add this amount of deisgn)
<img width="1087" alt="image" src="https://user-images.githubusercontent.com/49638882/183100251-b8a4328c-c7a3-4b37-b851-b7b3b653acdb.png">

Example Data:

### Indices
- locations
- rooms

### Location

{
  "location_id": "manchester",
  "name": "Manchester",
  "address": "8903 Superior Street",
  "objectID": "b035252d492ea_dashboard_generated_id"
}

### Room
{
  "room_number": 7638,
  "room_type": "Deluxe",
  "location_id": "manchester",
  "beds": 1,
  "view": "Pool",
  "price": 255.16,
  "currency": "GBP",
  "availability": "available",
  "objectID": "a20455fa179c1_dashboard_generated_id"
}

## Submission Guidelines

* The zip file should be named {yourname}.zip, and should itself contain the full-stack-recruitment-test project folder with your submission.

* The zip file should contain the [FOLLOW-UP.md](./FOLLOW-UP.md) file with answers to the follow-up questions.

* The zip file should **not** include the `node_modules` folder. (If Applicable)
