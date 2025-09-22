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
高速节点数量: `50`
<details>
  <summary>展开复制节点</summary>

    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@156.146.40.194:989#05-0000-SK
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDAwMS1ISyIsImFkZCI6IjFlNDI2MDQ2LXQwZmRzMC10MTJjbmotMW9sOTcuaGsucDVwdi5jb20iLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTNmYjY5ZmMtNzdjZi0xMWVlLTg1ZWUtZjIzYzkxMzY5ZjJkIiwiYWlkIjoiMiIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiMWU0MjYwNDYtdDBmZHMwLXQxMmNuai0xb2w5Ny5oay5wNXB2LmNvbSIsInRscyI6IiJ9
    trojan://wb6368@92.243.75.49:2087?allowInsecure=1&sni=hsdgbuys.pages.dev&ws=1&wspath=%2525252F#05-0008-RELAY
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDAwOS1SRUxBWSIsImFkZCI6ImRkZHZ2Ym4uOTMxLnBwLnVhIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MTc0Yjk1ZC0xMTVlLTRkMzktYWRkNi0xZjhkYjk1YmI4NjAiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzZXZTNVOURmMVdHeGdGbm9GUHcxIiwiaG9zdCI6ImRkZHZ2Ym4uOTMxLnBwLnVhIiwidGxzIjoidGxzIn0=
    trojan://o6x5BZAuSj@creativecommons.org:2053?allowInsecure=1&sni=mooshali.arshiacomplus.dpdns.org&ws=1&wspath=%2525252Fhishhhh123#05-0018-RELAY
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpRQ1hEeHVEbFRUTUQ3anRnSFVqSW9q@45.158.171.146:8080#05-0137-FR
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNToxUld3WGh3ZkFCNWdBRW96VTRHMlBn@45.158.171.146:8080#05-0139-FR
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo0YTJyZml4b3BoZGpmZmE4S1ZBNEFh@45.158.171.146:8080#05-0140-FR
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTplNDQ2OTMxMC0wMGZjLTQ1MjctOGFmYS03MTc4OGIzYmNlZjc@gw.liangyuandianwan.com:35602#06-0024-CN
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTplNDQ2OTMxMC0wMGZjLTQ1MjctOGFmYS03MTc4OGIzYmNlZjc@gw.liangyuandianwan.com:35603#06-0025-CN
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5MTc3ZGUxYS1hZWZmLTQzZjEtOTNhNi03ZGQwOGEyZmRjNDE@pr.fastsoonlink.com:40030#06-0026-PL
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5MTc3ZGUxYS1hZWZmLTQzZjEtOTNhNi03ZGQwOGEyZmRjNDE@us.fastsoonlink.com:40001#06-0027-US
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5MTc3ZGUxYS1hZWZmLTQzZjEtOTNhNi03ZGQwOGEyZmRjNDE@sgp.fastsoonlink.com:40005#06-0028-SG
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5MTc3ZGUxYS1hZWZmLTQzZjEtOTNhNi03ZGQwOGEyZmRjNDE@ru.fastsoonlink.com:40031#06-0029-RU
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5MTc3ZGUxYS1hZWZmLTQzZjEtOTNhNi03ZGQwOGEyZmRjNDE@fr.fastsoonlink.com:40034#06-0030-FR
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5MTc3ZGUxYS1hZWZmLTQzZjEtOTNhNi03ZGQwOGEyZmRjNDE@frk.fastsoonlink.com:40011#06-0031-AU
    vmess://eyJ2IjoiMiIsInBzIjoiMDYtMDAzMi1DTiIsImFkZCI6InYyNC5oZWR1aWFuLmxpbmsiLCJwb3J0IjoiMzA4MjQiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2JiM2Y4NzctZDFmYi0zNDRjLTg3YTktZDE1M2JmZmQ1NDg0IiwiYWlkIjoiMiIsIm5ldCI6IndzIiwicGF0aCI6Ii9vb29vIiwiaG9zdCI6InYyNC5oZWR1aWFuLmxpbmsiLCJ0bHMiOiIifQ==
    trojan://0C3YaEDx46ODTFTcaF8lXlZ3zeqSlF33wZagexzRjIyODa8RDwp8XSCO93ygCSYcSYABA@blength.appagent.net:18332?allowInsecure=1#06-0043-US
    trojan://eYaw9xlNDu4695IF3CyY2leZOTnY8ZSOD3Xa3DClz0xqZy7Z3eaBFaTKOSwCSAOyEap4D@connect.appagent.net:28333?allowInsecure=1&sni=connect.appagent.net#06-0044-US
    trojan://CZC2eFReAwaON4nzF3zY7XC9nB3IqIaT3Eaa8S7D3B5Y3XuSEp8Z0ygl08S3SSxy6wDRC@blender.appagent.net:28332?allowInsecure=1&sni=blender.appagent.net#06-0045-US
    trojan://OaFFcTDe9pSlez6x3SY8AARXwClzCRRDwSN8F3OqZAEYC0SE6F8gp3wCTCSTDYllcNceagCDD2C59S3@bolster.appagent.net:28332?allowInsecure=1#06-0046-US
    trojan://Npgx9nO3OBaZF5yxARYl93lFX08TlR3waDla733az8SqXe3YS3zjESECSZpAw428a6SID@metallic.isquirrel.net:443?allowInsecure=1#06-0048-US
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@185.213.23.226:989#08-0058-NO
    ss://YWVzLTI1Ni1nY206N2UxZGQ0YzU1YmY4NWRhNQ@212.192.12.77:30398#08-0059-HKtrojan%2F%2FF9OKESxKjSDExSeaOw7xyINxDzaOZqeKxCeIczYYED8ewZ2Yl9AppAySO3xwFNy3lCaXDDCFnlACSB0%40pricey.appagent.net28334%3FallowInsecure%3D1%2306-0050-US
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@51.15.17.169:989#08-0061-NL
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@154.90.62.168:989#08-0062-KR
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpwNzhuYUNmMkVmT2xSU0xUWDB3RlZ4@pupas-shirting-unsung.freesocks.work:443#08-0063-US
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@154.223.16.212:989#08-0064-CO
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA2NS1ISyIsImFkZCI6ImhrdC5nb3RvY2hpbmF0b3duLm5ldCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI5M2ZiNjlmYy03N2NmLTExZWUtODVlZS1mMjNjOTEzNjlmMmQiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJoa3QuZ290b2NoaW5hdG93bi5uZXQiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA2Ny1ISyIsImFkZCI6IjY5N2RjNTUxLXQxaTlzMC10bTUzY20tMW9sOTcuaGszLnA1cHYuY29tIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjkzZmI2OWZjLTc3Y2YtMTFlZS04NWVlLWYyM2M5MTM2OWYyZCIsImFpZCI6IjIiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IjY5N2RjNTUxLXQxaTlzMC10bTUzY20tMW9sOTcuaGszLnA1cHYuY29tIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@37.235.49.168:989#08-0068-IS
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@192.71.166.100:989#08-0069-GR
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@154.90.63.177:989#08-0149-KR
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@38.165.233.93:989#08-0150-PY
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpOazlhc2dsRHpIemprdFZ6VGt2aGFB@arxfw2b78fi2q9hzylhn.freesocks.work:443#08-0151-VN
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@185.153.197.5:989#08-0152-MD
    ss://YWVzLTI1Ni1nY206MGE5MTRlOWEtM2UzYi00NzBmLWEyNjctN2VhNzA4M2M0NWJi@77.110.110.240:443#23-0070-AT
    ss://YWVzLTI1Ni1nY206YTdmMDgyYzEtMGQxMi00NjA5LWI2YmYtZTc2MGI2NjhjZjIz@77.110.110.240:443#23-0071-AT
    ss://YWVzLTI1Ni1nY206MTAyYWQzZGEtMmQ1NS00OWQ2LWI4YzgtMmQ3ZTA0ZGYzM2Nh@77.110.110.240:443#23-0073-AT
    ss://YWVzLTI1Ni1nY206M2Y0MGJmM2QtMmYxZS00ZjQzLWJmNTQtZTVmZTc0MmEzYjRl@77.110.110.240:443#23-0074-AT
    ss://YWVzLTI1Ni1nY206ZDcwZWY4YjUtNjA0OC00YzBkLWJlNGQtZmM2MDM5OWIwZjQ1@77.110.110.240:443#23-0075-AT
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpqaWZ1UjJOVE0wWXQ@62.133.62.109:443#23-0076-FR
    ss://YWVzLTEyOC1nY206MTAwODY@160.16.123.124:10087#23-0081-JP
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpQdEh2NGJPNGpQdEJzSFdTbDFuNVFk@45.95.232.236:4248#23-0085-CH
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5dHFoTWRJclRrZ1E0NlB2aHlBdE1I@92.112.126.90:443#23-0103-NL
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5bGNDdnpOeHBOc25JTnlhWWZ6Yzhl@212.113.106.76:29149#23-0104-AT
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5ZFZMYWNjR0JxRng@62.60.233.21:443#23-0105-TR
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpVS3Z5aXhLUmRUU3cyOFFwODdrZUVS@macintosh.outlinekeys.net:19609#23-0107-NL
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo0YTJyZml4b3BoZGpmZmE4S1ZBNEFh@45.87.175.171:8080#23-0118-LT
    


</details>

### 所有节点
合并节点总数: `54`
[节点链接](https://raw.githubusercontent.com/caijh/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [clashnode](https://github.com/imyaoxp/clashnode), 节点数量: `54`


## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

