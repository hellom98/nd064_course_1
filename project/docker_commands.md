> docker build -t techtrends:latest .

> docker run --rm -d -p 7111:3111 techtrends:latest

> docker logs amazing_hamilton

# Logs

```
 * Serving Flask app 'app' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
WARNING:werkzeug:04-08-2023, 11:28:46,  * Running on all addresses.
   WARNING: This is a development server. Do not use it in a production deployment.
INFO:werkzeug:04-08-2023, 11:28:46,  * Running on http://172.17.0.2:3111/ (Press CTRL+C to quit)
INFO:werkzeug:04-08-2023, 11:29:00, 172.17.0.1 - - [08/Apr/2023 11:29:00] "GET /metrics HTTP/1.1" 200 -
INFO:werkzeug:04-08-2023, 11:29:00, 172.17.0.1 - - [08/Apr/2023 11:29:00] "GET /favicon.ico HTTP/1.1" 404 -
INFO:werkzeug:04-08-2023, 11:29:05, 172.17.0.1 - - [08/Apr/2023 11:29:05] "GET / HTTP/1.1" 200 -
INFO:werkzeug:04-08-2023, 11:29:05, 172.17.0.1 - - [08/Apr/2023 11:29:05] "GET /static/css/main.css HTTP/1.1" 200 -
INFO:app:04-08-2023, 11:29:28, Article "2020 CNCF Annual Report" retrieved!
INFO:werkzeug:04-08-2023, 11:29:28, 172.17.0.1 - - [08/Apr/2023 11:29:28] "GET /1 HTTP/1.1" 200 -
INFO:werkzeug:04-08-2023, 11:29:28, 172.17.0.1 - - [08/Apr/2023 11:29:28] "GET /static/css/main.css HTTP/1.1" 304 -
INFO:app:04-08-2023, 11:29:30, About Us page is retrieved
INFO:werkzeug:04-08-2023, 11:29:30, 172.17.0.1 - - [08/Apr/2023 11:29:30] "GET /about HTTP/1.1" 200 -
INFO:werkzeug:04-08-2023, 11:29:30, 172.17.0.1 - - [08/Apr/2023 11:29:30] "GET /static/css/main.css HTTP/1.1" 304 -
INFO:werkzeug:04-08-2023, 11:29:31, 172.17.0.1 - - [08/Apr/2023 11:29:31] "GET /create HTTP/1.1" 200 -
INFO:werkzeug:04-08-2023, 11:29:31, 172.17.0.1 - - [08/Apr/2023 11:29:31] "GET /static/css/main.css HTTP/1.1" 304 -
INFO:app:04-08-2023, 11:29:35, Article "qwerwe" created!
INFO:werkzeug:04-08-2023, 11:29:35, 172.17.0.1 - - [08/Apr/2023 11:29:35] "POST /create HTTP/1.1" 302 -
INFO:werkzeug:04-08-2023, 11:29:35, 172.17.0.1 - - [08/Apr/2023 11:29:35] "GET / HTTP/1.1" 200 -
INFO:werkzeug:04-08-2023, 11:29:35, 172.17.0.1 - - [08/Apr/2023 11:29:35] "GET /static/css/main.css HTTP/1.1" 304 -
INFO:werkzeug:04-08-2023, 11:30:06, 172.17.0.1 - - [08/Apr/2023 11:30:06] "GET /metrics HTTP/1.1" 200 -
INFO:werkzeug:04-08-2023, 11:30:10, 172.17.0.1 - - [08/Apr/2023 11:30:10] "GET /health HTTP/1.1" 404 -
INFO:werkzeug:04-08-2023, 11:30:13, 172.17.0.1 - - [08/Apr/2023 11:30:13] "GET /healthz HTTP/1.1" 200 -
INFO:app:04-08-2023, 11:30:59, Article "CNCF Cloud Native Interactive Landscape" retrieved!
INFO:werkzeug:04-08-2023, 11:30:59, 172.17.0.1 - - [08/Apr/2023 11:30:59] "GET /4 HTTP/1.1" 200 -
INFO:werkzeug:04-08-2023, 11:30:59, 172.17.0.1 - - [08/Apr/2023 11:30:59] "GET /static/css/main.css HTTP/1.1" 304 -
INFO:app:04-08-2023, 11:31:02, A non-existing article is accessed and a 404 page is returned.
INFO:werkzeug:04-08-2023, 11:31:02, 172.17.0.1 - - [08/Apr/2023 11:31:02] "GET /88 HTTP/1.1" 404 -
INFO:werkzeug:04-08-2023, 11:31:02, 172.17.0.1 - - [08/Apr/2023 11:31:02] "GET /static/css/main.css HTTP/1.1" 304 -
```