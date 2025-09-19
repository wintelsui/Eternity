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
高速节点数量: `40`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDAwMS1DTiIsImFkZCI6InY1LmhlZHVpYW4ubGluayIsInBvcnQiOiIzMDgwNSIsInR5cGUiOiJub25lIiwiaWQiOiJjYmIzZjg3Ny1kMWZiLTM0NGMtODdhOS1kMTUzYmZmZDU0ODQiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiL29vb28iLCJob3N0IjoidjUuaGVkdWlhbi5saW5rIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDAxMi1GUiIsImFkZCI6IjUxLjc3LjIyMC4xNzkiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ3Yjc4MWExLWQwMmYtNDczZS1hNTFkLTg0MzZhZTczZjI2NSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbGlua3dzIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    ss://Y2hhY2hhMjAtaWV0Zjphc2QxMjM0NTY@103.36.91.32:8388#05-0017-SG
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDEyMi1ERSIsImFkZCI6IjU3LjEyOS4yNC4xMzEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjAzZmNjNjE4LWI5M2QtNjc5Ni02YWVkLThhMzhjOTc1ZDU4MSIsImFpZCI6IjEiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbGlua3Z3cyIsImhvc3QiOiIiLCJ0bHMiOiJ0bHMifQ==
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo0OWRhZGQzYy1mM2NmLTQ4NjgtYmM2Yi1hNjFjYjA0OWFiMWI@autf.cokecloud.top:18071#06-0022-CN
    vmess://eyJ2IjoiMiIsInBzIjoiMDYtMDAyMy1DTiIsImFkZCI6ImZyZy5jb2tlY2xvdWQudG9wIiwicG9ydCI6IjEzNjQ2IiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ5ZGFkZDNjLWYzY2YtNDg2OC1iYzZiLWE2MWNiMDQ5YWIxYiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImZyZy5jb2tlY2xvdWQudG9wIiwidGxzIjoiIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo0OWRhZGQzYy1mM2NmLTQ4NjgtYmM2Yi1hNjFjYjA0OWFiMWI@xcsgp.cokecloud.top:29631#06-0024-CN
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo0OWRhZGQzYy1mM2NmLTQ4NjgtYmM2Yi1hNjFjYjA0OWFiMWI@xckr.cokecloud.top:33167#06-0025-CN
    trojan://453121aa-6c1d-33ed-a175-cb46aa8f22f0@suningyunyou.judelvin.com:13028?allowInsecure=1&sni=3t49hrhac.qqtoup81.top#06-0026-CN
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo0OWRhZGQzYy1mM2NmLTQ4NjgtYmM2Yi1hNjFjYjA0OWFiMWI@xcsgp.cokecloud.top:11277#06-0027-CN
    trojan://453121aa-6c1d-33ed-a175-cb46aa8f22f0@suningyunyou.judelvin.com:13033?allowInsecure=1&sni=hg2983hrfx.qqtoup81.top#06-0028-CN
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpPM2s1dTc5UnpjOGZBY3dMZjJjUXkz@142.93.166.6:80#06-0029-DE
    trojan://1640ef52-2db0-44ab-b3f3-8690b762ebc9@165.154.112.107:12000?allowInsecure=1&sni=aliyun.com#06-0034-HK
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpidnI5dTNhZVJRd0FhZmhqbXZIdHdI@159.65.155.229:80#06-0035-IN
    trojan://juzi@140.83.57.183:22735?allowInsecure=1&sni=juzi8186-sr1.pages.dev&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#06-0036-JP
    trojan://9e76767d-4bfa-4f04-a800-42e2f63afed2@160.16.104.143:443?allowInsecure=1&sni=www.linemo.jp#06-0037-JP
    trojan://installshield@38.180.249.177:8443?allowInsecure=1&sni=wrmelmwxlf.gktevlrqznwqqozy.fabpfs66gizmnojhcvqxwl.kytrcfzqla87gvgvs6c7kjnrubuh.cc#06-0038-SG
    vmess://eyJ2IjoiMiIsInBzIjoiMDYtMDA0MC1KUCIsImFkZCI6Ind3dy50aWt0b2suY29tLmpwNC52aWVmYXN0Lm5ldCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI5ZTc2NzY3ZC00YmZhLTRmMDQtYTgwMC00MmUyZjYzYWZlZDIiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3ZpZWZhc3QiLCJob3N0Ijoid3d3LnRpa3Rvay5jb20uanA0LnZpZWZhc3QubmV0IiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1jZmI6WG44aktkbURNMDBJZU8lMjUyNSUyNTIzJTI1MjQlMjUyM2ZKQU10c0VBRVVPcEgvWVdZdFlxREZuVDBTVg@103.186.154.187:38388#08-0046-VN
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@51.15.17.169:989#08-0048-NL
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@154.90.62.168:989#08-0049-KR
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@154.90.63.177:989#08-0050-KR
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@38.54.57.90:989#08-0051-BR
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpOazlhc2dsRHpIemprdFZ6VGt2aGFB@arxfw2b78fi2q9hzylhn.freesocks.work:443#08-0052-VN
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpYVU1UeWdFTTFqVllJdnlzWEtxQTVU@hackney-latest-strike.freesocks.work:443#08-0053-US
    ss://YWVzLTI1Ni1nY206MGE5MTRlOWEtM2UzYi00NzBmLWEyNjctN2VhNzA4M2M0NWJi@77.110.110.240:443#23-0054-AT
    ss://YWVzLTI1Ni1nY206YTdmMDgyYzEtMGQxMi00NjA5LWI2YmYtZTc2MGI2NjhjZjIz@77.110.110.240:443#23-0055-AT
    ss://YWVzLTI1Ni1nY206MTAyYWQzZGEtMmQ1NS00OWQ2LWI4YzgtMmQ3ZTA0ZGYzM2Nh@77.110.110.240:443#23-0057-AT
    ss://YWVzLTI1Ni1nY206M2Y0MGJmM2QtMmYxZS00ZjQzLWJmNTQtZTVmZTc0MmEzYjRl@77.110.110.240:443#23-0058-AT
    ss://YWVzLTI1Ni1nY206ZDcwZWY4YjUtNjA0OC00YzBkLWJlNGQtZmM2MDM5OWIwZjQ1@77.110.110.240:443#23-0059-AT
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpqaWZ1UjJOVE0wWXQ@62.133.62.109:443#23-0060-FR
    vmess://eyJ2IjoiMiIsInBzIjoiMjMtMDA2My1ERSIsImFkZCI6IjU3LjEyOS4yNC4xMjUiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjAzZmNjNjE4LWI5M2QtNjc5Ni02YWVkLThhMzhjOTc1ZDU4MSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbGlua3Z3cz9lZD0yMDQ4QEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTi0tQEhpQnllVlBOTiIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    ss://YWVzLTEyOC1nY206MTAwODY@160.16.123.124:10087#23-0065-JPtrojan%2F%2Fjuzi%40154.29.155.249443%3FallowInsecure%3D1%26sni%3Djuzi8186-sr1.pages.dev%26ws%3D1%26wspath%3D%25252F%25253Fed%25253D2560%2306-0044-US
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpQdEh2NGJPNGpQdEJzSFdTbDFuNVFk@45.95.232.236:4248#23-0069-CH
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@104.192.226.106:989#23-0071-USss%2F%2FY2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo0YTJyZml4b3BoZGpmZmE4S1ZBNEFh%4045.87.175.1718080%2323-0103-LT
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5dHFoTWRJclRrZ1E0NlB2aHlBdE1I@92.112.126.90:443#23-0088-NL
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5bGNDdnpOeHBOc25JTnlhWWZ6Yzhl@212.113.106.76:29149#23-0089-AT
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5ZFZMYWNjR0JxRng@62.60.233.21:443#23-0090-TR
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpVS3Z5aXhLUmRUU3cyOFFwODdrZUVS@macintosh.outlinekeys.net:19609#23-0092-NL
    


</details>

### 所有节点
合并节点总数: `41`
[节点链接](https://raw.githubusercontent.com/caijh/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [clashnode](https://github.com/imyaoxp/clashnode), 节点数量: `41`


## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

