# HyperGlow CN+ 站点

GitHub Pages 落地页(纯静态 HTML,无构建步骤)。

## 更新实机演示视频

`#shots` 区块按歌曲分两组展示真机录制的演示视频(每组:锁屏 / 息屏 AOD / 横屏各一段):

- 蝴蝶 · 洛天依 Official:`assets/shots/butterfly-{lockscreen,aod,landscape}.mp4`
- Take Me Hand · DAISHI DANCE:`assets/shots/take-me-hand-{lockscreen,aod,landscape}.mp4`

替换或新增步骤:

1. 把视频放进 `assets/shots/`(H.264 + yuv420p + `+faststart`、**无音轨**、单条约 1~2MB);
2. 修改 `index.html` 中对应 `<figure class="shot ...">` 里的 `<video src>`;
3. 提交推送后 Pages 自动重新发布(1-3 分钟)。

当前六段均统一为 **27.7 秒**、无声,自动循环播放(仅在进入视口时播放,页面底部有一小段 IntersectionObserver 脚本)。

## 启用 Pages(一次性)

仓库 Settings → Pages → Source = `Deploy from a branch`,分支 `main`、目录 `/(root)`。
启用后地址:`https://aodianjun.github.io/hyperglow-cnplus-site/`

## 内容维护提醒

- 功能清单与主仓库 README **不是**自动同步——README 是私有生成源的产物;站点这份是手工维护的,改功能后两边都要动。
- 支持区二维码:`assets/wechat-reward.jpg`(微信赞赏)、`assets/alipay.jpg`(支付宝收款)。
