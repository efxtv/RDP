# RDP
Kali / Widnows

## Free Linux RDP

- Start G-Shell/Github vps, paste command

```
$ sudo docker run --name ubvnc -p 6080:80 -p 5900:5900 dorowu/ubuntu-desktop-lxde-vnc:bionic &
```

- Access RDP VIA HTTP port 6080 VNC (Firefox)
```
$ ./ngrok http 127.0.0.1:6080
```

- Start RDP
```
$ sudo docker start ubvnc
```

- Stop RDP
  ```
$ sudo docker stop ubvnc
  ```
