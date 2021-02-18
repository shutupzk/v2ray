date -R
tzselect
cp /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime

bash <(curl -L https://raw.githubusercontent.com/v2fly/fhs-install-v2ray/master/install-release.sh)

vim config.json

systemctl start v2ray
