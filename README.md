# tabino-sns-img

tabino.tw の SNS 自動投稿で使う画像の配信用（GitHub Pages）。

- 毎朝 `~/tabino-sns/daily-prepare.sh` が当日の表紙カードを置いて push する
- Instagram / Threads の API は **公開 URL の画像しか受け付けない**ため、ここに置く
- 公開 URL: `https://satoiku0415-hash.github.io/tabino-sns-img/<日付>_<slug>/01.jpg`

🔴 `.nojekyll` を消さないこと。無いと Jekyll が `_` 始まりのパスを公開しない
   （2026-09 に音声で全滅した前例がある）。
