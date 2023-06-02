# AuctionService

## AuctionController

### Endpoint

Post an auction
this is the endpoint: (POST) http://localhost/4000/api/auction/create
Json Example for posting
{
    "Item": "139c132e-6fd5-44b8-a543-55aaddf71080",
    "StartTime": "2023-05-31T10:00:00",
    "EndTime": "2023-05-31T18:00:00",
    "StartingPrice": 50000
}

Get a list of auctions
this is the endpoint (GET) http://localhost/4000/api/auction/list

Get an auction from id
this is the endpoint (GET) http://localhost/4000/api/auction/{id}

Get Version
this is the endpoint (GET) http://localhost/4000/api/auction/version

# BidService

## BidController

### Endpoint

Post a Bid
this is the endpoint (POST) http://localhost/4000/api/bid/create
Json Example for posting
{
    "Amount": 65000,
    "Bidder": "3af9ef43-3906-4d2a-b608-a9c04c16e398",
    "Auction": "f842855f-8af8-4183-8fed-9eadc7b8a26c"
}

Get a bid from id
this is the endpoint (GET) http://localhost/4000/api/bid/{id}

Get Version
this is the endpoint (GET) http://localhost/4000/api/bid/version

# AuthService

## AuthController

### Endpoint

Post Login
this is the endpoint (POST) http://localhost/4000/api/auth/login
Json Example for posting
{
  "FirstName": "Michael",
  "LastName": "Sloth",
  "Email":"michaelsloth@email.com",
  "Password":"Password12345678"
}

# ItemService

## ItemController

### Endpoint

Post an Item
this is the endpoint (POST) http://localhost/4000/api/item/create
Json Example for posting
{
  "seller": "8426c7cd-8a91-4438-b55d-4fd7c13fbfbf",
  "Title": "Designer Chair",
  "Brand": "Armani",
  "Description": "Cotton and Leather blend",
  "CategoryCode": "CH",
  "location": "Aarhus"
}

Get a list of Items
this is the endpoint (GET) http://localhost/4000/api/item/list

Get an Item from id
this is the endpoint (GET) http://localhost/4000/api/item/{id}

Post an Item Image
this is the endpoint (POST) http://localhost/4000/api/item/uploadImage/{id}
use image file for posting 

Get Version
this is the endpoint (GET) http://localhost/4000/api/item/version

# UserService

## UserController

### Endpoint

Post an User
this is the endpoint (POST) http://localhost/4000/api/user/create
{
  "FirstName": "Michael",
  "LastName": "Sloth",
  "Email":"michaelsloth@email.com",
  "Password":"Password12345678"
}

Get a list of Users
this is the endpoint (GET) http://localhost/4000/api/user/list)

Get a User from id
this is the endpoint (GET) http://localhost/4000/api/user/{id})

Delete a User with Id
this is the endpoint (DELETE) http://localhost/4000/api/user/{id}

Get Version
this is the endpoint (GET) http://localhost/4000/api/user/version
