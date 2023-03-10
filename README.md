# kotodama è¨çµ

[![GitHub Pages](https://github.com/YunYouJun/kotodama/actions/workflows/gh-pages.yml/badge.svg?branch=main)](https://github.com/YunYouJun/kotodama/actions/workflows/gh-pages.yml)

> ð¬ ææ§è¨çµçé­æ³ï¼ä¸ä¸ªä¼éççº¯éæè¯è®ºç®¡çåå°ï¼å¼åä¸­...ï¼

[Demo é¢è§](https://kotodama.yunyoujun.cn)

- å¤ç¨1ï¼<kotodama.elpsy.cn>
- å¤ç¨2ï¼<kotodama.vercel.app>ï¼å½åå·²è¢«æ±¡æï¼

kotodama æ¯ä¸ä¸ªçº¯éæçç«ç¹ï¼æ¨å¯ä»¥ fork å¶èªè¡é¨ç½²ï¼ä¹å¯ä»¥ç´æ¥ä½¿ç¨å·²é¨ç½²ç `kotodama.yunyoujun.cn` | `kotodama.elpsy.cn` ç«ç¹ã

> `kotodama.yunyoujun.cn` çº¯éææç®¡äº GitHub Pagesï¼ä»£ç å°å§ç»ä¿æå¼æºï¼ä¸ä¼ä¹æ æ³è·åæ¨çç¨æ·åå¯ç ï¼è¯·æ¾å¿ä½¿ç¨ã

## Features

- ð¬ ç®ååªéé [Waline](https://github.com/walinejs/waline)ï¼~~æªæ¥å¯è½ééæ´å¤è¯è®ºç³»ç»ï¼åç~~ï¼
- â¡ï¸ [Vue 3](https://github.com/vuejs/vue-next), [Vite 2](https://github.com/vitejs/vite), [pnpm](https://pnpm.js.org/), [element-plus](https://github.com/element-plus/element-plus) - ([vitesse](https://github.com/antfu/vitesse/)) born for future

## Waline

- éé [Waline](https://github.com/walinejs/waline) åå°ç®¡çï¼å¼åä¸­...ï¼
  - å·²å®ç°åºç¡çç»å½ãè¯è®ºé¢è§ãç¿»é¡µãå é¤åè½
  - Todo: ç¼è¾è¯è®ºãç»èä¼åãGitHub ç»å½ãæ¹éå é¤ãå®¡æ ¸

> More info see [#552 | Waline](https://github.com/walinejs/waline/issues/552)

## èªè¡é¨ç½²

> æ¨èç´æ¥ä½¿ç¨ [kotodama.yunyoujun.cn](https://kotodama.yunyoujun.cn) æ [kotodama.elpsy.cn](https://kotodama.elpsy.cn)ãå¦ææ¨ä¸æ¾å¿ï¼ä¹å¯ä»¥èªè¡é¨ç½²ï¼ä½å¯è½éè¦èªå·±è®°å¾æ´æ°ã

```bash
# fork æç´æ¥ clone æ¬é¡¹ç®
git clone https://github.com/YunYouJun/kotodama

cp .env.example .env
```

éç½® `.env` ä¸­ç `VITE_API_BASE_URL` ç¯å¢åéä¸ºæ¨ç Waline åå°å°åï¼ä¾å¦ `https://waline.xxx.xxx`ã

### èªè¡æå»º

```bash
# å®è£ä¾èµ
npm install

# æå»ºäº§ç©
npm run build
```

å° `dist` ä¸çéææä»¶æç®¡äºæ¨çæå¡å¨ã

### GitHub Actions

Fork æ¬é¡¹ç®ã

è¿å¥ `Settings/Pages` Source è®¾ç½® Branch ä¸º `gh-pages`ï¼ä»¥å¯ç¨ GitHub Pagesã

è¿å¥ `Actions`ï¼è§¦å GitHub Page Workflow runã

> `.github/workflows/gh-pages.yml` æä»¶å°ä¼èªå¨è§¦åæå»ºï¼å¹¶å°æå»ºäº§ç©æ¨éè³ `gh-pages` åæ¯ã

å¦ææ¨éè¦èªå®ä¹ååï¼è¯·ä¿®æ¹é¡¹ç®ä¸­ `public/CNAME` æä»¶åå®¹ä¸ºæ¨èªå·±çååã

## FAQ

### Waline 403 Authorization éè¯¯

å¦ææ¨æ æ³æ­£å¸¸è¿æ¥æ¨ç Waline åå° APIï¼æ¨å¯è½éè¦éç½®ä¸ä¸å®å¨ååã
å° `kotodama.yunyoujun.cn` æ·»å è³æ¨çå®å¨ååä¸­ã

> [secureDomains | Waline](https://waline.js.org/reference/server.html#securedomains)

More info see [README.md](https://github.com/YunYouJun/kotodama/blob/main/README.md).

## [Sponsors](https://sponsors.yunyoujun.cn)

<p align="center">
  <a href="https://sponsors.yunyoujun.cn">
    <img src='https://fastly.jsdelivr.net/gh/YunYouJun/sponsors/public/sponsors.svg'/>
  </a>
</p>
