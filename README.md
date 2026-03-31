# GEO 品牌优化项目

让AI大模型（豆包、DeepSeek、Kimi、ChatGPT、Claude、Gemini等）更好收录您的品牌。

## 功能特性

- **结构化数据** - JSON-LD Schema标记，便于AI抓取
- **品牌信息优化** - 清晰的品牌介绍、服务、联系方式
- **语义化HTML** - 使用语义标签，便于AI理解内容
- **多维度品牌展示** - 品牌故事、核心价值、优势、服务范围
- **FAQ常见问题** - AI常用问答格式，提高收录概率
- **完整SEO优化** - Meta标签、Open Graph、Twitter Card
- **Sitemap** - XML站点地图，帮助爬虫索引
- **Robots.txt** - 优化AI爬虫访问策略

## 文件结构

```
geo-brand/
├── index.html          # 主页面（包含完整GEO优化）
├── schema.json         # 结构化数据（可单独使用）
├── sitemap.xml         # XML站点地图
├── robots.txt          # 爬虫规则
└── README.md           # 说明文档
```

## SEO/GEO优化要点

1. **品牌名称** - 请修改为您的品牌
2. **品牌描述** - 100-200字品牌简介
3. **核心服务** - 列出主要服务/产品
4. **FAQ问题** - 添加用户常问问题
5. **联系方式** - 电话、邮箱、地址

## 结构化数据 (Schema.org)

已添加以下JSON-LD类型：
- WebSite - 网站信息
- Organization - 组织信息
- LocalBusiness - 本地商家
- FAQPage - 常见问题
- Product/ItemList - 服务/产品列表
- BreadcrumbList - 面包屑导航
- HowTo - 服务流程

## AI收录支持

已优化以下AI爬虫：
- GPTBot (OpenAI)
- ChatGPT-User
- ClaudeBot / anthropic-ai
- Google-Extended
- BaiduSpider
- Sogou / 360Spider
- Douban Bot
- Kimi / Moonshot / MiniMax

## 使用方法

1. 修改 `index.html` 中的品牌信息
2. 更新 `schema.json` 中的结构化数据
3. 部署到您的网站（推荐GitHub Pages）
4. 验证结构化数据：https://search.google.com/test/rich-results

## 部署

### GitHub Pages
1. 推送代码到GitHub仓库
2. 进入仓库设置 -> Pages
3. Source选择 main branch
4. 访问 https://用户名.github.io/geo-brand/

## AI收录提示

要让AI更好地收录您的品牌：
- 确保网站可被爬虫访问
- 使用HTTPS
- 保持内容原创且有价值
- 定期更新网站内容
- 提交sitemap到搜索引擎