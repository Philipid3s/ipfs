### IPFS examples

```go
> ipfs version
ipfs version 0.4.7
```

```go
> ipfs init
```
A folder \.ipfs will be created under the User's Documents path.

```go
> ipfs add content\sw.png
121.86 KB / 121.86 KB [========================================================================] 100.00% 0s?added QmPjNd8ap3zugQCsNJKVWYxr5ohaiimrnovwe8pC5W1RSz sw.png
```
The file is added the your local IPFS

Now we start the local IPFS daemon:
```go
> ipfs daemon
Initializing daemon...
```

The png will be then accessible at this address: http://localhost:8080/ipfs/QmPjNd8ap3zugQCsNJKVWYxr5ohaiimrnovwe8pC5W1RSz





