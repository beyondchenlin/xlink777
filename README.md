# Xlink777

X 样式的外链记录页。版式在 index.html，内容在 data/feed.json。

定时任务只追加 data/feed.json 和 data/outbound_links.csv，不要改 index.html。页面打开时会读取 GitHub 上的 data/feed.json，所以新记录推上去之后，刷新就能看到。
