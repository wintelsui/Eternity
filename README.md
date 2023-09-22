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
高速节点数量: `61`
<details>
  <summary>展开复制节点</summary>

    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:24291#24-CN-00
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:33534#24-CN-01
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:23761#24-CN-02
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:45955#24-CN-03
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:33487#24-CN-04
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:64654#24-CN-05
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:59584#24-CN-06
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:37639#24-CN-07
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:63897#24-CN-08
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:13290#24-CN-09
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:10884#24-CN-10
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:53271#24-CN-11
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:63279#24-CN-12
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:65407#24-CN-13
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:33310#24-CN-14
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:29223#24-CN-15
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:59090#24-CN-16
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:34948#24-CN-17
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:55718#24-CN-18
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:28397#24-CN-19
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:53958#24-CN-20
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:22225#24-CN-21
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:46957#24-CN-22
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:24007#24-CN-23
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:29574#24-CN-24
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:64759#24-CN-25
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:26065#24-CN-26
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:30641#24-CN-27
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:59211#24-CN-28
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:41972#24-CN-29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:30139#24-CN-30
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:20014#24-CN-31
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:44773#24-CN-32
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:20887#24-CN-33
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:41342#24-CN-34
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:40171#24-CN-35
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:39211#24-CN-36
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:35387#24-CN-37
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:23310#24-CN-38
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:43441#24-CN-39
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:41868#24-CN-40
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:13793#24-CN-41
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:45175#24-CN-42
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:10515#24-CN-43
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:53991#24-CN-44
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:37169#24-CN-45
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:25997#24-CN-46
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:19975#24-CN-47
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:23319#24-CN-48
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:61163#24-CN-49
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:20922#24-CN-50
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:37115#24-CN-51
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:27048#24-CN-52
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:22254#24-CN-53
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:14562#24-CN-54
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:62506#24-CN-55
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:33912#24-CN-56
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx.jcnode.top:21781#24-CN-57
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzyd.jcnode.top:40788#24-CN-58
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowMzExZTU5MS1hNTVhLTQ0ZGMtYTlkNS0xNGU4NTNlNmFmYzQ@gzdx01.jcnode.top:65117#24-CN-59
    


</details>

### 所有节点
合并节点总数: `555`
[节点链接](https://raw.githubusercontent.com/caijh/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [clashnode](https://github.com/imyaoxp/clashnode), 节点数量: `555`


## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

