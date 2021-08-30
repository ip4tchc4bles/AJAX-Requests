# POST

```
var xhr = new XMLHttpRequest();
var uri = "www.domain.tld";
xhr.open("POST", uri);
xhr.setRequestHeader("Content-Type", "application/json;charset=UTF-8");
xhr.setRequestHeader("Authorization", "Bearer SeCret");


xhr.send(JSON.stringify({
              "name": value,
              "name": value,
              "name": value,
              "array": [{
                             "name": value,
                             "name": value,
                             "name": value,
                             "name": value,
                       }]
            }))
              
```
