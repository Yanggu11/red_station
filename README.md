# 高校红色资源站 · Campus Red-Culture Resource Station

**在线预览 / Live demo：<https://yanggu11.github.io/red_station/>**

面向高校的红色文化资源网站前端原型，按学段（小学、初中、高中）分类展示视频与图片资源，并包含资源列表、详情页、博客和"关于我们"页面。

A front-end prototype of a website that collects red-culture (Chinese revolutionary history) educational resources. Videos and images are grouped by school level (primary, junior high, senior high), with list, detail, blog and "about us" pages.

> 状态 / Status：原型阶段，资源卡片目前为占位内容。
> Prototype stage: the resource cards still hold placeholder content.

## 页面 / Pages

| 页面 / Page | 说明 / Description |
|---|---|
| `index.html` | 首页：资源卡片瀑布流与登录入口 · Home page with resource cards and a login entry |
| `grid.html` / `masonry.html` | 网格与瀑布流两种资源列表布局 · Grid and masonry list layouts |
| `single-post.html` | 资源详情页 · Resource detail page |
| `blog.html` | 资讯与文章页 · Articles and news |
| `about.html` | 关于我们 · About us |

## 技术 / Tech

HTML5 · CSS3 · Bootstrap 3 · jQuery · Font Awesome · Lightbox

## 本地运行 / Run locally

```bash
git clone https://github.com/Yanggu11/red_station.git
cd red_station
python3 -m http.server 8000   # 然后访问 http://localhost:8000
```

## 致谢 / Credits

页面框架基于 [templatemo](https://templatemo.com/) 的免费模板 *Highway*。

The page layout is based on templatemo's free *Highway* template.
