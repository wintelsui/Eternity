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
高速节点数量: `56`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMDAxLUpQIiwiYWRkIjoianAtMS5hbmV3c3RhcnQuY3lvdSIsInBvcnQiOiI1MDYxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjZhZDIyM2RiLWIwMWQtM2E1ZS05ZTAwLTMzZDY3MTMxYWI3ZCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImpwLTEuYW5ld3N0YXJ0LmN5b3UiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMDA0LU5PV0hFUkUiLCJhZGQiOiJ1czYtMS5hbmV3c3RhcnQuY3lvdSIsInBvcnQiOiI1MDYxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjZhZDIyM2RiLWIwMWQtM2E1ZS05ZTAwLTMzZDY3MTMxYWI3ZCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6InVzNi0xLmFuZXdzdGFydC5jeW91IiwidGxzIjoidGxzIn0=
    trojan://c4a282b0-1a8c-3b9a-a9c0-c1f6f2e9134a@gz0slb.aliyuncdn.smp-paymentservices-apple.com:56323?allowInsecure=1&sni=origin-a.akamaihd.net#04-005-NOWHERE
    trojan://c4a282b0-1a8c-3b9a-a9c0-c1f6f2e9134a@gz0slb.aliyuncdn.smp-paymentservices-apple.com:56432?allowInsecure=1&sni=cloudsync-prod.s3.amazonaws.com#04-006-NOWHERE
    trojan://c4a282b0-1a8c-3b9a-a9c0-c1f6f2e9134a@push04.endpoint.smp-paymentservices-apple.com:23452?allowInsecure=1&sni=steampipe.akamaized.net#04-007-CN
    trojan://c4a282b0-1a8c-3b9a-a9c0-c1f6f2e9134a@push04.endpoint.smp-paymentservices-apple.com:23453?allowInsecure=1&sni=steampipe-kr.akamaized.net#04-008-CN
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTA4LVJFTEFZIiwiYWRkIjoiczEuZGItbGluazAxLnRvcCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiIyNmNjZDk0Zi1kOTNmLTNlNzYtYmMxMi0wOTM5ZjJlNTkyZTUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2RhYmFpLmluMTcyLjY3LjczLjEyIiwiaG9zdCI6InMxLmRiLWxpbmswMS50b3AiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTA5LVJFTEFZIiwiYWRkIjoiczEuY24tZGIudG9wIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjI2Y2NkOTRmLWQ5M2YtM2U3Ni1iYzEyLTA5MzlmMmU1OTJlNSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZGFiYWkuaW4xMDQuMjAuMTQuMiIsImhvc3QiOiJzMS5jbi1kYi50b3AiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTEwLVJFTEFZIiwiYWRkIjoiczQuZGItbGluazAxLnRvcCIsInBvcnQiOiIyMDUyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjI2Y2NkOTRmLWQ5M2YtM2U3Ni1iYzEyLTA5MzlmMmU1OTJlNSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZGFiYWkuaW4xMDQuMjUuMTYxLjI1NSIsImhvc3QiOiJzNC5kYi1saW5rMDEudG9wIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTExLVJFTEFZIiwiYWRkIjoiczEuZGItbGluazAxLnRvcCIsInBvcnQiOiIyMDUyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjI2Y2NkOTRmLWQ5M2YtM2U3Ni1iYzEyLTA5MzlmMmU1OTJlNSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZGFiYWkuaW4xMDQuMTkuMTU1LjU2IiwiaG9zdCI6InMxLmRiLWxpbmswMS50b3AiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTEyLVJFTEFZIiwiYWRkIjoiczUuZGItbGluazAxLnRvcCIsInBvcnQiOiI4MDgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjI2Y2NkOTRmLWQ5M2YtM2U3Ni1iYzEyLTA5MzlmMmU1OTJlNSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZGFiYWkuaW4xMDQuMjQuMTUxLjIiLCJob3N0IjoiczUuZGItbGluazAxLnRvcCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTEzLVJFTEFZIiwiYWRkIjoiczUuY24tZGIudG9wIiwicG9ydCI6IjgwODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjZjY2Q5NGYtZDkzZi0zZTc2LWJjMTItMDkzOWYyZTU5MmU1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kYWJhaS5pbjE3Mi42NC43LjEyMSIsImhvc3QiOiJzNS5jbi1kYi50b3AiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTE0LVJFTEFZIiwiYWRkIjoiczQuZGItbGluazAyLnRvcCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiIyNmNjZDk0Zi1kOTNmLTNlNzYtYmMxMi0wOTM5ZjJlNTkyZTUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2RhYmFpLmluMTA0LjI1LjExNS4xMDIiLCJob3N0IjoiczQuZGItbGluazAyLnRvcCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTE1LU5PV0hFUkUiLCJhZGQiOiIxMi5tYW1hbWFqZC5zaXRlIiwicG9ydCI6IjIzNjEyIiwidHlwZSI6Im5vbmUiLCJpZCI6ImJjYjVjZjEzLTM1ZGYtMzgyMi05OGE2LWY2YTdjNmQzM2RlMCIsImFpZCI6IjIiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IjEyLm1hbWFtYWpkLnNpdGUiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTE2LUNOIiwiYWRkIjoiMTcubWFtYW1hamQuc2l0ZSIsInBvcnQiOiIyMzYxNyIsInR5cGUiOiJub25lIiwiaWQiOiJiY2I1Y2YxMy0zNWRmLTM4MjItOThhNi1mNmE3YzZkMzNkZTAiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIxNy5tYW1hbWFqZC5zaXRlIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTE3LUNOIiwiYWRkIjoiMTEubWFtYW1hamQuc2l0ZSIsInBvcnQiOiIyMzYxMSIsInR5cGUiOiJub25lIiwiaWQiOiJiY2I1Y2YxMy0zNWRmLTM4MjItOThhNi1mNmE3YzZkMzNkZTAiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIxMS5tYW1hbWFqZC5zaXRlIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTE4LUNOIiwiYWRkIjoiMTkubWFtYW1hamQuc2l0ZSIsInBvcnQiOiIyMzYxOSIsInR5cGUiOiJub25lIiwiaWQiOiJiY2I1Y2YxMy0zNWRmLTM4MjItOThhNi1mNmE3YzZkMzNkZTAiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIxOS5tYW1hbWFqZC5zaXRlIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTE5LUNOIiwiYWRkIjoiMTYubWFtYW1hamQuc2l0ZSIsInBvcnQiOiIyMzYxNiIsInR5cGUiOiJub25lIiwiaWQiOiJiY2I1Y2YxMy0zNWRmLTM4MjItOThhNi1mNmE3YzZkMzNkZTAiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIxNi5tYW1hbWFqZC5zaXRlIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTIwLUNOIiwiYWRkIjoiMTgubWFtYW1hamQuc2l0ZSIsInBvcnQiOiIyMzYxOCIsInR5cGUiOiJub25lIiwiaWQiOiJiY2I1Y2YxMy0zNWRmLTM4MjItOThhNi1mNmE3YzZkMzNkZTAiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIxOC5tYW1hbWFqZC5zaXRlIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTIxLUNOIiwiYWRkIjoiMTUubWFtYW1hamQuc2l0ZSIsInBvcnQiOiIyMzYxNSIsInR5cGUiOiJub25lIiwiaWQiOiJiY2I1Y2YxMy0zNWRmLTM4MjItOThhNi1mNmE3YzZkMzNkZTAiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIxNS5tYW1hbWFqZC5zaXRlIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTIyLU5PV0hFUkUiLCJhZGQiOiI1Lm1hbWFtYWpkLnNpdGUiLCJwb3J0IjoiMjM2MDUiLCJ0eXBlIjoibm9uZSIsImlkIjoiYmNiNWNmMTMtMzVkZi0zODIyLTk4YTYtZjZhN2M2ZDMzZGUwIiwiYWlkIjoiMiIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiNS5tYW1hbWFqZC5zaXRlIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTIzLUNOIiwiYWRkIjoiMTMubWFtYW1hamQuc2l0ZSIsInBvcnQiOiIyMzYxMyIsInR5cGUiOiJub25lIiwiaWQiOiJiY2I1Y2YxMy0zNWRmLTM4MjItOThhNi1mNmE3YzZkMzNkZTAiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIxMy5tYW1hbWFqZC5zaXRlIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTI0LUNOIiwiYWRkIjoiMTQubWFtYW1hamQuc2l0ZSIsInBvcnQiOiIyMzYxNCIsInR5cGUiOiJub25lIiwiaWQiOiJiY2I1Y2YxMy0zNWRmLTM4MjItOThhNi1mNmE3YzZkMzNkZTAiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIxNC5tYW1hbWFqZC5zaXRlIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMTU1LUNOIiwiYWRkIjoieGRkLmRhc2h1YWkuY3lvdSIsInBvcnQiOiI0NTA3NyIsInR5cGUiOiJub25lIiwiaWQiOiJiYWU2ZTU5NC1kNzY1LTQyM2MtYWIyYy0yZDdmMGUwMmE1NmQiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTQubWFtYW1hamQuc2l0ZSIsInRscyI6IiJ9
    trojan://d0d08cddacc3190ea81b1b792e1b5fde@36.151.251.48:41225?allowInsecure=1&sni=www.baidu.com#05-157-CN
    trojan://d0d08cddacc3190ea81b1b792e1b5fde@36.151.251.48:16158?allowInsecure=1&sni=www.baidu.com#05-158-CN
    trojan://d0d08cddacc3190ea81b1b792e1b5fde@36.151.251.48:44123?allowInsecure=1&sni=www.baidu.com#05-159-CN
    ss://MjAyMi1ibGFrZTMtYWVzLTEyOC1nY206MTJ4R1JtY0V5M1RWRVR6RTQ3TXJlQSUyNTNEJTI1M0Q@183.240.187.198:34664#09-184-CN
    trojan://trojan@109.234.211.66:8443?allowInsecure=1&sni=store.timimi.dpdns.org&ws=1&wspath=%2525252F#09-200-RELAY
    trojan://trojan@91.193.58.0:443?allowInsecure=1&sni=wahaha.yingyangkuaixian.dpdns.org&ws=1&wspath=%2525252F#09-228-RELAY
    trojan://tg-fq521free@45.67.215.95:443?allowInsecure=1&sni=torjan.xn--xhq44j.eu.org&ws=1&wspath=%2525252F#09-290-RU
    ss://YWVzLTI1Ni1nY206VEclMjUzQSUyNTQwRW5rZWx0ZV9ub3RpZiUyNTI2JTI1MjZURyUyNTNBJTI1NDBOb3RpZl9DaGF0@152.53.2.128:34045#14-413-AT
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@103.163.218.2:989#14-415-VN
    vmess://eyJ2IjoiMiIsInBzIjoiMTQtNDE3LUNOIiwiYWRkIjoidjMzLmhlZHVpYW4ubGluayIsInBvcnQiOiIzMDgzMyIsInR5cGUiOiJub25lIiwiaWQiOiJjYmIzZjg3Ny1kMWZiLTM0NGMtODdhOS1kMTUzYmZmZDU0ODQiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiL29vb28iLCJob3N0IjoidjMzLmhlZHVpYW4ubGluayIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1nY206MTkyOGFhNGQ2ZTNjOGRmMw@203.32.26.81:19028#14-418-KR
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@185.231.233.112:989#14-420-PT
    vmess://eyJ2IjoiMiIsInBzIjoiMTQtNDIyLUNOIiwiYWRkIjoidjguaGVkdWlhbi5saW5rIiwicG9ydCI6IjMwODA4IiwidHlwZSI6Im5vbmUiLCJpZCI6ImNiYjNmODc3LWQxZmItMzQ0Yy04N2E5LWQxNTNiZmZkNTQ4NCIsImFpZCI6IjIiLCJuZXQiOiJ3cyIsInBhdGgiOiIvb29vbyIsImhvc3QiOiJ2OC5oZWR1aWFuLmxpbmsiLCJ0bHMiOiIifQ==
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpvWklvQTY5UTh5aGNRVjhrYTNQYTNB@45.87.175.28:8080#14-423-LT
    trojan://7367d04e-4c59-4dff-a50e-12e730a09891@155.117.228.70:26193?allowInsecure=1#14-424-HK
    trojan://tg-fq521free@198.62.62.67:443?allowInsecure=1&sni=torjan.xn--xhq44j.eu.org&ws=1&wspath=%2525252F#14-426-US
    ss://YWVzLTI1Ni1nY206YXRqZ3NKWG1jdg@103.15.91.171:52327#14-428-VN
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@156.146.62.161:443#14-431-CH
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@156.146.62.163:443#14-432-CH
    trojan://Aimer@103.116.7.189:443?allowInsecure=1&sni=amepo.ambercc.filegear-sg.me#23-447-RELAY
    trojan://51c44c4e-f8c2-4419-a52b-b4b7bd915078@ap.liangyuandian.top:443?allowInsecure=1#23-448-SG
    ss://YWVzLTI1Ni1jZmI6WG44aktkbURNMDBJZU8lMjUyNSUyNTIzJTI1MjQlMjUyM2ZKQU10c0VBRVVPcEgvWVdZdFlxREZuVDBTVg@103.186.155.24:38388#23-449-VN
    trojan://Aimer@66.81.247.88:2083?allowInsecure=1&sni=amepo.ambercc.filegear-sg.me#23-454-RELAY
    trojan://Aimer@154.197.64.240:8443?allowInsecure=1&sni=amepo.ambercc.filegear-sg.me#23-456-RELAY
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozNjBlMjFkMjE5NzdkYzEx@103.111.114.29:57456#23-466-IN
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpKZ3lLZDlwNWpkWldxNXdxSlJvUXJF@104.192.227.162:443#23-474-US
    trojan://Aimer@92.243.74.3:8443?allowInsecure=1&sni=amepo.ambercc.filegear-sg.me#23-478-RELAY
    trojan://Aimer@199.34.228.187:443?allowInsecure=1&sni=amepo.ambercc.filegear-sg.me#23-486-US
    trojan://Aimer@216.198.53.212:8443?allowInsecure=1&sni=amepo.ambercc.filegear-sg.me#23-493-RELAY
    vmess://eyJ2IjoiMiIsInBzIjoiMjMtNDk5LUNIIiwiYWRkIjoiMTg2LjE5MC4yMTUuMTkzIiwicG9ydCI6IjIyMzI0IiwidHlwZSI6Im5vbmUiLCJpZCI6IjA0NjIxYmFlLWFiMzYtMTFlYy1iOTA5LTAyNDJhYzEyMDAwMiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiJhbWVwby5hbWJlcmNjLmZpbGVnZWFyLXNnLm1lIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMjMtNTA0LVNFIiwiYWRkIjoiMTY5LjE1MC4yMDguODMiLCJwb3J0IjoiMTgwMDAiLCJ0eXBlIjoibm9uZSIsImlkIjoiZjhjOGRjM2QtMGQzNy00NmIwLThiMzQtYTcyMzI4ODJmY2ZlIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6ImFtZXBvLmFtYmVyY2MuZmlsZWdlYXItc2cubWUiLCJ0bHMiOiIifQ==
    


</details>

### 所有节点
合并节点总数: `158`
[节点链接](https://raw.githubusercontent.com/caijh/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [clashnode](https://github.com/imyaoxp/clashnode), 节点数量: `158`


## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

