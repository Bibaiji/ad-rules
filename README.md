<div align="center">
<h1>AD Filter Subscriber</h1>
  <p>
    广告过滤规则订阅器，整合不同来源的规则，帮助你快速构建属于自己的规则集~
本项目旨在整合不同来源的广告过滤规则，通过 `Github Action` 定时执行，拉取远程规则，去重和分类输出。
根据过滤规则的特性，本项目将规则分为 `DOMAIN`、`REGEX`、`MODIFY`、`HOSTS` 四种类型，它们之间互不包含， 你可在配置文件中自由的对四种类型进行组合：

- `DOMAIN`：基于域名的过滤规则，适用于几乎所有广告过滤工具
- `REGEX`：基于正则表达式的**域名过滤**规则，适用于主流广告过滤工具
- `MODIFY`：基于正则和其他修饰符的过滤规则，可以拦截页面上的特定元素，但不适用于DNS过滤
- `HOSTS`：基于 `HOSTS` 的过滤规则，适用于支持 `HOSTS` 的所有设备

本程序基于 `Java17` 编写，使用 `Maven` 进行构建，你可以参照示例配置，编辑 `src/main/resources/application.yml`

#### **Github Action**

- fork 本项目
- 自定义规则订阅 (可选)
    - 参照示例配置，修改配置文件: `src/main/resources/application.yml`，注意本地规则文件应放入项目根目录 `rule` 文件夹
- 打开 `Github Action` 页面，选中左侧 `Update Filters` 授权 `Workflow` 定时执行(⚠ 重要步骤)
- 点击 `Run workflow` 或等待自动执行。执行完成后相应规则生成在配置中指定的目录下

#### **感谢**
    本项目forked from fordes123/ad-filters-subscriber,十分感谢大佬的项目支持.
