# このリポジトリの使い方

このリポジトリでは，理工学基礎実験でWordのテンプレートが配布されているのにもかかわらず，思想上，宗教上，その他やんごとなき理由により$\LaTeX$を使ってレポートを書きたい方向けに，レポートを代わりに書いて差し上げることはできないけれど，表紙なら配布可能だと思うのでご自由にお使いください．

完成品は[こちら](https://github.com/harry-keio-univ/kisozi/blob/master/mytemp.pdf)からどうぞ．

おソースは[こちら](https://github.com/harry-keio-univ/kisozi/blob/master/mytemp.tex)からどうぞ．

スニペットに登録したい方は，[こちら](https://github.com/harry-keio-univ/kisozi/blob/master/for_snippet.jsonc)から```kisozi:```の中身をユーザスニペットにコピペしてください．フォントはしっぽり明朝を使っているので，デフォルトのフォントを使いたい方は，
```tex
\usepackage[T1]{fontenc}
から
\newjfontfamily\jisninety[CJKShape=JIS1990]{ShipporiMincho-OTF-Bold}
まで
```
を削除してください．