# 玛雅历法 · maya core

传统历法和现代 Dreamspell。本仓从 [知几排盘](https://github.com/weihaoyang/qimen-llm-chart) 提取 TypeScript 源码及对应测试，可独立安装依赖并运行；当前没有发布 npm 包。

## 运行

需要 Node.js 20 或更高版本。

```sh
npm install
npm test
npm run typecheck
```

源码与测试位于 `src/`。

## 资料与案例

- [原项目研究论文](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/research/calculation-audit-paper.md)
- [原项目来源及技术说明](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/research/calculation-audit-paper.md)

- matches Glyph G1 on the Palenque Temple XIX platform before the era base（`src/chart.test.ts`）
- reproduces the reconstructed Quirigua Stela E date while distinguishing its disputed glyph（`src/chart.test.ts`）
- anchors 0.0.0.0.0 at 4 Ajaw 8 Kumkʼu (GMT 584283)（`src/chart.test.ts`）
- converts 2012-12-21 to 13.0.0.0.0 / 4 Ajaw / 3 Kʼankʼin（`src/chart.test.ts`）
- matches the highland day count anchor 1983-09-16 = 1 Bʼatzʼ（`src/chart.test.ts`）

这些案例验证列出的计算或文本字段，不代表预测效果经过验证。对于现代知识或几何构造，资料链接标注其实际来源，不冒称古籍。

## 授权

本仓代码按 [GPL-3.0-only](LICENSE) 发布，源自知几排盘。

- 来源：[https://github.com/oshimish/dreamspell-math](https://github.com/oshimish/dreamspell-math)；许可原文：[`dreamspell-math-MIT.txt`](LICENSES/dreamspell-math-MIT.txt).
- 来源：[https://github.com/joyozhang333-lgtm/mayan-kin](https://github.com/joyozhang333-lgtm/mayan-kin)；许可原文：[`mayan-kin-MIT.txt`](LICENSES/mayan-kin-MIT.txt).

外部资料和影像按各自来源的使用条件处理，本仓不附古籍影像。
