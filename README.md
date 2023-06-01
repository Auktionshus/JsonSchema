# AuctionService

## AuctionController

### Endpoint

Post ad auction
[this is the endpoint](https://localhost/4000/api/auction/create)
{
"Item": "f00d184f-4496-4629-aed4-ed9ea586f3cd",
"StartTime": "2023-05-31T10:15:00",
"EndTime": "2023-06-01T18:30:00",
"StartingPrice": "1000"
}

Get an auction list
[this is the endpoint](https://localhost/4000/api/auction/list)

Get an auction id
[this is the endpoint](https://localhost/4000/api/auction/id)

Get Version
[this is the endpoint](https://localhost/4000/api/auction/version)

# AuthService

## AuthController

### Endpoint

Post Login
[this is the endpoint](https://localhost/4000/api/login)
{
"Email":"michaelsloth@email.com",
"Password":"Password12345678"
}


# ItemService

## ItemController

### Endpoint

Post an Item
[this is the endpoint](http://localhost/4000/api/item/create)
{
"seller": "e8ee01df-bffb-449b-8f4c-44feb0ad20c0",
"Title": "Design Chair",
"Brand": "Armani",
"Description": "Catton and Lether blend",
"CategoryCode": "CH",
"location": "Aarhus Danmark"

}

Get an Item list
[this is the endpoint](http://localhost/4000/api/item/list)

Get an Item id
[this is the endpoint](http://localhost/4000/api/item/id)

Post an Item uploadImage/Id
[this is the endpoint](http://localhost/4000/api/item/uploadImage/id)

{
image.jpg
}

Get Version
[this is the endpoint](http://localhost/4000/api/item/version)

# UserService

## UserController

### Endpoint

Post an User
[this is the endpoint](http://localhost/4000/api/user/create)
{
"FirstName": "Michael",
"LastName": "Sloth",
"Email":"michaelsloth@email.com",
"Password":"Password12345678"
}

Get an User list
[this is the endpoint](http://localhost/4000/api/user/list)

Get an User/id
[this is the endpoint](http://localhost/4000/api/user/id)

Delet An User/Id
[this is the endpoint](http://localhost/4000/api/user/delet/id)

Get Version
[this is the endpoint](http://localhost/4000/api/user/version)
