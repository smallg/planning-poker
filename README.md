##Installation
    npm install -d
    node server.js

[http://localhost:5000](http://localhost:5000)



##Run in linux

npm install -g forever

forever start -o out.log -e err.log server.js



http://192.168.3.75:5000


cd /root/smallg/planning-poker

#start mock service
forever start -o out.log -e err.log server.js 

#stop mock service
forever stop server.js

#view service log 
tail -f out.log
