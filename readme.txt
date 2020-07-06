date -R
tzselect
cp /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime
wget https://install.direct/go.sh
bash go.sh

vim config.json

systemctl start v2ray
