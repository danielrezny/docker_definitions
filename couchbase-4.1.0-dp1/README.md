
This README will guide you through running Couchbase Server under Docker.

[Couchbase Server](http://en.wikipedia.org/wiki/Couchbase_Server) is an open-source, distributed (shared-nothing architecture) NoSQL document-oriented database and key-value store that is optimized for interactive applications.

Licensing information is covered towards the end of this guide.

For support, please visit the [Couchbase support forum](https://forums.couchbase.com/) or `#couchbase` on irc.freenode.net.

#Build image from this files
```
docker build -t YOUR_REPOSITORY/TAG_OPTIONAL .
```

# QuickStart

```
docker run -d -p 8091:8091 YOUR_REPOSITORY
```
To expose all ports from a created container you can start docker with following command
```
docker run -d --net=host YOUR_REPOSITORY
```


At this point go to http://localhost:8091 from the host machine to see the Admin Console web UI.  More details and screenshots are given below in the **Single host, single container** section.

# Background Information

other info is on official Couchbase repo
