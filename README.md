## ad-rules

广告过滤规则整合，使用 [fordes123/ad-filters-subscriber](https://github.com/fordes123/ad-filters-subscriber) 定时更新
> 可使用我搭建的私人DNS 详情可见[LINK](https://myipdns.top/archives/DNS) 
> AdGuardHome 推荐使用：`all.txt`</br>
> AdAway 等其他仅支持 hosts 的工具，推荐使用：`hosts.txt`

| 名称            | 说明                                                                   |                                       Github                                       |                                                Gitee                                                 |
|---------------|:---------------------------------------------------------------------|:----------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------:|
| `all.txt`     | 去重的规则合集，包含`DOMAIN`、`REGEX`、`MODIFY`、`HOSTS`，适用于 `AdGuard`、`AdBlock`等 |                                                                  [Link](https://raw.githubusercontent.com/Bibaiji/ad-rules/main/rule/all.txt)   |                                                                                  [Link](https://gitee.com/bibaiji/ad-rules/raw/main/rule/all.txt)   |
| `dns.txt`     | 包含 `DOMAIN`、`REGEX`、`HOSTS`规则，适用于`AdGuardHome` 等基于DNS的过滤工具           |                                                                [Link](https://raw.githubusercontent.com/Bibaiji/ad-rules/main/rule/dns.txt)   |                                                                                        [Link](https://gitee.com/bibaiji/ad-rules/raw/main/rule/dns.txt)   |
| `domain.txt`  | `DOMAIN` 域名规则，仅完整域名                                                 |                                                                          [Link](https://raw.githubusercontent.com/Bibaiji/ad-rules/main/rule/domain.txt) |                                                                                      [Link](https://gitee.com/bibaiji/ad-rules/raw/main/rule/domain.txt) |
| `hosts.txt`   | `HOSTS` 规则，适用于几乎所有设备                                             |                                                                    [Link](https://raw.githubusercontent.com/Bibaiji/ad-rules/main/rule/hosts.txt)  |                                                                                      [Link](https://gitee.com/bibaiji/ad-rules/raw/main/rule/hosts.txt)  |
| `modify.txt`  | `MODIFY` 修饰规则，添加了一些修饰符号的规则，AdG支持, `modify.txt` + `dns.txt` = `all.txt`                |                                                [Link](https://raw.githubusercontent.com/Bibaiji/ad-rules/main/rule/modify.txt) |                                                                                  [Link](https://gitee.com/bibaiji/ad-rules/raw/main/rule/modify.txt) |
| `private.txt` | 由本仓库维护的私有规则，主要是对上游规则的补充                                              |                                                            [Link](https://raw.githubusercontent.com/Bibaiji/ad-rules/main/rule/private.txt) |                                                                                      [Link](https://gitee.com/bibaiji/ad-rules/raw/main/rule/private.txt) |
| `regex.txt`   | `REGEX` 正则规则，包含正则的域名规则，AdGH支持                                                 |                                                          [Link](https://raw.githubusercontent.com/Bibaiji/ad-rules/main/rule/regex.txt) |                                                                                        [Link](https://gitee.com/bibaiji/ad-rules/raw/main/rule/regex.txt) |
| `private.txt`   | 由本仓库维护的私有规则，主要是对上游规则的补充， AdGH支持                                                 |                                              [Link](https://raw.githubusercontent.com/Bibaiji/ad-rules/main/rule/local-rule.txt) |                                                                                    [Link](https://gitee.com/bibaiji/ad-rules/raw/main/rule/local-rule.txt) |

<details>
<summary>点击查看上游规则</summary>
<ul>
    <li><a href="https://big.oisd.nl/">Oisd Big</a></li>
    <li><a href="https://nsfw.oisd.nl/">Oisd Nfsw</a></li>
    <li><a href="https://anti-ad.net/easylist.txt">anti-AD</a></li>
    <li><a href="https://cdn.jsdelivr.net/gh/banbendalao/ADgk@master/ADgk.txt">ADgk</a></li>
    <li><a href="https://adguardteam.github.io/HostlistsRegistry/assets/filter_37.txt">No Google</a></li>
    <li><a href="https://raw.gitmirror.com/lingeringsound/10007/main/adb.txt">10007</a></li>
    <li><a href="https://raw.githubusercontent.com/Goooler/1024_hosts/master/hosts">1024</a></li>
    <li><a href="https://raw.githubusercontent.com/VeleSila/yhosts/master/hosts">yhosts</a></li>
    <li><a href="https://file-git.trli.club/Domains/AccelerateHosts/github-hosts.txt">Github-hosts</a></li>
    <li><a href="https://github.com/TG-Twilight/AWAvenue-Adblock-Rule">AWAvenue-Adblock-Rule</a></li>
    <li><a href="https://raw.hellogithub.com/hosts">hellogithub</a></li>
    <li><a href="https://cdn.jsdelivr.net/gh/pboymt/Steam520/hosts">Steam520</a></li>
    <li><a href="https://adaway.org/hosts.txt">Adaway</a></li>
</ul>
</details>
