# Abstract Rest Service Benchmark

## Benchmark

The simple test with [AB](https://httpd.apache.org/docs/2.4/programs/ab.html):

```bash
$ ab -n 100000 -c 100 -H "Accept-Encoding: gzip, deflate" http://localhost:$PORT/api/test
```

> TODO Change to [WRK](https://github.com/wg/wrk)

---

## Results

|   | Service | Language | Framework | RPS |
| - | ------- | -------- | --------- | --- |
| 1 | [?](/?/) | ? | ? | ? |

---

## Services

### .Net Core Native Rest Service

Language: C#

Framework: .NET Core (ASP.NET Core 2.0)

Main tutorial: https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api

Run:

```bash
$ dotnet publish -c release -o published
$ dotnet dotNetCoreRestService.dll
```

Result:

```
TODO
```

---

### Java Spring Boot Rest Service

Language: Java

Framework: Oracle JDK8

Main tutorial: http://spring.io/guides/gs/rest-service

Run:

```bash
$ gradlew clean build
$ gradlew bootRun
```

Result:

```
TODO
```

---

### Java Light 4J Rest Service

Language: Java

Framework: Oracle JDK8

Main tutorial: https://github.com/networknt/light-example-4j/tree/master/demo

Run:

```bash
$ mvn clean install
$ cd target
$ java -jar service-example-0.1.0.jar
```

Result:

```
TODO
```

---

### Go Gorilla/Mux Rest Service

Language: Go

Framework: Go SDK 1.9.2

Main tutorial: https://www.codementor.io/codehakase/building-a-restful-api-with-golang-a6yivzqdo

Run:

```bash
$ go build
$ go-rest-service
```

Result:

```
TODO
```

---

### NodeJS Native Rest Service

Language: JavaScript  

Framework: Node.js 8.9.4 LTS  

Main tutorial: https://nodejs.org/api/http.html#http_class_http_server  

Run:  

```bash
$ node ./index.js
```  

Result:  

```
TODO
```

---

### NodeJS Express Rest Service

Language: JavaScript  

Framework: Node.js 8.9.4 LTS + Express 4.16.2

Main tutorial: http://expressjs.com/en/starter/hello-world.html  

Run:  

```bash
$ npm i  
$ node ./index.js  
```  

Result:  

```
TODO
```

---

### Python Aiohttp Rest Service

Language: Python 3.5  

Framework: aiohttp 2.3.7, uvloop 0.9.1

Main tutorial: https://aiohttp.readthedocs.io/en/stable/  

Run:  

```bash
$ pip install -r requirements.txt
$ python app.py
```  

Result:  

```
TODO
```

---

### Python Flask Rest Service

Language: Python 3.5

Framework: Flask 0.12.2

Main tutorial: http://flask.pocoo.org/

Run:

```bash
$ pip install -r requirements.txt
$ FLASK_APP=app.py flask run
```

Result:

```
TODO
```

---

### Python Sanic Rest Service

Language: Python 3.5  

Framework: Sanic 0.7.0, uvloop 0.9.1

Main tutorial: http://sanic.readthedocs.io/en/latest/  

Run:  

```bash
$ pip install -r requirements.txt
$ python app.py
```  

Result:  

```
TODO
```

---

### Rust Iron Rest Service

Language: RUST

Framework: iron 0.6.0

Main tutorial: https://github.com/iron/router/blob/master/examples/simple.rs

Run:  

```bash
$ docker build -t rustest .
$ docker run -p 8080:8080 -it rustest:latest
``` 

Result: 

```
TODO
```

> TODO Change to native run (not in Docker)

---

### Haskell Warp Rest Service

Language: Haskell

Framework: warp 3.2.13

Main tutorial: http://taylor.fausak.me/2014/10/21/building-a-json-rest-api-in-haskell/

Requirements:

* Install Haskell stack: https://docs.haskellstack.org/en/stable/README/
* Install Cabal package: `cabal install Cabal-2.0.1.1`

Run:

```bash
$ stack image container
``` 

Result: 

```
TODO
```

> TODO Change to native run (not in Docker)

---

## Hardware

### Home Station

Model: [iMac 18.3](https://support.apple.com/kb/SP760)

CPU: 3.4GHz quad-core Intel Core i5 (Turbo Boost up to 3.8GHz)

RAM: 8GB (two 4GB) of 2400MHz DDR4 memory

HDD: 1TB Fusion Drive

### Real Server

> TODO
