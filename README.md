# FreeProxiesScraper

Fork from TopFreeProxies.

## 仓库介绍
本仓库自动化功能全部基于 `GitHub Actions` 实现，如有需要可以自行 Fork 实现个性化需求，功能配置在 `./utils/config.ini` 配置文件中。

对网络上各免费节点池及博主分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。所筛选的节点链接在仓库 `./sub/sub_list.json` 文件中，其中大部分为其他 `GitHub` 仓库链接，如果大家有好的订阅链接欢迎提交 PR ，这些链接包含的所有节点会合并在仓库 `./sub/sub_merge.txt` 中。

测速筛选后的节点订阅文件在仓库根目录 `Eterniy`(Base64) 和 `Eternity.yaml`(Clash)。同时在仓库的 `./update` 中保留了原始节点链接的的记录。

订阅转换使用 [subconverter](https://github.com/tindy2013/subconverter) 实现，测速功能使用 [LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest) 在 `GitHub Actions` 环境下实现，所以美国节点较多，不能很好代表国内网络环境下节点可用性，目前正在解决这一问题。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择`Clash`, `Shadowrocket`之类能自动切换低延迟节点的客户端。

## 使用方法
将以下订阅链接导入相应客户端即可。链接中大部分为 SS 协议节点，少量 Vmess, Trojan ,SSR 协议节点，建议选择协议支持完整的客户端。

- [多协议Base64编码](https://raw.githubusercontent.com/caijh/FreeProxiesScraper/master/Eternity)
- [Clash](https://raw.githubusercontent.com/caijh/FreeProxiesScraper/master/Eternity.yaml)

>`Clash`链接所使用的配置在仓库`./update/provider/`中，有相应配置文件和以国家分类的`proxy-provider`。
>
>需要其它配置可使用订阅转换工具自行转换。
>自用在线订阅转换网址：[sub-web-modify](https://sub.v1.mk/)

## 节点信息
### 高速节点
高速节点数量: `48`
<details>
  <summary>展开复制节点</summary>

    trojan://253bc477d4e43c209f2d427272968280@36.151.251.6:9160?allowInsecure=1&sni=www.nintendogames.net#05-0003-CN
    trojan://253bc477d4e43c209f2d427272968280@36.151.251.6:4801?allowInsecure=1&sni=www.nintendogames.net#05-0004-CN
    trojan://9e76767d-4bfa-4f04-a800-42e2f63afed2@uk.viefast.net:443?allowInsecure=1&sni=csapp.catch.net.tw#05-0008-GB
    trojan://9e76767d-4bfa-4f04-a800-42e2f63afed2@telaviv.viefast.net:443?allowInsecure=1&sni=csapp.catch.net.tw#05-0021-IL
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDAyNS1ERSIsImFkZCI6IjU3LjEyOS4yNC4xMzEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjAzZmNjNjE4LWI5M2QtNjc5Ni02YWVkLThhMzhjOTc1ZDU4MSIsImFpZCI6IjEiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbGlua3Z3cyIsImhvc3QiOiIiLCJ0bHMiOiJ0bHMifQ==
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpPM2s1dTc5UnpjOGZBY3dMZjJjUXkz@142.93.166.6:80#05-0026-DE
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@38.54.57.90:989#06-0027-BR
    vmess://eyJ2IjoiMiIsInBzIjoiMDYtMDAyOC1DTiIsImFkZCI6InYzNi5oZWR1aWFuLmxpbmsiLCJwb3J0IjoiMzA4MzYiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2JiM2Y4NzctZDFmYi0zNDRjLTg3YTktZDE1M2JmZmQ1NDg0IiwiYWlkIjoiMiIsIm5ldCI6IndzIiwicGF0aCI6Ii9vb29vIiwiaG9zdCI6InYzNi5oZWR1aWFuLmxpbmsiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@154.90.63.177:989#06-0030-KR
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpvWklvQTY5UTh5aGNRVjhrYTNQYTNB@45.87.175.58:8080#06-0031-LT
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpvWklvQTY5UTh5aGNRVjhrYTNQYTNB@ltnl15.saint.ydns.eu:8080#06-0032-LT
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@38.165.233.93:989#06-0035-PY
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@154.223.20.79:989#06-0037-TW
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@154.90.62.168:989#08-0040-KR
    trojan://1640ef52-2db0-44ab-b3f3-8690b762ebc9@165.154.112.107:12000?allowInsecure=1#08-0041-HK
    ss://YWVzLTI1Ni1jZmI6WG44aktkbURNMDBJZU8lMjUyNSUyNTIzJTI1MjQlMjUyM2ZKQU10c0VBRVVPcEgvWVdZdFlxREZuVDBTVg@103.186.155.28:38388#08-0043-VN
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@185.153.197.5:989#08-0044-MD
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpSRkszOENnN0FQbmVTQjVjV0RjcGJt@switcher-nick-croquet.freesocks.work:443#08-0046-NL
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@51.15.17.169:989#08-0047-NL
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpOazlhc2dsRHpIemprdFZ6VGt2aGFB@arxfw2b78fi2q9hzylhn.freesocks.work:443#08-0048-VN
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@192.71.166.100:989#08-0049-GR
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@46.183.184.60:989#08-0050-HR
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA1MS1SRUxBWSIsImFkZCI6InRlc3QzLmZsaGEucnUiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiOWE4MTM0MGQtZjgxYi00Yzc2LThhYmItZjRkMzA1YzUzNWMwIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii85YTgxMzQwZC1mODFiLTRjNzYtOGFiYi1mNGQzMDVjNTM1YzAtdm1lc3MiLCJob3N0IjoidGVzdDMuZmxoYS5ydSIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpvWEdwMSUyNTJCaWhsZktnODI2SA@204.136.10.115:1866#08-0052-CH
    ss://YWVzLTI1Ni1nY206YW1hem9uZ3JlYXR2cG4@54.46.38.22:16888#08-0053-HK
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpRQ1hEeHVEbFRUTUQ3anRnSFVqSW9q@151.242.251.153:8080#08-0054-AE
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA1NS1SRUxBWSIsImFkZCI6IjEwNC4xNi4zOS4yNTUiLCJwb3J0IjoiMjA4MiIsInR5cGUiOiJub25lIiwiaWQiOiJmMWM2NzA1OS05YjUwLTQ4NjYtYmMwYy1hNzI4OGMxYjkyMGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzP2VkPTIwNDgiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA1Ni1JUiIsImFkZCI6Ijg5LjM5LjIwOC4yMTciLCJwb3J0IjoiNzAyMSIsInR5cGUiOiJub25lIiwiaWQiOiJhNWU2Zjc1OC0yZjkzLTQxZjktYmM2My00MGY3ZWZjNTgwMTMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA1Ny1SRUxBWSIsImFkZCI6IjEwNC4xNy4xMTkuMTM1IiwicG9ydCI6IjIwNTIiLCJ0eXBlIjoibm9uZSIsImlkIjoiYmRjN2Q3YzUtYmUwNS0zZGI4LTkzZTktNGQ0MTU3YmZhYTE3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kYWJhaS5pbjEzNTExOTE3IiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA1OC1ISyIsImFkZCI6IjEwMy4zOC44My4yNTMiLCJwb3J0IjoiMzcxMjIiLCJ0eXBlIjoibm9uZSIsImlkIjoiZWRjNDkzY2EtYjkzOS00MDk3LWUwYzMtYzhmZWUyNDNlYWM2IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA1OS1KUCIsImFkZCI6IjE1NC4zMS4xMTIuNTEiLCJwb3J0IjoiMjI5IiwidHlwZSI6Im5vbmUiLCJpZCI6IjQwYmM3YjY1LWVjOGEtMzIwMS1hNjQ2LWM5ZDFiNzEwOTFjNiIsImFpZCI6IjIiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA2MC1ISyIsImFkZCI6IjQ3Ljg2LjQzLjkxIiwicG9ydCI6IjIwNTIxIiwidHlwZSI6Im5vbmUiLCJpZCI6ImUwM2QxNjA5LWNkODgtNDQzZC05MTdiLTgzNDRjMTUyOWE4NSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@156.146.38.170:443#08-0061-USss%2F%2FYWVzLTI1Ni1nY206MGE5MTRlOWEtM2UzYi00NzBmLWEyNjctN2VhNzA4M2M0NWJi%4077.110.110.240443%2323-0062-AT
    ss://YWVzLTI1Ni1nY206YW1hem9uZ3JlYXR2cG4@3.115.88.171:16888#08-0120-JP
    ss://YWVzLTI1Ni1nY206YTdmMDgyYzEtMGQxMi00NjA5LWI2YmYtZTc2MGI2NjhjZjIz@77.110.110.240:443#23-0063-AT
    ss://YWVzLTI1Ni1nY206MTAyYWQzZGEtMmQ1NS00OWQ2LWI4YzgtMmQ3ZTA0ZGYzM2Nh@77.110.110.240:443#23-0065-AT
    ss://YWVzLTI1Ni1nY206M2Y0MGJmM2QtMmYxZS00ZjQzLWJmNTQtZTVmZTc0MmEzYjRl@77.110.110.240:443#23-0066-AT
    ss://YWVzLTI1Ni1nY206ZDcwZWY4YjUtNjA0OC00YzBkLWJlNGQtZmM2MDM5OWIwZjQ1@77.110.110.240:443#23-0067-AT
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpqaWZ1UjJOVE0wWXQ@62.133.62.109:443#23-0068-FR
    vmess://eyJ2IjoiMiIsInBzIjoiMjMtMDA3MS1ERSIsImFkZCI6IjU3LjEyOS4yNC4xMjUiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjAzZmNjNjE4LWI5M2QtNjc5Ni02YWVkLThhMzhjOTc1ZDU4MSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbGlua3Z3cz9lZD0yMDQ4QEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTiIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    ss://YWVzLTEyOC1nY206MTAwODY@160.16.123.124:10087#23-0073-JPss%2F%2FYWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw%40104.192.226.106989%2323-0079-US
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpQdEh2NGJPNGpQdEJzSFdTbDFuNVFk@45.95.232.236:4248#23-0077-CH
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5dHFoTWRJclRrZ1E0NlB2aHlBdE1I@92.112.126.90:443#23-0096-NL
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5bGNDdnpOeHBOc25JTnlhWWZ6Yzhl@212.113.106.76:29149#23-0097-AT
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5ZFZMYWNjR0JxRng@62.60.233.21:443#23-0098-TR
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpVS3Z5aXhLUmRUU3cyOFFwODdrZUVS@macintosh.outlinekeys.net:19609#23-0100-NL
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo0YTJyZml4b3BoZGpmZmE4S1ZBNEFh@45.87.175.171:8080#23-0111-LT
    


</details>

### 所有节点
合并节点总数: `44`
[节点链接](https://raw.githubusercontent.com/caijh/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [clashnode](https://github.com/imyaoxp/clashnode), 节点数量: `44`


## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

