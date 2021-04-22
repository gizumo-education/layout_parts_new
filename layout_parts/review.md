## １個がh1見出し

## 小見出し
- リスト
- 指摘点を書く
 - どのように改善したか書く

#  Q2 3点
-  clearfixを入れる.
- （brは後ろにつける.
- （pの閉じタグは改行してつける.
- 画像は、urlを使って挿入する.
- （連番はよくないexample1とかexample2とか.
- 画像のaltは何かしらかく.

# Q3 ２点
- tableには、theadとtbodyが必須。一行目のtrはtheadに入れる。残りはtbodyに。
- tableタグにつけない。クラスに適用すべきだから、.tableにする。
- td thもタグに直接css当ててる 
 - -table th,
   -table tdにする
  
# Q4 ０点
- (marginは上につけるのが一般的。下か上かで迷ったら上につける maegin-bottomをmargin-topに.

# Q5
- 1のbeforeより、8のafterの方が意味的には正しい。z-indexいらなくなる。.
- z-indexいらないところも入れておく。修正見越してz-indexは10、20などと書く。一個目は1で書く。.

# Q6
- クラス名、連番はよくない.
- text-alignの横並び。center1の中に、display: inline-blockにする。それで、親にtext-align: center.
- flexの、justify-contentをspace-aroundではなく、centerの方が良い。要素が増えても対応できるように。.
- webkitはなくても良い。ブラウザに対応させるためのもので、クロームで見る分には問題ない。.