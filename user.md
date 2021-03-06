# User

### Routes
####GET

|Ressource   | Description  |  on Success | on Failure |
|---|---|---|---|
|/profile/:ID   | returns profile information for requested user ID  | json object | statusCode: 404 | 
|/me           | returns profile of current user  | json object | statusCode: 404 |


####POST
|Ressource   | Description  |  on Success | on Failure |
|---|---|---|---|
|/login   | validate login information  | statusCode: 200 | statusCode: 404 |
|/me   | update user information  | statusCode: 200 | statusCode: 404 |



### Dummy Json Results
```
{
   _id: '4234324342',
   _rev: '1-dbe58c4eb46dc66b3b62ed4dfab2f3fe',
   picture: 'data:image/jpeg;base64,/9j/4QAYRXhpZgAASUkqAAgAAAAAAAAAAAAAAP/sABFEdWNreQABAAQAAABQAAD/4QMbaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wLwA8P3hwYWNrZXQgYmVnaW49Iu+7vyIgaWQ9Ilc1TTBNcENlaGlIenJlU3pOVGN6a2M5ZCI/PiA8eDp4bXBtZXRhIHhtbG5zOng9ImFkb2JlOm5zOm1ldGEvIiB4OnhtcHRrPSJBZG9iZSBYTVAgQ29yZSA1LjMtYzAxMSA2Ni4xNDU2NjEsIDIwMTIvMDIvMDYtMTQ6NTY6MjcgICAgICAgICI+IDxyZGY6UkRGIHhtbG5zOnJkZj0iaHR0cDovL3d3dy53My5vcmcvMTk5OS8wMi8yMi1yZGYtc3ludGF4LW5zIdGbi2h+OG5cdSUJ6KAimgqU2tJ6XFRQKcqZVxOZK97SHO225f8qsLntItaBj...',
   name: 'Gorenflo',
   surname: 'Steffen',
   mail: 'info@steffen.de',
   major: 'AIN',
   semester: '6',
   subscribed_groups: [
       {
           _id: '142001',
           name: 'Mathematik 1'
       },
       {
           _id: '142034',
           name: 'Digitaltechnik 1'
       }
   ],
   password: 'secret',
   type: 'user'
}
 

```

