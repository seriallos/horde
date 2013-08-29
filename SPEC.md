Usage
=====

GET a page a fixed number of times (ab mode)

    Horde = require "horde"

    # make 100 request with 10 concurrent agents
    options = {
      url:         "http://www.example.com/"
      concurrency: 10
      iterations:  100
    }

    Horde.run( options )

GET a page until the script is killed (siege mode)

    Horde = require "horde"

    options = {
      url:         "http://www.example.com/"
      concurrency: 10
    }

    Horde.run( options )

POST a form

    Horde = require "horde"

    options = {
      url:      "http://www.example.com/"
      post:
        username: "Bob"
        password: "secret"
      iterations: 100
    }

    Horde.run( options )

Multistep form

