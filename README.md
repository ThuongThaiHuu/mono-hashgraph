# Hashgraph in Go

## How to run
There are main.go located under [`cmd`](cmd) folder. 
- [`dledger`](cmd/dledger) contains a distributed ledger application that is built upon Hashgraph algorithm. <br>
You can run `dledger` by `$ go run main.go PORT_NUMBER`. Note that this application retrieves the peer information from [`peers.txt`](cmd/dledger/peers.txt)
