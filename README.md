Sample Application with Go and Gin
======================================

Running Locally
---------------

First, you need to have a working go environment:

http://golang.org/doc/install

### Build
```sh
go build
```

### Execute
```sh
./sample-go-gin
```

Deploying on Scalingo
---------------------

Create an application on https://scalingo.com, then:

```
git remote add scalingo git@scalingo.com:<name_of_your_app>.git
git push scalingo master
```

And that's it!

The application is running at this url: https://sample-go-gin.scalingo.io/

Deploy in one click
-------------------

[![Deploy to Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://my.scalingo.com/deploy?source=https://github.com/ipfaze/sample-go-gin#master)

Links
-----

https://golang.org
https://github.com/gin-gonic/gin/
