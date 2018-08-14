# simplest-http-server-for-minimalist

init Node.js and install these library(connect, serve-static)
```
$npm init
$npm install connect serve-static 
```

put this "server.js" and static-http-project (example,"yourProjectName") to npm root.
```
npm-root
|_>npm_modules
| |_>...
|
|_>package.json
|_>package-lock.json
|
|_>yourProjectName
  |_>index.html
  |_>etc{js,css,images,...}
```

and run this server.
```
$npm install //(optional)
$node server.js
```

A simple server start on port:3000;
after this, input your wep-static-project-directory.
```
localhost:3000/yourProjectName/
localhost:3000/yourProjectName/index.html
```

if you need change port number
edit server.js like this.
```
const connect = require('connect');
const serveStatic = require('serve-static');
connect().use(serveStatic(__dirname)).listen( XXXX , function(){
    console.log('->port: XXXX ');
});

XXXX re-write to you need.(default:3000)
```

LET'S DO THE Minimal Developments!!!
