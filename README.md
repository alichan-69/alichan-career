# alichan とは

<img width="160px" src="https://avatars.githubusercontent.com/u/67483287?v=4" />

| key     | value                                         |
| ------- | --------------------------------------------- |
| Name    | alichan                                       |
| GitHub  | [alichan](https://github.com/alichan)         |
| Twitter | [@alichan69](https://twitter.com/alichan0609) |

# alichan の経歴

<details> 
  <summary>
  <a href="https://github.com/alichan-69/AliceGame">個人でスマホゲーム開発(3000DL突破)</a>(2018/8 〜 2023/1)
  </summary>
  <div>

## アプリ概要

- デスゲームを題材とした脱出ゲームアプリ<br>

## 使用言語

- C#

## 使用ツール

- VsCode
- Unity

## 所感

- 初めてのプログラミングだったが、ios と android 両方に公開し、3000DL を突破、3 万円収益が入った
- シナリオ、イラスト、プログラミング全て自分でできたのでえらい
- 他の脱出ゲームを研究し、どのタイミングでミニゲームをいれればユーザーに飽きが来ないか、どのくらいの文量だとシナリオを読んでもらえそうかなどどちらかというとゲームの構成に力を入れた
- SNS でゲームのキャラクターが登場する漫画なども公開し、平均的に 150 いいねを超えることができたのでよかった
- 適当に Unity を選んだが、今思うとクロスプラットフォームに開発できるツールを選んで本当によかった
- ツイッターで感想を書いてくれる人がいて嬉しかった
</div>
</details>

<details> 
  <summary>
  電話を活用したサービスを展開する自社開発企業でバイト (2020/9 〜 2022/9)
  </summary>
  <div>
  <details>
  <summary>
    テスト用API呼び出しアプリの開発 (2020/10 〜 2020/12)
  </summary>
  <div>

## アプリ概要

- テスターの方が API 呼び出しを GUI のみで行うために、パラメーター、出力形式等を指定して自社 API の呼び出しを行えるツール<br>
- カスタマイズ版ポストマンの様な物

## 使用言語

- PHP
- js
- jquery

## 使用ツール

- VsCode
- xampp
- aws
  - EC2
- nginx

## 所感

- この時初めて aws を使用してコンテナを立て、サーバー上にデプロイするという経験をした
- そもそも aws の存在を知らなかったので、（それまで Xserver とか使ってた）仮想サーバーという概念自体知らない状態だったため、大変だった

  </div>
    </details>
    <details>
    <summary>
      電話を使用した新規Webアプリのフロントエンド開発 (2021/04 〜 2021/06)
    </summary>
    <div>

## アプリ概要

- あんまり言ってはいけない気がするので秘密 🙃<br>

## 使用言語

- Vue
- Vuetify
- Vuex
- ts

## 使用ツール

- VsCode
- nodejs
- git

## 所感

- 初のフレームワークを使用したフロントエンド開発を行う
- コンポーネント分割の概念、責務分け、状態管理の設計方法、ts による型安全性やチームメンバーのコードの読み心地を意識したコードの書き方を学ぶ
- また、github による基本的なブランチの切り方、マージのタイミング、プルリクエストの出し方、レビュー方法なども一通り学ぶ

  </div>
  </details>
  <details>
  <summary>
    社内人事評価ツールの開発 (2021/06 〜 2022/04)
  </summary>
  <div>

## アプリ概要

- 社内で使用されていた人事評価ツールの使用料が大幅に上がってしまったため、自社内で内製することになったという過程を経て作成されたツール<br>

## 使用言語

- React
- material-ui
- Redux
- ts
- python

## 使用ツール

- aws
  - S3
  - API Gateway
  - lambda
  - CodeCommit
- VsCode
- nodejs
- git

## 所感

- 先月まで Vue を触っていたのに React でフロントエンド作ってバックエンドは python、インフラは aws をフル活用するという案件を任されたので大変だった
- コンポーネント分割の設計、状態設計などは Vue 案件の時鍛えたのでそれをそのまま流用した
- バックエンドで API 作成するという経験を初めてした。最終的にはローカルでコード書いて lambda に自動デプロイする bash を利用してデプロイできるようになったのでよかった
- API への入出力のみだが、python でテストコードも書いた。
- 正直当時は足を引っ張っていた感じはあるが、ここで大幅に学ぶ体力のようなものがついたのでよし
    </div>
    </details>
  <details>
  <summary>
    マーケティング用の便利ツール開発 (2021/04 〜 2022/07)
  </summary>
  <div>

## アプリ概要

- 会社の宣伝のため（インフラ監視なども行っている会社だった）、インフラエンジニアが訪れることを目的とした便利ツールサイト<br>

## 使用言語

- nuxt
- Vue
- Vuetify
- Vuex
- ts

## 使用ツール

- aws
  - S3
  - CodeCommit
- VsCode
- nodejs
- git

## 所感

- 好きな技術で開発して良いと言われたが、できるだけ自分がいなくなっても保守・運用がしやすいように社内のエンジニアに現在プロダクトで使用しているフレームワーク・言語・それらのバージョンを聞き、できるだけ社内のデファクトスタンダードに合わせるように努めた
- この時期、丁度 Vue が Vue のデフォルトバージョンを 3 にすると宣言しており、将来的に Vue3 への移行は必須だと思われたが、周囲のライブラリ群がまだ Vue3 への対応に追いついていない状況であったため、バージョンは 2 にしたものの、CompositionApi 等を導入し、移行を行いやすいように努めた
</div>
</details>
</div>
  </details>
</details>

<details> 
  <summary>
  <a href="https://www.recruit.co.jp/">株式会社リクルートで短期バイト</a> (2021/11 〜 2021/12)
  </summary>
  <div>

## アプリ概要

- リクナビネクストのフロントエンド改修案件<br>

## 使用言語

- Vue
- js

## 使用ツール

- VsCode
- gitlab

## 所感

- フロントエンドが 10 人体制くらいの規模の大きめのチーム開発を初めてした
- 大企業で大人数で開発する際にどのようなフローで開発が回っていくのか知れてよかった
- 具体的には、チケットの切り方、バックエンドの方との意思疎通の計り方、wiki によるナレッジの共有の仕方、テストデータの作成、受け渡しの仕方など
- また、個人開発だと意識しないようなこと(ユーザーの発生させたイベントの監視、AB テスト)などの概念・導入方法も知れてよかった
- 後、大規模なサービスを vue で開発したらどのようなコンポーネントの切り方や状態設計の仕方になっていくのかなども実際のコードが見れてよかった
</div>
  </details>

<details> 
  <summary>
  都内外資系IT企業 (2023/04 〜)
  </summary>
  <div>

## 概要

- まだとくになし

  </div>
  </details>
  </div>
</details>

## 今後やってみたいこと

- サービス企画・技術選定・開発・運用・広告施策等など全体に手を出せるスモールなレベル感での開発
  - 理由としては、ゲーム開発時にサービスの内容を考えたり、広告施策を打ってみたり、マネタイズを考えるのが楽しかったから。<br>
- CI/CD、DevOps の導入
  - 理由としては、社内エンジニアの意向を聞き、それにあった技術選定やツールの導入を行い、社員の方ができるだけ快適に開発を行う環境を整えるというのが楽しかったため、感謝してもらえるのが嬉しかったため。
  - また、テストの手打ちや本番環境の汚染などを防ぐために仮想サーバーやテストコードを利用した開発のフローを考え、実際に運用してみるのが楽しかったため。

## 仕事への向き合い方

- 必要だったら、自分ができる範囲で行う方針
- 例えば、営業が必要だったら営業も行うし、広告施策が必要だったら広告施策も行う
- 絶対にこの技術が使いたい！このレベルのコードでないと許せない！などというのはなく、どちらかというとそれが利益につながっているのか、今やるべきことなのかを考え、そちらをやれるタイプ(それは経歴ををみていただければわかっていただけると思う)
- でも、できるだけエンジニアリングから離れたくはない

## 参考

- こちらの経歴書を書く上で、この方のリポジトリを参考にさせていただきました
  - [bannzai/personalhistory]https://github.com/bannzai/personalhistory

## 最後に

ここまで読んでいただき、本当にありがとうございました 🙇‍♀️
