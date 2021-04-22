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

# Q7
- font-size: 0;を、white-space: nowrap;を指定している要素の親に。white-spaceは使用しない。
- vertical-align:middleいらない

# Q8
- 画像ふんわり戻るようにする（戻る時にアニメーションできていない）。
 - .imgの中にtransition: all .5s;でまとめて指定する。transitionはhoverの中に描かない。
- テキスト左寄せ
- boxの名前かぶっている
 - relativeのところ img_wrapに入れてしまえば良い
- インデント大きい。
 - 半角スペースにする。
- maskも長さ0.５にする。0.6になってる。
- 0の時は単位いらない
 - bottom: 0%;からbottom: 0;にする。
- captionの中 bottom0 padding20px 
- コメントアウトは消して提出する

# Q9
- paraはpara_wrapに入れる。子要素全てにfont当たるから。
- z-indexはいらない。beforeの方が必ず下に来るから。