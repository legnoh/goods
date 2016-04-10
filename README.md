goods
=======

## about
- 自分の所持物を全て書き出してみる
- 商品名、JANコード、購入場所、購入価格、用途など
- 現在持っているもののみに特化する

## why
- 暮らしの冪等性を向上させる
- 良い品への移り変わりを考える

## what
- 家具(Furnitures)
- 家電(Electronics)
- 電子機器(Computers)
- ヘルスケア/美容家電(Healthcare/Beauty)
- 乗り物(vehicle)
- 食器(tableware)
- 医薬品(medicine,first aid outfit)
- 服、靴、タオル(Clothing,Shoes,towel)
- 食品(food)
- 日用品(daily necessaries)
- Webサービス(web service)

## branch
- master
  - 今所持しているもの、購入済のもの
- wish-*
  - 欲しいもの、購入検討を開始したもの
  - 複合している場合、複数製品をwish-* の中に含める
- trash-*
  - 捨てるもの、もう持たなくても良いもの
  - 検討段階で作る

## how to contribute
- 購入検討を開始した段階で、wish branchを切ってpull-reqを作成
  - 購入したらマージ
  - 却下した場合リジェクト
- 手持品を捨てる場合、trash branchを切ってpull-reqを作成
  - 捨てたらマージ
  - 思い留まったらリジェクト
