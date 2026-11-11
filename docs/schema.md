# 字段

以设置项的 `id` 为准。下面每个 id 都可写。

## 全站

职位发布设置：

| id | 类型 | 作用 |
| --- | --- | --- |
| `logo_url` | 图片 | Logo |
| `location_options` | 多行文本 | 地点选项，一行一项 |
| `salary_options` | 多行文本 | 薪资选项，一行一项 |
| `employment_type_options` | 多行文本 | 用工类型选项，一行一项 |

申请页联系信息：

| id | 类型 | 作用 |
| --- | --- | --- |
| `apply_contact_email_label` | 文本 | 联系邮箱标签 |
| `apply_contact_email` | 文本 | 联系邮箱 |
| `apply_contact_phone_label` | 文本 | 联系电话标签 |
| `apply_contact_phone` | 文本 | 联系电话 |
| `apply_contact_office_label` | 文本 | 办公地址标签 |
| `apply_contact_office_line1` | 文本 | 办公地址第一行 |
| `apply_contact_office_line2` | 文本 | 办公地址第二行 |
| `apply_contact_hours_label` | 文本 | 营业时间标签 |
| `apply_contact_hours_line1` | 文本 | 营业时间第一行 |
| `apply_contact_hours_line2` | 文本 | 营业时间第二行 |

`head_html`、`header_html`、`footer_html` 在两个分组里各出现一次，id 相同：申请页联系信息、页头页脚设置。

| id | 类型 | 作用 |
| --- | --- | --- |
| `head_html` | HTML | 自定义 head |
| `header_html` | HTML | 顶部导航 |
| `footer_html` | HTML | 页脚 |

| id | 类型 | 作用 |
| --- | --- | --- |
| `weixin_app_id` / `weixin_app_secret` / `weixin_enabled` / `weixin_debug` | 文本或开关 | 微信分享 |

## 首页 `index`

名字是招聘首页。子页面是 `channel`。

| id | 类型 | 作用 |
| --- | --- | --- |
| `hero_title` | 文本 | 主视觉标题 |
| `hero_description` | 多行文本 | 主视觉描述 |
| `hero_bg_url` | 图片 | 主视觉背景 |

## 职位组 `channel`

名字是招聘频道。这是壳，子页面是 `page`。

| id | 类型 | 作用 |
| --- | --- | --- |
| `title` | 文本 | 标题 |
| `description` | 多行文本 | 描述 |

## 职位 `page`

名字是职位详情。没有子页面模板。导入正文用这一页。

| id | 类型 | 作用 |
| --- | --- | --- |
| `title` | 文本 | 标题 |
| `location` | 选择 | 工作地点 |
| `employment_type` | 选择 | 用工类型 |
| `salary` | 选择 | 薪资区间 |
| `workplace_mode` | 选择 | 办公方式 |
| `featured` | 开关 | 精选职位 |
| `skill_tags` | 多行文本 | 技能标签，一行一项 |
| `responsibilities` | 富文本 | 岗位职责 |
| `requirements` | 富文本 | 任职要求 |
| `content` | 富文本 | 完整职位描述 |

反馈流没有设置项，不是内容模板。磁盘上没有搜索模板。
