---
# 内容显示设置
widget: pages
headless: true
active: true
weight: 20

title: "Talks"
subtitle: "Conference and Workshop Presentations"

# 页面过滤器
content:
  # 显示的文件夹
  page_type: talk
  filters:
    tag: ""
    category: ""
    publication_type: ""
    exclude_featured: false
  order:
    # 按时间倒序显示
    by: date
    dir: desc

# 外观设置
design:
  # 一页显示多少条
  number: 10
  # 是否显示分页
  pager: true
  # 是否显示年份分组
  group_by: "year"
  # 是否显示内容摘要
  show_content: false
---
