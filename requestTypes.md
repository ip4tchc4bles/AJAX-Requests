### XHR

**POST**
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

**GET**

```
var xhr = new XMLHttpRequest();
var uri = "www.domain.tld";
xhr.open("GET", uri);
xhr.setRequestHeader("Authorization", "Bearer SeCret");
xhr.send()
```

### Fetch

**POST**

```
fetch("www.domain.tld", {
  "headers": {
    "accept": "*/*",
    "accept-language": "en-US,en;q=0.9",
    "api-version": "v1.0",
    "authorization": "Bearer SeCreT",
    "content-type": "application/json;charset=UTF-8",
    "sec-ch-ua": "\" Not A;Brand\";v=\"99\", \"Chromium\";v=\"90\", \"Google Chrome\";v=\"90\"",
    "sec-ch-ua-mobile": "?0",
    "sec-fetch-dest": "empty",
    "sec-fetch-mode": "cors",
    "sec-fetch-site": "same-origin"
  },
  "referrer": "www.referrer.tld",
  "referrerPolicy": "strict-origin-when-cross-origin",
  "body": "{\"name\":value,\"name\":\"value\",\"name\":value,\"array\":[{\"name\":\"value\",\"name\":value"}]}",
  "method": "POST",
  "mode": "cors",
  "credentials": "include"
});
```


