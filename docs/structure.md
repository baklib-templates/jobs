# 结构

范围是 cms。快速开始放入网址或文件时，只建这个模板的站点，确认栏目后再写成站点页面，不建知识库。

`seeds/` 里有一套示例站。选「先用示例体验」时用这套种子，种子自己已有栏目，会跳过编排。

## 三层

1. 首页 `templates/index.liquid`，名字是招聘首页。子页面是 `channel`。
2. `templates/channel.liquid`，名字是招聘频道。它是职位组壳，子页面是 `page`。壳上只有标题和描述。
3. 正文是 `templates/page.liquid`，名字是职位详情。有 `title` 和 `content`，另有 `responsibilities`、`requirements`。没有子页面模板。

导入正文用 `page`，不写成职位组壳。

磁盘上没有 `search.liquid`。提问入口仍是 `-/search`。反馈流没有设置项，不是内容模板。
