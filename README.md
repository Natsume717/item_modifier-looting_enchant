# item_modifier-looting_enchant
item_modifierの1項目であるlooting_enchantに関するサンプルになります。

詳しくはブログ記事『[【マイクラ】looting_enchantでドロップ数を変化させる【item_modifier】](https://natsumake.com/item_modifier-looting_enchant/)』を参考にしてください。

<h3>概要</h3>
looting_enchantは、ドロップ増加のエンチャントが付与されているアイテムで倒した際の、アイテムドロップ数を変化させるものです。

具体的には、ドロップ増加のエンチャントレベルとcountで指示した値を掛け、さらにrollsの値を掛けた値分だけドロップするようになります。<br>
またlimitによって最大ドロップ数を決める（制限をかける）ことも可能です。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```とコマンドを打ってください。

タラのスポーンエッグとドロップ増加が付与されているネザライトの剣が付与されます。<br>
（ネザライトの剣に付与されているドロップ増加のレベルはそれぞれ異なります）

タラを倒すことで、ラピスラズリが手に入ります。<br>
この時入手できるラピスラズリの個数がlooting_enchantによって決められるため、エンチャントレベルごとにドロップ数が異なるというわけです。
