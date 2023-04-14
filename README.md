## AbBlock List

广告过滤规则整合，使用 [fordes123/ad-filters-subscriber](https://github.com/fordes123/ad-filters-subscriber) 定时更新
> AdGuard客户端(软件、扩展)、AdBlock、AdBlockPlus、uBlock Origin 推荐使用：`all.txt`</br>
> AdGuardHome 推荐使用：`dns.txt`</br>
> AdAway 等其他仅支持 hosts 的工具，推荐使用：`hosts.txt`

| 名称            | 说明                                                                   |                                       Github                                       |                                                ghproxy                                                 |
|---------------|:---------------------------------------------------------------------|:----------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------:|
| `all.txt`     | 去重的规则合集，包含`DOMAIN`、`REGEX`、`MODIFY`、`HOSTS`，适用于 `AdGuard`、`AdBlock`等 |  [Link](https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/all.txt)   |  [Link](https://ghproxy.com/https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/all.txt)   |
| `dns.txt`     | 包含 `DOMAIN`、`REGEX`、`HOSTS`规则，适用于`AdGuardHome` 等基于DNS的过滤工具           |  [Link](https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/dns.txt)   |  [Link](https://ghproxy.com/https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/dns.txt)   |
| `domain.txt`  | `DOMAIN` 域名规则，仅完整域名                                                 | [Link](https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/domain.txt) | [Link](https://ghproxy.com/https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/domain.txt) |
| `hosts.txt`   | `HOSTS` 规则，适用于几乎所有设备                                             | [Link](https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/hosts.txt)  | [Link](https://ghproxy.com/https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/hosts.txt)  |
| `modify.txt`  | `MODIFY` 修饰规则，添加了一些修饰符号的规则，AdG支持, `modify.txt` + `dns.txt` = `all.txt`                | [Link](https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/modify.txt) | [Link](https://ghproxy.com/https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/modify.txt) |
| `private.txt` | 由本仓库维护的私有规则，主要是对上游规则的补充                                              | [Link](https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/private.txt) | [Link](https://ghproxy.com/https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/private.txt) |
| `regex.txt`   | `REGEX` 正则规则，包含正则的域名规则，AdGH支持                                                 | [Link](https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/regex.txt) | [Link](https://ghproxy.com/https://raw.githubusercontent.com/xndeye/adblock_list/main/rule/regex.txt) |

<details>
<summary>点击查看上游规则</summary>
<ul>
    <li><a href="https://github.com/hoshsadiq/adblock-nocoin-list/">adblock-nocoin-list</a></li>
    <li><a href="https://github.com/durablenapkin/scamblocklist">Scam Blocklist</a></li>
    <li><a href="https://someonewhocares.org/hosts/zero/hosts">Dan Pollock's List</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt">AdGuard DNS filter</a></li>
    <li><a href="https://pgl.yoyo.org/adservers/serverlist.php?hostformat=adblockplus&showintro=1&mimetype=plaintext">Peter Lowe's List</a></li>
    <li><a href="https://adaway.org/hosts.txt">AdAway Default Blocklist</a></li>
    <li><a href="https://github.com/crazy-max/WindowsSpyBlocker">WindowsSpyBlocker</a></li>
    <li><a href="https://github.com/jdlingyu/ad-wars">ad-wars</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt">AdGuard Base</a></li>
    <li><a href="https://github.com/TG-Twilight/AWAvenue-Adblock-Rule">AWAvenue-Adblock-Rule</a></li>
    <li><a href="https://github.com/sbwml/halflife-list">halflife-list</a></li>
    <li><a href="https://github.com/uniartisan/adblock_list">uniartisan-adblock_list</a></li>
</ul>
</details>
