# 【DartSass】Gulp環境（SPファースト）

## 環境
- Gulpが使える環境が前提（4系）
- Nodeはバージョン14以降

## レスポンシブ時のfont-sizeについて
メディアクエリmd, sm, ss時（参照. _setting.scss 62行目）の
font-size(以下、fz)の相対値対照表

「md」
★fz16 = rem(23) 1.43倍
  fz14 = rem(21.6) *1.35
  fz12 = rem(17.6) *1.1

「sm」
  fz16 = rem(29.6) *1.85
★fz14 = rem(25.6) *1.6
  fz12 = rem(22.4) *1.4

「ss」
  fz16 = rem(46.4) *2.9
  fz14 = rem(41.6) *2.6
★fz12 = rem(35.2) *2.2

