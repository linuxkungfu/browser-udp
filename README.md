# webrtc data-channels
```
git clone https://github.com/linuxkungfu/browser-udp.git
```


### Start web server
```
python3 -m http.server 1985
```
#### Open browser
```
http://127.0.0.1:1985/
```
click "Copy browser SDP to clipboard" button
#### Linux/macOS
```
echo $clipboard-content | go run ./main.go
```

