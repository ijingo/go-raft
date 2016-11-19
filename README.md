# An Implementation of Raft in Go

[Raft](raft.github.io) is a distributed consensus protocol which is designed dedicatedly for 
understandabity.

This implementation is adapated from MIT 6.824 lab2, which finished Leader Election + Log Replication +
Log Compaction (Snapshot).

Test command:
```
cd go-raft
export GOPATH=$PWD
cd src/raft
go test
```

Enjoy.
