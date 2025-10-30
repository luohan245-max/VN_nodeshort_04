# NodeShort Landing (Telegram Only, ZH)

- 入口：`index.html`
- 资源：`/assets/*`
- 已包含：Meta Pixel (855402777027838)、UTM 透传、Telegram 深链（移动端先尝试拉起 App，失败回退 Web）、OG 分享大图。

## GitHub Pages
直接推送仓库根目录：
- index.html
- assets/
- vercel.json（可忽略）

## Vercel
New Project → 选择此仓库（Framework: None）→ Deploy。
`vercel.json` 已添加缓存策略。

## 注意
- canonical 目前已注释，等绑定正式域名后再启用。
- 如需越南语版本或多渠道 UTM 入口，请在 HTML 中替换文案或另建版本。
