## Installation
    npm install -d
    /**node server.js**/

[http://localhost:5000](http://localhost:5000)



## Run in linux

```bash
npm install -g forever
```

`forever start -o out.log -e err.log server.js`



http://192.168.3.75:5000


```bash
cd /root/smallg/planning-poker```

#start mock service
```bash
forever start -o out.log -e err.log server.js
```

#stop mock service
```bash
forever stop server.js
```

#view service log 
```bash
tail -f out.log
```
