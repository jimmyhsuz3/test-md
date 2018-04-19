![Minion](https://octodex.github.com/images/minion.png)

> a
  > b
    > c

# test-md
:smile:

- a
  - c
  
    - d
    
- b

```
abc
def
```

```java=
HttpClient client = new HttpClient();
    
GetMethod method = new GetMethod(url);

try {

    int statusCode = client.executeMethod(method);

    System.out.println(statusCode);
    System.out.println(new String(method.getResponseBody()));
    System.out.println(method.getResponseHeaders());

} finally {
    // Release the connection.
    method.releaseConnection();
}

```
