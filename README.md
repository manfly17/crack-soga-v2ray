## 启用破解

启用破解版只需在soga_key处输入任意字符即可，如留空则为原版社区版本。

## 完整教程

[doc.sprov.xyz](https://doc.sprov.xyz/)

## 脚本安装

``` bash
sudo bash < <(curl -Ls https://raw.githubusercontent.com/manfly17/crack-soga-v2ray/master/install.sh)
```

## 拉取镜像

docker pull manfly17/crack-soga:2.0.6

## Docker安装

docker run --restart=always --name crack-soga -d -v /etc/soga/:/etc/soga/ --network host manfly17/crack-soga:2.0.6 \
--type=sspanel-uim \
--server_type=v2ray \
--api=webapi \
--webapi_url=https://xxx.com/ \
--webapi_mukey=xxx \
--soga_key=cracked_by_RMan \
--node_id=1
```

