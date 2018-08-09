# simplest-http-server-for-minimalist

set node.
```
$npm init
$npm install connect serve-static 
```

put this "server.js" and static-http-project (example,"yourProjectName") to npm root.
```
server-root
|_>npm_modules
|_>package.js
|_>package-lock.js
|
|_>yourProjectName
  |_>index.html
  |_>etc{js,css,images,...}
```

and set up server.
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

LET'S DO THE Minimal Developments!!!
