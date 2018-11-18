# boomi-restish-api
A gem providing access to Boomi's restish API with json request and response data.
I wrote this instead of using the already available boomi-ruby gem because that one uses xml with rest. Our gem on the other hand, sets the 'Accept' and 'Content-Type' headers to 'application/json' allowing the use of json requests and responses and simplifying json to ruby parsing.
