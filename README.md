Noobz-VPN Manager Bot

### STOP ! PLEASE INSTALL NOOBZ-VPN BEFORE RUNNING ALL OF THIS COMMAND BELOW.

<a href=https://github.com/noobz-id/noobzvpns>Noobz-VPN Installer</href>

### Quick installation:
```
apt update && apt upgrade
apt install python3-pystemd
apt install python3 git
git clone https://github.com/rantempest/Noob
cd Noob
python3 -m pip install -r requirements.txt
mv noobzmanager.service /etc/systemd/system/
systemctl enable noobzmanager
```

### Environment setup (read the instruction inside):
```
nano noobz_manager.py
```

### Start or re-start Noobz-Manager service
```
systemctl start noobzmanager
```

### Stop Noobz-Manager service
```
systemctl stop noobzmanager
```

Feedback / error? its your problem
