# 商业札记

个人商业思考发布页。站点从 `index.html` 读取 `thoughts.json`，并提供麦肯锡与大型企业战略动向备忘录的阅读入口。

## 发布一篇新思考

在 `thoughts.json` 最外层数组中增加一项：

```json
{
  "date": "2026-09-26",
  "title": "AI 改变组织的，不只是效率",
  "category": "组织与技术",
  "summary": "用一两句话说明这篇思考的核心判断。",
  "body": "正文第一段。\n\n正文第二段。",
  "sources": [
    {"title": "来源标题", "url": "https://example.com/source"}
  ]
}
```

文章会按日期倒序显示。可在 GitHub 网页上直接编辑 `thoughts.json` 并提交；GitHub Pages 自动更新。发布前请检查文章和引用是否适合公开。
