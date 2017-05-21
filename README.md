# Chef-Docs


knife bootstrap 54.252.228.249 -x ubuntu -i C:\Users\Administrator\Desktop\susritha-sydney.pem --sudo --node-name susritha


knife winrm 'name:susritha3' chef-client --winrm-user ubuntu --winrm-password C:\Users\Administrator\Desktop\susrithasingapore.pem --attribute 52.221.242.170

knife winrm 'name:node1-windows' chef-client --winrm-user USER --winrm-password 'PASSWORD' --attribute ipaddress

sudo chef-server-ctl user-create susritha sai munukutla sai94@gmail.com admin123 --filename ~/.chef/susritha.pem
