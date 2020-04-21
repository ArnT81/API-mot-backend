# API-mot-backend
övningsuppgift 1, dokumentation av API
｜

## path: http://api.softhouse.rocks/users

## method: GET (curl http://api.softhouse.rocks/users｜jq)

## bodydata: 
<html lang="en">
<head>
<meta charset="utf-8">
<title>Error</title>
</head>
<body>
<pre>Cannot GET /users%7Cjq</pre>
</body>
</html>


## what method does: Displays HTML 

__________________________________________________________________________

## path: http://api.softhouse.rocks/posts

## method: POST (curl -i -X POST -H "Content-Type:application/json" http://api.softhouse.rocks/posts -d '{"title":"Hi, World", "body":"Fresh as morning dew", "userId": "1"}')


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


## what method does: Adds two new json strings, (Hi, World) in the title and (Fresh as morning dew) in the body segment

__________________________________________________________________________