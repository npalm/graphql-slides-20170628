## REST API

Resource: `/talks`
```
[
  {
    "title" : "GraphQL - The Next API Language",
    "speaker" : {
      "username" : "niek",
      "href" : "http://nextbuild.nl/speakers/niek"
    }
  }
  {
    "title" : "Scaling from 10.000 to 20 million devices",
    "speaker" : {
      "username" : "mark",
      "href" : "http://nextbuild.nl/speakers/mark"
    }
  }
]

```


!SUB
## REST API
Resource `/speakers/niek`

```
{
  "username" : "niek",
  "name" : "Niek Palm",
  "twitter" : "niekos77",
  "blog" : "https://040code.github.io",
  "github": "npalm",
  "city" : "Eindhoven",
  "shoppinglist" : {
    "href" : "http://nextbuild.nl/speakers/niek/shoppinglist"
  }
}
```

!SUB
## REST Architecture
![rest](images/rest-architecture.png)

!SUB
## REST Architecture
![rest-2](images/rest-architecture-2.png)
