# FireCommits
エンジニアによるエンジニアのための草刈機

## サービス概要
尊敬するエンジニアの草を撃って、間接的に勝つサービス。コミット数が多ければ多いほど、草が茂っていれば茂っている
ほど敵は強敵に。撃ってシェアして、コード書こう！

***DEMO:***
![Demo](https://github.com/hyde2able/FireCommits/blob/master/public/images/firecommits.gif)

## 遊び方
- [FireCommits](https://fire-commits.herokuapp.com/)にジャンプ
- 誰かのgithubを入力
- スペースキーでゲームスタート！
- 左キー: 左に移動, 右キー: 右に移動　で草の攻撃を逃げながら草を撃つ
- スコアを50000消費して体力10の塀を目の前に作れる。敵の弾のみ防ぎます。自弾は透過。
- 再度遊ぶ場合は、スペースを。
- プレイヤーは6種類あります。ただし、プレイヤーによって当たり判定がシビアなものあり。
- 体力は3。

## ゲーム仕様
- 体力は3。　攻撃を受けると1秒間の無敵タイムあり
- 草の色が濃いほど、入力するgithub垢のコントリビューションが多いほど撃ってくる頻度が高い
- また、得点も高い。
- 50000点消費すると、目の前に体力10の壁を設置できる。
- ゲーム終了後、たまに[FireCommits公式アカウント](https://twitter.com/FireCommits)でプレイ結果がつぶやかれる

## 技術スタック
- node.js(server)
- enchant.js(client)
- jQuery(client)
- milkcocoa(datastore)
- heroku(PaaS)

## 追記
まだ未完成。以下、今後修正予定。
- ランキング蘭はランキングの役割を果たしていない。(解決)
- 変なアカウント名を入力したら落ちちゃう。。(解決?)
- 終わったらスコアとか呟きたい(解決)
- 草を全部打ち終わったクリア画面の未実装(解決) 
- プレイヤーによって打ち方を変えたい
- スマホに対応(解決。ただし重たいし、UIくそ)
- 撃たれた時の無敵時間(解決 1s)

2015/11

## Author

[@pokohide](https://twitter.com/pokohide)


## License

[MIT](http://b4b4r07.mit-license.org)



