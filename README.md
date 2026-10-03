# HyperGlow CN+ 站点

GitHub Pages 落地页(纯静态 HTML,无构建步骤)。

## 更新截图

`#shots` 区块预留了三个截图位。拿到实机截图后:

1. 把图片放进 `assets/`(建议 `shot-lockscreen.jpg` / `shot-aod.jpg` / `shot-editor.jpg`,宽 1080);
2. 把对应 `.shot` div 里的占位文字换成 `<img src="assets/xxx.jpg" alt="...">`;
3. 提交推送后 Pages 自动重新发布(1-3 分钟)。

## 启用 Pages(一次性)

仓库 Settings → Pages → Source = `Deploy from a branch`,分支 `main`、目录 `/(root)`。
启用后地址:`https://aodianjun.github.io/hyperglow-cnplus-site/`

## 内容维护提醒

- 功能清单与主仓库 README **不是**自动同步——README 是私有生成源的产物;站点这份是手工维护的,改功能后两边都要动。
- 支持区二维码:`assets/wechat-reward.jpg`(微信赞赏)、`assets/alipay.jpg`(支付宝收款)。
