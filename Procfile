node: nodejs websocket-relay.js supersecret 8081 8080
ffmpeg: bash -c 'sleep 30; ffmpeg -f v4l2 -framerate 24 -video_size 320x240 -i /dev/video0 -f mpegts -codec:v mpeg1video -s 320x240 -b:v 32k -bf 0 http://localhost:8081/supersecret'
