# API-mot-backend
övningsuppgift 1, dokumentation av API
｜

## path:
## method: 
## bodydata: 
## what method does: 

| jq structure answere


## path: http://api.softhouse.rocks/users/1

## method: 
GET

## bodydata: 
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   253  100   253    0     0    627      0 --:--:-- --:--:-- --:--:--   627
{
  "address": {
    "geo": {
      "lat": -37.3159,
      "lng": 81.1496
    },
    "street": "Kulas Light",
    "suite": "Apt. 556",
    "city": "Gwenborough",
    "zipcode": "92998-3874"
  },
  "_id": "5e806d9f42fbde006b6b9ec5",
  "id": 1,
  "name": "Leanne Graham",
  "username": "Bret",
  "email": "Sincere@april.biz",
  "__v": 0
}

## what method does:
fetch the first user object 

__________________________________________________________________________

## path: http://api.softhouse.rocks/posts

## method: 
POST 

## bodydata: 
 % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   179  100   112  100    67    370    221 --:--:-- --:--:-- --:--:--   592HTTP/1.1 201 Created
X-Powered-By: Express
Access-Control-Allow-Origin: *
Content-Type: application/json; charset=utf-8
Content-Length: 112
ETag: W/"70-U5L+tLF9Kbvt6Van8+A/6n0vLYs"
Date: Tue, 21 Apr 2020 08:58:46 GMT
Via: 1.1 google

{"_id":"5e9eb5c609cee0002106f319","body":"Fresh as morning dew","title":"Hi, World","userId":1,"id":825,"__v":0}


## what method does: 
Adds two new json strings, (Hi, World) in the title and (Fresh as morning dew) in the body segment

__________________________________________________________________________

## path: http://api.softhouse.rocks/posts/13

## method: 
DELETE

## bodydata: 
 % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100     2  100     2    0     0      9      0 --:--:-- --:--:-- --:--:--     9OK

## what method does: 
deletes post 13
__________________________________________________________________________

## path: http://api.softhouse.rocks/posts/3

## method: 
PUT

## bodydata: 
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   159  100   124  100    35    855    241 --:--:-- --:--:-- --:--:--  1104{"expose":true,"statusCode":400,"status":400,"body":"{\n  \"name\": \"Me Myself and I\", ...}","type":"entity.parse.failed"}

## what method does: 
The PUT method requests that the enclosed entity be stored under the supplied URI. If the URI refers to an already existing resource, it is modified; if the URI does not point to an existing resource, then the server can create the resource with that URI.
__________________________________________________________________________
## path: curl -X PATCH http://api.softhouse.rocks/posts/12 -H "Content-Type:application/json" -d  '{
  "name": "some other name"}'

## method: 
PATCH

## bodydata: 
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    44  100    14  100    30      2      4  0:00:07  0:00:06  0:00:01     9userId missing

## what method does: 
Update a Resource
__________________________________________________________________________
## path:
## method: 
## bodydata: 
## what method does: 