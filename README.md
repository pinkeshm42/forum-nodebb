# Forum NodeBB (custom)

[**NodeBB Forum Software**](https://nodebb.org) is powered by Node.js and supports either Redis, MongoDB, or a PostgreSQL database. 
It utilizes web sockets for instant interactions and real-time notifications. NodeBB takes the best of the modern web: 
real-time streaming discussions, mobile responsiveness, and rich RESTful read/write APIs, while staying true to the original 
bulletin board/forum format &rarr; categorical hierarchies, local user accounts, and asynchronous messaging.

NodeBB by itself contains a "common core" of basic functionality, while additional functionality and integrations are enabled through the use of third-party plugins.

##### [Try Live Open Source](//try.nodebb.org) | [Git Open Source](//github.com/NodeBB/NodeBB)


### Get NodeBB v1.19.5
```
git clone -b v1.19.x https://github.com/NodeBB/NodeBB.git forum-nodebb
cd forum-nodebb
```


## Run in Windows

### MongoDB in Docker 
Change the `docker-compose.yml` leaving only code related to MongoDB and run the container.
```
docker-compose up -d
```

To test the connection you can use MongoDB Compass `mongodb://root:root@localhost:27017/?authSource=admin&readPreference=primary&appname=MongoDB%20Compass&directConnection=true&ssl=false`

### NodeBB in local
`config.json` has the connection to mongo DB. 

```
nodebb install
```

Should lunch the web installer.  Insert username, email, pwd for the NodeBB forum and click Install NodeBB.  


## Links


* [Demo](https://try.nodebb.org)
* [Documentation](//docs.nodebb.org) 
* [How to install NodeBB on Windows](https://docs.nodebb.org/installing/os/windows/)
* [Git NodeBB Open Source](//github.com/NodeBB/NodeBB)

