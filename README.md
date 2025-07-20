# Bilibili-Video-Reply-Crawler
Python爬虫获取Bilibili视频评论
这是一个段落。

<div style="border:1px solid #ccc; padding:8px;">
  <svg>
  <h3>自定义标题</h3>
  <p>这是一段通过 HTML 插入的文本。</p>
</div>
基于 https://zhuanlan.zhihu.com/p/275603349 修改，支持BV、av、cv，用法见`--help`。

支持通过GitHub Actions自动获取issue标题中的BV、av、cv号，自动爬取评论并回复到issue中。（本仓库不启用此功能，请Fork后自行启用Actions）

GitHub Actions的单个Job运行时间限制为6小时，因此每次最多只能爬取约80000条评论。不要在issue提交大于此数量的视频，运行时间超时不会保留结果。
