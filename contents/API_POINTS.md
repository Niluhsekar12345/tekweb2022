# API POINTS

## Users

### Menampilkan data users
```

GET: /users

response:
[
{
  "id"            :"";
  "name"          :"";
  "motto"        :"";
  "ig_url"        :"";
},
{
...
}
]

```

## Menampilkan data user dengan id tertentu

```

GET: /users/[id]

response:
[
{
    "id": "",
    "name": "",
    "motto": "",
    "ig_url": "",
},
{
...
}
]

```

## Menambahkan data user

```

POST: /users

data:
{
    "name": "",
    "motto": "",
    "ig_url": "",
}

response:
true    //if true
false   //if false

```


## Mengubah data user

```

PUT: /about

data:
{
    "id":"",
    "name": "",
    "motto": "",
    "ig_url": "",
}
response:
true    //if true
false   //if false

```

## Menghapus data user

```

DELETE: /users/[id]

response:
true    //if true
false   //if false

```

# ARTICLES


## Menampilkan articles berdasarkan id

```

GET: /articles/[id]

response:
[
{
    "id": "",
    "title": "",
    "content": ""
    "author_id": "",
    "thumbnail_url": "",
    "created_date": ""
},
{
    ...
}
]

```

## Menambahkan articles

```

POST: /articles

data:
{
    "id": "",
    "title": "",
    "content": ""
    "author_id": "",
    "thumbnail_url": "",
    "created_date": ""
}

response:
true    //if true
false   //if false

```

## Mengubah article

```

PUT: /articles

data:
{
    "id": "",
    "title": "",
    "content": ""
    "author_id": "",
    "thumbnail_url": "",
    "created_date": ""
}

response:
true    //if true
false   //if false

```

## Menghapus article

```

DELETE: /articles

response:
true    //if true
false   //if false

```

**DATABASE DESIGN**
![Design Database]
(https://raw.githubusercontent.com/Niluhsekar12345/tekweb2022/main/images/USER.png)

