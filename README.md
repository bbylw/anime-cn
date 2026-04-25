# Anime.js

<p align="center">
  <picture align="center">
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/images/animejs-v4-logo-animation-dark.gif">
    <img align="center" alt="Anime.js V4 logo animation" src="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/images/animejs-v4-logo-animation.gif" width="560">
  </picture>
</p>

<p align="center">
  <strong>
  <em>Anime.js</em> 是一个快速、多用途、轻量级的 JavaScript 动画库，拥有简单而强大的 API。<br>
  它可以作用于 CSS 属性、SVG、DOM 属性和 JavaScript 对象。
  </strong>
</p>

<p align="center">
  <img alt="NPM Downloads" src="https://img.shields.io/npm/dm/animejs?style=flat-square&logo=npm">
  <img alt="jsDelivr hits (npm)" src="https://img.shields.io/jsdelivr/npm/hm/animejs?style=flat-square&logo=jsdeliver">
  <img alt="GitHub Sponsors" src="https://img.shields.io/github/sponsors/juliangarnier?style=flat-square&logo=github">
</p>

## 赞助商

Anime.js 完全免费，并且只有在我们的赞助商帮助下才得以实现。
请通过 <a target="_blank" href="https://github.com/sponsors/juliangarnier">GitHub Sponsors</a> 赞助我们，帮助项目持续健康发展。

### 铂金赞助商

<table>
  <tbody>
    <tr>
      <td>
        <a target="_blank" href="https://ice.io/?ref=animejs">
          <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/ice-open-network-logomark.png?v=200126">
            <img align="center" src="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/ice-open-network-logomark-dark.png?v=200126" width="310">
          </picture>
        </a>
      </td>
      <td>
        <a target="_blank" href="https://hyperswitch.io/?utm_source=julian&utm_medium=github&utm_campaign=animejs_sponsorship">
          <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/juspay-logomark.png?v=200126">
            <img align="center" src="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/juspay-logomark-dark.png?v=200126" width="310">
          </picture>
        </a>
      </td>
      <td>
        <a target="_blank" href="https://github.com/sponsors/juliangarnier">
          <picture>
            <img align="center" src="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/placeholder-large.png?v=200126" width="310">
          </picture>
        </a>
      </td>
    </tr>
  </tbody>
</table>

### 银色赞助商

<table>
  <tbody>
    <tr>
      <td>
        <a target="_blank" href="https://www.testmuai.com/?utm_medium=sponsor&utm_source=animejs">
          <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/testmu-ai-logomark.png?v=200126">
            <img align="center" src="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/testmu-ai-logomark-dark.png?v=200126" width="141">
          </picture>
        </a>
      </td>
      <td>
        <a target="_blank" href="https://inspatialapp.com/?ref=animejs">
          <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/inspatial-logomark.png?v=200126">
            <img align="center" src="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/inspatial-logomark-dark.png?v=200126" width="141">
          </picture>
        </a>
      </td>
      <td>
        <a target="_blank" href="https://github.com/sponsors/juliangarnier">
          <picture>
            <img align="center" src="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/placeholder-small.png?v=200126" width="141">
          </picture>
        </a>
      </td>
      <td>
        <a target="_blank" href="https://github.com/sponsors/juliangarnier">
          <picture>
            <img align="center" src="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/placeholder-small.png?v=200126" width="141">
          </picture>
        </a>
      </td>
      <td>
        <a target="_blank" href="https://github.com/sponsors/juliangarnier">
          <picture>
            <img align="center" src="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/placeholder-small.png?v=200126" width="141">
          </picture>
        </a>
      </td>
      <td>
        <a target="_blank" href="https://github.com/sponsors/juliangarnier">
          <picture>
            <img align="center" src="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/sponsors/placeholder-small.png?v=200126" width="141">
          </picture>
        </a>
      </td>
    </tr>
  </tbody>
</table>

获取特色内容请成为 <a target="_blank" href="https://github.com/sponsors/juliangarnier">GitHub 赞助者</a>。

## 用法

Anime.js V4 通过导入 ES 模块来使用：

<table>
<tr>
  <td>

```javascript
import {
  animate,
  stagger,
} from 'animejs';

animate('.square', {
  x: 320,
  rotate: { from: -180 },
  duration: 1250,
  delay: stagger(65, { from: 'center' }),
  ease: 'inOutQuint',
  loop: true,
  alternate: true
});
```

  </td>
  <td>
    <img align="center" alt="Anime.js code example" src="https://raw.githubusercontent.com/juliangarnier/anime/master/assets/images/usage-example-result.gif">
  </td>
</tr>
</table>

## V4 文档

完整文档请访问：<a target="_blank" href="https://animejs.com/documentation">这里</a>。

## V3 迁移指南

V3 到 V4 的迁移指南请访问：<a target="_blank" href="https://github.com/juliangarnier/anime/wiki/Migrating-from-v3-to-v4">这里</a>。

## NPM 开发脚本

首先运行 `npm i` 安装所有必要的依赖包。
然后使用 `npm run <script>` 执行以下脚本：

| 脚本 | 动作 |
| --- | --- |
| `dev` | 监听 `src/**/*.js` 的变更，将 ESM 版本打包到 `lib/` 并在 `types/` 中生成类型声明 |
| `dev:test` | 同时运行 `dev` 和 `test:browser` |
| `build` | 将 ESM / UMD / CJS / IIFE 版本打包到 `lib/` 并在 `types/` 中生成类型声明 |
| `test:browser` | 启动本地服务器并运行所有浏览器相关测试 |
| `test:node` | 启动 Node 相关测试 |
| `open:examples` | 启动本地服务器以便在本地浏览示例 |

© [Julian Garnier](http://juliangarnier.com) | <a target="_blank" href="https://github.com/juliangarnier/anime/blob/master/LICENSE.md">MIT 许可协议</a>