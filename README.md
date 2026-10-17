# 中学数学 レベル0（小学校のやりなおし）

公開URL: https://chugaku-suugaku0.senta1111.workers.dev/

- 配信するのは `public/index.html` の1枚だけ（KaTeXの式表示も中に入っている）。
- 内容: 倍数と約数 / 小数と分数 / 分数の計算 / 割合・比・速さ。全22ステップ・157問。
- 問題を直す・足すとき: `tools/gen0.js` を直す。
  1. `cd tools`
  2. `node gen0.js`（`src/data.js` を作る）
  3. `node check.js`（答えと選択肢の検査。ALL OK が出ること）
  4. `node build.js --repo`（`tools/public/index.html` を作る）→ `public/index.html` に置きかえる
