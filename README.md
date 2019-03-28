# Subscribe
订阅


v2ray链接格式
{'add':服务器,
'port':端口,
'id':用户id,
'aid':额外id,
'type':伪装类型,
'net':传输协议,
'ps':别名,
'host':伪装域名,
'path':路径,
'tls':底层传输安全,
'v':版本号
}
json数据如下
{
"ps": "备注别名",
"add": "111.111.111.111",
"port": "32000",
"id": "1386f85e-657b-4d6e-9d56-78badb75e1fd",
"aid": "100",
"net": "tcp",
"type": "none",
"host": "www.bbb.com",
"tls": "tls"
}

net ：传输协议（tcp\kcp\ws)
type:伪装类型（none\http\srtp\utp\wechat-video）
host：伪装的域名

1)非ws伪装中间逗号(,)隔开"
2)ws path
3)ws path+host(中间分号(;)隔开)
4)h2 path
tls：底层传输安全（tls)
