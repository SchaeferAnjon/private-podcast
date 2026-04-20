# private-podcast

Claude Code 驱动的私人播客流水线。灵感来源 [数字生命卡兹克 - Dear Tape 视频](https://www.youtube.com/watch?v=aarPx3OK9ks)。

## 架构

```
内容 (PDF/URL)
  → Claude 生成播客脚本
  → MiniMax T2A v2 合成 mp3
  → GitHub Release 托管音频 (稳定 HTTPS URL)
  → docs/podcast.xml RSS feed
  → GitHub Pages 部署
  → Apple Podcasts 订阅 feed URL
```

## Feed URL

订阅这个 URL 到 Apple Podcasts / 泛用播客客户端：

```
https://schaeferanjon.github.io/private-podcast/podcast.xml
```

## Episodes

| # | 发布日期 | 标题 | 时长 |
|---|---|---|---|
| 001 | 2026-04-20 | 足球入门：听懂朋友聊球所需要的一切 | 28:43 |
