# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## Running with Docker

```
docker build -t rottenpotatoes .
docker run -it --rm -p 3000:3000 -v "$PWD":/app rottenpotatoes
rails server -b 0.0.0.0   # inside the container
```

Then open http://localhost:3000.
