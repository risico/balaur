![balaur logo](logo.png)

# :dragon: Balaur - Instant SSH connections
Quickly search and connecto to SSH droplets


*Warning!* This is a work in progress


## Installation instructions
In order for this to work you'll need to have Golang installed and GOPATH set correctly (including the GOPATH/bin folder).

```go get -u https://www.github.com/risico/balaur```

`balaur` should now be in your path. It will now need your DO API key. Run `balaur init`, it will ask you about your API key and it will save it.

`balaur` will retrieve all droplets and let you choose between a list
