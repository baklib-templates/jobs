# 怎么用

1. 用这个模板建 cms 站点。职位写在站点页面上，不要再建知识库。
2. 还没有自己的职位时，可以用种子里的示例站看结构。示例会跳过编排。
3. 首页用 `index`，下面建 `channel` 当职位组，组里再建 `page`。
4. 职位写 `title` 和 `content`。职责用 `responsibilities`，要求用 `requirements`。
5. 从网址或文件导入时，正文写成 `page`，不写成职位组壳。
6. 模板里没有 `search.liquid`。提问入口仍是 `-/search`。

编排方案见 [activation.yml](activation.yml)：职位保持来源层级、顶层目录变成职位组，或全部挂在首页下。
