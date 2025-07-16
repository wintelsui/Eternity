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
高速节点数量: `44`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMDAxLUpQIiwiYWRkIjoianAtMS5hbmV3c3RhcnQuY3lvdSIsInBvcnQiOiI1MDYxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjZhZDIyM2RiLWIwMWQtM2E1ZS05ZTAwLTMzZDY3MTMxYWI3ZCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImpwLTEuYW5ld3N0YXJ0LmN5b3UiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMDA0LU5PV0hFUkUiLCJhZGQiOiJ1czYtMS5hbmV3c3RhcnQuY3lvdSIsInBvcnQiOiI1MDYxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjZhZDIyM2RiLWIwMWQtM2E1ZS05ZTAwLTMzZDY3MTMxYWI3ZCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6InVzNi0xLmFuZXdzdGFydC5jeW91IiwidGxzIjoidGxzIn0=
    trojan://842c54f4-c4b8-3139-ba3d-eddb97e56b0e@gz0slb.aliyuncdn.smp-paymentservices-apple.com:56323?allowInsecure=1&sni=origin-a.akamaihd.net#04-005-NOWHERE
    trojan://842c54f4-c4b8-3139-ba3d-eddb97e56b0e@gz0slb.aliyuncdn.smp-paymentservices-apple.com:56432?allowInsecure=1&sni=cloudsync-prod.s3.amazonaws.com#04-006-NOWHERE
    trojan://842c54f4-c4b8-3139-ba3d-eddb97e56b0e@push04.endpoint.smp-paymentservices-apple.com:23452?allowInsecure=1&sni=steampipe.akamaized.net#04-007-CN
    trojan://842c54f4-c4b8-3139-ba3d-eddb97e56b0e@push04.endpoint.smp-paymentservices-apple.com:23453?allowInsecure=1&sni=steampipe-kr.akamaized.net#04-008-CN
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTA4LVJFTEFZIiwiYWRkIjoiczQuZGItbGluazAyLnRvcCIsInBvcnQiOiIyMDUyIiwidHlwZSI6Im5vbmUiLCJpZCI6ImNhOWMyZTAzLTg2MDctMzJiMS1iY2MyLTEyODgxNTM4YTRjZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZGFiYWkuaW4xMDQuMjUuNzYuMTMiLCJob3N0IjoiczQuZGItbGluazAyLnRvcCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTA5LVJFTEFZIiwiYWRkIjoiczIuZGItbGluazAyLnRvcCIsInBvcnQiOiI4MDgwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImNhOWMyZTAzLTg2MDctMzJiMS1iY2MyLTEyODgxNTM4YTRjZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZGFiYWkuaW4xNzIuNjQuMy4xNDgiLCJob3N0IjoiczIuZGItbGluazAyLnRvcCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTEwLVJFTEFZIiwiYWRkIjoiczQuZGItbGluazAxLnRvcCIsInBvcnQiOiIyMDg2IiwidHlwZSI6Im5vbmUiLCJpZCI6ImNhOWMyZTAzLTg2MDctMzJiMS1iY2MyLTEyODgxNTM4YTRjZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZGFiYWkuaW4xMDQuMjEuMTgxLjM5IiwiaG9zdCI6InM0LmRiLWxpbmswMS50b3AiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTExLVJFTEFZIiwiYWRkIjoiczEuZGItbGluazAxLnRvcCIsInBvcnQiOiIyMDgyIiwidHlwZSI6Im5vbmUiLCJpZCI6ImNhOWMyZTAzLTg2MDctMzJiMS1iY2MyLTEyODgxNTM4YTRjZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZGFiYWkuaW4xNzIuNjQuMTAuODEiLCJob3N0IjoiczEuZGItbGluazAxLnRvcCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTEyLVJFTEFZIiwiYWRkIjoiczUuZGItbGluazAyLnRvcCIsInBvcnQiOiIyMDg2IiwidHlwZSI6Im5vbmUiLCJpZCI6ImNhOWMyZTAzLTg2MDctMzJiMS1iY2MyLTEyODgxNTM4YTRjZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZGFiYWkuaW4xMDQuMjAuMTE4LjEwNCIsImhvc3QiOiJzNS5kYi1saW5rMDIudG9wIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTEzLVJFTEFZIiwiYWRkIjoiczUuY24tZGIudG9wIiwicG9ydCI6IjIwOTUiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2E5YzJlMDMtODYwNy0zMmIxLWJjYzItMTI4ODE1MzhhNGNmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kYWJhaS5pbjE3Mi42NC4xMy4xNjEiLCJob3N0IjoiczUuY24tZGIudG9wIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDQtMTE0LVJFTEFZIiwiYWRkIjoiczMuY24tZGIudG9wIiwicG9ydCI6IjgwODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2E5YzJlMDMtODYwNy0zMmIxLWJjYzItMTI4ODE1MzhhNGNmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kYWJhaS5pbjEwNC4xNi43LjIyNiIsImhvc3QiOiJzMy5jbi1kYi50b3AiLCJ0bHMiOiIifQ==
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
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMTI3LVJFTEFZIiwiYWRkIjoiNGMyMGNiLmQwNmM0MTc3LnNob3AiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTUyNzk3YjYtMjFhMC00ZTY2LTkyMzktMzBlZjVjMGVmY2RmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiNGMyMGNiLmQwNmM0MTc3LnNob3AiLCJ0bHMiOiIifQ==
    ss://MjAyMi1ibGFrZTMtYWVzLTEyOC1nY206MTJ4R1JtY0V5M1RWRVR6RTQ3TXJlQSUyNTNEJTI1M0Q@183.240.187.198:34664#09-154-CN
    trojan://trojan@109.234.211.66:8443?allowInsecure=1&sni=store.timimi.dpdns.org&ws=1&wspath=%2525252F#09-171-RELAY
    trojan://trojan@91.193.58.0:443?allowInsecure=1&sni=wahaha.yingyangkuaixian.dpdns.org&ws=1&wspath=%2525252F#09-199-RELAY
    trojan://tg-fq521free@45.67.215.95:443?allowInsecure=1&sni=torjan.xn--xhq44j.eu.org&ws=1&wspath=%2525252F#09-261-RU
    ss://YWVzLTI1Ni1nY206aVVCMDkyM1JCQQ@154.3.8.151:30067#14-386-US
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@185.153.197.5:989#14-387-MD
    trojan://tg-fq521free@198.62.62.67:443?allowInsecure=1&sni=torjan.xn--xhq44j.eu.org&ws=1&wspath=%2525252F#14-388-US
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@46.183.185.37:989#23-390-MK
    trojan://f282b878-8711-45a1-8c69-5564172123c1@172.67.181.173:443?allowInsecure=1&sni=vpn.stupidworld.web.id&ws=1&wspath=%2525252F#23-391-RELAY
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozNjBlMjFkMjE5NzdkYzEx@185.193.102.7:57456#23-403-FI
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpVS0s1WFV2aklsT2tlVGJCQTBuZllo@2.56.207.150:8443#23-408-AM
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpuUVNBUk9UaE9iTVcxbksyMnRoajZK@83.172.138.137:8443#23-409-DE
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpFSlFmRkZMMnJtMXNHMDVmUlIxN0ZN@154.205.147.68:8443#23-410-OM
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowdGNickgwR1FObUdKeEdNNWRrZURo@46.246.90.6:8443#23-411-SE
    trojan://telegram-id-directvpn@3.68.174.66:22223?allowInsecure=1&sni=trojan.burgerip.co.uk#23-412-DE
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpPVUVSaXl4dnJ6VEppNWtmdHg5ODBH@213.111.142.216:8443#23-416-US
    ss://YWVzLTI1Ni1nY206ZDk4OWZmM2Q0NmE2M2Y2Mw@185.22.152.92:10111#23-440-RU
    ss://YWVzLTI1Ni1jZmI6WG44aktkbURNMDBJZU8lMjUyNSUyNTIzJTI1MjQlMjUyM2ZKQU10c0VBRVVPcEgvWVdZdFlxREZuVDBTVg@103.186.154.35:38388#23-444-VN
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpvWklvQTY5UTh5aGNRVjhrYTNQYTNB@193.29.139.251:8080#23-465-NL
    


</details>

### 所有节点
合并节点总数: `141`
[节点链接](https://raw.githubusercontent.com/caijh/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [clashnode](https://github.com/imyaoxp/clashnode), 节点数量: `141`


## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

