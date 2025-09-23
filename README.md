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
高速节点数量: `51`
<details>
  <summary>展开复制节点</summary>

    trojan://02XtoczO7V@creativecommons.org:443?allowInsecure=1&sni=mooshali.arshiacomplus.dpdns.org&ws=1&wspath=%2525252Fhishhhh123#05-0011-RELAY
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDAxNC1HQiIsImFkZCI6IjUxLjc1LjE2MC4yMzciLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjNhZGJhNDYyLTMxOGYtNGE2Yy1hZDdhLTI5MjNiYzc0ZjIwNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbGlua3Zrd3NzIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpBemRHNFBRTVpsVUhkWlNFVDkwN2Ny@185.247.118.230:4362#05-0015-DE
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDAxNi1GUiIsImFkZCI6IjU3LjEyOC4xODkuMjQwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIwM2ZjYzYxOC1iOTNkLTY3OTYtNmFlZC04YTM4Yzk3NWQ1ODEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2xpbmt2d3MiLCJob3N0IjoiIiwidGxzIjoidGxzIn0=
    trojan://a94fafdb-10d6-46c2-be8a-5c2e8358fbb0@172.67.187.28:443?allowInsecure=1&sni=dddDdDdDDFfFf.iran2035.dPdNS.ORG&ws=1&wspath=%2525252Fxa846InEcmjyiKVby2Lp#05-0017-RELAY
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDAyMS1SRUxBWSIsImFkZCI6ImVmN2MyMzgzLTAzYmItZmVjMi0zMjdiLTM0ZjZiMmFjZTdjYi5mcmVldnBuYXRtMjAyNS5kcGRucy5vcmciLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjM0YTdkYTBjLWE0M2EtNDliOC1hOGQwLTY0YjQzMTAwMDkwZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZTdKUzVFVEplQTg1VnlqUENZWHdFVEwiLCJob3N0IjoiZWY3YzIzODMtMDNiYi1mZWMyLTMyN2ItMzRmNmIyYWNlN2NiLmZyZWV2cG5hdG0yMDI1LmRwZG5zLm9yZyIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDEzOS1NWSIsImFkZCI6IjIxMS4yNS4yNDYuMTMxIiwicG9ydCI6IjM0NzgxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjdkZDIwMDdiLTBjZDAtNGJhYy1hOGRmLTM0NDhiNTk1NDVmZCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYXJraSIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDE1Mi1ISyIsImFkZCI6IjY5N2RjNTUxLXQxaTlzMC10bTUzY20tMW9sOTcuaGszLnA1cHYuY29tIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjkzZmI2OWZjLTc3Y2YtMTFlZS04NWVlLWYyM2M5MTM2OWYyZCIsImFpZCI6IjIiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IjY5N2RjNTUxLXQxaTlzMC10bTUzY20tMW9sOTcuaGszLnA1cHYuY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDE1NS1TQyIsImFkZCI6IjE1NC4yMDEuODAuMjE0IiwicG9ydCI6IjExMTU5IiwidHlwZSI6Im5vbmUiLCJpZCI6ImQ5MjAyZmRkLTU2NzktNDNhNy1hOTMzLTBkMDc2MDViYWIzYyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYXJraSIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDE1Ni1ISyIsImFkZCI6IjguMjE3LjE3MS4xOTMiLCJwb3J0IjoiMzYzMDAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjc4Y2RiMTQtMjJhNi00ZmIyLWEwNDAtYjM1M2VjYjk4OWNlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDE1OC1ISyIsImFkZCI6IjguMjE3LjIyMC4zMCIsInBvcnQiOiIzMTEyMyIsInR5cGUiOiJub25lIiwiaWQiOiIxMmY3MTY0Yi1lM2UxLTQyNjQtODZjYy02ODAyODkwMmNkMTkiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2Fya2kiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDE1OS1ISyIsImFkZCI6IjguMjE3LjIyMC4zMCIsInBvcnQiOiIzOTY0OCIsInR5cGUiOiJub25lIiwiaWQiOiIyYzI1ODNiNi1lY2UwLTRkM2QtYTdmNS1jZjM3YzRhNmZhOGQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2Fya2kiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDE2MC1ISyIsImFkZCI6IjQ3LjIzOS44MS4xMTMiLCJwb3J0IjoiMjk3NjAiLCJ0eXBlIjoibm9uZSIsImlkIjoiZmQyOTg3Y2MtYjI1Zi00OTY2LTg0NmEtYjBkNjVkM2MxZTRiIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDE2MS1ISyIsImFkZCI6IjQ3Ljc2LjE1Ny4yMzQiLCJwb3J0IjoiMTQ0NzkiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTA2MDZjMTQtY2JhNC00M2ZmLTk1ODYtOWVkZDhiZWYyMWE0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDE2Mi1ISyIsImFkZCI6IjguMjE4LjguODQiLCJwb3J0IjoiMjMzMjYiLCJ0eXBlIjoibm9uZSIsImlkIjoiODcxZDA0ZGYtZmM1OC00NzBhLWJhY2EtZGFhZTI4ODY5MTY0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDYtMDAyNC1KUCIsImFkZCI6IjMxLjU3LjE3Mi4yMzUiLCJwb3J0IjoiNTE4OTciLCJ0eXBlIjoibm9uZSIsImlkIjoiMmIyODFjNTYtM2ZjMi00NDljLWFiMzktYTdkYTVhMDIyNDA0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDYtMDAyNi1HQiIsImFkZCI6IjE3Mi4xOTIuMjYuMTYxIiwicG9ydCI6IjI2OTMxIiwidHlwZSI6Im5vbmUiLCJpZCI6ImVhN2IwMTczLWEyN2MtNGVhMS1hMTU2LWNkNjBjMjFlMzUzNiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@51.15.17.169:989#06-0038-NL
    vmess://eyJ2IjoiMiIsInBzIjoiMDYtMDA1MC1KUCIsImFkZCI6IjE1OC4xMDEuMTMwLjIzOCIsInBvcnQiOiIyMzk3MiIsInR5cGUiOiJub25lIiwiaWQiOiJhMTJmMWFhMi05NmMyLTRlYjItZjMzMi1mYTdkN2FmMjY1YTQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDYtMDA1OC1NWSIsImFkZCI6IjM4LjU0Ljk4LjExMCIsInBvcnQiOiIyMDUyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjY2NWQ5YjhmLTE1M2QtNDkwNy1hZGFjLWRlMTJhZmQ5Yzg1MSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    trojan://tunnel-astrovpn_official928@206.206.126.109:8441?allowInsecure=1&sni=zula.ir.AstroVPN-official.AstroVPN-official.workers.dev.AstroVPN_Official.org.AstroVPN.com.AstroVPN_Official.xyz.AstroVPN_Official.AstroVPN_Official.AstroVPN_Official.AstroVPN_Official.AstroVPN_Official.AstroVPN_Official.AstroVPN_Official.AstroVPN_Official.monster.AstroVPN_OfficialJoinTelegram-------------AstroVPN_Official----------Join.ir#06-0065-SG
    vmess://eyJ2IjoiMiIsInBzIjoiMDYtMDA4MC1SRUxBWSIsImFkZCI6ImNmLjg3Nzc3NC54eXoiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjJjODMzYzVkLWNiY2MtNGFmYi04OWJhLWQxN2RjMzlkYjZmMCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvdm1lc3MtYXJnbz9lZD0yNTYwIiwiaG9zdCI6ImNmLjg3Nzc3NC54eXoiLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1jZmI6WG44aktkbURNMDBJZU8lMjUyNSUyNTIzJTI1MjQlMjUyM2ZKQU10c0VBRVVPcEgvWVdZdFlxREZuVDBTVg@103.186.155.16:38388#06-0081-VN
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@154.90.63.177:989#08-0082-KR
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@154.90.62.168:989#08-0083-KR
    ss://YWVzLTI1Ni1jZmI6WG44aktkbURNMDBJZU8lMjUyNSUyNTIzJTI1MjQlMjUyM2ZKQU10c0VBRVVPcEgvWVdZdFlxREZuVDBTVg@103.186.154.152:38388#08-0085-VN
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@154.223.16.212:989#08-0086-CO
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@46.183.184.60:989#08-0087-HR
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@37.235.49.168:989#08-0088-IS
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@38.165.233.93:989#08-0089-PY
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@185.153.197.5:989#08-0090-MD
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@156.146.40.194:989#08-0091-SK
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpOazlhc2dsRHpIemprdFZ6VGt2aGFB@arxfw2b78fi2q9hzylhn.freesocks.work:443#08-0092-VN
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@185.213.23.226:989#08-0169-NO
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNToyakNNTEZQM3kwamsyRW1BZzdOeWd0@194.87.45.189:443#23-0113-ES
    trojan://df36ace8-640b-42bb-8169-198901af6d9e@185.184.68.7.sslip.io:443?allowInsecure=1&sni=185.184.68.7.sslip.io&ws=1&wspath=%2525252FhH2W0g0FgNjEuZUTo#23-0128-US
    vmess://eyJ2IjoiMiIsInBzIjoiMjMtMDEyOS1VUyIsImFkZCI6IjE4NS4xODQuNjguNy5zc2xpcC5pbyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiZGYzNmFjZTgtNjQwYi00MmJiLTgxNjktMTk4OTAxYWY2ZDllIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9ZRmhScXZRVGlGZ05qRXVaVVRvIiwiaG9zdCI6IjE4NS4xODQuNjguNy5zc2xpcC5pbyIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowTmVONXRhN0ZMYTVCOURMeXRVMHVt@212.34.140.184:443#23-0177-NL
    trojan://telegram-id-directvpn@18.153.45.158:22223?allowInsecure=1&sni=trojan.burgerip.co.uk#23-0178-DE
    trojan://telegram-id-privatevpns@18.153.45.158:22222?allowInsecure=1&sni=trojan.burgerip.co.uk#23-0179-DE
    trojan://telegram-id-directvpn@13.36.206.216:22223?allowInsecure=1&sni=trojan.burgerip.co.uk#23-0184-FR
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@212.102.53.194:443#23-0185-GB
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@212.102.53.80:443#23-0186-GB
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@212.102.53.198:443#23-0187-GB
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@212.102.53.81:443#23-0190-GB
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@156.146.62.163:443#23-0191-CH
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@149.34.244.82:443#23-0192-NL
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@149.34.244.68:443#23-0194-NL
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTplVWg0bFNwaTduT1lqMHZTcnFMVWgw@95.163.176.37:8506#23-0196-AT
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpvWklvQTY5UTh5aGNRVjhrYTNQYTNB@45.87.175.92:8080#23-0197-LT
    


</details>

### 所有节点
合并节点总数: `55`
[节点链接](https://raw.githubusercontent.com/caijh/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [clashnode](https://github.com/imyaoxp/clashnode), 节点数量: `55`


## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

