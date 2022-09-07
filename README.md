# A very slow http server

Responds to the following endpoints:

## `/fast`

Responds immediately successfully.

## `/slow`

Responds successfully after 1 second.

Also accepts a `seconds` query param that specifies the length of delay (e.g. `GET /slow?seconds=30`)
